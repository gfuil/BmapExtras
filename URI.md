#调起Bmap说明

通过geo-uri方式，坐标系为国测局坐标(GCJ02)

geo:latitude,longitude?q=place_name


##调用示例：

Uri uri = Uri.parse("geo:39.903740,116.397827?q=天安门广场");
Intent intent = new Intent(Intent.ACTION_VIEW, uri);
startActivity(intent);