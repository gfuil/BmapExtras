# 调起Bmap说明

通过geo-uri方式，坐标为国测局坐标系(GCJ02)

geo:latitude,longitude?q=place_name


## 调用示例：

Uri uri = Uri.parse("geo:39.903740,116.397827?q=天安门广场");

Intent intent = new Intent(Intent.ACTION_VIEW, uri);

startActivity(intent);



#### 凭我一人之力我无法适配众多APP，请反馈至第三方APP开发团队，使用本方式可调用手机上任何一款地图APP，而不仅仅只是固定国内三大地图APP
