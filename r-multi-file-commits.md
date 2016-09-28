#### Why do you think some version control systems, like Git, allow saving multiple files in one commit, while others, like Google Docs, treat each file separately?

Git incorporates the idea of a repository into its system. The top result on google returns this very definition for 'repository.'

> a place, building, or receptacle where things are or may be stored.

Extending that definition to code, its clear that the repository is a container where all code resides in together to build a program. In programming often times a single file will depend on another one, or many more for that matter. This dependency reinforces the need for a commit that saves multiple files. Doing so creates a snapshot of the current project with, ideally everything in operating condition so that any differences beyond that point may be monitored.
