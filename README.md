# Parsers for clash  
 
# 主要功能特色
- 自带测速选择（机场各节点）
- 按国别测速分组(按国别分组)
    - 美国
    - 日本
    - 台湾
    - 新加坡
    - 韩国
    - 香港
    - 其它
- 可独立选择机场
    - Openai
    - Bing（2023-04-08添加，可用new bing）
    - Google（2023-05-06添加，强化谷歌线路的一致化，可以找Bard聊天了💬）
    - YouTube
    - GitHub
- 广告屏蔽

# 界面效果
![界面效果图](https://github.com/pencilheart/Parsers-for-clash/assets/61617063/7ff392aa-64c0-4e6e-8a1a-cade722dad88)



# 用法
直接复制parsers.yml的内容到clash的“setting--profiles--parsers”中，执行“profiles”的连接更新即可
ps：我用的是Clash for Windows
![image](https://github.com/iczrac/Parsers-for-clash/assets/73928031/2cf51196-ded5-4cfe-b78b-445410a05bd2)

# [safari翻译失效](https://github.com/ripperhe/Bob/issues/405)
CFW设置中的system proxy->bypass domain加入以下，使系统翻译服务不走代理
```
- "sequoia.apple.com"
- "seed-sequoia.siri.apple.com"
```

# 特别鸣谢
来自网络的各方力量
（按照内容更新，陆续更新技术贡献的各方名录）

@blackmatrix7[blackmatrix7/ios_rule_script: 分流规则、重写写规则及脚本。](https://github.com/blackmatrix7/ios_rule_script)
