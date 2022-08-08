# is_my_domain_blocked
判断你的域名是否被运营商劫持阻断

# 0.电脑本地连接dns设置为自动获取

# 1.获取本地宽带运营商dns
```
http://nstool.netease.com
```

# 2.读取该dns缓存的域名记录
```
cmd 命令行执行(替换成你的域名和查询到的dns)
nslookup www.xxxxx.com 114.114.114.114
```

# 3.如果返回 0.0.0.0 或者 127.0.0.1 则域名已被运营商劫持阻断

# 4.运营商劫持阻断原因
```
公安部推送涉诈域名要求处置
https://tjca.miit.gov.cn/jactpub/front/mailpubdetail.do?transactId=306874&sysid=40
```

# 5.全国拨测
```
https://www.boce.com/hijack
```

# 6.劫持阻断 与 墙 的区别
```
劫持阻断一般针对已备案域名，有涉诈嫌疑。仅部分地区运营商阻断，非全国。
停止网站业务或改正一段时间内一般都能解封。
```
