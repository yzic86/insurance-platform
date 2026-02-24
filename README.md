# 保险宣传平台（纯前端版）
## 项目说明
本项目为纯前端实现的保险宣传承接平台，无需数据库和后端服务，所有数据存储在data.js中，适合内容更新频率较低的场景。

## 部署步骤
1. 将整个insurance-platform文件夹上传至Web服务器（如Nginx、Apache）；
2. 准备images文件夹中的图片（logo、轮播图、险种图标），替换为实际图片；
3. 准备files文件夹中的附件（如有）；
4. 修改data.js中的数据为实际的保险公司/宣传内容信息；
5. 访问index.html即可打开首页。

## 内容修改说明
- 新增/修改保险公司：编辑data.js中的insuranceCompanies数组；
- 新增/修改宣传内容：编辑data.js中的newsList数组；
- 新增/修改轮播图：编辑data.js中的bannerList数组；
- 联系方式修改：直接修改data.js中对应公司的contact字段。

## 注意事项
- 图片/附件路径需与data.js中配置的一致；
- 支持主流浏览器（Chrome/Firefox/Edge/Safari）；
- 基础适配移动端，可根据需求进一步优化样式。