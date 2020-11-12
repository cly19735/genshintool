# 原神工具箱  
满足个人需求的小工具：  
1. 本人长期开着原神不关，所以干别的事儿的时候需要快速且方便的给原神静音。我懒得去合成器里单独关闭原神通道
2. 原神关闭需要等半天退到登录界面，还要再等半天才出现退出按钮，极其恶心浪费时间。而且还关不干净，游戏关闭以后启动器还在
3. 爬墙的时候我不想看到一坨空气  
因此就有了这个小工具

##
目前反和谐是无效的，mhy每次加载游戏都会校验贴图，如果发现被改了会下载新的。国内外目前都没有找到更新的解决办法，我也在进行一些尝试，比如试图破解游戏的校验逻辑，看看米哈呦有没有把hash存在本地某个文件中，但目前还没有什么效果，如果后续有了解决办法，会在第一时间更新。
## 程序界面
![img](img/1.png)
## 使用
[下载](https://github.com/manakanemu/genshintool/releases/)zip后解压，随便放在那里，会根据注册表找原神装在那里了。  
1. 双击“Genshin Tool.exe”打开工具
1. 软件打开时会启动原神
2. 选择“4. 关闭游戏”可以把游戏、工具箱、和原神启动器三者都关了
3. 按钮前面的数字就是该按钮的i 快捷键
4. 可以给“Genshin Tool.exe”在桌面创建快捷方式，然后把快捷方式图标改成原神图标
## 卸载
直接删除文件夹就可以，软件不创建任何临时文件，不改动注册表  
## 其他
1. 最近写python比较顺手，就直接用python实现了，打包出来肯定比c和c#写的大，硬伤
2. 随手写的工具，没有美化ui
3. 如果需要自行编译，请在编译时加上uac许可，例如` pyinstaller -D -w tool.py --uac-admin `
