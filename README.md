# lyrictextview
歌词渐变文本控件<br/>
**代码很少，可直接复制（lyricTextView、attrs）**<br/>
控件详解：[http://blog.csdn.net/ccy0122/article/details/72870580](http://blog.csdn.net/ccy0122/article/details/72870580)<br/>


## 效果

![image](https://github.com/CCY0122/lyrictextview/blob/master/20170605210655907.jpg)
![image](https://github.com/CCY0122/lyrictextview/blob/master/lyric.gif)
      
## 使用方法<br/>

1、xml里定义：<br/>
```xml
   <com.example.lyrictextview.LyricTextView
        android:id="@+id/lyric"
        android:layout_width="match_parent"
        android:layout_height="60dp"
        android:background="#44000000"
        app:changed_color="#ff0000"
        app:default_color="#000000"
        app:direction="left"
        app:progress="0.7"
        app:text="按时大大的飒飒的"
        app:text_size="26sp" />
```
2、代码里设置:<br/>
```java
   LyricTextView ltv = new LyricTextView(context);<br/>
   ltv.setText/setProgress/setDefaultColor...(都有对应的getter、setter）
   也可以直接ltv.setAll(progress, text, textSize, defaultColor, changeColor, direction);
```
<br/>
<br/>  
    
