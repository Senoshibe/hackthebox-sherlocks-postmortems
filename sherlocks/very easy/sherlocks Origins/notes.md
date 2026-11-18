Wireshark notes

Use ftp as a filter to find any activity/stolen data taken via the FTP protocol (usually port 21) 

use ftp-data filter to show resources transferred over the FTP procol and also hopefully find what command was used to download the file. 

Go to File > Export Objects > FTP-DATA to find the exfiltrrated files

**Thoughts**

Pretty straight forward exercise, just reaching entries from Wireshark. As long as I know the keywords I need to search, just using common sense by checking timestamps and scouring for any seemingly related information was the extent of the exercise. 

I doubt there's anyone silly enough to leave credentials in a plain text file. Also password seemed pretty complex enough. I wonder how realistic it is to fall on this password using brutforce tactics. Maybe it's a passwordlist from somewhere
