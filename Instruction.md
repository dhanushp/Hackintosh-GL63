# Instruction
Before proceeding with the installation, Make sure you have downloaded the following 

### Requirements
* MacOs DMG file. Download it from [here](https://drive.google.com/open?id=1bxaEpsYhN6FKiUQB7-9_xlaMZbgd2IPn)
* EFI file from the [Repository](https://github.com/ResponsiveUser/Hackintosh-GL63)
* [balenaEtcher](https://www.balena.io/etcher/) for flashing MacOS DMG into usb
* [Explorer++](https://explorerplusplus.com/download) for making changes in default EFI partition
* [MiniTool Partition Wizard](https://www.partitionwizard.com/free-partition-manager.html)

<b>Once all the required files are downloaded, Follow the below instruction</b>

##### Step 1 :
Open balenaEtcher and click on Select image.

![altt text](https://i.imgur.com/IFw9isE.png?1)

##### Step 2 :
Browse to the folder where you have placed the MacOs DMG file and Select it.

![altt text](https://i.imgur.com/di4IlZZ.png)

##### Step 3 :
Now click on Select target.

![altt text](https://i.imgur.com/i1i4McV.png)

##### Step 4 :
Select the drive in which you would like to flash the Image.

![altt text](https://i.imgur.com/RRRtl7M.png)

##### Step 5 :
Now Click on <b>Flash</b> and wait for it to flash the drive.

![altt text](https://i.imgur.com/pvih4yp.png)

##### Step 6 :
Open MiniTool partiton wizard and Right-Click on the EFI.

![altt text](https://i.imgur.com/JFs1zeN.jpg)

##### Step 7 :
Select Change letter and choose assign A letter to the selected EFI volume and Click on the Apply changes present on the top left corner.

![altt text](https://i.imgur.com/JFs1zeN.jpg)

##### Step 8 :
Once the changes have been applied, you would be able to see the volume in your file explorer.

![altt text](https://i.imgur.com/R6SwYZi.png)

##### Step 9 :
Extract the Explorer++ and run it as <b>Administrator</b>.

![altt text](https://i.imgur.com/Tse5uTH.png)

##### Step 10 :
Browse to the EFI folder on the pendrive using Explorer++  and delete the Existing files.

![altt text](https://i.imgur.com/dbpYaHm.png)

##### Step 11 :
Now copy the files from [Repository](https://github.com/ResponsiveUser/Hackintosh-GL63) and paste inside the EFI folder present in the USB drive.

![altt text](https://i.imgur.com/NvM0x1D.png)

##### Step 12 :
Once all the above steps are done, Restart your device and boot from USB drive. You will be entering Clover and Select <b>Install macOS Catalina</b> to install Catalina in your device. 