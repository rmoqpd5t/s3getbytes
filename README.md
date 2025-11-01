# s3getbytes
Modification to s3simple to specify number of bytes to download

Useage example:
./s3getbytes get s3://bucket/file.txt outfile.txt 99

This downloads 100 bytes (i.e. 0-99) of the file specified e.g. file.txt and saves it in the local file specified i.e. outfile.txt
