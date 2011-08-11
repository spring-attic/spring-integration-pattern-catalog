# Fork the Repository
1. go to [https://github.com/SpringSource/spring-integration](https://github.com/SpringSource/spring-integration)
2. hit the "fork" button and choose your own github account as the target
3. for more detail see [http://help.github.com/fork-a-repo/](http://help.github.com/fork-a-repo/)

# Setup your Local Development Environment
1. `git clone --recursive git@github.com:<your-github-username>/spring-integration.git`
2. `cd spring-integration`
3. `git remote show`  
_you should see only 'origin' - which is the fork you created for your own github account_
4. `git remote add upstream git@github.com:SpringSource/spring-integration.git`
5. `git remote show`  
_you should now see 'upstream' in addition to 'origin' where 'upstream' is the SpringSource repository from which releases are built_

# A Day in the Life of a Contributor
* _Always_ work on topic branches.
* For example, to create and switch to a new branch for issue INT-123: `git checkout -b int123`
* You might be working on several different topic branches at any given time, but when at a stopping point for one of those branches, commit (a local operation). Then push to 'origin' (which is your own fork). Then to begin working on another issue (say INT-101): `git checkout int101`. The _-b_ flag is not needed if that branch already exists in your local repository.
* When ready to resolve an issue or to collaborate with others, `git push` to origin (your fork).
* If you want to collaborate with another contributor, have them fork your repository (add it as a remote) and `git fetch <your-username>` to grab your branch. Alternatively, they can use `git fetch --all` to sync their local state with all of their remotes.
* If you grant that collaborator push access to your repository, they can even apply their changes to your branch.
* When ready for your contribution to be reviewed for potential inclusion in the master branch of the canonical spring-integration repository (what you know as 'upstream'), issue a pull request to the SpringSource repository (for more detail, see [http://help.github.com/send-pull-requests/](http://help.github.com/send-pull-requests/)).
* The project lead may merge your changes into the upstream master branch as-is, he may keep the pull request open yet add a comment about something that should be modified, or he might reject the pull request by closing it.
* A prerequisite for any pull request is that it will be cleanly merge-able with the upstream master's current state. **This is the responsibility of any contributor.** Any pull request that cannot be applied cleanly will most likely be rejected. For a full explanation, see the Pro Git section on rebasing: [http://progit.org/book/ch3-6.html](http://progit.org/book/ch3-6.html). As stated there: "> Often, you’ll do this to make sure your commits apply cleanly on a remote branch — perhaps in a project to which you’re trying to contribute but that you don’t maintain."

# Keeping your Local Code in Synch
* more soon...