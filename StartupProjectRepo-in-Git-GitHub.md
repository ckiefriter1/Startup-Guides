To start a new project (which we will do each week in this program), we need to 
Create a new directory on our local computer that will contain our project/assignment code
Create a new repository on GitHub. 
Once we create the repository or repo on GitHub, it will give us a list of commands to run locally on Command Prompt (Windows) or Terminal (Mac) from within the directory that we created for our project.   The list of commands will allow us to connect the directory on our local computer with the GitHub repo on the GitHub server, and subsequently back-up our programs to the GitHub Server repo.

For example:
We create a new local directory for our weekly project using our CLI (Terminal or Command Prompt):  mkdir week1Assignment
We log into our GitHub account in a browser of our choice and create a new repository   ***NOTE:  The GitHub repo name could be something like week1Assignment, as well.
We run the commands that GitHub gives us in our CLI in the directory we made***NOTE:  we have to cd into the new local directory first:   cd week1AssignmentThe commands used in Terminal (Mac) or Command Prompt (Windows) typically look like this:

echo "# week1assignment" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/GitUser/week1assignment.git
git push -u origin main


***Note: GitUser will be your GitHub account username
***Note: instead of running git add README.md we can run git add . to add all files.
![image](https://user-images.githubusercontent.com/124002280/222978119-3896cb24-62f6-4bb1-a54e-404f1a8d1891.png)
