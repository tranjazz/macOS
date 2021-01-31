# M1版Mac下更改默认输入法，即删除英文ABC输入法

### 使用鼠须管输入法之后，默认的输入法依然是英文 ABC，并且没办法删除。 
### 搜索一番，找到方法如下:

1、打开 ~/Library/Preferences/ com.apple.HIToolbox.plist，记得先备份一个。可以 使用Xcode打开，或者下载plist edit pro。  
2、把EnabledInputSource 节点下除了你想要的输入法 之外的都删除，只留下鼠须管相关的。如图  
3、重启Mac

![Aaron Swartz](https://raw.githubusercontent.com/tranjazz/photo/main/截屏2021-01-31%2015.32.17.png)

![Aaron Swartz](https://raw.githubusercontent.com/tranjazz/photo/main/截屏2021-01-31%2015.32.35.png)

![Aaron Swartz](https://raw.githubusercontent.com/tranjazz/photo/main/截屏2021-01-31%2015.32.49.png)


