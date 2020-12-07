# Thief Book in Browser
摸鱼神器 Thief Book 的浏览器脚本版。浏览器本地运行，使用后不留痕迹。

## 使用说明
打开浏览器的控制台（Console），复制下面的代码并在控制台执行，成功后，当前页面左下角会出现操作界面和提示。

```javascript
fetch("https://raw.githubusercontent.com/chocovon/thiefbook-js/master/thiefbook.js").then(response => response.text()).then(text => eval(text))
```