# Welcome to Electromagnetism and antenna theory v2 contributing guide
Thank you for investing your time in contributing to our project.

In this guide, you will get an overview of the contribution workflow from opening an issue, creating a PR, reviewing, and merging the PR.

Use the table of contents icon <img src="./assets/images/table-of-contents.png" width="25" height="25" /> on the top left or right corner of this document to get to a specific section of this guide quickly.

# Getting started
To get your local machine ready to compile the latex files and make your contributions please check the [README.md](./README.md) file.

# Issues
## Create a new issue
*Not much of a reader then maybe a video will do, [check here](https://youtu.be/HnrNeuAYZOg).*

If you spot an(any) error(s) and you do not want to edit the project files but would rather leave it to the contributors to handle, you can still help by providing a detailed explanation of the error(s) and the correction(s) using the guide as follows:

- ensure you have the latest book from the online storage. The link can be found in the [README.md](./README.md) file.
- find related issues on the same chapter from [existing issues #2](https://github.com/AllisonOge/electromagnetism-and-antenna-theory-v2/issues) and [existing issues #1](https://github.com/AllisonOge/electromagnetism-and-antenna-theory-v2-1/issues) and comment on the error(s) spotted (please follow the guide for explaining spotted error(s) in bold)
- if no related issues, create an issue with the title format "chp[#]-sec[#]: [closest title to the error]" e.g. "chp1-sec1.7: radar formula is incorrect" or "chp17-sec17.2: incorrect derivation of divergence theorem".
- **Provide a screenshot of the error(s) spotted and comment on correction(s) or provide a screenshot of the clearly written correction(s)**

## Solve an issue
Scan through our [existing issues #2](https://github.com/AllisonOge/electromagnetism-and-antenna-theory-v2/issues) and [existing issues #1](https://github.com/AllisonOge/electromagnetism-and-antenna-theory-v2-1/issues) to find one that interest you. You can narrow down the search using `labels` as filters. If you find an issue to work on, you are welcome to open a pull request (PR) with a fix.

# Make changes
We encourage small changes, no more than 15 commits per PR.

## Make changes locally
- fork the repository 
- create a working branch and make your changes.

## Commit your changes
Commit the changes once you are happy with them. Don't forget to self-review to speed up the review process

# Pull Request
When you're finished with changes, create a pull request also known as a PR.
- fill out the "ready for review" template so that we can review your PR.  This template helps reviewers understand your changes as well as the purpose of your PR.
- don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
- Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge. Once you submit your PR, one of the contributors will review your proposal. We may ask questions or request additional information.
- We may ask for changes to be made before a PR can be merged either using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or PR comments. You can then make the changes in your fork, and commit them to your branch.
- As you update your PR and apply changes, mark each conversation as [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
- If you run into any merge issues check this [git tutorial](https://github.com/skills/resolve-merge-conflicts) to help you resolve merge conflicts and other issues.

If all this jargon is new to you then I suggest you spend a little time understanding how pull request (PR) works with these videos, [understanding PRs](https://www.youtube.com/watch?v=For9VtrQx58) and [creating a PR in GitHub](https://www.youtube.com/watch?v=rgbCcBNZcdQ).

# Compilation files
Depending on the latex compiler being used you might generate files that the gitignore file did not take note of. So please before committing any changes ensure no new files which were not intended are committed. 

To do so add the extensions of those files to the gitignore file before committing any changes in your working branch. If however they have been committed before the gitignore file is updated then follow this [guide](https://devconnected.com/how-to-clear-git-cache/) to remove the previous commits from git cache.
