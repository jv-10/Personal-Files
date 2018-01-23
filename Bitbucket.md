#Clone and Push from Bitbucket using git

Clone and Push from [Bitbucket](https://bitbucket.org/)

### Pull

Clone from Bitbucket

1. From the repository, click + in the global sidebar and select Clone this repository under Get to work.

2. Copy the clone command (either the SSH format or the HTTPS).
	If you are using the SSH protocol, ensure your public key is in Bitbucket and loaded on the local system to which you are cloning.

3. From a terminal window, change to the local directory where you want to clone your repository.

4. Paste the command you copied from Bitbucket, for example:

CLONE OVER HTTPS:
```
 $ git clone https://username@bitbucket.org/teamsinspace/documentation-tests.git
 ```
CLONE OVER SSH:
```
$ git clone git@bitbucket.org:teamsinspace/documentation-tests.git
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
