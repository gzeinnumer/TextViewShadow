# TextViewShadow

Source https://stackoverflow.com/questions/3297437/shadow-effect-for-a-text-in-android

- colors.xml
```xml
<resources>
    <color name="light_font">#FBFBFB</color>
    <color name="grey_font">#ff9e9e9e</color>
    <color name="text_shadow">#7F000000</color>
    <color name="text_shadow_white">#FFFFFF</color>
</resources>
```

- example1
```xml
<TextView
    ...
    android:shadowColor="@color/text_shadow"
    android:shadowDx="1"
    android:shadowDy="1"
    android:shadowRadius="2"
    android:textStyle="bold" />
```
![](https://i.stack.imgur.com/VrRD5.png)

- example2
```xml
<TextView
    ...
    android:shadowColor="@color/text_shadow"
    android:shadowDx="-1"
    android:shadowDy="-1"
    android:shadowRadius="1"
    android:textStyle="bold" />
```
![](https://i.stack.imgur.com/PZzzD.png)

- example3
```xml
<TextView
    ...
    android:shadowColor="@color/text_shadow_white"
    android:shadowDx="-2"
    android:shadowDy="-2"
    android:shadowRadius="1"
    android:textStyle="bold" />
```
![](https://i.stack.imgur.com/g0gkN.png)

---

```
Copyright 2021 M. Fadli Zein
```