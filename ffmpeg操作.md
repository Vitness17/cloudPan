## FFmpeg操作

### 视频



#### ffmpeg -ss  00:00:00 -i input.mp4 -t 60 output.mp4 (剪切视频文件)

#### ffmpeg -ss  00:00:00 -i input.mp4 -to 00:01:00 output.mp4 (剪切视频文件)

##### -ss:视频的起始位置；

##### -i:输入视频；

##### -t:剪切持续时间；

##### -to:视频的结束时间；



#### ffmpeg -f concat -i list.txt -c copy output.mp4(合并视频)

##### -f concat:使用concat当时合并视频；

##### -i list.txt：输入视频文件，list.txt里面为两个视频的地址；

#### eg:![1537170615026](C:\Users\ATC\AppData\Local\Temp\1537170615026.png)