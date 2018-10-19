# 常见问题

本章节收集了网友常问问题，提问之前请先阅读该章节

## 如何自定义样式

审查元素的样式，进行覆盖，考虑到样式优先级问题，可用 `!important` 增加优先级，或增加 `className`，然后使用比如`.myClass.at-tabs` 这样的方式增加优先级。

## 如何修改边框、下划线样式

边框下划线有些组件是使用 `::after` 伪类，在微信开发者工具审查不到，但是实际是存在的，建议用 H5 模式审查样式。