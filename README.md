# judge-browser 浏览器UA识别
# 使用方法
```
<script src="judge-browser.js" type="text/javascript" charset="utf-8"></script>
<script type="text/javascript">
	var client = new Client();
	console.log("Engine ：" + client.engine.name + " " + client.engine.version);
	console.log("Browser：" + client.browser.name + " " + client.browser.version);
	console.log("System ：" + client.system.name + " " + client.system.version);
</script>
```

