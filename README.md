# RecuvaOS-File-Recovery
A bootable WinPE image with Recuva file recovery software installed. Can be used to recover files from formatted drives. THis was made with the official WinPE image and edited with NTLite. This will only work with X64 architecture. I have been working on a X86 version but there are problems with "Missing BOOTMGR"


## Instructions:
1. Download all the files as a zip folder.
2. Extract the zip file
3. Open the file named Rufus-3.15.exe (If you want to get the latest version it can be found at https://rufus.ie/)
4. Insert USB Drive that is 500MB of bigger. (WILL BE FULLY ERASED)
5. On the device dropdown select the usb drive if it is not selected already. (Make sure you have selected the right one)
6. Now click the select button and navigate to the "RecuvaOS_AMD64.wim" file, select it and click open.
7. Now select your partition scheme. (Usually MBR for older computers and GPT for newer ones.)
8. You can ignore the "file system" and "cluster size" but you can change the "Volume Label" to what ever you want. (This is going to be the name of the USB drive)
9. Click "Show advanced format options" and make sure that the box with "Quick Format" is selected or it could take hours to format the drive.
10. Now you should be able to click the start button. Only pull out your USB drive when it has completed. It only took about 2 minutes for my USB to be ready.
11. It should look something like this:
<img width="347" alt="Screenshot 2021-09-28 112858" src="https://user-images.githubusercontent.com/91357710/135009959-3da73cba-6bd8-467f-8183-dcce1dc09668.png">


## Usage:
To use this drive you will need to shutdown your computer and boot from it. To do this you will need to figure out what key you need to press to get into your boot selection menu or BIOS. (Usualy the key will be either F2, F10, or F12 But you may have to look up your computers make to find out the key) You will need to select the USB as a boot drive. Once it is booted in you should be able to scan for files and recover them to abother drive.


## Conclusion:
If you have any questions feel free to ask. Any suggestions? Send them through.

