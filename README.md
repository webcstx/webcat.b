# 新年祝福页面
面向APP内嵌使用的节日祝福页面，红金喜庆主题，独立多语言分页跳转模式。

[English](b.md)
[Français](c.md)
[Español](d.md)

## 语言页面清单
- `newyear-zh.html` 中文
- `newyear-en.html` English
- `newyear-fr.html` Français
- `newyear-es.html` Español

## 功能说明
- 节日流动渐变背景、流光文字、飘落粒子特效
- 用户可输入并提交新年祝福
- 右上角语言链接，点击跳转至对应语言独立页面
- 底部保留「关于软件」跳转入口
- 移动端适配，适合 WebView 嵌入

## 页面跳转标记
### 中文页右上角跳转代码
```html
<a class="lang-switch" href="newyear-en.html">English</a>
<a class="lang-switch" href="newyear-fr.html">Français</a>
<a class="lang-switch" href="newyear-es.html">Español</a>
