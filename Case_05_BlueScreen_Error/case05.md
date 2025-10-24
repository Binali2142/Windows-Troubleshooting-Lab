#  Case 05: Blue Screen Error (BSOD)

##  Issue Description
System crashes with BSOD and error “DRIVER_IRQL_NOT_LESS_OR_EQUAL”.

##  Root Cause
Corrupted or outdated network driver.

##  Troubleshooting Steps
1. Checked **Event Viewer, System logs**.  
2. Found error referencing network adapter driver.  
3. Opened **Device Manager, Network Adapter**.  
4. Right-clicked, **Update Driver**.  
5. Restarted system, error resolved.

 **Before:**  
![BSOD error](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_05_BlueScreen_Error/01_blue_screen_of_death.png)

 **After:**  
![Fixed driver](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_05_BlueScreen_Error/02_driver_updated.png)

##  Resolution
Updated driver eliminated system crash.

##  Lessons Learned
Event Viewer helps identify root causes of system-level failures.
