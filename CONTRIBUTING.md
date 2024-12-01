# How to contribute

This project is intended to be open to all and a true community effort. Everyone should feel empowered to contribute additional photos, blogs, talks, papers, research, etc for individuals listed on the project.

## Contributors

Contributors are the public community members who do not have specific access to the RestInCode (RiC) repository. This would be the majority of people who want to help contribute.

### Adding new people

Verify that an Issue [does not already exist](https://github.com/restincode/restincode/issues) for the individual you wish so submit. Once you've made sure, please use one of our <a href="https://github.com/restincode/restincode/issues/new/choose">existing templates</a> to open an issue for the following:

- Add New Person to Site
- Bug report
- Feature request

Alternatively you can open a <a href="https://github.com/restincode/restincode/issues/new">regular issue</a> or you can also choose to submit the json file (located in [people/](https://github.com/restincode/restincode/tree/master/people)) directly (via a pull request). If you wish to submit your own json, please utilize this [template](https://github.com/restincode/restincode/blob/master/people/_template.json) to get started.

### Adding data to existing person

Every person on RiC should have an open [Issue](https://github.com/restincode/restincode/issues) within the project. The first step is to search and locate the existing Issue for the person who's data you want to add to. Once you've located it, just leave a comment on the Issue with the new information to be added.

If you cannot find the person, you can add them using our Issue [template](https://github.com/restincode/restincode/issues/new?assignees=&labels=Add+Person%2C+Needs+Review%2C+People&template=add-new-person-to-site.md&title=) template.

### Testing your changes locally

Using the provided Gemfile you can test locally by running `bundle install` and executing `bundle exec jekyll serve` to run a local web server on http://localhost:4000. Please verify your changes before submitting a Pull Request.

## Maintainers

Maintainers are the people who have commit access to the RestInCode repository and can manage Issues and Pull Requests.

### Triaging a new Issue

The majority of new GitHub Issues will be used to add new individuals to Rest In Code (RiC). The Issue subject will be a real name and/or a handle. **An open Issue to add a person should never be closed**. It will be used long-term to add new data and discuss the current memorial of this individual. Anyone is welcome to contribute, including sharing links related to the person, personal stories, or general thoughts on their friends who have passed. Use labels to identify what work if any needs to be completed on the current Issue/person.

#### What to look for

Verify there are no duplicate Issues for this name or handle. If there are, attempt to merge their contents and apply appropriate labels.

### Triaging a Pull Request (PR)

PRs could be anything from People, new data, code changes, web site changes, documentation or more. Applying the appropriate labels will be most important to ensuring they are handled correctly.

#### What to look for

The big thing to look for will be that the persons name is spelled correctly in all places (people/.json, inside the name.json, in the peoplelist.json, images/.(jpg|png), etc). This name should match in all places. Verify any social media links, references, or other URLs that may wind up on the final memorial are working and go where expected. In addition to submitting links to us, please use [archive.org](https://archive.org) and/or [archive.today](https://archive.today/) to preserve the content.

### Using Labels

- **Add Person** - This shows that the PR or Issue is to add a new person to the RiC project. Should be replaced by "Person Added" once the work is completed.
- **Add Data** - This shows that the PR or Issue is to add additional data, such as contributions or images to an existing person.
- **BUG** - A bug in the actual website/github config/or jsons.
- **Code** - A change to the actual code for this website.
- **Ideas** - A proposed idea or change to the project, website, templates, or other materials.
- **Needs Review** - This PR or Issue requires a Maintainer to review the changes and ensure that everything looks appropriate and up to standards.
- **People** - This represents a PR or Issue that is specifically about a person in the memorial.
- **Person Added** - This represents a person who's been added (a json created) to the memorial. Should be applied after the work is complete, and should replace the "Add Person" tag.
- **Project** - Used to identify PRs or Issues that relate to the RiC project and not any of the people within it.
- **Task** - A basic task being requested. This could fall within project, code, bug, or other non people focused work.
- **Work in Progress** - This will be applied if the PR or Issue should **NOT** be accepted in its current state. This is for work-in progress PR's that require more work from the contributor.
