# lyrictextview
歌词渐变文本控件<br/>
代码很少，可直接复制（lyricTextView、attrs）<br/>
控件详解：[http://blog.csdn.net/ccy0122/article/details/72870580](http://blog.csdn.net/ccy0122/article/details/72870580)<br/>
使用方法<br/>
1、xml里定义：<br/>
   <com.example.lyrictextview.LyricTextView<br/>
        android:id="@+id/lyric"<br/>
        android:layout_width="match_parent"<br/>
        android:layout_height="60dp"<br/>
        android:background="#44000000"<br/>
        app:changed_color="#ff0000"<br/>
        app:default_color="#000000"<br/>
        app:direction="left"<br/>
        app:progress="0.7"<br/>
        app:text="按时大大的飒飒的"<br/>
        app:text_size="26sp" /><br/>
2、代码里设置:<br/>
   LyricTextView ltv = new LyricTextView(context);<br/>
   ltv.setText/setProgress/setDefaultColor...(都有对应的getter、setter）<br/>
   也可以直接lty.setAll(progress, text, textSize, defaultColor, changeColor, direction);<br/>
<br/>
<br/>
![image](https://github.com/CCY0122/lyrictextview/blob/master/20170605210655907.jpg)
![image](https://github.com/CCY0122/lyrictextview/blob/master/lyric.gif)
        
    
