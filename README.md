# GradientProcessIndication
渐变进度指示圈

效果图：
![gradient_process_indication.png](/media/gradient_process_indication.png)

使用：
```
    <com.bird.fingerprint.custom.ProcessIndication
        android:layout_width="match_parent"
        android:layout_height="40dp"
        process:
        process_index="3"
        process:shader_end_color="#D10000"
        process:shader_start_color="#FFBDBD" />
```

process_index是当前所在的进度值，也可以通过setIndex(index)方法设置

process:shader_start_color="#FFBDBD"是渐变色的起始颜色

process:shader_end_color="#D10000"是渐变色的结束颜色
