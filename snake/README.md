# 贪吃蛇游戏

一个使用 HTML5 Canvas + JavaScript 开发的经典贪吃蛇游戏。

## 在线游玩

已部署到 Vercel，直接访问以下地址即可游玩：

> https://tryai-delta.vercel.app/

## 功能特性

- 经典贪吃蛇玩法
- 三档速度可调（慢/中/快）
- 得分与最高分记录（本地存储）
- 键盘控制（方向键 / WASD）
- 移动端触控支持
- 暂停/继续功能
- 精美渐变视觉效果

## 操作说明

| 操作 | 按键 |
|------|------|
| 移动 | 方向键 / WASD |
| 暂停 | 空格键 |

## 本地运行

直接在浏览器中打开 `index.html` 即可开始游戏。

## 部署方式（Vercel）

1. 将仓库导入 Vercel（https://vercel.com）
2. 用 GitHub 账号登录，选择 `charliezh929/tryai` 仓库
3. 点击 Deploy，Vercel 会自动部署
4. 根目录的 `vercel.json` 配置了路由重写，将 `/` 指向 `/snake/index.html`
5. 部署完成后，通过 Vercel 分配的域名即可在线游玩

## 项目结构

```
tryai/
  ├── vercel.json      # Vercel 路由配置
  └── snake/
        ├── index.html  # 游戏主文件
        └── README.md   # 项目说明
```