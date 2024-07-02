[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283534&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.



## BELOW IS A COMPREHENSIVE REPORT OUTLINING THE STEPS TAKEN TO SET UP DEVELOPER ENVIRONMENT

# Step 1: Select and Install Your Operating System (OS)
Task:
Install Windows 11.

Steps:
Download Windows 11 Installation Media:

Visit the Windows 11 Download Page.
Click "Download Now" to get the Installation Media Creation Tool.
Run the Tool:

Execute the downloaded tool and follow the on-screen instructions to create a bootable USB or upgrade directly.
Install Windows 11:

If using a bootable USB, insert it into your computer, restart, and boot from the USB. Follow the prompts to install Windows 11.
Set Up Windows 11:

Complete the initial setup, including signing in with your Microsoft account and configuring settings.
Troubleshooting:
Issue: Installation media creation tool fails to run.
Solution: Ensure your system meets the requirements for Windows 11 and disable any conflicting software, such as antivirus programs.

## Step 2: Install a Text Editor or Integrated Development Environment (IDE)
Task:
Install Visual Studio Code (VS Code).

Steps:
Download the Installer:

Visit the Visual Studio Code Download Page.
Select the appropriate installer for your OS and download it.
Run the Installer:

Follow the on-screen instructions to install VS Code.
Launch VS Code:

Open VS Code and customize your settings as needed.
Customizations:
Settings Sync: Enable Settings Sync to synchronize your settings across devices.
Themes: Install and activate your preferred theme from the Extensions marketplace.
Troubleshooting:
Issue: VS Code fails to launch.
Solution: Reinstall VS Code or run it as an administrator.


## Step 3: Set Up Version Control System
Task:
Install Git, create a GitHub account, and initialize a Git repository.

Steps:
Install Git:

Visit Git Downloads and download the installer.
Run the installer and follow the instructions.
Configure Git:

Open a terminal or Git Bash and run:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Create a GitHub Account:

Visit GitHub and sign up for a free account.
Initialize a Git Repository:

Create a new directory for your project:
mkdir my-project
cd my-project

Initialize Git:
git init

Create a README file and make your first commit:
echo "# My Project" > README.md
git add README.md
git commit -m "Initial commit"
Push to GitHub:

Create a new repository on GitHub.
Follow the instructions provided by GitHub to push your local repository to the remote repository.
Customizations:
.gitignore File: Create a .gitignore file to exclude unnecessary files from the repository.

Troubleshooting:
Issue: Git commands fail to execute.
Solution: Ensure Git is correctly installed and added to your system's PATH.


## Step 4: Install Necessary Programming Languages and Runtimes
Task:
Install Python.

Steps:
Download the Installer:

Visit the Python Downloads Page.
Select the latest version and download the installer.
Run the Installer:

Check the box to add Python to PATH.
Follow the instructions to complete the installation.
Verify Installation:

Open a terminal and run:
python --version
pip --version

Customizations:
Virtual Environments: Use venv to create isolated Python environments for your projects.

Troubleshooting:
Issue: Python not recognized as an internal or external command.
Solution: Ensure Python is added to the system PATH during installation.

## Step 5: Install Package Managers
Task:
Install pip (Python's package manager).

Steps:
Verify pip Installation:

pip is included with Python. Verify it by running:
pip --version
Upgrade pip if Necessary:

Run the following command to ensure pip is up to date:
pip install --upgrade pip

Customizations:
Configure Pip.conf: Customize pip settings by creating a pip.conf file.
Troubleshooting:

Issue: pip command not found.
Solution: Ensure Python and pip are correctly installed and added to PATH.


## Step 6: Configure a Database (MySQL)
Task:
Install MySQL.

Steps:
Download the Installer:

Visit the MySQL Downloads Page.
Select the MySQL Installer and download it.
Run the Installer:
Choose the setup type (Developer Default is recommended).
Follow the instructions to complete the installation.

Configure MySQL:
Set up a root password and configure MySQL as needed.

Verify Installation:
Open the MySQL command line client and log in with the root password to ensure it works.

Customizations:
MySQL Workbench: Install MySQL Workbench for a graphical interface to manage databases.

Troubleshooting:
Issue: Unable to start MySQL service.
Solution: Ensure no other application is using the default MySQL port (3306).

## Step 7: Set Up Development Environments and Virtualization (Optional)
Task:
Consider using Docker or virtual machines.

Steps:
Install Docker:
Visit Docker Downloads and download Docker Desktop.
Follow the installation instructions.

Verify Installation:
Open a terminal and run:
docker --version

Use Docker:
Create a Dockerfile in your project directory and build your Docker image as needed.

Customizations:
Docker Compose: Use Docker Compose to manage multi-container Docker applications.

Troubleshooting:
Issue: Docker not running.
Solution: Restart Docker Desktop or your computer.


## Step 8: Explore Extensions and Plugins
Task:
Enhance VS Code with extensions.

Steps:
Open VS Code:
Click on the Extensions icon in the Activity Bar or press Ctrl+Shift+X.

Install Recommended Extensions:
Search for and install extensions like:
Python
GitLens
Prettier - Code formatter
ESLint
Docker

Configure Extensions:
Customize the settings for each extension as needed.

Customizations:
Settings Sync: Enable Settings Sync to synchronize extension settings across devices.

Troubleshooting:
Issue: Extensions fail to install.
Solution: Check your internet connection and retry.
