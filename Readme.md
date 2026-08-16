## Lab assignment 1

### Initializing Git
- unzip the student-portal folder provided
- run command `git init` to initialize a git repository inside the folder

### Setting up gitIgnore
- create a .gitignore file inside our repository by using `touch .gitignore`
- this .gitignore will keep a track of all the files / folders which we don't want to track
- we have created a legacy folder which contain passwords of users
- adding that folder name to .gitignore will help to dont push our legacy files to github

### Performing initial commit
- first we need to track our files, for that we can use `git add <filename>` or `git add .`
- (optional) to check the status of our repository, we can use command `git status` or `git status -s` as shorthand
- to commit our changes, use command `git commit -m "commit message"`

### Linking github remote
- to push our repository to github repository, we need to add remote
- a remote is basically a location, specified by URL to point our push location
- to add a remote use command `git remote add <remoteName> <urlName>`
- to show all the remote created, use command `git remote` or `git remote -v` for checking remote and their respective URL also
