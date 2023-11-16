# Welcome to Team 5607 Programmer's Guide

The *Programmer's Guide* allows those interested in being part of the programming team to have a consistent setup.

## Getting Started

### GitHub UserID

* Make sure you have a [github.com](https://github.com) user id.
* You will need to get added to the *SEASON-YEAR*-Programming Team to be able to contribute.
* New to Git and Github? Check out this article for a basic intro on how to do code versioning with Github. [Github QuickStart](https://docs.github.com/en/get-started/quickstart/hello-world)

  
### WPILib.org
Firewall's progamming team relies heavily on WPILib.org's set of tools and libraries to jump start our robot's programming. They publish updates with every season. So it's good to be familiar with their docuementation and check for periodic updates during the competition season.  So go ahead and visit [wpilib.org](http://wpilib.org).
* [2023 WPILib Installation Guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html)
* [WPILib GitHub ](https://github.com/wpilibsuite/allwpilib/releases/tag/v2023.4.3) Download page for grabbing current releasses once you've installed WPILib's version of Visual Studio

### Fast track to becoming a Firewall programming Expert
Mentors recommend reviewing the following pages of the WPILib documentation to be program champions and decrease chance of frustation.
* [WPILIb Visual Studio Code Basics an WPILib Extensions](https://docs.wpilib.org/en/stable/docs/software/vscode-overview/vscode-basics.html) The version of Visual Studio Installer that you downloaded from the WPILib Install site has some commands built in to help you program. This section helps you leverage them. Be sure to click through to the commands section.
*  [Creating a Robot Program](https://docs.wpilib.org/en/stable/docs/software/vscode-overview/creating-robot-program.html) Overview of how to organize FRC Robot code. 
* [Building and Deploying Robot Code](https://docs.wpilib.org/en/stable/docs/software/vscode-overview/deploying-robot-code.html#) You've got your code all written, now what do you do??? Just keep clicking through this section to learn how to build, deploy, and debug with WPILib and Visual Studio.

## Robot In A Weekend -*RIAW*
* Setup a GitHub account if you don't have one. [github.com](https://github.com)
* Install Visual Studio with the WPILib Installer
* Grab the RIAW code from GitHub
     * Go the the  [Firewall/RIAW-TimedRobot public repository](https://github.com/FirewallRobotics/RIAW-TimedRobot.git) Be sure to "Star" it so it shows up under "Stars" in your personal profile, that will make it easier to find again later. While you are saving repositories, star this [Programming Guide Repo](https://github.com/FirewallRobotics/ProgrammingSetup) as well.
     * [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) the repository.
       * Open "Terminal" in WPILib Visual Stuio 2023, or current year version.
       * Change directory to where you want your Firewall workspace to be.
       * git clone https://github.com/FirewallRobotics/RIAW-TimedRobot.git
       * #### change into the `repo` directory
               cd RIAW-TimedRobot

         #### create a new branch to store any new changes
               git branch my-branch

         #### switch to that branch (line of development)
               git checkout my-branch

         #### make changes, for example, edit `file1.md` and `file2.md` using Visual Studio or Text editor
         #### stage the changed files
              git add file1.md file2.md

         #### take a snapshot of the staging area (anything that's been added)
              git commit -m "my snapshot"

         #### push changes to github
              git push --set-upstream origin my-branch      
         
  * Design behaviors you want to implement for this robot, place on story board, priortize, break up into pairs, and divy out tasks.
  ### Preliminary list of tasks:
   * Setup to program the Revrobotics Spark max controllers
      * 2023 RIAW design has two Neo motors with Revrobotics Spark Max Controllers. Check out Rev robotics support documentation for the [Spark Max controllers
](https://docs.revrobotics.com/sparkmax/gs-sm) The Controller Area Network (CAN bus) is a message-based protocol designed to allow the Electronic Control Units (ECUs) found in today's automobiles, as well as other devices, to communicate with each other in a reliable, priority-driven fashion.
      * Someone with a Windows computer system will need to [ download the latest rev hardware client](https://docs.revrobotics.com/sparkmax/rev-hardware-client/getting-started-with-the-rev-hardware-client#installation-instructions) so that we can configure the Spark max controllers.
      * [Revrobotics API for CANSparkMax](https://codedocs.revrobotics.com/java/com/revrobotics/package-summary.html) 
  
## Continue on!
### That's all great, but I want to Specailize!!
Do you prefer to work with user interfaces? or are you fascinated by a world with image processing and machine learning?  The team can use your passion and intrest working in either or all of these specialist areas...keep reading :)
* We want an out of this world control dashboard!! so we need exeperts on:
  * [ Dashboards](https://docs.wpilib.org/en/stable/docs/software/dashboards/index.html) WPILib has 4 to choose from. Glass is the newest. Check them out and see what layouts you can create with them. Drive team will thank you!
  * [ DriverSation](https://docs.wpilib.org/en/stable/docs/software/driverstation/index.html#)
  * [ RobotSimulation](https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/robot-simulation/index.html)
  * [ Joysticks ](https://docs.wpilib.org/en/stable/docs/software/basic-programming/joystick.html#driver-station-joysticks)
* Image processing so our robot can choose targets and assist drivers.
  * [ Vision Processing](https://docs.wpilib.org/en/stable/docs/software/vision-processing/index.html) Yes!! Give us _*vision*_.
* [ Hardware Tutorials](https://docs.wpilib.org/en/stable/docs/hardware/hardware-tutorials/index.html) How to make the motors go, understand sensor output, control pnematics, etc. etc.

### Crosstrain
We can't program the robot if the componenents aren't wired in correctly. Consider cross training with the Electical team so that we can work more efficently.
* Check out this overview of [Basic FRC robot wiring](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-1/intro-to-frc-robot-wiring.html#attach-battery-connector-to-pdp)
* [ Wiring the Spark Max Controllers](https://docs.revrobotics.com/sparkmax/gs-sm)## Go back to the top level [Readme](https://github.com/FirewallRobotics/ProgrammingSetup/blob/main/README.md#programmingsetup)

## Notes from past seasons
### VSCode
If you followed the steps above in the WPLILib Installation Guide You do not need to download Visual Studio again.

Note that while Visual Studio Code can be installed as a stand alone IDE(Integrated Development Environment) it is recommeded
to use the Visual Stuidio Installer linked to WPILib install. See installation steps at the following link or find the 
instructions for the corresponding competion year.
https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html

You will want to become familiar with the user interface.  Be sure to take some time to read over:  https://code.visualstudio.com/docs/getstarted/userinterface

### Install Python (co-processor programmers)

A python installation is required to do any co-processor programming.  Python 3 is required to meet our needs.
[Install Python 3](https://docs.python-guide.org/starting/installation/)
* Be sure to follow the *Python 3 Installation Guides*

#### Install VSCode Extensions

* Bracket Pair Colorizer
* CodeMetrics
* Debugger for Chrome
* Docker
* ESLint
* Git Graph
* GitLab Workflow
* GitLens
* Kubernetes
* Live Share
* Remote Development
* Todo Tree
* Trailing Semicolon
* Trailing Spaces
* Visual Studio IntelliCode
* vscode-icons
* YAML
* Python extension from Microsoft

#### Enable Python Linting

Linting will ensure our Python code is consistently styled.
  * From the Command Palette
    * "Python: Enable Linting"
    * "Python: Select Linter", pycodestyle

You may need to install pycodestyle on your platform(Computer of choice).

### Install WPILib Components

Coming Soon...
