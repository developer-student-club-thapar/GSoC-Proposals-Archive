<img src="https://raw.githubusercontent.com/developer-student-club-thapar/officialWebsite/master/src/assets/dsc_logo.png">

# Contributing to GSoC-Proposals-Archive :

GSoC-Proposals-Archive is an Apache 2.0 Licensed project and uses the standard GitHub pull requests process to review and accept contributions.

There are several areas of GSoC-Proposals-Archive that could use your help. For starters, you could help in improving the sections in this document by either creating a new issue describing the improvement or submitting a pull request to this repository. 

* If you are a first-time contributor, please see [Steps to Contribute](#steps-to-contribute).
* If you would like to work on something more involved, please connect with the [Developer Student CLub TIET](https://discord.gg/Ma9ZAGJ) Contributors. 
* If you would like to make code contributions, all your commits should be signed with Developer Certificate of Origin. See [Sign your work](#sign-your-work). 

## Steps to Contribute :

* Find an issue to work on or create a new issue. The issues are maintained at [GSoC-Proposals-Archive](https://github.com/developer-student-club-thapar/GSoC-Proposals-Archive/issues). 
* Claim your issue by commenting your intent to work on it to avoid duplication of efforts. 
* Fork the repository on GitHub.
* Create a branch from where you want to base your work (usually master).
* [Add Upstream to your clone](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork)
* Make your changes.
* For adding a new organisation - 
    * Make sure to add it to the list of `Featured Organisations` section of the README.
    * You can check `.sample_folder` in the root of the repo for a sample.
* Commit your changes by making sure the commit messages convey the need and notes about the commit.
* Push your changes to the branch in your fork of the repository.
* Submit a pull request to the original repository. See [Pull Request checklist](#pull-request-checklist)
* Make sure that before you create a new branch for new changes,[syncing with upstream](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork) is neccesary.

## Naming Conventions
* If you are adding a proposal please try to follow the file naming conventions that is  `YearOfSubmission_YourName.pdf`
* Add the proposal only in pdf format . No other format will be accepted .
* In case the repository root deesn't has the folder of the organization you submitted your proposal to , add a new folder using the following steps :
    - Add a folder in the repo root named after the organization eg: CNCF
    - Add 2 folders inside the newly created organization folder name `Accepted` and `Rejected` respectively .
    - **NOTE:** If a folder does not have any file, you should add a blank `.gitkeep` file, so that the folder is tracked by the VCS.
    - Add your proposal to the appropriate sub folder following the file naming conventions .

## Pull Request Checklist :
* Rebase to the current master branch before submitting your pull request.
* Commits should be as small as possible. Each commit should follow the checklist below:

  - For code changes, add tests relevant to the fixed bug or new feature
  - Pass the compile and tests - includes spell checks, formatting, etc
  - Commit header (first line) should convey what changed
  - Commit body should include details such as why the changes are required and how the proposed changes
  - DCO Signed 
  
* If your PR is not getting reviewed or you need a specific person to review it, please reach out to the Developer Student Club TIET at the [DSC TIET Discord Server](https://discord.gg/Ma9ZAGJ)

## Sign your work 

We use the Developer Certificate of Origin (DCO) as an additional safeguard for the GSoC-Proposals-Archive project. This is a well established and widely used mechanism to assure that contributors have confirmed their right to license their contribution under the project's license. Please add a line to every git commit message:

```
  Signed-off-by: Random J Developer <random@developer.example.org>
```

Use your real name (sorry, no pseudonyms or anonymous contributions). The email id should match the email id provided in your GitHub profile. 
If you set your `user.name` and `user.email` in git config, you can sign your commit automatically with `git commit -s`. 

You can also use git [aliases](https://git-scm.com/book/tr/v2/Git-Basics-Git-Aliases) like `git config --global alias.ci 'commit -s'`. Now you can commit with `git ci` and the commit will be signed.

## Community

The DSC TIET community is active on its discord server , join the server to interact eith the community members . 
- [DSC TIET Discord Server](https://discord.gg/Ma9ZAGJ)
