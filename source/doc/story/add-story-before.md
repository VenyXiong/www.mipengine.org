title: 开发小故事前期准备
layout: examples
---

## 小故事的概念

### 小故事是什么

​	小故事是一种可交互的多媒体卡片，是由多元化内容组成的媒体形态，可带来沉浸式、多媒体、可交互的浏览体验，如图，是一个小故事的示例；

- 示例

<img src="http://mipstatic.baidu.com/static/mip-static/mip-story/demo/static/oscar5.gif" width="276" height="494" />

### 小故事产品构成

​	每个小故事（Story）下有多个段落（View），每个段落（View）可自由组合音频、视频、图片、GIF、文字等富媒体元素(Element)。

<!-- - 示例 -->

<!-- ![intro-view-layer-element (1)](http://mipstatic.baidu.com/static/mip-static/mip-story/demo/static/intro-view-layer-element.jpg) -->

### 小故事面向人群

​	小故事采用开放的[MIP技术](https://www.mipengine.org/)，能让站长、自媒体、开发者、商家等各种可以提供优质有创意内容的人群使用工具或MIP技术进行小故事创作。

​	在百度搜索结果页的呈现形式如图：

![搜索结果页展示](http://mipstatic.baidu.com/static/mip-static/mip-story/demo/static/%E6%90%9C%E7%B4%A2%E7%BB%93%E6%9E%9C%E9%A1%B5%E5%B1%95%E7%A4%BA.png)

## 起步教程

### 技术储备

开发一个小故事的技术储备：

1. HTML，CSS和JavaScript的基本知识；
2. 对MIP的基础原理和规范，请参考[MIP 的开发文档](https://www.mipengine.org/doc/00-mip-101.html) ；

### 开发环境和demo

1、下载代码；

- 下载本教程的代码，下载地址如下：[oscar-demo](http://mipstatic.baidu.com/static/mip-static/mip-story/demo/story-demo.zip)；
- 提取zip文件的内容，减压后在story-demo目录下的oscar-story.html是完整小故事demo的入口。

2、运行示例页面

​	运行示例代码的方法和访问一个mip页面的方法一样，MIP 页文件可以直接运行，你可以选择如下方式，像预览普通 HTML 文件一样预览 MIP-HTML 页面：

- 直接在浏览器中打开（由于 XML HTTP Requests 失败可能会导致某些元素预览失败）。
- 在本地部署一个服务，如 Apache，Nginx 等。
   使用 MIP-CLI 辅助预览，使用方法见 MIP 博客：[开发教程一](http://www.cnblogs.com/mipengine/p/mip_cli_1_install.html)。

设置完本地的web服务，通过访问一下URL，可查看小故事的Demo示例：

```
http://localhost:8000/oscar-story.html
```

完成了以上准备工作，那么接下来，让我们开始开发属于你自己的小故事。


## 小故事开发系列教程

[一、开发小故事前期准备](https://www.mipengine.org/doc/story/add-story-before.html)

[二、小故事的组织结构](https://www.mipengine.org/doc/story/story-organization-structure.html)

[三、为小故事创建一个封面](https://www.mipengine.org/doc/story/add-story-cover.html)

[四、为小故事添加更多的内容段落](https://www.mipengine.org/doc/story/add-story-section.html)

[五、为小故事段落中的元素添加交互动画](https://www.mipengine.org/doc/story/add-story-animation.html)

[六、为小故事添加背景音乐](https://www.mipengine.org/doc/story/add-story-music.html)

[七、为小故事添加封底页面](https://www.mipengine.org/doc/story/add-story-end.html)

[八、为小故事添加页面统计](https://www.mipengine.org/doc/story/add-story-pix.html)

[九、对小故事进行页面代码规范校验](https://www.mipengine.org/doc/story/add-story-validate.html)