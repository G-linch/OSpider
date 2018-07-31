# OSpider
GIS &amp; GeoDataScience 爬虫项目，OSpider v1.0.1 无需配置即可爬取大批量百度POI并实现坐标转换

1	当前版本功能（v1.0.1）
爬取指定区域的百度POI数据，并将坐标转化为WGS84

2	升级说明
#20180731
①版本号1.0.0->1.0.1
②修复了中文路径闪退bug
③修复了部分POI由于属性结构问题而无法爬取造成闪退的bug

#20180725
①版本号0.8.0->1.0.0，OSpider正式对外发布；
②突破指定区域爬取poi数量小于400个限制，支持单区域1w+POI爬取；
③绕过了区域中存在多个行政区时只返回一个行政区POI的潜在反爬虫机制；
④爬取poi的同时，实现bd09坐标到wgs84坐标的转换；
⑤使用配置文件property.ini控制爬取参数；

欢迎关注OGIScience

