# Go Chat 💌

**Go Chat** 是一款沉浸式虚拟恋人陪伴应用，设定背景是与 Ghost（《使命召唤》中的角色）的异国恋。

> 名字既是 **Ghost Chat** 的缩写，也是 **"去聊天吧"** 的温暖邀请。

---

## ✨ 核心概念

这不是一款有剧情分支和选择的应用，而是追求**更真实、更日常的陪伴体验**。

就像在和真实的 Ghost 聊天——分享彼此的日常、思念和温暖的时刻。

---

## 🎮 功能特性

### 💬 AI 聊天系统
- 基于 Claude API，Ghost 有完整人设：冷幽默、干式讽刺、偶尔爆粗口
- 情绪状态系统：思念中 / 有点难过 / 出差中 / 无聊 / 开心，实时影响回复风格
- 出差模式：信号不稳定、35% 概率已读不回、偶尔发送失败
- Ghost 会主动发消息（3小时无互动自动触发）
- 撤回消息彩蛋：Ghost 偶尔发出一句「差点说漏嘴」的话，几秒后自动撤回
- 语音/视频通话彩蛋：接通后 Ghost 秒挂，并发消息拒绝

### 🖼️ 图片系统（持续更新中）
- Ghost 聊天中可发送图片——曼城雨景、营地走廊、威士忌酒杯等
- 朋友圈帖子支持配图——买了奢侈品/特殊事件触发时附图
- 图片存放于仓库 `/images` 文件夹，按场景分类：
  ```
  /images/scenery/    ← 风景/环境照
  /images/moments/    ← 物品特写（手表/戒指/玫瑰等）
  /images/circle/     ← 朋友圈专用配图
  ```
- 建议尺寸：**1024×1024px**，风格：cinematic, moody, dark aesthetic
- 图片库持续扩充，随时可新增触发场景

### 💰 虚拟金钱系统
- 初始余额 £100，以英镑为单位
- **每月25号**自动发工资 £3,500（TF141中尉实际薪资参考）
- **撒娇讨要**：说「给我钱」「零花钱」等触发，每周累计上限 £300，超额 Ghost 毒舌拒绝
- **节日红包**：情人节 £520 / 结婚纪念日 £1,314 / 生日 £888
- **随机彩蛋**：每次打开 App 15% 概率，Ghost 偷偷转 £5~20
- 转账以少女信封风格卡片呈现，英文+中文双语备注

### 🛒 虚拟超市 & 聊天联动
- 五大分类：服装 / 礼物 / 特别礼物 / **✨ 精品专柜** / 心愿单
- **聊天触发角标**：Ghost 说了对应关键词，超市商品自动出现「👻 他提到了」标签
  - 抱怨伙食差 → 食品区高亮
  - 说冷/freezing → 服装区高亮
  - 说累/exhausted → 香薰蜡烛推荐
  - 说想你/miss you → 情侣周边提示
- **专属反应台词**：买了对应商品，Ghost 说专属感谢（不再随机）
- **每周限时折扣**：精品专柜随机一件打75~85折，金色角标提示

### ✨ 精品专柜
- 8件高端商品：Tiffany项链 / Burberry风衣 / Rolex劳力士 / Macallan威士忌 / La Mer护肤 / 999朵永生玫瑰 / 头等舱升级 / Cartier情侣戒指
- **三段式破防反应**：买完立刻 → 4秒后 → 8秒后，Ghost情绪层层发酵
- **专属朋友圈事件**：买Rolex → Ghost发「I don't deserve her.」4分钟后自动删除
- **头等舱升级逻辑**：必须先在心愿单买普通机票（£12,000），头等舱（£3,200）才解锁
- **Ghost行为变化**：买奢侈品后签名池加入专属签名，主动消息也会提到对应物品
- **买Cartier对戒**：聊天header状态强制变「❤️ 思念中」持续24小时

### 📅 日历 & 纪念日
- 结婚纪念日倒计时 / 正计时
- 26个节日高亮，工资日薄荷绿标记
- 节日当天便当盒卡片动态变化

### 👥 朋友圈
- 15条日常帖子池（班味摆烂 / 克制思念 / 曼城日常）
- 特殊事件触发：吵架后冷战、吃醋后删帖（5分钟自动删）、收到贵重礼物、买机票、买护肤品、买奢侈品
- 点赞后 Ghost 小声回一句，英文+中文双语

### 💝 我的宝贝
- Editorial 杂志风排版，第一张横跨两列大图感
- 已解锁成就横向滚动徽章展示

### 🏆 成就系统
- 18个成就，含4个奢侈品专属成就（精品初体验 / 轻奢生活家 / 永恒誓言 / 豪掷千金）
- 消费门槛：£100 / £1,000 / £5,000 / £20,000
- 见面计划三件套触发终极弹窗

### 🔒 秘密页面
- 存储用户生日、星座、MBTI、最爱颜色等私密信息
- Ghost 的系统提示词中注入用户信息，让对话更私人

