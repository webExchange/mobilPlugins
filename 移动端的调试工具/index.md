### eruda ###
可以在移动端界面进行调试
只需引入
```
(function () {
        var script = document.createElement('script');
        script.src = "http://eruda.liriliri.io/eruda.min.js";
        document.body.appendChild(script);
        script.onload = function () {
            eruda.init()
        }
    })();
```
打开移动端页面后，界面会出现红色箭头所指的，点击它就可以调试了

![](https://i.imgur.com/swyO5zu.png)

会出现如下界面

![](https://i.imgur.com/PHZdTED.png)

就像电脑上的控制台一样，可以调试了