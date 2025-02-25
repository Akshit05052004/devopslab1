# devopslab1
this repo is for the devops lab 1 

1. Initialize a Git Repository (git init)
If you haven’t cloned the repository yet and want to create a new local repository:
git init
(This initializes a new Git repository in your current directory.)
However, since you already have a GitHub repository, you should clone it instead.

2. Clone the Repository (git clone)
To clone the devopslab1 repository to your local machine:
git clone https://github.com/Akshit05052004/devopslab1.git
This will create a folder named devopslab1 containing the repository.

3. Navigate into the Repository
cd devopslab1

4. Add a New File and Stage It (git add)
Create a new file (e.g., test.txt):
echo "This is a test file" > test.txt
Then add it to the staging area:
git add test.txt

5. Commit Changes (git commit)
Commit the changes with a message:
git commit -m "Added test.txt file"

6. Push Changes to GitHub (git push)
If you cloned the repository, you can push the changes to GitHub:
git push origin main  # If the default branch is 'main'
(Replace main with master if needed.)
If it’s your first time pushing, set the upstream branch:
git push --set-upstream origin main

7. Remove a File from Git (git rm)
To remove test.txt from the repository and stage the deletion:
git rm test.txt
Then commit the removal:
git commit -m "Removed test.txt file"

Push the changes:
git push origin main
Summary of Commands:
git clone https://github.com/Akshit05052004/devopslab1.git
cd devopslab1
echo "This is a test file" > test.txt
git add test.txt
git commit -m "Added test.txt file"
git push origin main
git rm test.txt
git commit -m "Removed test.txt file"
git push origin main
