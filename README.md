# Branch model
I want a branch model that works for Focus, three developers with ongoing DEV and PROD deploys every couple of months or so.

[git-with-development-staging-and-production-branches](https://stackoverflow.com/questions/15072243/git-with-development-staging-and-production-branches) mentions 
[A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/) and a proposal by Josef Kufner for *"simpler method, where development is done in master branch and stable versions are tagged in master branch and they have their stable branch for patches if required."*. I am interested in the first instance in this simpler method which is what I'll try out in this repository. 

## Steps
- Tag releases
- Tag latest
- Check out latest with common @latest syntax (e.g. don't need to know commit identifier
- Commit some development changes
- branch Latest and apply a patch
If I can get this working then it is both simple and adequite for Portal.


[SO how-do-i-git-push-under-a-different-username-after-a-commit](https://stackoverflow.com/questions/77361153/how-do-i-git-push-under-a-different-username-after-a-commit) acran resposne is informative. 
