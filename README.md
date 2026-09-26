# Mental Models OS

个人模型库网页版。

## 部署目标
推荐使用 GitHub Pages。仓库内容放在根目录后，将 Pages Source 指向 `main / root` 即可。

## 文件
- `index.html`：模型库主页面
- `manifest.webmanifest`：移动端/PWA元数据
- `.nojekyll`：避免 GitHub Pages 的 Jekyll 处理

## 使用
打开网站后可：
- 全文搜索模型
- 按分类筛选
- 查看核心一句话、触发条件、底层逻辑、行动指令、边界/反例、关联模型、现实案例

## 后续维护
模型更新后只需要重新生成并覆盖 `index.html`。
