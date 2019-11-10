# Github Basics Step-by-Step

- Create repo
- Clone repo somewhere appropriate (will create new directory) 
    `git clone <url-goes-here>`
- Make changes
- `git add .`
- `git commit -m "description of changes"`
If working alone:
- `git push origin master`

If adding a feature on team project:

Create a new branch and push to it 
- `git checkout -b feature-name`
- `git push origin feature-name`

When the feature is complete, open a Pull Request from github to merge changes to master branch

## Nomenclature

clone: copies repository and links it to its github url
add: adds local files to be tracked. `.` refers to everything in the current folder
commit: makes a log of current changes with a description
push: communicates changes to the github server

