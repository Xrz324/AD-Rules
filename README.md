<div align="center">
<h1>AD Filter</h1>
  <p>
    广告过滤规则整合
  </p>
<!-- Badges -->

<br/>
<h2 id="a">📔 项目说明</h2>

本项目旨在整合不同来源的广告过滤规则，通过 `Github Action` 定时执行，拉取远程规则，去重和分类输出。
根据过滤规则的特性，分为 `DOMAIN`、`REGEX`、`MODIFY`、`HOSTS` 四种类型，之间互不包含，请自行选择：

- `DOMAIN`：基于域名的过滤规则，适用于几乎所有广告过滤工具
- `REGEX`：基于正则表达式的**域名过滤**规则，适用于主流广告过滤工具
- `MODIFY`：基于正则和其他修饰符的过滤规则，可以拦截页面上的特定元素，但不适用于DNS过滤
- `HOSTS`：基于 `HOSTS` 的过滤规则，适用于支持 `HOSTS` 的所有设备

<br/>
