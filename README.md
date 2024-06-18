[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292041&assignment_repo_type=AssignmentRepo)
# Dev_Setup
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Steps:

   Visit the Windows 11 download page.
   Follow the instructions to download the Windows 11 installation media.
   Create a bootable USB drive with the downloaded installation media.
   Restart the computer and boot from the USB drive.
   Follow the on-screen instructions to install Windows 11.

   

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   IDE: Visual Studio Code

Steps:

Visit the Visual Studio Code download page.
Download the installer for your operating system.
Run the installer and follow the on-screen instructions to complete the installation.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Version Control System: Git and GitHub

Steps:

Visit the Git download page and download the Git installer for your operating system.
Run the installer and follow the on-screen instructions to install Git.
Open Git Bash and configure Git with your user information:
sh
Copy code
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
Visit GitHub and create an account.
Create a new repository on GitHub.
Clone the repository to your local machine:
sh
Copy code
git clone https://github.com/yourusername/your-repository.git
Initialize a Git repository and make your first commit:
sh
Copy code
cd your-repository
echo "# Your Project" >> README.md
git add README.md
git commit -m "Initial commit"
git push -u origin main


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Programming Language: Python

Steps:

Visit the Python download page and download the installer for your operating system.
Run the installer and follow the on-screen instructions to install Python. Ensure you check the option to add Python to your PATH.
Verify the installation by opening a command prompt and typing:
sh
Copy code
python --version


5. Install Package Managers:
   If applicable, install package managers like pip (Python).



6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Package Manager: pip (Python)

Steps:

pip is installed by default with Python. Verify the installation by typing:
sh
Copy code
pip --version


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

   Database: MySQL

Steps:

Visit the MySQL download page.
Download the MySQL Installer for Windows.
Run the installer and follow the on-screen instructions to install MySQL Server and MySQL Workbench.
Configure MySQL Server by setting up a root password and other settings as needed.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Virtualization Tool: Docker (Optional)

Steps:

Visit the Docker download page and download Docker Desktop for Windows.
Run the installer and follow the on-screen instructions to install Docker.
Verify the installation by opening a command prompt and typing:
sh
Copy code
docker --version

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

Extensions for Visual Studio Code:

Python: Provides IntelliSense, linting, and debugging support for Python.
GitLens: Enhances the built-in Git capabilities.
Prettier: Code formatter.
ESLint: Linting for JavaScript and TypeScript.
Steps:

Open Visual Studio Code.
Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+X.
Search for and install the desired extensions.

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

