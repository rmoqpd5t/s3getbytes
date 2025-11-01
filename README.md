# s3getbytes
Modification to s3simple adding the ability to specify the number of bytes to download

Useage example:
```
export S3_ACCESS_KEY_ID=********************
export S3_HOSTNAME=object-arbutus.cloud.computecanada.ca
export S3_SECRET_ACCESS_KEY=****************************************
./s3getbytes get s3://bucket/file.txt outfile.txt 99
```
This downloads the specified number of bytes (i.e. 0-99) of the file specified (i.e. file.txt) and saves it in the local file specified (i.e. outfile.txt)
