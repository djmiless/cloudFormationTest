A solution to test your cloud formation templates with a tool called "Taskcat"
Taskcat is an open source tool provided by the aws quickstart team.


*REQUIREMENTS 
prerequisities include Python, pip and TaskCat.

TaskCat uses Python so you will need to install Python.

Currently only installation via pip is supported to install taskcat, From your IDE terminal, type the following command to install taskcat

A) pip3 install taskcat
To verify TaskCat is installed, type "taskcat --version" from the command line

From your IDE terminal, type the following command to run TaskCat against your CloudFormation template.

B) taskcat test run 

When successful, the results will display "stack launch was successful" as part of the result messages.
TaskCat will create and delete CloudFormation stacks for all the files listed in the .taskcat.yaml file
Once it’s complete, you can open the index.html generated in the taskcat_outputs directory to view the TaskCat dashboard.To do this, right click on the index.html file in your IDE and click Preview on the context menu.


-- Windows
Taskcat on Windows is not supported.

If you are running Windows 10 it is recommended that you install Windows Subsystem for Linux (WSL) and then install taskcat inside the WSL environment.