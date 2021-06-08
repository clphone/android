# 6月第一份周报 

###### 蔡笠沣

1、安卓编译环境的搭建

  安装Android Studio后安装虚拟机再配置即可。

2、FrameLayout实例

```android
<?xml version="1.0" encoding="utf-8"?> //文字属性
<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"  //设置布局长宽
    android:layout_height="match_parent"
    android:background="@drawable/guangchang"  //调用图片作为布局背景
    >
    <TextView
        android:layout_width="410dp"
        android:layout_height="160dp"
        android:text="主菜单"
        android:textSize="80dp"
        android:textColor="#000000"
        android:gravity="center" //设置文字在文字框的位置
        android:textStyle="bold"
        android:shadowColor="#8BC34A"
        android:shadowRadius="3.0" //设置阴影
        android:shadowDy="10.0"
        android:shadowDx="10.0"
        />
    <Button
        android:id="@+id/map"  //命名按钮
        android:text="校园地图"
        android:textStyle="bold"
        android:textSize="40dp"
        android:layout_width="250dp"
        android:layout_height="80dp"
        android:layout_marginTop="140dp"
        android:layout_marginLeft="75dp"
        android:background="@drawable/btnshape2"
        />
    <Button
        android:id="@+id/introduction"
        android:text="学校简介"
        android:textStyle="bold"
        android:textSize="40dp"
        android:layout_width="250dp"
        android:layout_height="80dp"
        android:layout_marginTop="240dp"
        android:layout_marginLeft="75dp"
        android:background="@drawable/btnshape3"
        />
    <Button
        android:id="@+id/web"
        android:text="学校网站"
        android:textStyle="bold"
        android:textSize="40dp"
        android:layout_width="250dp"
        android:layout_height="80dp"
        android:layout_marginTop="340dp"
        android:layout_marginLeft="75dp"
        android:background="@drawable/btnshape4"
        />
    <Button
        android:id="@+id/eat"
        android:text="美食推荐"
        android:textStyle="bold"
        android:textSize="40dp"
        android:layout_width="250dp"
        android:layout_height="80dp"
        android:layout_marginTop="440dp"
        android:layout_marginLeft="75dp"
        android:background="@drawable/btnshape5"
        />
    <Button
        android:id="@+id/play"
        android:text="周边玩乐"
        android:textStyle="bold"
        android:textSize="40dp"
        android:layout_width="250dp"
        android:layout_height="80dp"
        android:layout_marginTop="540dp"
        android:layout_marginLeft="75dp"
        android:background="@drawable/btnshape6"
        />

</FrameLayout>
```

