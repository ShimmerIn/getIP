# getIP

## 1、前情提要

   本项目主要是基于缺钱产生的一点想法，技术用的不是很深（其实没啥技术，就是简单的爬虫以及简单的提交），
同时为了锻炼自己写文档能力和熟悉git的产物，有不当之处，请看到文档的大佬轻喷。下面介绍下大概想法，近
期看了下域名圈，一个四字母.com的域名可以卖到七八千，而三字母，三数字就更不用说了。于是想通过技术手段
找到剩余未发掘的域名，提前抢注，混点饭钱。

## 2、技术

### 2.1、python3.6
   requests<br/>
   beautifulsoup<br/>
   re<br/>
   pymysql
### 2.2、mysql


## 3、核心内容

1、把所有数字遍历，生成一张三数字、四数字的数字表。遍历所有字母，同样生成一张三字母、四字母的字母表。<br/>
2、循环字母表，拼接url，提交到whois，读取注册信息，标识未注册域名<br/>
3、调用微信接口，发掘出未注册域名，提醒抢注。

## 4、项目进度

   实现到了第二步，发现大量的域名都被抢注了，基本没有漏网之鱼来捡了。死心的咸鱼默默的开源下自己的想法以
及代码，赚钱大计划泡汤了，心累~

## 5、有兴趣一起学习的好友可以加下

   VX:HelloTiancl
