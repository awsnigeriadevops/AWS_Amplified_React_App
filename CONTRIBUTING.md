# Contributor's Guide

Issues can be submitted by anyone. 

**Contents**

- [Choosing an Issue](#choosing-an-issue)
- [Getting Started](#getting-started)
- [Submitting a Pull Request](#submitting-a-pull-request)

## Choosing an Issue

Before getting started and setup with contributing, you'll want to look at and choose an issue to work on. Here is a basic workflow you want to work from:

1. Search through issues
2. Find issue you want to work on
3. Check if someone else has already worked on and made a pull request on said issue
4. (Optional) Double check pull requests for someone who has worked on the pull request


You can find open issue [here](https://github.com/awsnigeriadevops/AWS_Amplified_React_App/issues).

Once you've found an issue you want to work on, take a look at the issue to see if anyone else has made a pull request for this issue yet.

You can tell if someone has correctly referenced and worked on an issue if in the issue you find some text saying, the following:

>  This was referenced on ____

where that `____` is the date and below it is the pull request of another individual working on that issue.

To be extra sure no one has worked on it, you can [take a look at the pull requests](https://github.com/awsnigeriadevops/AWS_Amplified_React_App/pulls) as well to see if anyone has made a similar pull request.


### Getting Started

1. Fork the repository

2. Clone and then open it up on your prefered code editor

3. Open terminal and set upsream branch: `git remote add upstream https://github.com/awsnigeriadevops/AWS_Amplified_React_App.git`

4. Pull upstream `git pull upstream main`

5. Create a new branch for the task your are doing eg: `git checkout -b new_work_branch`

6. After making changes, do `git add .`

    **Note:** using a `git add .` will automatically add all files. You can do a
    `git status` to see your changes, but do it **before** `git add`.

7. Commit your changes with a descriptive commit message `git commit -m "commit message"`

8. To make sure there are no conflicts: `git pull upstream main`

9. Push changes to your new branch: `git push origin your-current-branch-name`

10. Create a pull request to the main branch

    Within GitHub, visit this main repository and you should see a banner
    suggesting that you make a pull request. While you're writing up the pull
    request, you can add `Closes #XXX` in the message body where `#XXX` is the
    issue you're fixing. Therefore, an example would be `Closes #42` would close issue
    `#42`.

### Submitting a Pull Request

If you decide to fix an issue, it's advisable to check the comment thread to see if there's somebody already working on a fix. If no one is working on it, kindly leave a comment stating that you intend to work on it. By doing that,
other people don't accidentally duplicate your effort.


