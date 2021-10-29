# Readpst

Shared Library to convert Outlook pst file: https://www.five-ten-sg.com/libpst/

Small changes are made to the readpst.c in order to adjust the storage of the E-Mail attachments. Every E-Mail gets an extra directory for it's attachments named like this: ."E-Mail-number".eml . 
In order to use this you have to put the new -N option when invoking readpst. (e.g.  readpst -D -b -N -8 -t e -q -j 0 -o "Target/EML/Folder" "Path/to/pstfile.pst")

All changes made to the code are under the arrangements of the GPL.
