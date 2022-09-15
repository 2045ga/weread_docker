# weread_docker
微信读书刷时常，docker版本，运行在24小时NAS


## 目的

群晖、威联通等设备24小时不关机，用于模拟微信读书在线时

## 思路

采用playwright库模拟爬虫访问微信读书网页

1. 尝试二维码登录
2. 自动阅读
3. 阅读到章节底部，点击下一章
4. 设置重启容器间隔，每7天重启阅读
5. 自动兑换时长
6. 推送阅读时长通知


## 运行

`docker run -d `


书籍推荐：【带着农场混异界】 1万多章，很难一周内刷完

## 参考

- https://github.com/DoooReyn/WxRead-WebAutoReader
- WxRead-WebAutoReader
