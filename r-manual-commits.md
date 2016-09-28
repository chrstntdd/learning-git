#### What do you think are the pros and cons of manually choosing when to create a commit, like you do in Git, vs having versions automatically saved, like Google Docs does?

Having the ability to manually choose when to commit code is beneficial to the user by allowing them to be in control of the commit history. Google Docs on the other hand will automatically save multiple versions of documents and flood the history with unreasoned saves. Git solves this problem by placing the responsibility of choosing when to save a file on the user. While this can lead to subjective views on when to be saving work, it is generally accepted to be committing changes when one logical, cohesive, complete change is made. This could be once a new feature has been implemented or when a *#SINGLE* bug is fixed. Committing after a single typo correction in a program's README only to commit once more when another typo was fixed would pollute the commit history with two minute changes in the matter of a minute or so. It would be better practice to fix all the typos in the document, then just commit afterwards with a clear commit message indicating the change.