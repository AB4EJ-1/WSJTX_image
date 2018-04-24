# WSJTX_image
Hybrid SSTV:  Uses FT8 mode to exchange pictures using FT8 with ftp server handling the images (just like EasyPal hybrid mode)
Based on WSJT-x package from Joe Taylor, K1JT, of Princeton. 
To use, run wsjtx.exe.  
Note: the program pushes the image file you want to an ftp server. You and people you want to exchange pictures with must
agree on and use the same ftp server, which you must have a log-in for, and enter this in the configuration screen on both systems.
Note 2: FT8 mode, like most digital modes, is dependent on a very accurate PC clock. You must install and run a clock sync
propgram such as Dimension 4 to sync your pc clock.
Note 3: File names are restricted to 8 bytes plus the file extension, e.g.,  IMAGE001.jpg
Select FT8IMG mode. Use the Load Image button and select a jpg. The program will put the file name into the FT8 send area.
Click Enable Tx. The program will send the file name at the next 15-sec slot.
When the receiving station gets the file name, it will show up
in the Band Activity area. Double click on that, and the program (running at the recipient) will download and display
the image.
