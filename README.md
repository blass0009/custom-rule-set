# custom-rule-set
#### 一些surfboard自定义规则集
#### CDN_list.txt是可以直连的CDN地址，用于半代理
#### C_blacklist.txt是自定义白名单
#### C_blacklist.txt是自定义黑名单，包括一些想要拦截的内容（包括但不限于广告）
#### 使用例：
```
RULE-SET,https://raw.githubusercontent.com/blass0009/custom-rule-set/main/CDN_list.txt,DIRECT
RULE-SET,https://raw.githubusercontent.com/blass0009/custom-rule-set/main/C_black_list,REJECT
```
