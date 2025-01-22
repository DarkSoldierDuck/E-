# 关于脚本

## 这是什么?

* E网通自动刷课脚本

## 这个脚本有哪些功能？

* 自动
* 刷课
* 反防作弊

## 这个脚本有哪些缺点？

* 不能自动写题

#配置

## Edge

* [下载EdgeDrive](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver)
* 将msedgedriver.exe置于C:\Users\你的电脑账户名\AppData\Local\Programs\Python\你的Python版本\Scripts中,运行脚本

## 其它
* [下载YourBrowserDrive]()
* 将yourbrowserdriver.exe置于C:\Users\你的电脑账户名\AppData\Local\Programs\Python\你的Python版本\Scripts中,运行脚本
* 需修改
```javascript
logging.info("正在启动Edge...")
driver = webdriver.Edge()
```
为
```javascript
logging.info("正在启动YourBrowser...")
driver = webdriver.YourBrowser()
```


#杂项

## 感激
感谢以下的作者,排名不分先后

* [firstlight & ChatGPT]
* [493505110](https://github.com/493505110/FuckEWT360)

## 关于作者

```javascript
	[Jesse](https://space.bilibili.com/1770180796)
```
