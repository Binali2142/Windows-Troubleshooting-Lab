# Case 02: Network Connectivity Issue

## Issue Description
User unable to browse the internet; shows “No Internet Access.”

## Root Cause
Corrupted or outdated IP configuration.

## Troubleshooting Steps
1. Opened CMD as Administrator.  
2. Ran `ipconfig`, found no valid IP address.  
3. Executed:
4. Restarted network adapter via `ncpa.cpl`.  
5. Verified internet restored.

ipconfig /release
ipconfig /renew
ipconfig /flushdns

 **Before:**  
![ipconfig error](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_02_Network_Issue/01_No_network.png)

 **After:**  
![Network restored](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_02_Network_Issue/02_Network_restored.png)

##  Resolution
Renewing IP configuration fixed the network issue.

##  Lessons Learned
DHCP issues are common and often solved by releasing and renewing IPs.

