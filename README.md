![image](https://github.com/xiaott-ahh/five-six-vue/blob/master/src/assets/images/logo.png)
***
![](https://img.shields.io/badge/language-java-red.svg)  ![](https://img.shields.io/badge/licsense-MIT-green.svg)
# 项目简介
这是一个前后端分离的电影管理和推荐系统，采用Vue.js + Spring Boot技术栈开发
- 前端项目地址：[前端项目](https://github.com/xiaott-ahh/five-six-vue)
- 后端项目地址：[后端地址](https://github.com/xiaott-ahh/five-six)
# 前台效果
## 主页
主页是网站的门户，进行导航和slogan的展示，提供搜索的功能

![image](https://github.com/xiaott-ahh/five-six-vue/blob/master/src/assets/showGifs/home.gif)
## 搜索
可以根据关键词进行搜索（导演、演员)，后端目前采用模糊查询的方式返回数据库中的记录

![image](https://github.com/xiaott-ahh/five-six-vue/blob/master/src/assets/showGifs/search.gif)
## 电影集
该页是电影信息展示和选择界面，仿豆瓣界面设计；可以根据类别、评分、时间进行电影的搜索；目前包含1500+电影信息（也就是爬200部封一次ip吧...）

![image](https://github.com/xiaott-ahh/five-six-vue/blob/master/src/assets/showGifs/movies.gif)
#### 待完成
- [ ] 加入电影的资源地址
- [ ] 爬更多的电影...
## 向我推荐
该界面主要是根据用户的浏览记录和收藏等信息对其进行个性化推荐

![image](https://github.com/xiaott-ahh/five-six-vue/blob/master/src/assets/showGifs/rec.gif)
## 影讯
待开发...
# 后台效果
后台主要进行用户管理、角色配置以及电影信息管理

![image](https://github.com/xiaott-ahh/five-six-vue/blob/master/src/assets/showGifs/manage.gif)
# 技术架构

# 主要技术栈
## 前端
- Vue.js
- ElementUI
- axios
## 后端
- Spring Boot
- MyBatis
- Apache Shiro
## 数据库
- MySQL
