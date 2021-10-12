# Form Helper
本插件专为Web开发者和测试人员开发的表单数据自动填充，并支持自定义mock数据。支持Vue、React、AngularJs等构建的网站，目前只支持输入框和文本框。

## 一、表单填充配置
在表单所在页面右键点击“配置表单填充规则”，改操作会获取页面上的input，便于快速设置表单规则，如下图：
![image](https://user-images.githubusercontent.com/19631145/132083640-8d404758-d69e-4cb6-ab86-9f2a9d81d565.png)

示例
然后进入“表单规则配置”页，在站点中找到对应的站点对表单项mock数据进行配置。
![image](https://user-images.githubusercontent.com/19631145/132083707-b70b8aee-ffa8-41bf-bb54-00c8fb68ee2e.png)


## 二、快捷键配置
“快捷键配置”插件默认配置了常用的几种规则，可以对其进行修改。

常用规则配置示例
银行卡号只会生成19位的卡号，符合LUHN算法。

手机号 @tel

银行卡号  @bank

座机号 @landline
电子邮箱  @email

身份证号码 @id

日期  @date("yyyy-MM-dd")

正则表达式 /\d{5,10}/

更多用法请参考: [Mockjs](http://mockjs.com/examples.html) 

## 三、chrome翻译配置

某些网址使用chrome自带的翻译功能时会将代码块也进行翻译，不利于阅读，该功能可以指定我们不想翻译的内容。

![image](https://user-images.githubusercontent.com/19631145/136877939-7e9ba5f0-0ff4-4f94-ba8d-f00c86b7065d.png)

以github为例，通过元素审查获取代码块最顶级的标签或、class等。然后在插件配置页进行配置。
![image](https://user-images.githubusercontent.com/19631145/136878108-19440a74-88e5-4335-9936-91fb4aa93ff2.png)

ps: 网址匹配的 window.origin 暂不支持正则匹配。





