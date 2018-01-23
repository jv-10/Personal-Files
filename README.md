# Web Developing

All I need for web developing

## Pull and Push from Bitbucket using git

Pull and Push from [Bitbucket](https://bitbucket.org/)

### Pull

Pull from Bitbucket

```
Give examples
```

### Push from Bitbucket
You can check the status by entering git status at anytime
```
git status
```

1. Create your new files or edit existing files in your local project directory.

2. So that you can enter commands for your repository.
```
cd <path_to_local_repo>
```
3. Enter git add --all at the command line to add the files or changes to the repository.
```
git add --all
```
4. Enter git commit -m '<commit_message>' at the command line to commit new files/changes to the local repository. For the <commit_message> , you can enter anything that describes the changes you are committing.
```
git commit -m '<commit_message>'
```
5. Enter git push  at the command line to copy your files from your local repository to Bitbucket.
```
git push -u origin master
```
6. If prompted for authentication, enter your Bitbucket password.
