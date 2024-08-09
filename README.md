# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   Step 1
   Check system requirements
   Before downloading windows 11, ensure that your PC meets the minimum system requirements. Checke your PC compatiblity using the PC Healthy Check available from Microsoft.
   If you are running windows 10 and your PC meets the minimum system requirements to upgrade to windows 11,you will click download and install.
    If the windows update isn't giving you quick option to upgrade to windows 11, one can download windows 11 installation assistant,when it finish downloading run Windows11InstallationAssistant.exe and give administrator approval.
    Select accept and install, then begin the windows 11 update process


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code.  https://www.microsoft.com/software-download/windows11
step 1
Visit the official website of the Visual Studio Code using any browser eg google chrome 
Step 2
Press the download for windows on the website to start the download of Visual Studio Code applications .
Step 3 
When the download is completed, the Visual Studio Code icon will appear in the downloads folder.
Step 4 
open the download and click on the installer icon to start the installation process.
step 5
License Agreement
After the installer opens click I accept the agreement and then click the next button. 
Step 6
Select Additional Tasks
Choose the location data for running VSCode, then click next.
Step 7
Ready to Install
Click on the install button.
Step 8
 Installing 
 After clicking the install button, it will take about a minute to inatall Visual Studio Code on your laptop.
 Step 9 
  After the installation setup for VSCode is finished, a window will show up, tick "Launch Visual Studio Code" checkbox and then click finish. 
  Now the Visual Studio Code Window will open successfully.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   Step 1
   Visit the official git download page and click the latest Git version for windows 64-bit.
   Step 2
   Double click the downloaded file to launch the installer.
   step 3
   Review the GNU General Public License, and when you are ready to install click next 
   Step 4
   The inataller will prompt you to an installation location, leave the default one and click next.
   Step 5
   Select Components
   Leave the defaults and click next.
   Step 6 
   Select Start Menu Folder
   Click next.
   Step 7
   Choosing the default editor used by Git
   Select a text editoryou want to use with Git, and then click next.
   Step 8 
   This step allow you to choose a different name for your initial branch. You can leave the default option and click next.
   STEP 9 
   This step allow you to change the path environment, leave it at default and click next.
   STEP 10
   Choosing the SSH executable 
   The installer prompts you to select the SSH client for Git to use. Leave it as dwfault and click next
   Step 11
   choosing HTTPS transport backed
   Leave it at default and click next
   Step 12 
   Configuring the line ending conversions 
   leave it at default and click next.
   Step 13
   Configuring the terminal emulator to use with Git Bash 
   Leave it at default and click next.
   Step 14 
   the setp allow you to choose what the git pull command will do.leave it at default and click next.
   step 15 
   this step is to choose which credential helper to use. Leave default option and click next.
   Click next again then click install.
   step 16 
   Once the installation is completed tick the box to view release notes and click finish.

   How to configure 
   My identity in git is my username or my email adress, this is what git uses every time one creates a commit.
   step 1
   open git bash and write git config --global user.name "[username]" where name is your actual name 
   Step 2
   Write git config -- global user.email "[eamil]" where email is your actual email.


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from  programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Step 1
  Visit the official page for python www.python.org choose the correct link for your device and proceed to downloading.
  Step 2
  Run the installer 
  double click the downloaded file to lounch the python installer. Click the Add python.exeto PATH and after that click the Install Now Button, the setup will start installing python.
  Step 3 
  After completing the setup python will be installed on your windows system. A successful message will pop up.
  Step 4 
  Verify the python installation in windoews 
  Close the window after successful installation of python. Check if the installation of python was successful by using command prompt. To access the command prompt click on the start menuand type "cmd" in the search bar, then run as an administrator. On the command promtpt type 
  python --version and pip --version


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Before installing pip chake if it is already installed, type pip help in the command prompt. If pip respond with an error message then you have to install pip.
   step 1 
   download PIP get-pip.py, run this curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py on the command prompt.
   Step 2
   Install pip
   Run this python get-pip.py on the command prompt.
   step3 
   Type this python -m pip help to verfy installation
   step 4
   Add pip to path
   Add it to windows environment variables 
   open start menu, search for environment variables, and press enter.
   Click the environment variable, double click path to edti, select new and add the directory where PIP is installed. Click ok to save changes.
   Open a new command prompt session and run this "pip help" to test the changes.
   Step 5
   configuration
   To view the current configuration and all the possible file locations type "pip config -v list"
   Incase one need to upgrade pip type pip install --upgrade pip and get the latest version of pip.

                                                                                                  
  6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   Step 1
   Visit the official website of MySQL, choose the type of your operating then choose the version number for the MySQL community server.
   Step 2 
   After downloading the setup, unzip it and double click the file unzip it.
   step3 
   Double click the file to open and choose the seup type, here I select full option and clck next.
   step 4
   Check Requirements
   Here I click execute to install all the requirements automatically or to skip them, and then I click next.
   step 5
   Here there is a dialog box that asks for confirmation of a few products not getting installed, click yes button. After clicking yes one will be able to see a list of all the products which are going to be installed, click execute button and the products will be downloaded and installed. After the installation is completed click next.
   Steo 6 
   product configuration
   click next, and then click on the Standalone MySQL Server/Classic MySQL Replication option and click next.
   Step 7
   Types of network
   here I selected the Config Type as 'Development Machine' and Connectivity as TCP/IP and Port Number is 3306 then click next
   Step 8 
   Select the Authentication Method and click next.
   Step 9
   Accaount and Roles 
   The account will request for password, then click next
   Step 10
   Windows Service 
   leave everthing at default and click next.
   Apply Configuration 
   Here click execute and then click finish.
   Step 11
   Product Configuration 
   leave it at default and then next.
   Step 12 
   MySQL Router Configuration
   Choose configure the Router and click next
   Step 13 
   Connect to server
   Here we have to mention the root password click next and then select the applied configuration and click execute and then click finsh button.



7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. E/
\xplore Extensions and Plugins:
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
