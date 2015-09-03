The purpose of this class library is to allow the parsing of ISO9660 format disk images and navigating the file system present in the image.

The result is the ability to find the sector offset and length of file data within the disk image so that the file data can be read easily from that image.

NOTE: We do not currently support any of the extensions to the ISO format, such as Joliet; nor does this code support other image formats, such as UDF.