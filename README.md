<p align="center">
COBALT STRIKE 4.7.2 : Out Of Band Update
</p>

<p align="center">
  <img src="https://github.com/AnonymousServersForTeamsWithC2/COBALT-STRIKE-4.7.2/blob/main/img1.png" alt="animated" />
</p>

``` 
October 17, 2022 Cobalt Strike 4.7 - Cobalt Strike 4.7.2
-------------
+ Added new memory option for Malleable C2 Profile for BOF execution, allowing user to define how BOF exists in memory.
+ Updated the way Beacon handles BOF
   BOF memory sections are now co-located, this fixes an issue where BOF might not run due to address offsets > 4GB.
   Added support for additional relocation types.
   Increased the number of available dynamic functions from 32 to 64.
+ Added SOCKS5 proxy server support, including DNS resolution and UDP support.
+ Updated sleep mask to execute as BOF.
   Sleep mask size limit increased from 769 bytes to 8192 bytes.
+ Updated module stomping to support the ability to specify a starting ordinal when searching for exported functions.
+ Updated steal_token to make it possible to steal tokens from previously inaccessible processes by making the access mask customizable.
   Also updated the Steal_token dialog in the UI to make it easier to set the access mask.
+ Added option to import credentials in "View - Credentials" list. An additional export option has been added to facilitate this.
+ Added a stageless payload generator dialog that allows you to set "Thread" or "Process" as exit options.
+ Added a new command "clipboard" to steal the contents of the Windows clipboard.
   An Aggressor Script function "bclipboard" was also added to steal the contents of the Windows clipboard.
+ Updated Beacon interaction in UI. Double-clicking on the Beacon now opens the Beacon Console (i.e. interacting with the Beacon).
+ Added preference to set whether to always show team server tab bar (unchecked by default).
+ Added a new menu item that allows users to generate x86 and x64 stageless payloads for all available payload variants at once.
   A new Aggressor script function "all_payloads" has also been added to do this without showing a dialog.
+ Updated file browser handling to ensure actions are shown on the Beacon console and logged in the activity report the same way as when running the "ls" command.
+ Updated Process Browser handling to ensure actions are shown on the Beacon console and logged in the activity report the same way as when running the "ps" command.
+ Added sleep time tracking function.
   The sleep time of each Beacon is recorded and displayed in a new column in the Beacon table view
   Keep sleep time between team server restarts.
+ Added Beacon Health feature that uses each Beacon's sleep time and last check-in time to indicate if a Beacon is alive, disconnected or dead.
+ Updated the icons used in the UI and simplified the toolbar, removing buttons for some less popular functions.
+ Added dark mode option in UI.
+ Updated main menu to flatten and reorganize some menus.
+ Added a new dialog showing default shortcuts (Help -> Default shortcuts)
+ Updated Beacon and SSH console timestamps. They are both turned on by default now.
+ Updated Beacon status bar to show more information.
   The left section now shows hostname, host OS bitness (x86 or x64), username, process ID, process bitness (x86 or x64), parent process ID (linked beacons only), beacon comment ( Truncate if > 50 characters).
   The right section now shows the last connection time.
+ Updated event status bar to include team server local IP and beacon count.
+ Added two new Beacon console commands.
   "file_browser" opens the file browser.
   "process_browser" opens the process browser.
+ Updated Beacon context menu. Changes to Beacon, SSH, Graph, and Targets options.
+ Added automatic parsing and resolution of Windows error codes.
   Added a new Beacon console command "windows_error_code" that can be used independently to convert Windows error codes to messages.
   Added a new Aggressor script function "windows_error_code" that can be used to convert Windows error codes to messages.
+ Updated "ps" command output.
   Parent/child process relationships are resolved and displayed as a tree.
+ Updated images for beacons, sessions and goals in pivot and table views.
+ Updated Aggressor script function "setup_reflective_loader" to output ReflectiveLoader function offset to script console.
+ Fixed a reliability issue with how copy/paste works. Text is now reliably copied to the clipboard.
```

### SOCKS5 PROXY SERVER SUPPORT
### INCRASED FLEXIBILITY OF HOW BOF EXISTS IN MEMORY
### SLEEP MASK UPDATE
### TOKEN STORE
### MOD STAMPEDE UPDATE
### DARK MODE
### BEACON HEALTH TRACKING
### PHASELESS PAYLOAD GENERATOR WITH EXIT OPTION

<p align="center">
  <img src="https://github.com/AnonymousServersForTeamsWithC2/COBALT-STRIKE-4.7.2/blob/main/img2.png" alt="animated" />
</p>

```
# Cobalt Strike 4.7.2 (October 17, 2022)
5cc4e4df156579cbd01a09dd4c1daca513113f771cb5034a22c1e1dfb3ba424b	Cobalt Strike 4.7.2 Licensed (cobaltstrike.jar)

# Cobalt Strike 4.7.1 (September 16, 2022)
2387c9ead13876d70a332c4ce57c4c090232d346376e174c703b38cda39f3f8f	Cobalt Strike 4.7.1 Licensed (cobaltstrike.jar)

# Cobalt Strike 4.7 (August 17, 2022)
c1cda82b39fda2f77c811f42a7a55987adf37e06a522ed6f28900d77bbd4409f	Cobalt Strike 4.7 Licensed (cobaltstrike.jar) 
```

<p align="center">
  <img src="https://github.com/AnonymousServersForTeamsWithC2/.github/blob/main/profile/inject.png" alt="animated" />
</p>

<p align="center">
We host live workouts that are conducted remotely and do not contain pre-recorded videos.For training programs or other services,please contact us                                     injectexpdev@proton.me

<p align="center">
official website www.injectexp.dev
</p>
