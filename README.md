# MySimpleStyle
android drawable样式

1:简单虚线
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="line"
    >
    <!-- dashGap 虚线间隔(0时 实线)  dashWidth 每一段线宽() width(高度)-->
    <stroke android:color="#e6e6e6" android:dashGap="3dp" android:dashWidth="8dp" android:width="2dp"/>
    <size android:height="2px"/>
</shape>

用的时候必须添加 android:layerType="software";


