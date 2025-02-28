# XunJson

## 介绍
 **XunJson是一款由讯暮团队开发的轻量级、快速、便捷的Android Json解析库**

## 优点
 **简单易用：几行代码解决**
 **轻量级：so库大小仅328kb**
 **快速解析：执行代码到完成解析不超过5ms**

## 使用
 **导入库后执行以下代码即可**
String json = "{\"name\":\"Alice\", \"age\":25, \"city\":\"Paris\"}";  //示例
String age = JsonUtils.parseJson(json, "age");  // age为需要解析的字段
Log.d("XunJson", "Age: " + age);  //打印解析结果
