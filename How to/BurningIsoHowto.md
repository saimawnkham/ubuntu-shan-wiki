##လွၵ်းလၢႆး ဢဝ် ISO သႂ်ႇၶဝ်ႈၼႂ်းၶႅပ်း 

###Downloading an Ubuntu ISO

Ubuntu is distributed over the Internet as DVD image (.iso) files. The GettingUbuntu page has links to the ISO image files, as well as other methods of getting Ubuntu.

###Burning the ISO on to a DVD

Unlike a regular data file, the ISO file cannot be simply dragged and dropped or copied directly onto a disc. It needs to be burned in a specific way that expands/extracts the image so you have usable files on your disc. 

To install Ubuntu from a DVD, you first need to burn the downloaded ISO image onto a DVD. This requires:

1. A working DVD burner (i.e. R/W drive)
2. A blank DVD. (recent Ubuntu versions do not fit on to CD any more)
Inexpensive "write once" DVD-Rs are a good choice for burning ISO images.


###Burning from Windows


####Windows 7/8/8.1

1. Right-click on an ISO image and choose “Burn disc image”.


![Window7_right.jpg](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=windows7_right.jpg)

2. Select a disk burner (drive) and press "Burn".

![windows7_burn.jpg](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=windows7_burn.jpg)

	If you check “Verify disc after burning”, it will verify that the ISO image has been burned correctly
	
	
##Windows 2000 or newer: Infra Recorder

1. Download and install Infra Recorder, a free and open source image burning program.

2. Insert a blank CD in the drive and select Do nothing or Cancel if an autorun dialog pops up.

3. Open Infra Recorder and click the 'Write Image' button in the main screen.
Alternatively you can select the 'Actions' menu, then 'Burn image'.
![infrarecorder3.png](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=infrarecorder3.png)
4. Select the Ubuntu CD image file you want to use, then click 'Open'.
5. In the dialog, click 'OK'.



##Windows XP or newer: ISO Recorder

1. Download and install the appropriate version of ISO Recorder.

2. Insert an unformatted CD into your burner. (Note: one can burn DVDs with this tool only from Vista.)

3. Open Windows Explorer, browse to your ISO file, right-click and choose "Next".

![iso-recorder.gif](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=iso-recorder.gif)

##Burning from Mac OS X

**Note**: To burn most ISOs, you can use Apple's Disk Utility (Disk Copy in older versions).

1. Launch Disk Utility (Applications → Utilities → Disk Utility).
2. Insert your blank CD/DVD.
3. Drag and drop your .iso file to the left pane in Disk Utility. Now both the blank disc and the .iso should be listed.
4. Select the .iso file, and click on the Burn button in the toolbar.ng) ![macosx_disk-utility.png](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=macosx_disk-utility.png)
5. Ensure that the "Verify burned data" checkbox is ticked (you may need to click on the disclosure triangle to see the checkbox).6.  
6. Click on Burn. The data will be burned and verified.
![](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=macosx_disk-utility_burn.png)

##Burning from Ubuntu

	The procedure may differ slightly depending on which version of Ubuntu you are using

1. Insert a blank CD into your burner. A "CD/DVD Creator" or "Choose Disc Type" window might pop up. Close this, as we will not be using it.![ubuntu_blankcd_dialog.png](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=ubuntu_blankcd_dialog.png)
 
2. Browse to the downloaded ISO image in the file browser.
3. Right click on the ISO image file and choose "Write to Disc". ![ubuntu_rightclick_cd.png](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=ubuntu_rightclick_cd.png)
4. Where it says "Select a disc to write to", select the blank CD. ![ubuntu_imageburn.png](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=ubuntu_imageburn.png)
5. If you want, click "Properties" and select the burning speed. Lower speeds offer greater reliability, but will take longer to write. ![ubuntu_imageburn_properties.png](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=ubuntu_imageburn_properties.png)
6. Start the burning process.
7. The program should automatically check whether the image has been burned correctly.
8. If the standard CD burning application does not work, install K3B and follow the instructions for Kubuntu below.


##Burning from Kubuntu
	The procedure may differ slightly depending on which version of Kubuntu you are using

1. Insert a blank CD into your burner. Open K3B from the KDE menu 
2. On the near bottom of the application where it says "Welcome to K3b - The CD and DVD Kreator" click "more actions..." and then pick "Burn Image". ![kubuntu_1.png](https://help.ubuntu.com/community/BurningIsoHowto?action=AttachFile&do=get&target=kubuntu_1.png)
3. You may want to enable the disk verification option to make sure the image is burned correctly, and lower the burning speed to have more reliability.
4. Start the burning process.
5. You can use the default settings.

		See CdDvd/Burning if you would like to burn from the command line (terminal)
		
##If the burning fails
If the CD writing fails, try writing at a slower speed. For better results, try the slowest burn speed reasonably possible. Most GUI tools have a "Properties" button to select speed but with Brasero those sorts of options appear after pressing the "burn" button first. This is the single most likely cause of problems but is much more widely known than MD5sum/SHA error-checking. Slower speeds ensure greater accuracy.