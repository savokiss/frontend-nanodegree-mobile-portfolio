## Website Performance Optimization portfolio project

性能优化课程 @ [Critical Rendering Path course](https://www.udacity.com/course/ud884).

PageSpeed 链接 @ [Google PageSpeed](https://developers.google.com/speed/pagespeed/insights)

本项目在线链接 @ [http://savokiss.me/frontend-nanodegree-mobile-portfolio/](http://savokiss.me/frontend-nanodegree-mobile-portfolio/)

### Getting started
- 本项目不需要任何其他构建工具，直接运行 index.html 即可

### Optimization Overview

#### Part 1: 优化 index.html 达到 pageSpeed 90分以上
1. 将打印的 css 设置 media 为 print
2. 移除 GoogleAnalytics 代码
3. 根据 pageSpeed 的建议压缩过大的图片
4. 将 pizzeria.jpg 图片增加缩略图版本以优化在首页显示的是小图的加载速度
5. 移除不必要的字体链接

#### Part 2: 优化 pizza.html 的帧速
1. 优化 `updatepositions` 方法以达到 滚动时保持 60 fps
2. 优化 `changePizzaSizes` 方法以达到 滑块跳转 pizza 大小的实际小于 5ms