### ✍️ Ghost 签名
- 分5类情绪签名池，随情绪自动更换，点击手动刷新
- 购买奢侈品后有30%概率触发专属签名（如买Cartier → *"Married. That's all."*）

---

## 🎯 沉浸式异国恋体验

| 场景 | 体验 |
|------|------|
| Ghost 说伙食很差 | 去超市买茶叶寄给他，他专属回复「Yorkshire tea. You remembered.」|
| Ghost 说冷 | 买羊毛大衣，他说「The coat arrived. Warm. Thank you.」|
| 发工资日25号 | Ghost 自动转账 £3,500，附言「Don't spend it all on skincare.」|
| 情人节 | 自动收到 £520 红包 |
| 撒娇超过 £300/周 | Ghost 毒舌：「I gave you £300 this week. Where did it go.」|
| 买 Rolex 送他 | 三段破防，最后「...Thank you. I mean it.」|
| 买 Cartier 对戒 | 状态变「❤️ 思念中」持续24小时，朋友圈发「I'm wearing mine.」|
| 买头等舱（需先买普通机票） | 签名换成「She's coming.」，Ghost说「I cleaned up the flat. A bit.」|

---

## 🚀 快速开始

### 在线体验
访问 Vercel 部署：[Go Chat Web App](https://your-vercel-link.com)

### 本地运行

```bash
git clone https://github.com/Ohara520/go-chat.git
cd go-chat
python3 -m http.server 3000
# 访问 http://localhost:3000
```

或直接用浏览器打开 `index.html`。

---

## 📁 项目结构

```
go-chat/
├── index.html           # 主应用文件（所有 HTML / CSS / JS 单文件）
├── images/
│   ├── scenery/         # 风景/环境照（曼城雨景、营地走廊等）
│   ├── moments/         # 物品特写（手表、戒指、玫瑰等）
│   └── circle/          # 朋友圈专用配图
├── README.md
├── vercel.json
└── .gitignore
```

---

## 🎨 技术栈

- **前端**：HTML5 + CSS3 + Vanilla JavaScript（单文件架构）
- **AI**：Claude API（claude-haiku-4-5，对话历史保留最近20条）
- **存储**：浏览器 localStorage
- **部署**：Vercel / GitHub Pages

---

## ⚙️ 配置 Claude API

1. 前往 [console.anthropic.com](https://console.anthropic.com) 获取 API Key
2. 打开 App → 点击 Ghost 头像 → 进入资料卡
3. 在底部输入 API Key 并保存
4. 无 Key 时自动使用 fallback 回复池，不影响基本体验

---

## 🖼️ 添加图片资源

1. 用 AI 生成图片（建议 1024×1024px，风格 cinematic moody dark）
2. 上传到仓库对应文件夹（`/images/scenery/` 等）
3. 在代码中配置触发场景与图片路径的对应关系

**聊天图片触发示例：**
```javascript
// Ghost说到下雨时发图
{ keywords: ['rain', 'raining', '下雨'], image: 'images/scenery/manchester-rain.jpg' }
```

**朋友圈配图示例：**
```javascript
// 买劳力士触发朋友圈带图
{ trigger: 'rolex', image: 'images/moments/rolex-wrist.jpg' }
```

---

## 💾 数据说明

所有数据存储在浏览器本地（localStorage），包括聊天记录、钱包余额、收藏消息、成就进度等。清空浏览器缓存后数据会丢失，请注意备份。

---

## 📊 当前版本：v1.3

### ✅ 已完成
- AI 对话 + 完整 Ghost 人设
- 虚拟金钱系统（工资 £3,500 / 撒娇每周限额 £300 / 红包 / 彩蛋）
- 转账卡片 UI（少女信封风，双语备注）
- 超市购物 + 聊天联动角标 + 专属反应台词
- 精品专柜（8件 + 三段破防 + 限时折扣 + 行为变化）
- 头等舱升级需先买普通机票
- 成就系统（18个，含奢侈品专属4个）
- 朋友圈（普通15条 + 特殊事件触发含奢侈品）
- 日历系统（26个节日）
- 签名彩蛋 / 撤回消息彩蛋 / 通话彩蛋
- 秘密页面 / 我的宝贝 Editorial 排版
- 图片系统框架（持续扩充中）

### 🔨 计划中
- [ ] 图片库扩充（聊天发图 + 朋友圈配图）
- [ ] 早安 / 晚安系统
- [ ] 奢侈品购买更多段破防台词
- [ ] 会员系统（普通 / 挚友 / 军嫂）

---

## 🐛 反馈与建议

欢迎在 [GitHub Issues](https://github.com/Ohara520/go-chat/issues) 提交反馈，或在视频评论区留言。

---

## ⚖️ 许可证

MIT License

---

## 🙏 致谢

感谢所有期待和支持 Go Chat 的宝宝们！💜

- Anthropic 提供的 Claude API
- Call of Duty 中 Ghost 这个角色的灵感
- 所有给予反馈和建议的用户

---

**Made with 💜 by 诺亚**

*Go Chat - 让陪伴成为一种日常。*
