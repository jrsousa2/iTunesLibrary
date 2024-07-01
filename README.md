# iTunesLibrary
Migrate your iTunes library with a free applet built in Python.

Check video tutorial on Youtube to learn how to use it (not available yet).

Instructions:
This program lets you change the location of all the tracks in your iTunes library to a new drive on the disk.
It doesn't move the files, you need to that manually first (just cut and paste the folder from its current drive to a new desired one).
Reason to do it that way is that it's faster and more convenient than doing it with the program.
For example, just cut the folder that has the files in the iTunes library and paste it to a new drive that you want to migrate the files to.

Launch the application and enter the old and the new drive.
This program will simply fix the location of the files in your iTunes library to point to the new drive.
It only changes the drive, the relative paths need to remain exactly the same (e.g., from "D:\MP3\Abba - SOS.mp3" to "E:\MP3\Abba - SOS.mp3").
You can do a test on a small number of files first, to verify that all is working. The track whose location was updated is added to a new playlist in iTunes.

The program uses the iTunes library XML file to locate the original path for each track and update it to point to the new drive, thus fixing the missing paths after the files are moved.
