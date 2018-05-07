# poetry-desktop

欢迎使用诗词桌面！

程序使用 Go 语言开发。

目前仅支持 Windows 。

## 简介
能够自动、定时地从网路上随机获取一首唐、宋诗或宋词，并将文本整合在背景图片上，最后自动设置为壁纸。

要查看帮助请在程序所在目录打开cmd命令行输入: poetry-desktop --help
```
NAME:                                                                                           
   poetry-desktop.exe - A new cli application                                                   
                                                                                                
USAGE:                                                                                          
   poetry-desktop.exe [global options] command [command options] [arguments...]                 
                                                                                                
VERSION:                                                                                        
   1.0                                                                                        
                                                                                                
COMMANDS:                                                                                       
     help, h  Shows a list of commands or help for one command                                  
                                                                                                
GLOBAL OPTIONS:                                                                                 
   --interval value, -i value  设置诗词桌面自动切换时间间隔，单位：小时 (default: "1")                              
   --font value, -f value      设置显示的字体 (default: "fonts/FangZhengKaiTiJianTi-1.ttf")            
   --fontsize value, -s value  设置字体大小 (default: "25")                                           
   --imgloc value, -l value    指定背景图片位置 (default: "images/poetry_bg_0.jpg")                     
   --color value, -c value     设置字体颜色，格式为 rgba (default: "(0,0,0,0.8)")                         
   --xoffset value             设置文字整体在X轴方向的偏移量 (default: "+0")                                  
   --yoffset value             设置文字整体在Y轴方向的偏移量 (default: "+0")                                  
   --help, -h                  show help                                                        
   --version, -v               print the version                                
```

## 使用效果
![alt text][3]
![alt text][4]

## 下载
1. 请前往 [Releases] [0]页面下载（国内环境下速度可能较慢）
2. [Yandisk][2]

[0]: https://github.com/okcy1016/poetry-desktop/releases
[2]: https://yadi.sk/d/MhkJwXQ43VUaug
[3]: http://128.199.227.220:8003/Temp/Screenshot%20from%202018-05-06%2021-26-24.png
[4]: http://128.199.227.220:8003/Temp/Screenshot%20from%202018-05-06%2021-34-58.png

## 致谢
感谢以下项目的贡献者：

1. 中华古诗词数据库
https://github.com/chinese-poetry/chinese-poetry

2. A simple, fast, and fun package for building command line apps in Go
https://github.com/urfave/cli

3. ImageMagick 7
https://github.com/ImageMagick/ImageMagick

4. Set the desktop wallpaper on Windows
https://github.com/sindresorhus/win-wallpaper
