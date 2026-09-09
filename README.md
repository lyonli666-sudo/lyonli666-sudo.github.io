# Lucky Draw

A standalone, browser-based lucky draw application designed for company events, annual meetings, team celebrations, and prize drawings.

一个无需安装、可直接在浏览器运行的企业活动抽奖工具。支持参会者与奖品导入、随机抽奖、缺席补抽、中奖记录、品牌设置、中英文界面以及舞台揭晓效果。

> Current Version / 当前版本：**v1.1.5**  
> Updated / 更新日期：**2026-09-09**

---

## Features / 功能

### Participant Management / 参会者管理

- Import participant lists from TXT or CSV
- 支持 TXT / CSV 参会者名单导入
- Supports Chinese and English names
- 支持中英文姓名
- Duplicate display names are treated as separate participants
- 同名人员仍可作为不同参会者参与抽奖
- Participant data is locked after successful application to reduce accidental changes during live events
- 成功应用名单后自动锁定，降低现场误操作风险
- Use **Reset Participants** before replacing the participant list
- 只有执行 **Reset Participants / 重置参会者** 后才能重新导入

### Prize Management / 奖品管理

- Import prize tiers, prize names and quantities
- 导入奖项、奖品名称及数量
- Automatically tracks remaining prizes
- 自动统计剩余奖品数量
- Prize data is independently locked after successful import
- 成功导入后奖品数据独立锁定
- Use **Reset Prizes** before replacing prize data
- 只有执行 **Reset Prizes / 重置奖品** 后才能重新导入

### Lucky Draw / 抽奖

- Select prize tier and number of winners
- 选择奖项及本轮中奖人数
- Animated participant rolling wall
- 动态参会者滚动墙
- Random winner selection
- 随机抽取中奖者
- Prevents eligible winners from being drawn repeatedly
- 防止已中奖人员重复参与普通抽奖
- Supports multiple draw rounds
- 支持多轮抽奖

### Winner Management / 中奖管理

- Winner records grouped by prize tier
- 按奖项显示中奖记录
- Mark a winner as absent
- 支持标记中奖者缺席
- Restore attendance before redraw
- 补抽前可恢复为在场状态
- Redraw absent winner slots
- 支持缺席名额补抽
- Export winner records
- 支持导出中奖名单
- Large winner result dialogs support independent scrolling
- 多人中奖时结果名单可独立滚动
- Draw Results header and **Close / 关闭** remain visible while scrolling
- 滚动多人中奖名单时，顶部标题及 **Close / 关闭** 始终保持可见

---

## Brand & Stage / 品牌与舞台

The application can be customized directly from **Preferences / 偏好设置**.

支持：

- Custom Event Title / 自定义活动标题
- Custom Brand Logo / 自定义品牌 Logo
- Light & Dark Appearance / 浅色与深色模式
- Chinese & English Interface / 中英文界面
- Accent Color / 强调色
- Draw Effects / 抽奖揭晓特效

### Accent Colors

Available presets:

- Neutral
- Blue
- Green
- Purple
- Gold
- Custom Color

The selected accent color is also used by interface highlights and celebration effects.

---

## Draw Effects / 抽奖特效

Three presentation levels are available.

### Minimal

Clean and restrained winner reveal.

简洁、正式，不使用额外舞台庆典效果。

Recommended for formal corporate events.

### Spotlight

Adds a focused winner reveal with a darker surrounding environment, winner-card emphasis and spotlight treatment.

增加舞台压暗、中奖卡片聚光以及揭晓动画。

Recommended for most company events.

### Celebration

Includes the Spotlight presentation plus multiple waves of lightweight celebration particles.

在 Spotlight 基础上增加多波庆典撒花效果。

Designed for:

- Major prizes
- Annual parties
- Final prize rounds
- Celebration moments

Celebration particles run inside an independent visual-effects layer and do not change the page layout.

### Preview

Use **Preview** in Preferences to test Draw Effects.

Preview does **not**:

- Create a winner record
- Reduce prize inventory
- Change draw history

---

## Sound & Speed / 音效与速度

Preferences also include:

- Sound On / Off
- Volume
- Rolling Speed

These settings are stored locally in the browser.

---

## Online Demo / 在线体验

GitHub Pages:

https://lyonli666-sudo.github.io/

---

## Run Locally / 本地运行

Lucky Draw is designed as a **single standalone HTML file**.

No server, build tool, Node.js, package manager or installation is required.

### Steps

1. Download the HTML file.
2. Double-click it.
3. Open it with Chrome, Edge, Firefox or Safari.
4. Import participants.
5. Import prizes.
6. Start the draw.

For live events, Chrome or Microsoft Edge is recommended.

---

## Participant File Format / 参会者文件格式

TXT and CSV are supported.

### TXT Example

One participant per line:

```text
Mia Xu
Alex Lu
张三
李四
