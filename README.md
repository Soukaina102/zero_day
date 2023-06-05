# Create and setup your Git and GitHub account

## Prerequisites
Before you begin, ensure that you have Git installed on your computer. If Git is not installed, you can download and install it from the official Git website (https://git-scm.com/).

## Configure Your Basic Info
To set up your basic information (name, email) on your local machine, follow these steps:
1. Open git bash.
2. Run the following commands, replacing `Your Name` with your actual name and `youremail@example.com` with your email address:
       git config --global user.name "Your Name"
       git config --global user.email "youremail@example.com"

## Creating the Repository on GitHub.com 
1. Open your web browser and go to https://github.com/.
2. Once you're logged in, click on the "+" button in the top right corner of the page and select "New repository" from the dropdown menu.
4. On the "Create a new repository" page, provide the following information:
- Repository name: `zero_day`
- Description: This is my first repository as a full-stack engineer.
- Visibility: Keep it as public (default).
- Checkboxes: Leave the checkboxes for README, .gitignore, and license unchecked.

## Setting Up the Project on Your Computer
1. Open git bash.
2. Navigate to your home directory using the following command:
cd ~
3. Create a directory named `zero_day` by running the following command: 
mkdir zero_day
4. Navigate to the newly created `zero_day` directory: 
cd zero_day
5. Initialize Git in the `zero_day` directory:
git init
6. Add the remote origin by running the following command:
git remote add origin https://github.com/your-username/zero_day.git
Replace `your-username` with your actual GitHub username.
7. Create a file named `README.md` using your preferred command line editor(vi)
Add content to the `README.md` file to provide an overview of your project.
