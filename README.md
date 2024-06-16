[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283002&assignment_repo_type=AssignmentRepo)
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


-- ANSWERS --

** Installing our operating system - Ubuntu(Linux)

Installing Ubuntu involves several straightforward steps. Here's a step-by-step procedure:

### Step 1: Obtain Ubuntu Installation Media

1. **Download Ubuntu ISO**: Visit the official Ubuntu website and download the latest stable release ISO file. Choose the 64-bit system architecture.

2. **Create Bootable USB**: Once downloaded, create a bootable USB drive using Rufus. This USB will be used to install Ubuntu on your computer.


### Step 2: Boot from USB and Start Installation

3. **Insert Bootable USB**: Insert the bootable USB drive into a USB port on your computer.

4. **Access Boot Menu**: Restart your computer and access the boot menu. This is usually done by pressing a key (like F12, Esc, or Del) immediately after powering on your computer. Select the USB drive as the boot device.

### Step 3: Install Ubuntu

5. **Start Ubuntu Live Session**: Once the computer boots from the USB, you will see the Ubuntu installer screen. Here, choose "Try Ubuntu" to run a live session and ensure everything works properly before installing.

6. **Launch Installer**: Double-click the "Install Ubuntu" icon on the desktop or select it from the Applications menu to start the installation process.

7. **Choose Installation Options**:
   - **Language**: Select your preferred language.
   - **Keyboard Layout**: Choose your keyboard layout.
   - **Updates and Other Software**: You can choose to install updates and third-party software during the installation process. This is optional.

8. **Prepare Installation Type**:
    - **Installation Type**: Choose "Erase disk and install Ubuntu" if you want to use the entire disk for Ubuntu. 

9. **Select Location**: Choose your timezone.

10. **Create User Account**: Enter your name, computer name, username, and password. 

11. **Begin Installation**: Click "Install" to begin the installation process. The installer will copy files to your hard drive and configure the system.

### Step 4: Complete Installation

12. **Restart**: Once the installation is complete, you will be prompted to restart your computer. Remove the USB drive before restarting.

13. **Login**: After rebooting, Ubuntu will boot from your hard drive. Enter your password to log in to your newly installed Ubuntu system.

- Installing VS Code

### Using Command Line 

1. **Open Terminal**: You can open the terminal either by pressing `Ctrl + Alt + T` or by searching for "Terminal" in the application launcher.

2. **Update Package Repository**: Run the following command:
   
   sudo apt update

3. **Install Visual Studio Code**: Use the following command to install VS Code:
   
   sudo apt install code
   
   This command will prompt you to enter your administrative password. Type it in and press Enter.

4. **Wait for Installation**: The terminal will download and install Visual Studio Code along with any necessary dependencies. 

5. **Launch VS Code**: Once installed, you can launch Visual Studio Code by typing `code` in the terminal and pressing Enter.

- Installing git and configuring it

### Step 1: Install Git

1. **Open Terminal**: You can open the terminal 

2. **Update Package Repository**: Run the following command:
   
   sudo apt update
   

3. **Install Git**: Use the following command to install Git:
   
   sudo apt install git

  
4. **Verify Installation**: After installation completes, verify that Git has been installed correctly by checking its version:
   
   git --version


### Step 2: Configure Git

5. **Set Up Your Identity**: Configure Git with your name and email address. This information will be used to identify your commits. Run the following commands, replacing `Your Name` and `your.email@example.com` with your own name and email:
   
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"

6. **Verify Configuration**: You can verify your Git configuration by listing all settings:
   
   git config --list

   This will display all the Git configurations set globally.

### Step 3: Initialize a Git Repository

7. **Navigate to Your Project Directory**: Navigate to the directory where you want to initialize a Git repository. For example, if you want to create a new repository in your home directory, use:
   
   cd ~

9. **Initialize Git Repository**: Use the following command to initialize a new Git repository in the current directory:

   git init
   
   This command creates a new `.git` subdirectory in your current directory, which contains all of the necessary Git metadata for your repository.

10. **Start Tracking Files**: Add files to the repository and start tracking them. For example, to start tracking all files in the current directory, use:
   
    git add .
   
    This command stages all files in the current directory for the next commit.

11. **Commit Changes**: Commit the staged files to the repository with a descriptive commit message. For example:
   
    git commit -m "Initial commit"
   
    Replace `"Initial commit"` with a meaningful message describing the changes made in this commit.


- Installing python and pip on ubuntu


### Step 1: Update Package Index

1. **Open Terminal**

2. **Update Package Repository**: Run the following command:
   
   sudo apt update

### Step 2: Install Python 3

3. **Install Python 3**: Use the following command to install Python 3 and the `python3-pip` package:

   sudo apt install python3 python3-pip


### Step 3: Verify Installation

4. **Verify Python 3 Installation**: After installation completes, verify that Python 3 is installed correctly by checking its version:
   
   python3 --version
   
   This command should output the installed Python 3 version


- Virtual Environment

Python Virtual Environments: It's good practice to use Python virtual environments (venv) for project-specific dependencies to avoid conflicts between different Python projects. You can create a virtual environment using:

python3 -m venv myenv

Activate virtual environment:

source myenv/bin/activate

and deactivate it with:

deactivate

- Installing MySQL on Ubuntu
   

### Step-by-Step Procedure to Install MySQL on Ubuntu:

### Step 1: Update Package Index

1. **Open Terminal**: 

2. **Update Package Repository**: Run the following command:
   
   sudo apt update

### Step 2: Install MySQL Server

3. **Install MySQL Server**: Use the following command to install the MySQL server package:
   
   sudo apt install mysql-server
 
4. **Configure MySQL Installation**: During the installation process, you may be prompted to set a root password for MySQL. Choose a strong password and remember it. If not prompted, MySQL will be installed with a default root password.

### Step 3: Secure MySQL Installation 

5. **Secure MySQL Installation**: MySQL comes with a script to secure the installation. Run the following command and follow the prompts to secure your MySQL server:
   
   sudo mysql_secure_installation
   
   This script will allow you to set a root password if you haven't already, remove anonymous users, disallow root login remotely, and remove the test database.

### Step 4: Verify MySQL Installation

6. **Verify MySQL Service**: After installation, MySQL should start automatically. You can verify the MySQL service status by running:
   
   sudo systemctl status mysql
   
   This command should show that MySQL is active (running).

### Step 5: Access MySQL

7. **Access MySQL Shell**: You can access the MySQL command-line shell by typing:
   
   sudo mysql
   
   You'll be prompted to enter the root password you set during installation.

-Installing MySQL Workbench


### Step-by-Step Procedure to Install MySQL Workbench on Ubuntu:

### Step 1: Update Package Index

1. **Open Terminal**: 

2. **Update Package Repository**: It's a good practice to update your package repository before installing new software. Run the following command:
   
   sudo apt update
 

### Step 2: Install MySQL Workbench

3. **Install MySQL Workbench**: Use the following command to install MySQL Workbench from the Ubuntu repositories:
  
   sudo apt install mysql-workbench
  

### Step 3: Launch MySQL Workbench

4. **Launch MySQL Workbench**: After installation completes, you can launch MySQL Workbench from the application menu or by typing `mysql-workbench` in the terminal.






