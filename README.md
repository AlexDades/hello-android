<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.android.helloandroid.HelloAndroid">

<ImageView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:id="@+id/logo"
    android:src="@drawable/logo"
    android:layout_centerHorizontal="true"

    />


    <ImageView
        android:id="@+id/udacityIcon"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_above="@+id/street"
        android:layout_alignLeft="@+id/logo"
        android:layout_alignStart="@+id/logo"
        android:layout_below="@+id/blueline"
        android:layout_toLeftOf="@+id/udacity"
        android:layout_toStartOf="@+id/udacity"
        android:paddingTop="16dp"
        android:src="@drawable/udacityicon" />


    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@id/logo"
        android:background="#42A5F5"
        android:id="@+id/blueline"/>



    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/udacity"
        android:text="Udacity"
        android:textSize="24sp"
        android:layout_below="@id/blueline"
        android:padding="16dp"
        android:layout_centerHorizontal="true"

        />


    <TextView
        android:id="@+id/street"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/udacity"
        android:layout_toEndOf="@+id/udacityIcon"
        android:layout_toRightOf="@+id/udacityIcon"
        android:paddingTop="8dp"
        android:paddingLeft="16dp"
        android:text="2465 Latham St"
        android:textSize="24sp"
        />


    <TextView
        android:id="@+id/state"
        android:layout_width="match_parent"
        android:layout_height="match_parent"

        android:layout_alignBottom="@+id/location"
        android:layout_alignParentEnd="true"
        android:layout_alignParentRight="true"
        android:layout_below="@+id/street"
        android:layout_toEndOf="@+id/phone"
        android:layout_toRightOf="@+id/phone"
        android:paddingLeft="16dp"
        android:text="Mountain View, CA 94043"
        android:textSize="24sp" />


    <ImageView
        android:id="@+id/phone"
        android:layout_width="match_parent"
        android:layout_height="match_parent"

        android:layout_alignBottom="@+id/phoneNumber"
        android:layout_alignEnd="@+id/udacityIcon"
        android:layout_alignLeft="@+id/udacityIcon"
        android:layout_alignRight="@+id/udacityIcon"
        android:layout_alignStart="@+id/udacityIcon"
        android:layout_below="@+id/location"
        android:padding="2dp"
        android:src="@drawable/phone" />

    <ImageView
        android:id="@+id/location"
        android:layout_width="55dp"
        android:layout_height="110dp"
        android:layout_below="@+id/udacityIcon"
        android:layout_marginEnd="30dp"
        android:layout_marginRight="30dp"
        android:layout_toLeftOf="@+id/street"
        android:layout_toStartOf="@+id/street"
        android:paddingBottom="8dp"
        android:paddingTop="8dp"
        android:src="@drawable/location" />

    <TextView
        android:id="@+id/phoneNumber"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"

        android:layout_below="@+id/state"
        android:layout_toEndOf="@+id/phone"
        android:layout_toRightOf="@+id/phone"
        android:padding="16dp"
        android:text="650-555-5555"
        android:textSize="24sp" />

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_below="@+id/phone"
        android:paddingTop="8dp"
        android:src="@drawable/ladder" />

</RelativeLayout>






