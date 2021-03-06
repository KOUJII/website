# 用户研究院 | 一个用户研提供究知识的平台
## 一.策划
* [产品文档](https://github.com/KOUJII/website/blob/master/%E9%A1%B9%E7%9B%AE%E7%AD%96%E5%88%92%E6%96%87%E6%A1%A3.md)
* **思维导图**  
![思维](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/%E7%94%A8%E6%88%B7%E7%A0%94%E7%A9%B6%E9%99%A2%EF%BC%88%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE%EF%BC%89.png)
* **网站地图**  
![网站](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/%E7%94%A8%E6%88%B7%E7%A0%94%E7%A9%B6%E9%99%A2%EF%BC%88%E7%BD%91%E7%AB%99%E5%9C%B0%E5%9B%BE%EF%BC%89.png)  
通过[访谈](https://github.com/KOUJII/website/blob/master/%E8%AE%BF%E8%B0%88.md)，修改了网站的目的以及内容，增加了“线下活动”，以及“关于我”模块，令网站更加完整。

## 二.管理
### Wordpress信息管理 
* **文章vs页面**:一共有21篇文章，6个页面
* **标签与分类**:一共有25个标签，16个分类目录
每篇文章至少有一个标签，且至少处在一个分类目录下
***

### Wordpress界面设计
* **选单与侧边栏**：5个一级菜单，二级菜单不超过7个；侧边栏放置搜索框、“功能”、“近期文章”、“近期评论”、“文章归档”
* **主页互动性**:主页侧边栏放置了搜索框、登录功能以及评论功能
* **小工具**:首页的最新资讯使用了`Meta slider`插件以呈现幻灯片的形式；首页的最新文章、最新活动使用了`SiteOrigin`；二级页面的面包屑导航使用了`Flexy Breadcrumb`插件,修改了css自行把面包屑最后一栏的字体加大。
![meta](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/%E5%B9%BB%E7%81%AF%E7%89%87.png)  
  
![site](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/site.png)  
 
![mian](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/%E9%9D%A2%E5%8C%85%E5%B1%91.png)

***
### Wordpress平面设计
* **[图库](https://github.com/KOUJII/website/tree/master/%E5%9B%BE%E5%BA%93)与配色**：图片内容以人、手机、电脑为主，统一使用[pixabay](https://pixabay.com/)网站的图片，授权方式：CC0，可以做商业用途，不要求署名；风格以非官方务实活泼为主；配色上，网站主要使用蓝色，但整体较为单调，因此选取图片时，会配合网站，图片以清爽简单为主，采用了红色橙色为基调或亮点的图片，增添网站活泼度
* **字型丶字体大小与排版**：字体手动修改css，标题使用了非衬线体-微软雅黑、正文使用了衬线体-宋体；字体标题比正文略大一些；文章排版，通过[访谈]("/访谈稿.md")，修改了间隔、标题加粗、图片统一排放。  

***
## 三.运营
### 云端架站
* **安全性**：安装且使用`wordfence`插件,观察网络攻击次数之后，尝试增加ssl以提高网站安全性，但失败了...    

![安全性](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/wordfence.png)  

* **域名**：域名为：http://jianbingguozi.me/
* **效能及Availability**：在效能测试网站http://ping.chinaz.com/ 对全世界144个探测点进行测试，测试国内及国外的速度，由于本网站的服务器建在新加坡，国内的速度相对慢些。针对这个问题，我使用chrome浏览器，查找首页耗时长的文件，结果发现首页图片中有五张的加载时间过长，遂换去。

![截图](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/chrome_2018-07-11_15-34-51.png)  

***
### 用研 
* **[访谈](https://github.com/KOUJII/website/blob/master/%E8%AE%BF%E8%B0%88.md)**:通过访谈，了解甲方以及用户的需求，首页增加了副标题;导航由原来的“研究、方法、应用”变成了现在的“用户研究、用户研究方法、线下活动、关于我”;首页原本仅摆放最新文章，现在新建了页面，首页摆放“最新咨询、最新文章、最新活动”三个模块，侧边栏还增加了搜索登陆等功能;增加了面包屑;调整了文章排版。
* **[焦点小组](https://github.com/KOUJII/website/blob/master/%E7%84%A6%E7%82%B9%E5%B0%8F%E7%BB%84.md)**:通过与三位同学进行焦点小组的用户调研，增加修改了面包屑最后一栏加粗加大;调整文章排版；图片更改成pixbay网站的图片，免授权;网站首页加了口号。
***
### 站长工具
* **SEO**:安装了`yoast SEO`插件，为了提高首页的排名，因此安装之后在首页增加了seo关键词。
* **流量分析**:  
1.从6月22号开始，使用了百度站长工具以及必应站长工具，使用站长工具之后我发现每天的索引量较少，因此在每篇文章加入seo关键词。收获是：在百度搜索关键词“中大南方 文传 用户研究”关键词排名前十；在必应搜索同样的关键词排名第一;  
2.从6月14日开始，安装并使用`jetpack`插件，根据我对网站浏览量统计的观察，对每个页面增加seo关键词，试图提高网站的浏览量。 

(百度)![百度](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/%E7%99%BE%E5%BA%A6%E7%B4%A2%E5%BC%95%E9%87%8F.png)  
![百度](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/%E7%99%BE%E5%BA%A6.png)  

(必应)![必应](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/%E5%BF%85%E5%BA%94%E7%AB%99%E9%95%BF%E5%B7%A5%E5%85%B7.png)
![必应](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/%E5%BF%85%E5%BA%94.png)  
 
 (jetpack)  
 
![jetpack](https://github.com/KOUJII/website/blob/master/%E6%88%AA%E5%9B%BE/jetpack.png)


