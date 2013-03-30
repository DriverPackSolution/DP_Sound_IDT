IDT(R) HD Audio Driver [Formerly SigmaTel(R) HD Audio Driver]
=============================================================

March 25, 2009

This driver package supports the following operating systems:
- Windows XP 32
- Windows XP 64
- Windows Vista 32
- Windows Vista 64

Un-installation instructions
============================
If upgrading from previous IDT or SigmaTel driver, uninstall the original driver before running setup.

+To uninstall in Windows XP 32 and 64:
--------------------------------------
Go to "Start", "Control Panel", "Add or Remove Programs", select IDT and/or Sigmatel driver and "Remove".


+To uninstall in Windows Vista 32 and 64:
-----------------------------------------
Go to "Start", "Control Panel", "Programs and Features", select IDT and/or Sigmatel driver and "Uninstall". 



Installation of new driver
==========================
(Typical user) To install using the Wizard, run setup.exe from the DISK1 folder, reboot if required.

+(Advanced user) INF installation with Windows XP:
--------------------------------------------------
  1. Go to "Control Panel", "System", Hardware tab - "Device Manager", under Sound, video and game controllers, right-click High Definition Audio CODEC and select "Update Driver..."
  2. Choose "Install from a list or specific location (Advanced)" and choose "Next".
  3. Check the box "Include this location in the search:" and browse to DISK1\WDM\WinXP folder from the driver package and choose "Next".
  4. XP will now install the audio driver from the INF file.


+(Advanced user) INF installation with Windows Vista: 
-----------------------------------------------------
  1. Go to "Control Panel", "System", "Device Manager" on the left side, under Sound, video and game controllers, right-click High Definition Audio CODEC and select "Update Driver Software".  
  2. Select "Browse my computer for driver software". 
  3. Navigate to the WDM folder located in the DISK1 folder and choose "Next".   4. Vista will now install the audio driver from the INF file.

Thanks, 
IDT PC Audio Team