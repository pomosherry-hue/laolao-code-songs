# 姥姥快乐密码歌 · 小程序设计稿

在线画布（可以点着试）：https://claude.ai/artifact/KJiKc1SxQFiQsbaQwdxJjb

风格沿用 Mimi 小程序（`mimi-color-songs/miniprogram/app.wxss`）：奶油底 `#FFF7E8`、深棕字 `#3B2A1A`、黄色圆角头 `#FFC93C`、白边圆角卡片、胶囊按钮、底部浮动白色导航栏。为了老人好用，字和按钮都比 Mimi 大一号：正文不小于 18px，按钮不低于 56px。

| 文件 | 页面 |
|---|---|
| `Main.dc.html` | 首页：姥姥头像、兑换码按钮、今天的歌、季度筛选、歌曲卡片（未解锁的盖锁）、底部导航 |
| `Player.dc.html` | 听歌：歌曲颜色的背景动画、大字歌词（当前句黄色高亮）、播放控制、伴奏切换 |
| `Code.dc.html` | 快乐密码弹窗：大字密码，去小游戏 / 再听一遍 / 发给家里人 |
| `Game.dc.html` | 动动脑·擦窗户：点掉雨点，天放晴，出现快乐密码；不计时、不扣分 |
| `Redeem.dc.html` | 输入兑换码看全集：页面不提任何费用 |

直接用浏览器打开 `app-preview.html` 就能看全部页面，还能点着试。这些 `.dc.html` 是设计稿的源文件，要在上面的画布里打开才能看。开发时请按设计稿用微信小程序的 wxml/wxss 重新实现。
