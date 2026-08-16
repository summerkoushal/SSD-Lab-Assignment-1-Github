## Lab assignment 1

### Initializing Git
- Unzip the student-portal folder provided
- Run command `git init` to initialize a git repository inside the folder

### Setting up gitIgnore
- Create a .gitignore file inside our repository by using `touch .gitignore`
- This .gitignore will keep a track of all the files / folders which we don't want to track
- We have created a legacy folder which contain passwords of users
- Adding that folder name to .gitignore will help to dont push our legacy files to github

### Performing initial commit
- First we need to track our files, for that we can use `git add <filename>` or `git add .`
- (Optional) to check the status of our repository, we can use command `git status` or `git status -s` as shorthand
- To commit our changes, use command `git commit -m "commit message"`

### Linking github remote
- To push our repository to github repository, we need to add remote
- A remote is basically a location, specified by URL to point our push location
- To add a remote use command `git remote add <remoteName> <urlName>`
- To show all the remote created, use command `git remote` or `git remote -v` for checking remote and their respective URL also
