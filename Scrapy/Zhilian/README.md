# Zhilian
## 抓取智联招聘中的岗位信息   

## 主要使用scrapy进行抓取，存储是使用MongoDB   
## 分析抓取页面   
```
    a.打开浏览器开发者工具，查看network中的请求信息，发现网站是通过ajax进行渲染的   
    b.点击浏览器开发者工具的xhr选项，可以看到ajax请求，然后请求url获得json数据   
```
