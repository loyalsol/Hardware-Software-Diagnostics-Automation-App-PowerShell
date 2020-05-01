# Hardware/Software-Diagnostics-Automation-App
Hardware/Software Diagnostics Automation App version 3.0 using powershell

UPDATED VERSION 3.0 -

Has both GUI and CLI Version and changed the behaviour and the way of the program output in the terminal
GUI Version - Added GUI Progress as front-end and Terminal execution will be at back-end followed by default open the log file with internet explorer and also with resource monitor application
CLI Version - Added CLI as well with Progress bar in the front-end and Terminal execution will be at the back end with 3 options to open the log files in either Notedpad OR Notepad++ OR internet explorer and also with resource monitor application. Also, can exit code without opening the files as well.
By default, the log file and real time performance data file will be located in the same directory where the application/software resides in the system
Compiled the code to a executable file with administrator rights enabled by default and when running the software, admin rights will be required to accept the software to run on the system

Added the "Getting of Installed Softwares - Software Name | Version | Installed Date | Publisher Information"

The below are the following features added to the code and the code will take all the information for the below and log into a file which is a read-only file and also performance monitoring graph with read-only mode.

Get the System Information
Get the OS Information
Get the Operating System: OS Version
Get the BIOS Version
Get the Baseboard (Motherboard) Details
Get the Motherboard Status
Get the CPU Processor Information
Get the Integrated Device Electronics Controller Status
Get the Onborad Device Details
Get the Physical Memory RAM Details
Get the Cache Status
Get the Keyboard Status
Get the Mouse Status
Get the Group Names (Installed Softwares)
Get the Installed Softwares - Software Name | Version | Installed Date | Publisher Information
Get the Installed Drivers and it's Status
Get the Disk Drive
Get the Disk Predictive Status Failure
Get the Disk Partition
Get the Logical Drives Details
Get the Network Adapter Details
Get the Network Adapter Configuration
Get the Network Protocol List and Status
Get the Battery Details
Get the Battery Charge Detail
Get the Battery Status
Get the Temperature Sensor Status
Get the Fan Sensor Status
Get the Printer and its Status
Get the BUS Version
Get the USB Controller status
Get the Screen Graphic Card Details
Get the Graphic card status
Get the CPU, RAM, Network Bandwidth both receive/send real time usage
Get the SCSI Controller status
Get the Serial Port Connection Status
Get the Audio Usage
Get the Real-Time Calculation of CPU Usage, Memory Usage, and Network Usage for a period of 2 minutes with 25 samples with an interval of 5 seconds once
Get the Application Event Logs (Software Logs) for the last 5 days
Get the System Event Logs for the last 5 days
Get the Microsoft Office Event Logs
Get the current end for execution current end time and store it
Calculate the difference of two timings and store and show it
Log the Real time values of CPU Usage, Memory Usage and Network Usage and plot and save the file in .blg format
Log all the above values into a text file and open it for us automatically according to the option given by the user during the initialization of the code
