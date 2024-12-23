# iTunes Library Migration Tool
Migrate your iTunes library with a free application built in Python.

Check video tutorial on YouTube to learn how to use it (not available yet).

Instructions:
This program lets you change the location of the tracks in your iTunes library to a new drive on the disk.
It doesn't move the files, you need to that manually first (just cut and paste the folder from its current drive to a new desired one).
Reason to do it that way is that it's faster and more convenient than doing it with the program. The relative paths need to remain the same, only the drive can change.

Launch the application and enter the old and the new drive. The program will fix the location of all the files in the iTunes library to point to the new drive.

The program uses the iTunes library XML file to locate the original path for each track and update it to point to the new drive, thus fixing the missing/broken paths after the files are manually moved. A simple GUI was created with the TkInter module.

The user can do a test first with a single file (or a couple of files) for safety. For example, move file "D:\MP3\Abba - SOS.mp3" to "E:\MP3\Abba - SOS.mp3" and launch the program to see how it works. Updated files are added to a new playlist.

Executable file is available in the link https://jrsousa2.gumroad.com/l/itunes
