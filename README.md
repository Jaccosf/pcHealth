# pcHealth

Check the health of your Windows installation and much more!

![GitHub](https://img.shields.io/github/license/REALSDEALS/pcHealth?label=License) ![GitHub Top Language](https://img.shields.io/github/languages/top/REALSDEALS/pcHealth?color=green&label=Batchfile) ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/REALSDEALS/pcHealth?label=Release) ![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/REALSDEALS/pcHealth?include_prereleases&label=Release) ![GitHub Repo Size](https://img.shields.io/github/repo-size/REALSDEALS/pcHealth?label=Repo%20Size)

## What is the main purpose?

pcHealth is an executable .bat/.ps1 file, which gives you the possibility to check not only your Windows installation on corrupt files, but it can also check your battery level. This is handy if your laptop can't hold its battery power properly. Besides that you can also get your Ninite from the script! It is also possible to open and re-open the created logs.

## How to use?

First of all I want to thank your for installing/using my pcHealth script.
It's quite a handy tool for any IT'er or other computer related problem solving/troubleshooting.

### Now more information on how to use it;

- Download this repository.
- Extract it to the desktop to be sure that it will run with full permissions.
- Open the `scripts` folder and choose your preferred method by choosing the `CMD` or `PowerShell` folder.
- Open the file in the chosen folder and read the rules carefully.
- Enter in the number of the desired command that you want to run. (Number + ENTER)
- Patiently wait for the script to finish.
- You can chose, depending on the command, what you want to do next. (Open logs ect.)

### SYSINFO - Number 1

Running this command will give you the information about the system.
For example, which CPU, what the PC its name is ect.

### CPUANDGPUINFO - Number 2

When number 2 has ran, you can read back which CPU and GPU are in the system.

### SFC - Number 3

When running SFC the command will start an system scan, to check the integrity of the Windows files.
When it comes back positive you don't have to do anything else, your system doesn't have any corrupt files, Windows related.

When it comes back negative, you have the option to check the logs (be sure to check the bottem of the log) to see what is in need of a repair. After that you have the option to start the DISM command to try and repair the corrupt files. If this works you may want to restart your pc and run the SFC command again.

### DISM - Number 4

The DISM command is a command to run an image scan/check and/or repair of your Windows image (iso.)

If the commands fail, you get the option to repair the image.
This may not work, if it doesn't and errors keep appearing, then it might be smart to re-install the pc with a clean version of Windows.

### SFC & DISM - Number 5

This entry runs the SFC and the DISM command after each other.
After the SFC you get the option to return to the menu when no corrupt files are found.

### Battery report - Number 6

When you enter this number the script will generate a battery report.
In this battery report you can read up on your battery status from your laptop.

### Open Windows Update - Number 7

With this entry you will open the GUI to Windows Update, to search and start for Windows Update(s.)

### Do a short Ping request - Number 8

This command will run a short ping command with small package(s) so we can to get a conclusion if the pc/laptop gets a connection or not.

### Do a continues Ping request with package bytes of 256 - Number 9

Number 9 will run a continues ping test with package bytes of 256, you have to manually stop it with (ctrl + c.)

### Re-open the Battery Report - Number 10

This entry will re-open the generated battery report file.

### Re-open the DISM Log - Number 11

With this entry you can re-open the DISM/CBS.log.

### Get your Ninite - Number 12

When entered number 12 a download will start, this download will install:

- Edge
- Chrome
- VLC
- 7ZIP

Edge will be installed so you have the latest version of it, after a clean install this is recommanded.

## Get your Windows License Key - Number 13

Want to find your systems license key? 
You can, just run this simple line of code.

### Log off, restart and/or shutdown - Number 14

When entering this number you get to choose if you want to log off, restart or shutdown your pc.

### Open up a sub-menu with downloadables! - Number 15

Open up a handy dandy menu with direct links to download servers of a small handfull of usefull IT programs!
So you can test your system.

### Close the Script - Number 16

With number 14 you can close the script.

## Questions

If you have any questions about this project or anything else regarding this repository...

Feel free to contact me!
You can mail me - please check out my profile to write an email to me.

## Win_Scan

Yes, Win_Scan is my other repository, but the function that Win_Scan does has been implemented here...
So you can use both, I'll keep both of them up, but this one will be more advanced when it's finished.

Link to Win_Scan: https://github.com/REALSDEALS/Win_Scan
