# 可喵大人の控制 静态资源

服务器的静态资源、CSS 结构、Javascript 文件、图片、字体等使用 CDN 托管。

## 文件路径

> 使用 `jsDelivr` 托管，根路径为 `https://cdn.jsdelivr.net/gh/winkyneverlose/static-resources/`

```
static-resources/
│
├── root/
│ ├── img/
│ │ ├── kemiao.jpg # 网站管理员可喵大人的头像
│ │ └── assistant.jpg # 可喵大人助手的头像
│
├── font/
│
├── icon/
│
├── img/
│ ├── default_avatar.png # 用户默认头像
│ ├── default_avatar.svg # 用户默认头像（矢量）
│ └── game/ # 游戏内图片
│
├── audio/
│ ├── effects/ # 音效
│ └── music # 背景音乐
│
├── game/
│ └── background/ # 游戏场景背景图片资源库
│
└── background/
├── game1.jpg # 游戏 ID 为 game1 的背景图片
├── game2.jpg # 游戏 ID 为 game2 的背景图片
└── **** # 其他游戏背景图片
```

> 游戏背景图片必须以游戏 ID 命名，且 .jpg 格式
