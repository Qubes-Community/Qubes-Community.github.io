### 1. About

We are an independent volunteer community striving to build and improve end-user content for [Qubes OS](https://www.qubes-os.org/), such as guides, documentation, code & scripts, tips, ...

**The project's tasks are**:

* to make it easier for Qubes OS users to submit documentation, tips, suggestions and more generally, any resource related to the Qubes OS project. Despite the project being hosted on GitHub, knowing git is not a requirement.
* to assist in getting documentation contributions QA'd and potentially submitted to the [official QubesOS documentation](https://www.qubes-os.org/doc/).
* to host, or link to projects, documentation, code, or resources, which are better suited to be distributed in the Community.
* to build a larger community around the Qubes OS project.

**Disclaimer**: this site is run by volunteers. The Qubes OS Project is not affiliated with this site and does not endorse the content of any of these pages. The members of this community are Qubes users so they obviously focus on security but there's no guarantee about the content published in this site so use it at your own risk.

### 2. Content

The `docs/` and `code/` subfolders in the ['Contents'](https://github.com/Qubes-Community/Contents) repository contain contributed documentation that has been reviewed, and code + links to third-party resources.

Ongoing reviews and QA of pending user-contributed content can be seen in [issues](https://github.com/Qubes-Community/Contents/issues) and [pull requests](https://github.com/Qubes-Community/Contents/pulls) (see section [Contributing](#contributing) below).

Documentation suggestions are filed as [issues](https://github.com/Qubes-Community/Contents/issues) with a `Doc suggestion: ...` title. Their purpose is:
- to test the waters about a documentation topic before spending further time to document it, as well as avoiding duplicate work by other community members.
- to avoid forgetting about interesting topics (eg. from insightful [qubes-users](https://www.qubes-os.org/mailing-lists/#qubes-users) and [qubes-devel](https://www.qubes-os.org/mailing-lists/#qubes-devel) threads or personal user experience) when one doesn't have time to write full-fledged documentation on the spot.



<!-- The project hosts various projects which have their own repositories. They are referenced where appropriate in the README.md files in `code/` categories subfolders. Alternatively you can search them through the project's [main github page](https://github.com/Qubes-Community). -->


<a name="contributing"></a>
### 3. Contributing

Anyone is welcome to submit content or documentation suggestions they deem fit for inclusion in this community effort (or potentially in the official Qubes documentation). As Qubes OS users we value privacy and security so please keep the project's [collective vision](/strategic-statement.md) in mind.

Contributing content is done:

- by submitting pull requests (a relatively easy process - see ["learning git"](#learning-git) below).
- or, for users not comfortable with git, by [creating a new issue](https://github.com/Qubes-Community/Contents/issues) in the ['Contents'](https://github.com/Qubes-Community/Contents) repository. After optional discussion in the issue's thread and after the content is deemed fit for submission a community member will create a pull request on your behalf and take care of everything "git"; alternatively - if you prefer - he/she will help you creating your own pull request. Note however that in the former case you'll loose attribution/credit because github doesn't allow transferring a pull request's ownership.

Documentation suggestions are filed as new issues with a `Doc suggestion:` title (eg. `Doc suggestion: finding out disk usage in R4`). A quick description of the suggestion should be given in the issue's body, with links to relevant mailing list posts or third-party resources if applicable. It isn't mandatory that the user who filed the issue write the documentation: anyone can pick up an issue and submit documentation.

The ['Contents'](https://github.com/Qubes-Community/Contents) repository is where most pull requests and issues are expected to be submitted. Contributors who plan to submit content to the [official qubes-doc repository](https://github.com/QubesOS/qubes-doc) but who would like to get preliminary feedback/QA from the community can submit pull requests to the [forked qubes-doc repository](https://github.com/Qubes-Community/qubes-doc).


<!-- 
- submitting pull requests or issues related/specific to the various project repositories living under this project.-->

### 4. Licensing

GPLv2 or later is required for any documentation content so that it matches QubesOS's official documentation. You are otherwise free to use whatever license you want when submitting code/programs, provided it fits in the open source git/fork model. Note that GPLv2 will be assumed if content is published without mentioning its license.

<a name="learning-git"></a>
### 5. Learning git for further contributions

It would ease the burden on community members if returning contributors who are not proficient with git learn the few basic concepts required to submit pull requests themselves.

This [github help page](https://help.github.com/articles/about-pull-requests) explains what pull requests are.

The official Qubes OS documentation [contribution guidelines](https://www.qubes-os.org/doc/doc-guidelines/) is then a good place to start with. It is based on contributing to the official qubes-doc repository but is applicable to this (or any other) project.

However the guide doesn't approach the problem of keeping a forked repository synchronized with "upstream" (eg. the official repository). This isn't a trivial problem ([github help page](https://help.github.com/articles/syncing-a-fork/)), especially when you have made changes in your forked repository ([stackoverflow post](https://stackoverflow.com/questions/7244321/how-do-i-update-a-github-forked-repository)). So until you are proficient enough to understand the steps involved, a simple alternative that does not require command line usage is to delete the forked repository and re-fork it from upstream. This is a bit of a "nuclear" option though and you'll obviously loose any changes you've made in your forked repository.

