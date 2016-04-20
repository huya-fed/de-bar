# de-bar

---

一个de-bar工具，依赖于jq

简易控制台，开发、测试环境可以考虑启用。

---

## INSTALL


	fis install huya-fed/de-bar


## USAGE

	在sass文件中引用样式
	@import "components/de-bar/de-bar.css";

	var Saidebar = require('de-bar');
    Saidebar.open();
	Saidebar.log("log");
	Saidebar.info("info");
	Saidebar.warn("warn");
	Saidebar.error("error");


## API

### .log(String message)

### .info(String message)

### .warn(String message)

### .error(String message)

### .open()

### .close()
