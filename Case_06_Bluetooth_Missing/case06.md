# Case 06: Missing / Disabled Bluetooth Adapter

## Issue Description
Bluetooth toggle missing in Settings, Bluetooth & Devices.

## Root Cause
Bluetooth adapter disabled in Device Manager.

## Troubleshooting Steps
1. Opened **Device Manager, Bluetooth section**.  
2. Found adapter with a **down arrow** (disabled).  
3. Right-clicked, **Enable device**.  
4. Verified Bluetooth toggle appeared in Settings.  
5. Paired Bluetooth mouse successfully.

 **Before:**  
![Bluetooth adapter disabled](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_06_Bluetooth_Missing/01_Bluetooth_disabled.png)

 **After:**  
![Bluetooth restored](https://github.com/Binali2142/Windows-Troubleshooting-Lab/blob/main/Case_06_Bluetooth_Missing/02_Bluetooth_restored_fx.png)

## Resolution
Enabled adapter; Bluetooth working normally.

## Lessons Learned
Always verify the adapter status in Device Manager before reinstalling drivers.

