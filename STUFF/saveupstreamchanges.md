# HOW TO CHECK OUT AND SAVE YOUR CHANGES ON A NEW BRANCH WITH YOUR TEMPLATES CODE

username mlopsaustin@gmail.com



git clone  [GitHub - mlopsaustin/GITVAULTSYNC: folder i use to sync my vault and settings to git](https://github.com/mlopsaustin/GITVAULTSYNC.git)


git clone git@github.com:mlopsaustin/GITVAULTSYNC.git

cd <repository_name>

git checkout -b <branch_name>

# Make your changes to the code using your preferred text editor or IDE

git add .
git commit -m "Your commit message here"

git checkout main

git pull origin main

git merge <branch_name> ## your created stuff

git push origin main
