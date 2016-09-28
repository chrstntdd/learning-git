### How might using version control make you more confident to make changes that could break something?


So much data about the past is collected with git and also git has many features that allow history to be recorded accurately.

Commits allow the user the save a snapshot of their current directory/repo. With that commit comes a commit message that will briefly outline the changes made in that commit.

Each commit can be viewed in a list within the command line with each unique receiving its own unique id. This allows the commits to be used as arguments in some of the built in functions git offers.

These functions include `git diff`, allowing for users to see the changes between two commits by passing in two commit ids. The first id will be the older commit while the second id will be the newer one. This command will allow us to view the changes across all the files within the repository, useful, but there's an even greater tool at our expense here with the power of git.

`git checkout` is a very valuable tool to a developer. This command allows us to pass in a single commit id and be able to revert all of our files within that repository back to the previous version specified by the commit id. Now we have restored our files back into their previous selves, we can debug from that point in time as if nothing changed.
