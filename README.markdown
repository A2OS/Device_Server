# Authenticating to the Build Server
You must be a member of the Ammonia OS organization, and your
membership must be public at https://github.com/AmmoniaOS  

Jenkins will authorize using OAuth to GitHub.

# Adding or updating a device

This repository is preconfigured to use the git-review plugin. More information can be found at:
https://pypi.python.org/pypi/git-review

Edit cm-build-targets and submit a change to gerrit for review. The
syntax for that file is documented in its first few lines.
You can upload your change to gerrit with commands like these:

    git add aos-build-targets
    git commit
    git review

Once you have submitted your change add the group "Release" to the reviewers.
