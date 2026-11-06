# A Roll for Two — 复刻站

纪念日电子礼物站：模拟胶片冲洗交互，放回忆照片和告白文字。

## 结构
- `index.html` — 壳（场景切换、过场、音乐）
- `scene/` — 7 个场景页（封面、暗房、信封、胶卷、灯箱、手电筒、书、片尾）
- `content.js` — 唯一的数据文件：所有文字、照片路径、音乐都在这里换
- `lib/` — Three.js + GLTFLoader
- `models/` — 指南针、8mm 放映机 3D 模型
- `img/`、`font/`、`music/`、`sfx/` — 贴图、字体、音乐、音效
- `u/` — 照片占位（换成自己的照片即可，文件名对应 content.js 里的引用）

## 部署（Vercel）
1. 把这个文件夹推到 GitHub 仓库
2. Vercel → Add New Project → Import 这个仓库 → Framework 选 Other，不用构建命令
3. 部署后得到公开链接；以后改 `content.js` 后推送到 GitHub，Vercel 自动重新部署

## 在线改（Bolt.new）
Bolt.new → 导入这个 GitHub 仓库，即可在线改代码和内容。
