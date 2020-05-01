# Hardware/Software-Diagnostics-Automation-App
Hardware/Software Diagnostics Automation App version 3.0 using powershell

UPDATED VERSION 3.0 -

Has both GUI and CLI Version and changed the behaviour and the way of the program output in the terminal.

GUI Version - Added GUI Progress as front-end and Terminal execution will be at back-end followed by default open the log file with internet explorer and also with resource monitor application.

CLI Version - Added CLI as well with Progress bar in the front-end and Terminal execution will be at the back end with 3 options to open the log files in either Notedpad OR Notepad++ OR internet explorer and also with resource monitor application. Also, can exit code without opening the files as well.

By default, the log file and real time performance data file will be located in the same directory where the application/software resides in the system.

Compiled the code to a executable file with administrator rights enabled by default and when running the software, admin rights will be required to accept the software to run on the system.

Added the "Getting of Installed Softwares - Software Name | Version | Installed Date | Publisher Information".

The below are the following features added to the code and the code will take all the information for the below and log into a file which is a read-only file and also performance monitoring graph with read-only mode.

1. Get the System Information

2. Get the OS Information

3. Get the Operating System: OS Version

4. Get the BIOS Version

5. Get the Baseboard (Motherboard) Details

6. Get the Motherboard Status

7. Get the CPU Processor Information

8. Get the Integrated Device Electronics Controller Status

9. Get the Onborad Device Details

10. Get the Physical Memory RAM Details

11. Get the Cache Status

12. Get the Keyboard Status

13. Get the Mouse Status

14. Get the Group Names (Installed Softwares)

15. Get the Installed Softwares - Software Name | Version | Installed Date | Publisher Information

16. Get the Installed Drivers and it's Status

17. Get the Disk Drive

18. Get the Disk Predictive Status Failure

19. Get the Disk Partition

20. Get the Logical Drives Details

21. Get the Network Adapter Details

22. Get the Network Adapter Configuration

23. Get the Network Protocol List and Status

24. Get the Battery Details

25. Get the Battery Charge Detail

26. Get the Battery Status

27. Get the Temperature Sensor Status

28. Get the Fan Sensor Status

29. Get the Printer and its Status

30. Get the BUS Version

31. Get the USB Controller status

32. Get the Screen Graphic Card Details

33. Get the Graphic card status

34. Get the CPU, RAM, Network Bandwidth both receive/send real time usage

35. Get the SCSI Controller status

36. Get the Serial Port Connection Status

37. Get the Audio Usage

38. Get the Real-Time Calculation of CPU Usage, Memory Usage, and Network Usage for a period of 2 minutes with 25 samples with an interval of 5 seconds once (Maximum of 3 minutes of time)

39. Get the Application Event Logs (Software Logs) for the last 5 days and Get the System Event Logs for the last 5 days

40. Get the Microsoft Office Event Logs

Get the current end for execution current end time and store it.

Calculate the difference of two timings and store and show it.

Log the Real time values of CPU Usage, Memory Usage and Network Usage and plot and save the file in .blg format.

Log all the above values into a text file and open it for us automatically according to the option given by the user during the initialization of the code.
