# ffmepg-commend-list
Useful commends in ffmpeg (continue updating as I discovered new one)

Compress image: all images in the folder
```for /f "tokens=1 delims=." %a in ('dir /B *.jpg') do ffmpeg -i "%a.jpg" -y -compression_level 95 "%a.jpg"
 ```
