# DWPOP-UP
Android 弹出框，类似淘宝菜单弹出框
如果有更多想法，联系我Q:232190315.
# 效果图
![](https://raw.githubusercontent.com/DavidWangTM/DWPOP-UP/blob/master/pop-up.gif)

Installation
--------------
###compile
```
compile 'com.facebook.rebound:rebound:0.3.8'
```
###Layout-XML
```objective-c
<tm.davidwang.dwpop_up.DWPOPView
        android:id="@+id/line1"
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"
        android:background="#50000000"
        android:layout_below="@+id/top_lin"
        >

        </tm.davidwang.dwpop_up.DWPOPView>

```
Properties
--------------
```objective-c
setAdapterView(View view)
and
/**
* @param qcTension tension as defined in the Quartz Composition
* @param qcFriction friction as defined in the Quartz Composition
/
setAdapterView(View view,double qcTension,double qcFriction)

//执行动画
showanimation()

//设置背景颜色
setDWBackgroundColor()

```