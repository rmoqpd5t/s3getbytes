# s3getbytes
Fork of [s3simple](https://github.com/paulhammond/s3simple) adding the ability to specify the number of bytes to download

Useage example:
```
export S3_ACCESS_KEY_ID=********************
export S3_HOSTNAME=object-arbutus.cloud.computecanada.ca
export S3_SECRET_ACCESS_KEY=****************************************
./s3getbytes get s3://bucket/file.txt outfile.txt 99
```
This downloads up to the byte specified (e.g. 0-99) of file (e.g. file.txt) in the specified bucket and saves it in the local file specified (e.g. outfile.txt)
