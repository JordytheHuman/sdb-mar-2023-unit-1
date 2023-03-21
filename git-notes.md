## Create an initial repository

Use the command in the terminal `git init` YOU MUST BE IN THE DIRECTORY YOU ARE WANTING TO TRACK

-In V.S. Code you can right click the folder you want to start tracking and choose `Open in Integrated Terminal`

## List all the changes that Git is tracking

Use the command in the terminal of `git status`

## Adding files to the Staging Area

Use the command in the terminal: `git add .`

## Commiting our changer and adding a message

Use the command in the terminal `git commit -m "YOUR MESSAGE HERE"`

## If it is asking for credentials

git config --global user.name "JordytheHuman"
git config --global user.email "Jordankaufman27@gmail.com"
git config --list

# Github

1. Create a repository and give it a unique name. Ex: sdb-mar-2023-unit-1
2. Copy the last option and paste it into the terminal

# Already have a repo or a github repo and you want to update with changes.

1. `git add .`
2. `git status` - to verify (optional)
3. `git commit -m "ADD NEW MESSAGE HERE"` - Ex "added styling" or "fixed bug"
4. `git push origin main`
