# android
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content" >


        <ImageView
            android:id="@+id/profile"
            android:layout_width="128dp"
            android:layout_height="130dp"
            android:layout_gravity="center"
            android:layout_marginTop="5dp"
            android:src="@drawable/alluarjun1" />

        <TextView
            android:id="@+id/titleText"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginLeft="21dp"
            android:layout_marginTop="10dp"
            android:layout_toRightOf="@+id/profile"
            android:text="Chandana"
            android:textColor="#03A9F4"
            android:textSize="30sp" />

        <TextView
            android:id="@+id/mailText"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_below="@+id/titleText"
            android:layout_gravity="center"
            android:layout_marginLeft="22dp"
            android:layout_marginTop="-1dp"
            android:layout_toRightOf="@+id/profile"
            android:text="chandana@gmail.com"
            android:textColor="#222222"
            android:textSize="24sp" />

        <TextView
            android:id="@+id/numberText"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_below="@+id/mailText"
            android:layout_gravity="center"
            android:layout_marginLeft="24dp"
            android:layout_marginTop="11dp"
            android:layout_toRightOf="@+id/profile"
            android:text="123-567-90"
            android:textColor="#222222"
            android:textSize="25sp" />


    </RelativeLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="114dp"
        android:layout_marginTop="20dp"
        >

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:text="Education"
            android:textColor="@color/cardview_light_background"
            android:textSize="25sp"

            />

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:text="Certification"
            android:layout_marginLeft="25"
            android:textColor="@color/cardview_light_background"
            android:textSize="25sp" />


    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_marginTop="25dp">
        <ImageButton
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:layout_weight="1"
            android:background="@drawable/insta">

        </ImageButton>
        <ImageButton
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:layout_weight="1dp"
            android:layout_marginLeft="25"
            android:background="@drawable/snap1">

        <ImageButton
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:layout_weight="1dp"
            android:background="@drawable/whatsapp">

        </ImageButton>

        <ImageButton
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:layout_weight="1dp"
            android:background="@drawable/fb"
            >

        </ImageButton>


    </LinearLayout>


</LinearLayout>

