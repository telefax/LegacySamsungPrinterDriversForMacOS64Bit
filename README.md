# MacOS Samsung Drivers for ML-1660 laser printer (and probably more printers)

These drivers/files are taken from the official install of the Samsung laser printer ML-1660, which are since long gone after HP acquired Samsung printer business.

The laser printer works perfectly fine but officially the drivers does not support 64-Bit MacOS and I have also lost the original install package for the drivers.
It is impossible to find online and there are lots of forum posts of people trying to get their hardware working again.

It would be a shame to throw this printer away, considering both the environmental impact and that we are also in a chip crisis.

While I'm pretty cluless when it comes to printers and printing, with these files and instruction you will hopefully be able to get your old but working hardware running in all its glory again. 

The repo contains other printers as well, which was probably bundled into the original installer. Chances are that this will work for lots of other printers as well.

Tested on MacOS Monterey (MacOS 12.4) with Samsung ML-1660.

## Installation instructions

1. Download the files from the repo.
2. Open a terminal and copy the files to the following locations 

```sudo cp -r Samsung /Library/Printers/```

```sudo cp -r PPDs /Library/Printers/```

3. Go into MacOS System Preferences -> Printers & Scanners -> Plus sign (+) to install a new printer.
   If the printer is powered on, you should see it listed in the "Add Printer" dialogue.
   
   Select it and you should be able to press the "Add" button.


After you have installed the printer, there might be some nag screens with MacOS permisions, you can go ahead and approve these in the security settings in MacOS. So far I only encountered this in one install out of two.
