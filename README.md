[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280560&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

1. Check System Requirements:
Ensure your system meets the minimum requirements: 1 GHz 64-bit processor, 4 GB RAM, 64 GB storage, UEFI firmware with Secure Boot, TPM 2.0, DirectX 12 compatible graphics, and a 9” HD display.
 2. Backup Your Data:
Backup important files to an external drive or cloud storage.
3. Create a Bootable USB Drive:
Download the Windows 11 ISO from the Microsoft website.
Use the Rufus tool or the Windows Media Creation Tool to create a bootable USB drive (at least 8 GB).
4. Configure BIOS/UEFI Settings:
Restart your computer and enter BIOS/UEFI (press F2, F12, DEL, or ESC during startup).
Enable UEFI mode and Secure Boot. Set the USB drive as the primary boot device.
5. Install Windows 11:
Insert the bootable USB drive and restart your PC to boot from it.
Follow the Windows Setup screen instructions: select language, time, and keyboard preferences, then click "Next" and "Install Now".
Enter your product key or skip if you don't have it.
Accept the license terms and choose "Custom: Install Windows only (advanced)".
Select the drive/partition for installation, deleting existing partitions for a clean install if necessary.
6. Complete Installation:
The setup will copy files and restart multiple times.
Set up your region, keyboard layout, Microsoft account, and privacy settings.
7. Install Updates and Drivers:
Go to Settings > Update & Security > Windows Update to install updates and drivers.
Download additional drivers from your manufacturer’s website.

8. Restore Data and Install Software:
Restore your backed-up data and reinstall necessary applications.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   To download visual studio
   a. Open a browser on your laptop and Visit the Visual Studio website and click on "Download Visual Studio.", then choose the version you want and whether it is 32 bits or 64 according to the capabilities of your laptop.
   b. Run the downloaded installer and click next. After if click next for the start up menu. After then click on create desktop icon also check other boxes.
   c.  When the istallation is done you can click on the finish button and launch for it to run. Then the text edit of visual studio will open and you can create your first project.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   -> to install git open browser and type git download and download it. After download open and run as administrator then follow the procedure till fully install.

   To configure git
  Open Git Bash and configure your Git username and email:
- git config --global user.name "Your Name"
- git config --global user.email "your.email@example.com"

 To create github account
 - Open a browser and type github sign up. Then you will have to pass in your email address and create a password. Then after you will have to enter your user name, and then you will be send a verification email to vefiry your account and your account is created.

 To  Initialize a Git repository
 Initialize a new Git repository:
   git init

make your first commit
 git commit -m "This is my first commit"
  
4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  a. first you have to open cmd and type python --version to check the version of python if it is already install. if it is not there then you will procced to install
  b. Open a browser and ytpe python.org then go to download and pick windows and download the version of the python.
  c. After you have download run the downloaded python.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   -> To install pip you have to open command promp (cmd) for windows then, type winget install pip. Download process take place untill pip if fully install in your device. There after to confrim if pip has been install, you will type pip --version and you will be able to see the version of it.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
1. Download MySQL Installer:
Visit the MySQL Community Downloads page: MySQL Installer.
Download the appropriate MySQL Installer (Windows 32-bit or 64-bit).
2. Run the Installer:
Locate the downloaded MySQL Installer file and double-click to run it.
Select "Setup Type" as "Developer Default" to install the necessary components for development.
3. Choose a Setup Type:
Select "Server only," "Client only," "Full," or "Custom." For most purposes, "Developer Default" is recommended.
4. Install MySQL Server:
Follow the prompts to install the MySQL server. The installer will download and install all selected components.
5. Configure MySQL Server:
Server Configuration: Choose "Standalone MySQL Server."
Type and Networking: Use default settings or adjust based on your requirements. Ensure the port is set to 3306.
Authentication Method: Choose "Use Strong Password Encryption" for better security.
6. Set Root Password:
Set a strong root password for the MySQL server.
Optionally, create additional MySQL user accounts.
7. Configure Windows Service:
Check "Configure MySQL Server as a Windows Service" to ensure MySQL starts automatically with Windows.
Name the service (default: MySQL57).
8. Apply Configuration:
Review the configuration settings and click "Execute" to apply them.
The installer will configure the MySQL server and start the service.
9. Complete Installation:
Once configuration is complete, click "Finish" to exit the installer.
10. Verify Installation:
Open the MySQL Command Line Client or MySQL Workbench.
Log in using the root account and password set during installation.
Execute a simple SQL query to ensure the server is running correctly: SHOW DATABASES; 

    
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

1. Choose Virtualization Tool:
Select a virtualization tool like Docker or a virtual machine (VM) software such as VirtualBox or VMware.
Install Docker:
2. Download Docker from the Docker website.
Run the installer and follow the prompts to complete the installation.
Verify installation by opening a terminal and running docker --version.
3. Install Virtual Machine Software:
Download VirtualBox from the VirtualBox website or VMware from the VMware website.
Run the installer and follow the prompts to complete the installation.
4. Create Docker Containers or VMs:
For Docker: Write a Dockerfile defining your environment and build it using docker build -t your_image_name ..
For VMs: Create a new VM, allocate resources (CPU, RAM, storage), and install your preferred OS.
5. Configure Environments:
Install necessary dependencies and tools in your Docker container or VM.
Use configuration management tools like Docker Compose or Vagrant for complex setups.
6. Test and Validate:
Run your applications within the Docker container or VM to ensure everything works correctly.
Make adjustments as necessary to ensure consistency across different development environments.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

1. Determine Your Requirements:
Identify the features you need, such as syntax highlighting, linting, code formatting, version control integration, and language-specific tools.
2. Open the Extensions Marketplace
Access the Marketplace:
In Visual Studio Code (VS Code), click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X.
For other editors like Atom, Sublime Text, or IntelliJ IDEA, access their respective plugin or package managers from the menu or a similar interface.
3. Search for Extensions
Search for Extensions:
Use the search bar to find extensions relevant to your needs. For instance, search for "Python", "ESLint", "Prettier", or "Git".
4. Review and Install
Review and Install:
Read descriptions, reviews, and ratings to ensure the extension fits your needs.
Click the install button to add the extension to your editor.
5. Configure Extensions
Configure Extensions:
After installation, some extensions may require additional configuration. Follow the prompts or refer to the extension documentation.
Configure settings to tailor the extension to your workflow. For example, configure linting rules in .eslintrc for ESLint.
6.  Test the Setup
Test the Extensions:
Test the installed extensions by opening a relevant file and checking if the features work as expected (e.g., code formatting, syntax highlighting).
7.  Keep Extensions Updated
Update Regularly:
Regularly check for updates to keep your extensions up-to-date and ensure you have the latest features and fixes.

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
