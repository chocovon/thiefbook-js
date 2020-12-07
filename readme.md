# Thief-Book in Browser
摸鱼神器 Thief Book 的浏览器脚本版。浏览器本地运行，使用后不留痕迹。

## 使用说明

### 浏览器 Console 运行
打开浏览器的控制台（Console），复制下面的代码并在控制台执行，成功后，当前页面左下角会出现操作界面和提示。<br>
某些页面会因为安全策略禁止运行外部脚本，请直接复制完整 js 文件内容并执行。

```javascript
fetch("https://raw.githubusercontent.com/chocovon/thiefbook-js/master/thiefbook.js").then(response => response.text()).then(text => eval(text))
```

### 油猴脚本
[Greasy Fork](https://greasyfork.org/zh-CN/scripts/418268-thief-book-in-browser)