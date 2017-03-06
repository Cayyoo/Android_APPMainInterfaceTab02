# App主界面Tab实现方法：Fragment实现Tab(界面不能滑动)

```java
/**
 * App主界面Tab实现方法：Fragment实现Tab(界面不能滑动)
 *
 * 注意：这里使用v4包
 */
```

```java
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical" >

    <include layout="@layout/top" />

	<FrameLayout 
	    android:id="@+id/id_content"
	    android:layout_width="fill_parent"
	    android:layout_height="0dp"
	    android:layout_weight="1"/>

    <include layout="@layout/bottom" />

</LinearLayout>
```

![img](https://github.com/ykmeory/APP_MainInterface_Tab02/blob/master/img.jpg "screenshot")
