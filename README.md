<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="20dp">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        tools:layout_editor_absoluteX="20dp"
        tools:layout_editor_absoluteY="20dp">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="80dp"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/tvuser"
                android:layout_width="110dp"
                android:layout_height="wrap_content"
                android:text="用户名" />

            <EditText
                android:id="@+id/user"
                android:layout_width="251dp"
                android:layout_height="wrap_content"
                android:ems="10"
                android:hint="请输入用户名"
                android:inputType="textPersonName"
                android:minHeight="48dp" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="80dp"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/tvpwo"
                android:layout_width="111dp"
                android:layout_height="wrap_content"
                android:text="密码" />

            <EditText
                android:id="@+id/pwo"
                android:layout_width="259dp"
                android:layout_height="wrap_content"
                android:ems="10"
                android:hint="请输入密码"
                android:inputType="textPassword"
                android:minHeight="48dp" />
        </LinearLayout>

        <Button
            android:id="@+id/button5"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="登录"
            tools:ignore="MissingConstraints,OnClick"/>

        <Button
            android:id="@+id/buttonR"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="注册" />

        <TextView
            android:id="@+id/tvRC"
            android:layout_width="match_parent"
            android:layout_height="wrap_content" />

    </LinearLayout>

</androidx.constraintlayout.widget.ConstraintLayout>
