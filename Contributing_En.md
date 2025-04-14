Thank for your contribution. Please follow the guidelines below to contribute to the project.
# Summary
- [1. Fork the project](#1-fork-the-project)
- [2. Clone your fork](#2-clone-your-fork)
- [3. Find an issue or open your own issue](#3-find-an-issue or open your own issue)
- [4. Create a branch](#4-create-a-branch)
- [5. Add your changes](#5-add-your-changes)
- [6. Open a pull request](#6-open-a-pull-request)

# 1. Fork the project
To fork the project, click on the "Fork" button at the top of the project page. This will create a copy of the project in
your account.

# 2. Clone your fork
To clone the project, click on the "Code" button and copy the URL. Then, open your terminal and run the following command:
```git clone <URL>```. Then, navigate to the project folder with the command ```cd Dollar-BC``` and create a virtual 
environment with the command ```python -m venv venv```. Activate the virtual environment with the command, on Linux,
```source venv/bin/activate``` and on Windows, ```venv\Scripts\activate.bat```. Finally, update pip with the command
```pip install --upgrade pip``` and install the project dependencies with the command ```pip install -r requirements.txt```.

# 3. Find an issue or open your own issue
To find an issue, go to the "Issues" tab and look for an issue that you would like and comment "Bora" to work on. 
You can also open your own issue if you have a feature request or found a bug.
# 4. Create a branch
To create a branch, run the following command in your terminal:
```git checkout -b <branch-name>```. The branch name should correspond to the issue you are working on. 
For example, if you are working on issue #1, the branch name should be "1".
See the example:```git checkout -b 1```.
# 5. Add your changes
To add your changes, run the following command in your terminal:
```git add .```. This will add all the changes you made to the staging area. 
Then, run the following command to commit your changes:
```git commit -m "Your commit message"```. The commit message should be descriptive and explain what changes you made.
# 6. Open a pull request
To open a pull request, go to the "Pull requests" tab and click on the "New pull request" button.
Select the branch you created and click on the "Create pull request" button.
Add a title and description to your pull request and click on the "Create pull request" button.
This will notify the project maintainers that you have made changes and would like them to be reviewed.
**Recommendations**
- Detail your changes in the pull request description;
- If it needs, add images to the pull request;
- If it is a bug, add the steps to reproduce the bug;
- Resolve just one issue per pull request;
- Write one issue for each task;
- avoid writing comments in the code, for this, write on Documentation.md;
