# TNG 日常开销

一个纯前端的静态记账网页(单个 `index.html`),用来记录 TNG eWallet 的日常进出。

## 功能
- 记一笔(支出/收入),日期、时间可修改,备注可选
- 点任意一笔可编辑或删除
- 日历按月查看,可选单日或日期区间看合计
- 月报卡片(点"分享给家人"),截图发给家人

## 使用
直接用浏览器打开 `index.html`,或部署到任意静态托管(GitHub Pages、Netlify、Cloudflare Pages)。

## 数据存储
在 Claude 之外运行时,数据保存在浏览器本地(localStorage),不会同步到其他设备。
