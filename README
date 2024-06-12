# git clone vs git remote add

git clone creates an exact copy of an git remote repository into our local file system, hence everything is mapped with the remote repositories including the branches and tags.

git remote add just adds the remote repository to the local repository. This justs acts as a pointer/a means to get to the remote repo from local. You need to explicitly pull all the branches,commits etc from remote. Also, need to specify the upstream branch to the local branch.

Use case to use git remote add instead of git clone is when you have to handle multiple remotes for a single repository.

## Commands

### Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

In order to push someting to a remote repository using "git remote add"
```bash
git init
git remote add origin git@github.com:rahul27shinde/Dummy.git

git add .
git commit -m "Added files from Folder"
git pull origin master --rebase (If remote has files)
git push --set-upstream origin  master
```

### In order to push something to a remote repository using "git clone"

```bash
git clone git@github.com:rahul27shinde/Dummy.git

git add .
git commit -m "Added files from Clone Folder"
git push
```
Here no need to 1) Set Upstream branch
				2) Pull from remote repo.
				3) Create a git repo beforehand
				4) Add a git repo as remote

## UseCase
It depends if you want to add another remote repository or not.

Sometimes you might want to have two separate remotes because:

you use one as a backup
you use one to deploy with
you collaborate with separate teams that have different accesses
you want to pull in an upstream repository such as an open source project that you forked from
