# 🐧Linux
How to Switch from Windows to Linux!

Switching to Linux may look hard, but it's
just a matter of wrongdoing. Depending on
the Linux Distribution, it could be really
easy or really hard.

# DON'T BE LIKE PEWDIEPIE WHO'S FIRST DISTRO WAS ARCH. NEVER.

Welcome to a long-time user's POV on How to
Switch to Linux.
------------------------------------------
# WHAT IS A LINUX?
Linux is actually NOT an operating System
itself, it is a Kernel (the heart of the OS)
And because of that There are many 
Linux-based Operating Systems (Distros)
That cater to Different types of Users.

For Example:
Ubuntu is a Linux Distro for Normal Users.
Debian is a Linux Distro for Server Users.
Android is a Linux Distro for Phones.
------------------------------------------
# Links
These Links are here for - Well idk.

Ubuntu)
These are links to the ISOs You'll need
for later.
------------------------------------------
[Ubuntu 24.04 LTS](https://ubuntu.com/download/desktop/thank-you?version=24.04.3&architecture=amd64&lts=true "Ubuntu with Long Updates")

This link downloads the iso for Ubuntu 
24.04. LTS means this Version receives
Lots of Software Updates. This may Change 
as the case for Ubuntu 16.04 LTS. Ubuntu
24.04 LTS lasts until April 2029 without
An ESM Subscription and until April 2034 
With Said Subscription.
------------------------------------------
[Ubuntu 25.04](https://releases.ubuntu.com/plucky/ubuntu-25.04-desktop-amd64.iso "Ubuntu With Latest Features")

This Link downloads the iso for Ubuntu 
25.04. This isn't LTS so it might not receive
as much Software updates as 24.04 but it
includes newer features such as GNOME 48 
and rust.
------------------------------------------
[Ubuntu Asahi Linux (for M1 and M2 Series Macs only!)](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://ubuntuasahi.org/&ved=2ahUKEwi6pb_BmrSPAxWqnq8BHQbsJfQQFnoECAsQAQ&usg=AOvVaw3ijN5JlDKz7tfvy4HhQ2_J "Ubuntu for overpriced Workstations")

This link redirects you to the Ubuntu Asahi
Linux Website, which has a guide on how to 
install This, which is out of scope of this guide.
------------------------------------------
[BalenaEtcher](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://etcher.balena.io/&ved=2ahUKEwjlm5fVmrSPAxUvn68BHcEGLpcQFnoECB8QAQ&usg=AOvVaw3qmwskOrLYXXgXtycdQXNa "Use a USB Drive!")

This link downloads the BalenaEtcher Windows
App which is needed to create the Install Media.
------------------------------------------
[Debian](https://cdimage.debian.org/debian-cd/current/amd64/iso-dvd/debian-13.0.0-amd64-DVD-1.iso "For PCs that run like Crap")

Use this instead of Ubuntu if your PC Doesn't reach the Requirements.
------------------------------------------
# How To Install
What you'll need:
1 USB Drive with 8gb Capacity 

A PC With 2ghz Processor, 4gb ram,
and 25gb of drive space
(Note: Check Settings/About to check requirements, if not met Download
Debian Instead)

Any of the ISOs Used (Ubuntu 24.04, 25.04,
or Debian Trixie)

BalenaEtcher Installed
------------------------------------------
# Step 1: Create Install Media
You'll need:

*A Working PC

*A USB Drive

*Your ISO Image

*BalenaEtcher Installer

1. Download the Installer Above
And Double-click to open. Follow the
steps to Install BalenaEtcher.
2. insert your USB Drive. Make Sure
there is NOTHING on it.
3. Open BalenaEtcher, then Select your
iso and USB Drive, and click Flash.
this should take around 15 minutes.
------------------------------------------
# Step 2: Boot into Linux
You'll need:
*A Working PC
*Your Install Media

1. Power Off your Computer.
2. Press your Computer's BIOS Key as
soon as your PC's Logo Appears.
This may be:

For Acer Users: Press F2.

For HP Users: Press ESC.

For Intel Mac Users: Press and Hold Option.

4. You are now in the BIOS. For All PCs
Excluding Intel Macs, Navigate through the
BIOS by using the left and right arrow
keys to switch tabs, up and down to select
options, and Enter or Spacebar to select.
For ACER users, Turn on The F12 Boot Menu
in the Main Tab.
For HP Users, Make sure it is Turned on.
for Mac Users, there is no Mac BIOS. do
absolutely nothing.
5. Restart your PC (skip if you're a Mac
User.)
6. Enter the Boot Menu.
For Acer Users, Press F12.
For HP Users, Press F9.
Navigate Through the Boot Menu and Select
Your USB Drive. if you Accidentally booted
into Windows or macOS instead, Just
Restart this step.
------------------------------------------
# Install Linux
Congratulations! You Are now in the
Setup! This is very Important.
Make Sure to follow the steps carefully
Especially if you want to Dualboot.

1. For Ubuntu Users only, Click the
Installer icon on your Desktop. Debian
has the Setup Loaded for you.
2. Follow the Instructions on the setup
until you reach the Disk Setup Part.
3. Once you're on there, Make sure to
select "Install on Free Space" if you
want to Keep Windows or "Format Disk"
if you want to replace Windows. Make
Sure you have Back up all of your
Personal data. if not, Reboot into
Windows One Last Time and Back up your
files from there.
4. ON DEBIAN ONLY: Once you reach the
Part asking for the Install Components,
Select "Desktop Environments" and Select
KDE Plasma.
5. Once you are done, Reboot your System.

# Congratulations! You have successfully switched to Linux.
------------------------------------------
# Additional Setup:
FOR UBUNTU USERS:
1. Log In to Your account and
Press The Win Key.
2. Open Terminal.
3. type in "sudo apt update; sudo apt upgrade"
4. Enter Your Password. You Can't see the
Password while typing, so watch your keys
and be careful.
5. Once that finishes, type "sudo apt install kde-full -y" or "sudo apt install kde-standard -y".
6. Enter Password when prompted.
7. When Prompted to choose a Display Manager, Choose SDDM.
8. Reboot your system.
9. before you log in, you'll see a desktops tab or something similar. Click it and Select KDE or KDE Plasma.
Congratulations! Now your Linux looks
like Windows 10! If you really want to
make it look like Windows 10, Download a
theme from the KDE Store.

FOR DEBIAN USERS:
When you boot Debian, you'll see a Boot
menu. This is called GRUB. You Should have
2 Options: Debian and Windows/macOS (macOS could be shown as Darwin or BSD."
if not, follow these steps. Oh, and Mac Users begone.
1. For Now, Boot into Debian.
2. Open Terminal and check if you have a
package named os-prober. Run "os-prober"
and there should be command options. if
not, install with "sudo apt install os-prober".
2. still in the terminal, type "sudo nano /etc/default/grub" and add "GRUB_DISABLE_OS_PROBER=false".
3. save the file by pressing "ctrl+x" and choose y.
4. reboot.

The issue should now be fixed!
------------------------------------------
# Basic Commands
nano - text editor

apt/apt-get - app installer

cp - copy file

sudo - admin privileges

rm - delete file

rm -rf - delete folder

mv - move file

exit - exit terminal

# End of Tutorial!
©2025 NinMan64 Productions

v1.1


.... .... . ..... ...   . ........       .

