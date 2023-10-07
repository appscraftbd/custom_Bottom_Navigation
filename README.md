# custom_Bottom_Navigation
<h3>Active Indicator</h3><br>
color.xml

   ```
 <color name="select-name">Your_color</color>
   ```
them
   ```
  <style name="App.Custom.Indicator" parent="Widget.Material3.BottomNavigationView.ActiveIndicator">
        <item name="android:color">@color/select-name</item>
        
    </style>
```

activity.xml
```
 <com.google.android.material.bottomnavigation.BottomNavigationView
     android:id="@+id/bottomnav"
     android:layout_width="match_parent"
     android:layout_height="wrap_content"
     android:background="#8ED6D0"
     app:itemIconTint="@color/white"
     app:itemTextColor="@drawable/backitem"
     app:labelVisibilityMode="labeled"
     app:itemActiveIndicatorStyle="@style/App.Custom.Indicator"
     app:menu="@menu/bar_item"
     android:layout_alignParentBottom="true"
     />

```
