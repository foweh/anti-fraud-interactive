# 反诈小易 · 校园反诈情景互动

> 面向高校的反诈宣传互动网站：用情景对话、剧本杀、PK 问答把「刷单、杀猪盘、冒充客服」等高发骗局演一遍。
> An interactive anti-fraud awareness site for campuses — plain HTML + Vue components, no build step.

## 功能

| 模块 | 说明 |
| --- | --- |
| 情景对话 | 以聊天记录形式逐句还原骗局全过程，标出话术与破绽（`fanzha-demos/ChatPage.vue`） |
| 互动剧本 ×4 | 海龟汤、火眼金睛、剧本杀、反诈 PK（`fanzha-demos/demo-*.html`） |
| 演示合集 | 一键切换全部情景（`fanzha-demos/demos.html`） |
| 入口页面 | 视觉海报式首页 + 反诈小易形象素材（`index.html`） |

## 目录结构

```
index.html                  入口页
fanzha-demos/               情景演示（demos.html + 4 个剧本 + ChatPage.vue）
fanzha-xiaoyi/              反诈小易静态资源
assets/                     图片、图标、头像
```

## 运行

纯静态、无后端、无构建：

```bash
# 方式一：直接打开
open index.html
# 方式二：本地起服务（推荐，避免个别浏览器限制）
python3 -m http.server 8000
# 浏览器访问 http://localhost:8000
```

## 说明

- 校园宣传用途，案例均为虚构改编，不含真实个人信息。
- 若用于线下活动，建议配合易班/公众号推文投放。
