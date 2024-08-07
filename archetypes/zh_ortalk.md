{{/*- The following var extracts Talk #s -*/}}
{{- $talkNo := substr .Name 7 -3 -}}
---
title: "ORTalk {{ $talkNo }}: " # 在此添加talk的题目
date: {{ .Date }}
draft: true
# 编辑完成后把 `draft` 改成 false (不要双引号)
tags: [""]
categories: [""]
series: "OR Talk"
summary: "" # 在此添加talk总结
hiddenFromHomePage: false
hiddenFromSearch: false
toc:
  enable: true
  auto: true
mapbox:
share:
  enable: true
comment:
  enable: true
---
 

## 分享摘要
在此加入talk的内容摘要。


## 分享提纲
如果有的话，在此加入talk的内容摘要。
1. 第一点
2. 第二点


## 嘉宾介绍
在此添加嘉宾照片。步骤：
1. 在static/or_images下添加一个文件夹，文件夹名为“or_XX”（替换XX为当前talk编号）；
2. 上传照片到static/or_images/or_XX，并把图片文件名修改为“speaker.png”；
3. 把下面这行指令中的“41”修改为当前talk编号XX，并把嘉宾名字改为当前talk的嘉宾名字；
4. 删掉这段文字。
{{< figure src="/or_images/or_41/speaker.png" title="彭天翼" width="200">}}

在此添加嘉宾简介。


## 直播回放
{{< bilibili BV11G411R7hR >}}
把上面的BV号改成当前talk对应的bv号即可。


## 相关资料及延伸阅读
- 像这样列举相关的文章。
- Farias, Vivek, Andrew Li, Tianyi Peng, and Andrew Zheng. "Markovian interference in experiments." *Advances in Neural Information Processing Systems* 35 (2022): 535-549.

---

### 往期直播及相关推文
- 像这样列举相关的推文。注意符号都是英文符号。
- [推文名称](推文链接)
- [专访｜华人运筹学新星、MIT博士生 彭天翼：协助全球最大啤酒生产集团进行销售决策](https://mp.weixin.qq.com/s/GSfAatYmLMcVna1Q12exHA)
---