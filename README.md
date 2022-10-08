# openwrt-package

包含了 如下应用
- Argon 主题
- Argon 主题配置应用
- vssr(Helloworld)上网冲浪应用
- luci-app-advanced 高级设置
- lua-maxminddb lua版本的maxminddb ip库解析器

## 使用方法

添加 src-git bingo235 https://github.com/bingo235/openwrt-package 到 OpenWRT源码根目录feeds.conf.default文件

然后执行

```bash
./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
```
