<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    >

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/heart_tree"
        android:scaleType="centerCrop"
        />

    <TextView
        android:layout_width="240dp"
        android:layout_height="wrap_content"
        android:text="thank you For this good initiative"
        android:layout_centerHorizontal="true"
        android:layout_alignParentRight="true"
        android:fontFamily="casual"
        android:textSize="32sp"
        android:textColor="@android:color/white"
        android:layout_centerVertical="true"
        />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="From Zakari"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        android:textColor="@android:color/white"
        android:textAppearance="@style/Base.TextAppearance.AppCompat.Large"
        android:fontFamily="serif"/>



</RelativeLayout>
