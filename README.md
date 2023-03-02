# Action Bar Text Center and Font Change

## Create New Layout Recourse File

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:gravity="center"
    >

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/app_name"
        android:textSize="22sp"
        android:textStyle="bold"
        android:fontFamily="@font/bangla_font"
        android:textColor="@color/white"
        />

</LinearLayout>
```

## Main Activity Java

```
getSupportActionBar().setDisplayOptions(ActionBar.DISPLAY_SHOW_CUSTOM);
getSupportActionBar().setCustomView(R.layout.toolbar_text_center);
```
