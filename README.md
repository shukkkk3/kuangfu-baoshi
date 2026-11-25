# 匡扶堡室

三国题材游戏同盟的单页主页，单文件 HTML（CSS、JS、图片全部内联），不依赖任何构建和外部资源。

## 页面结构

固定顶栏 → 首屏（会动的 3D 卡通汉堡）→ 公告 → 关于 → 赛季战史 → 整屏图片停顿 → 成员名册 → 核心成员 → 功勋榜（深色）→ 招募加入 → 友军同盟 → 收尾大字与页脚。

首屏的汉堡会呼吸起伏，鼠标移动时轻微转向，周围的小配料按远近分层视差；全页还有飘浮的小汉堡粒子。

## 打开方式

把 `index.html` 下载到本地，双击即可在浏览器中打开，不需要启动服务器。

## 修改内容

用任意文本编辑器打开 `index.html`，搜索 `const DATA = {`，按行内注释填写：`slogan`、`bulletins`、`about`、`chronicles`、`roster`、`members`、`hall`、`contacts`、`allies` 等字段。留空的字段会自动显示「待填写」。

## 部署到 GitHub Pages

1. 仓库 Settings → Pages
2. Source 选择 `Deploy from a branch`，分支选 `main`，目录选 `/ (root)`
3. 保存后等一两分钟，访问 `https://shukkkk3.github.io/kuangfu-baoshi/`

## 说明

页面内所有文字为占位内容，正式使用前需要替换为同盟的真实信息。
