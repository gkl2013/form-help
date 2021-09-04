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

手机号@tel=>13125404501

银行卡号@bank=>6225315001616947532

座机号@landline=>637-16755165

电子邮箱@email=>i.nhmhkj@mfsmxisg.ba

身份证号码@id=>320000197706152126

日期@date("yyyy-MM-dd")=>2001-06-17

正则表达式/\d{5,10}/=>39247225

更多用法请参考: [Mockjs](http://mockjs.com/examples.html)
