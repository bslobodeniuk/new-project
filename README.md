Here are the steps to create a new GitHub repository and a development branch:

Create a new repository on GitHub:

Go to GitHub and log in to your account.
Click on the '+' icon in the upper right corner and select 'New repository'.
Name your repository 'new-project' and add a description if you want.
Choose whether the repository should be public or private.
Initialize the repository with a README.
Click 'Create repository'.
Clone the repository to your local machine:

Open your terminal.
Navigate to the directory where you want to clone the repository.
Run the command: git clone https://github.com/username/new-project.git
Create a new branch named 'development':

Navigate into the cloned repository: cd new-project
Run the command: git checkout -b development
Push the new branch to the remote repository:

Run the command: git push -u origin development
Now, you have a new GitHub repository with a 'development' branch. You can start working on new features in this branch without affecting the 'main' branch.

Remember to replace 'username' with your actual GitHub username in the 'git clone' command.