# http-file-sever
http server for file upload and download

# run
go run main.go

# upload
* use curl POST to upload file
```bash
curl $hostname:$port/upload -F 'uploadFile=@/tmp/file-to-upload'
```


# quot
https://github.com/zupzup/golang-http-file-upload-download
