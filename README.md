# Android自定义圆形图片 RoundImageView
 ```
<declare-styleable name="RoundImageView">
      <attr name="image_radius" format="dimension" />//圆角大小
      <attr name="image_shadow_radius" format="dimension" />//阴影大小
      <attr name="image_circle" format="boolean" />//是否圆形
      <attr name="image_shadow" format="boolean" />//是否阴影
      <attr name="shadow_color" format="integer"/>//阴影颜色
 </declare-styleable>


<com.hirezy.roundimageview.RoundImageView
      android:layout_width="300dp"
      android:layout_height="200dp"
      android:layout_gravity="center_horizontal"
      android:src="@mipmap/tu"
      app:image_shadow="true"
      app:image_radius = "16dp"
      app:image_shadow_radius="20dp"/>
```

