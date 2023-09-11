#ffmpeg 
wmv -> mp4
```shell
ffmpeg -i "xxxx.wmv" -c:v libx264 -crf 23 -c:a aac -q:a 100 "xxxx.mp4"
```
mkv - mp4
```shell
ffmpeg -i xxx.mkv -codec copy xxxx.mp4
```
