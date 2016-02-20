#### psgsandroidmd
- 3

style.xml
```
<style name="AppTheme" parent="@android:style/Theme.Material.Light.DarkActionBar/NoActionBar">
```

for compat reason, if MinSDKVersion<21,folder name should be
drawable-v21,values-v21(api21 and above)
drawable,values(below21)


```java
if(Build.VERSION.SDK_INT>=Build.VERSION_CODES.LOLLIPOP){
}else{
}
```

Palette:

colorPrimary
colorPrimaryDark
textColorPrimary,textColorSecondary(control three dots)
windowBackground
navigationBarColor


colorControlHighlight(button animation color)

colorControlNormal        //checkbox
colorControlActivated    //ticketed checkbox
colorButtonNormal
4-2 done

