# Readpst

#### Source

Shared Library to convert **Outlook pst file** on [five-ten.](https://www.five-ten-sg.com/libpst/)

#### Changes applyed to source code

Small changes are made to the **readpst.c** in order to adjust the storage of the E-Mail **attachments**. 

Every E-Mail gets an extra directory for it's attachments named like this: __.__*E-Mail-number*__.__*eml* . 

In order to use this you have to put the new **-N** option when invoking readpst from the shell. 

*e.g.* `readpst -D -b -N -8 -t e -q -j 0 -o "Target/EML/Folder" "Path/to/pstfile.pst"`

#### License

All changes made to the code are under the arrangements of the [**GPL**](https://github.com/SOURCEPARK/Readpst/blob/main/LICENSE).
