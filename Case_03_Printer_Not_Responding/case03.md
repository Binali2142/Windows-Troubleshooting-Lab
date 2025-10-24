# Case 03: Printer Not Responding

## Issue Description
Document stuck in the printer queue and not printing.

## Root Cause
Printer queue paused or spooler service stuck.

## Troubleshooting Steps
1. Opened **Devices and Printers, Generic/Text-Only printer**.  
2. Clicked **See what’s printing**.  
3. Found document paused.  
4. Selected **Printer, Pause Printing** (simulated freeze).  
5. Clicked **Resume Printing**, document printed.

 **Before:**  
![Printer queue stuck](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_03_Printer_Not_Responding/01_Printer_error_simulated.png)

 **After:**  
![Print success](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_03_Printer_Not_Responding/02_Printer_fixed_simulated.png)

## Resolution
Resuming queue fixed the issue.

## Lessons Learned
Printer queue management is key to resolving non-printing problems.

