# page-monitor
前端UI测试自动化库page-monitor介绍
原作者仓库[page-monitor](https://github.com/fouber/page-monitor)
里面有文档


-----
## 下面是我这个的介绍
在config.json里面设置要测试的网页

`npm run catch`得到第一次页面加载的截图and dom树等
`npm run catch` again，再次得到第二次的截图

这时，你得到了两个以时间戳命名的文件夹

在`diff.js`里，替换变量version1 和version2 ，就是对比的版本
然后，
`npm run diff`,对比俩版本，得到结果
