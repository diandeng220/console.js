# console.js
console for mobile browser or old ie  
让手机浏览器拥有控制台  
![console](mb.png)  

## 显示代码报错
```javascript
// 代码出错会被打印出来
window.xxfun();
```

## 显示 console.log 调试信息
```javascript
setTimeout(function() {
    console.log('log 会被显示:', {
        name: 'wsf',
        obj: {
            list: [1, 2, 3]
        }
    });
    console.log(navigator.userAgent);
}, 6000)
```
双击保存变量

## 执行 js
可在控制台下方 run js
* 输入代码，回车执行。
* 支持单行和多行，多行语句加上分号再换行即可。
* 没有输入直接回车清空控制台。

## 为什么要使用
* 移动web log 信息看不到
* 移动web 出错看不到报错
* 手机浏览器、混合型 app、微信web 开发调试
* ie 6 7 没有控制台也可使用

## 使用方法
1.引入 `console.js`，尽量放在所有脚本最前面
```html
<script src="../console.js"></script>
```

2.需要调试时，在 url 上加入 "?console" 参数则打开，去掉则关闭
```
http://domain/path/page?console
```


## 下载
<a href="https://rawgit.com/wusfen/console.js/master/console.min.js">console.min.js</a>

## 示例
<a href="https://rawgit.com/wusfen/console.js/master/example.html?console">example.html?console</a> |
<a href="https://cdn.rawgit.com/wusfen/console.js/94c229ab/example.html?console">[cdn]example.html?console</a>  
![qrcode](qrcode.png)  
