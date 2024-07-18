# ChinaDomains

厌倦dnsmasq-china-list带来太多无用的记录。从DNS查询里面，提取出中国IP的域名。


## RuleSets

1. 以.cn结尾，标记为真
2. dig+ecs AliDNS A记录，返回的结果里面包含至少1个China IP，标记为真
3. 贝叶斯算法，少量标签分类
