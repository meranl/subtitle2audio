# [subtitle2audio](https://github.com/kizx/subtitle2audio)

字幕朗读，由字幕生成音频 | Subtitle reading, generated audio from subtitles  
更多细节见[我的博客](https://www.2bboy.com/archives/151.html)

## 使用

- 安装依赖  
  `pip install -r requirements.txt`
- 安装 ffmpeg

1. 下载解压[ffmpeg](https://ffmpeg.zeranoe.com/builds/)
2. 将解压的 ffmpeg/bin 路径添加到系统环境变量

- 填写百度 KEY  
  在[百度 AI 平台](https://console.bce.baidu.com/ai/?_=1550569312984#/ai/speech/overview/index)获取相关 KEY  
  打开 main.py 填写相应填写 KEY

- 启动  
  `python main.py [.srt文件]`