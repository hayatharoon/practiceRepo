# **What is Git?**

- Git is distributred version control system which track changes to our project files over time.
- Git enables us to record project changes and go back to a specific version of the tracked files at any given point of time.
- This system can be used by many people to efficiently work together and collaborate on team projects, where each developer can have their own version of the project, distributed on their computer.
- And later on, these individual versions of the project can be merged and adapted into the main version of the project.

## **Repositories:**

A Git repositories is a container for a project that is tracked by Git.

- **Local Repositories:** Local repository is an isolated repository stored on our computer, where you can work on the local version of your project.
- **Remote Repositories:** Remote repository is generally stored outside of your isolated local system, usually on a remote server.

## **Initialization (init Command):**

```
git init
```

This command will create a hidden file with the name `.git` for our project and this file contain all the internal tracking data about our repository.
And if we want ti see this file thetype a command `ls -h` then you will see this file on your system.

## **Checking the status of Repository:**

```
git status
```

This command will shows us which files have been changed, which files are added and also which files are tracked or untracked.

## **Commiting:**

Committing is the process in which the changes are `officially` added to the Git repository.

## **Restore the Commit:**

If we want to delete the commit then copy the commit key below that deleting commit and run:

```
git reset <commit_key>
```

Whatever commit we copied then all the commit above that commit will be deleted.
