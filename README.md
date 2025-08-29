# 30天运动记录本（GitHub Pages 版）

**无云端、无 CSV 导出，仅使用浏览器本地存储（localStorage）**。适合直接部署到 GitHub Pages，手机/电脑都能访问使用。

## 使用方法

1. 新建仓库（例如 `fitness30`），把本项目的 `index.html` 放到仓库根目录。
2. 打开 GitHub → Repository → **Settings** → **Pages** → **Build and deployment**：
   - Source: 选择 **Deploy from a branch**
   - Branch: 选择 **main** 分支，**/root** 目录
3. 保存后，稍等几分钟，GitHub 会生成访问链接，如：  
   `https://<你的用户名>.github.io/fitness30/`

## 功能说明

- 30 天表格：日期 / 距离 / 步数 / 千卡 / 体重 / 体重变化 / 体重状态 / 预计达成天数
- 顶部 KPI：累计距离、累计步数、累计消耗、体重变化、当前 BMI
- 图表：体重折线 / 热量柱状（Chart.js CDN）
- 本地持久化：自动保存到 `localStorage`
- 一键清空：支持清空当前设备上的本地数据
- **分享链接**：点击“生成当前页面可分享链接”，会把当前状态编码到 URL 的 `#hash`，复制后在其它设备打开即可加载该状态（不需要服务器）

> 注意：分享链接会包含你的记录数据，请只与信任的人分享。

## 定制

- 想要自定义颜色、字体、Logo，或改成多语言、增加运动类型/MET 计算、导入导出等，请在 ChatGPT 里告诉我，我会生成新版文件。

## 许可

MIT License © 2025
