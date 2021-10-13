# git commit

The command `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is called a commit.

Commits comes with commit messages that are required for each commit. You add messages to a commit by using the `-m` flag followed by a message in quotes.

A commit message _can_ be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

---
For Example, if we have an application that we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:

```
git add .
git commit -m "Added register functionality"
```

Then when viewing the history of a gir repository, you can pinpoint where the registration functionality was added.

It's really easy to get confused about when changes were made so It's always a good idea to use commit messages and to commit regularly to be able to track changes easily.

## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)
