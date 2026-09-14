# Lucky Draw

A polished, standalone lucky draw application designed for company events, annual meetings, team celebrations, town halls, and prize drawings.

一个无需安装、无需服务器、可直接在浏览器运行的企业活动抽奖工具。支持参会者与奖品导入、随机抽奖、缺席补抽、中奖记录、奖品可视化核对、中英文界面、品牌自定义以及多种舞台滚动效果。

> Current Version / 当前版本：**v2.2.34**  
> Updated / 更新日期：**2026-09-14**

---

## Overview / 项目简介

Lucky Draw is built as a **single standalone HTML file**.

No Node.js, npm, database, backend service, or installation is required. Download the HTML file and open it directly in a modern browser.

Lucky Draw 采用 **单 HTML 文件** 设计，无需安装 Node.js、npm、数据库或任何后端服务。下载后双击 HTML 文件即可运行，非常适合公司年会、团队活动、会议抽奖以及现场大屏展示。

### Key Highlights / 核心特点

- Single-file standalone application / 单 HTML 文件独立运行
- Participant & prize import / 参会者与奖品导入
- Random winner selection / 随机抽奖
- Multiple draw rounds / 多轮抽奖
- Absent winner redraw / 缺席补抽
- Winner history & CSV export / 中奖记录与 CSV 导出
- Prize dashboard / 奖品可视化核对
- Multiple rolling styles / 多种名字滚动方式
- Chinese & English UI / 中英文界面
- Light & Dark mode / 浅色与深色模式
- Custom branding / 品牌自定义
- Sound & stage effects / 音效与舞台效果
- Responsive interface / 响应式界面
- Local browser storage / 浏览器本地保存设置

---

## Features / 功能

### Participant Management / 参会者管理

Import participant lists from **TXT or CSV** files.

支持通过 **TXT / CSV** 文件导入参会者名单。

- Supports Chinese and English names
- 支持中英文姓名
- Duplicate display names can participate independently
- 同名人员仍可作为不同参会者参与抽奖
- Participant data is locked after successful application
- 成功应用名单后自动锁定，降低现场误操作风险
- Upload status remains visible after successful import
- 上传成功后持续显示完成状态
- Use **Reset Participants / 重置参会者** before replacing the list
- 更换名单前需要先执行 **重置参会者**

---

### Prize Management / 奖品管理

Import prize tiers, prize names and quantities from CSV.

支持导入奖项、奖品名称以及奖品数量。

- Automatically tracks remaining prizes
- 自动统计剩余奖品
- Prize data is independently locked after successful import
- 奖品导入后独立锁定
- Upload status remains visible after successful import
- 上传成功后持续显示完成状态
- Use **Reset Prizes / 重置奖品** before replacing prize data
- 更换奖品前需要先执行 **重置奖品**

### Prize Dashboard / 奖品核对

Imported prize data can be visually reviewed before the event.

导入奖品后，可以通过可视化界面快速核对奖品名称及数量。

Available views:

- Horizontal Chart / 横状图
- Cards / 卡片

The preferred display mode can be selected from **Preferences / 偏好设置**.

---

## Lucky Draw / 抽奖舞台

The draw stage is designed for live presentation on large screens.

抽奖舞台针对会议室、大屏以及现场活动展示进行了优化。

- Select prize tier
- 选择当前奖项
- Select number of winners
- 设置本轮中奖人数
- Automatically limits the maximum available winners
- 自动限制本轮最大可抽人数
- Random winner selection
- 随机抽取中奖者
- Prevents normal draws from selecting previous winners again
- 普通抽奖自动排除已中奖人员
- Supports multiple draw rounds
- 支持连续多轮抽奖
- Animated winner reveal
- 中奖结果动画揭晓

### Rolling Styles / 名字滚动方式

Two stage rolling styles are available:

#### Rapid Shuffle / 快速闪选

Names rapidly change across multiple columns.

经典快速名字跳动模式，适合正式会议及企业活动。

#### Slot Reels / 滚轮模式

Names move vertically in multiple synchronized reels, inspired by slot-machine displays.

名字以多列纵向滚轮方式滚动，让抽奖过程更具有节奏感。

The rolling style can be changed from **Preferences / 偏好设置**.

---

## Winner Management / 中奖管理

Winner records are automatically organized by prize tier.

中奖记录会按照奖项自动分类显示。

- View winner history
- 查看中奖记录
- Group winners by prize tier
- 按奖项分类
- Mark a winner as absent
- 标记中奖者缺席
- Restore attendance
- 恢复中奖者在场状态
- Redraw absent winner slots
- 对缺席名额进行补抽
- Export winner records as CSV
- 导出中奖名单 CSV

### Winner Result Dialog / 中奖结果弹窗

Large winner lists use an independently scrollable result area.

多人中奖时，中奖名单区域可以独立滚动，同时保持标题和操作区域固定，方便现场查看。

The redraw result dialog uses the same structured layout for consistent presentation.

补抽结果同样采用统一的结果展示结构。

---

## Preferences / 偏好设置

Lucky Draw includes a centralized Preferences panel for interface and stage customization.

所有主要外观和舞台设置均集中在 **偏好设置** 中管理。

Available settings include:

- Event Title / 活动标题
- Brand Logo / 品牌 Logo
- Appearance / 外观模式
- Interface Language / 界面语言
- Accent Color / 强调色
- Prize Display Mode / 奖品显示方式
- Stage Rolling Style / 舞台滚动方式
- Draw Effects / 抽奖特效
- Mouse Glow / 鼠标光晕
- Sound / 音效
- Volume / 音量
- Rolling Speed / 滚动速度

---

## Appearance / 外观

### Light & Dark Mode

Lucky Draw supports both light and dark interfaces.

支持浅色和深色界面，并针对文字层级、边框、卡片以及舞台区域进行了适配。

### Accent Colors / 强调色

Multiple accent colors are available to match different event themes.

强调色会应用于按钮、状态、界面高亮以及部分舞台效果。

### Mouse Glow / 鼠标光晕

An optional subtle pointer glow can be enabled from Preferences.

可以在偏好设置中开启或关闭鼠标光晕，用于增强桌面端的界面交互感。

---

## Draw Effects / 抽奖特效

Different presentation levels are available depending on the event style.

### Minimal

Clean and restrained winner reveal.

简洁、正式，适合会议及较正式的企业活动。

### Spotlight

Adds focused winner presentation and stage emphasis.

增加舞台聚焦以及中奖卡片强调效果。

### Celebration

Adds celebration particles for important prize moments.

适合大奖、年会以及最终奖项揭晓。

Visual effects run independently and do not change the page layout.

所有舞台视觉效果均独立运行，不会改变页面布局。

### Preview

Use **Preview / 预览** in Preferences to test effects before the event.

Preview does not:

- Create winner records
- Reduce prize inventory
- Change draw history

预览不会产生真实中奖记录，也不会减少奖品数量或修改抽奖历史。

---

## Sound & Speed / 音效与速度

Preferences include:

- Sound On / Off
- Volume
- Rolling Speed

支持：

- 音效开关
- 音量调节
- 名字滚动速度

These preferences are stored locally in the browser.

---

## Chinese & English / 中英文界面

Lucky Draw provides a bilingual interface.

Lucky Draw 支持完整的中英文界面切换，包括：

- Navigation
- Dashboard
- Data Management
- Draw Stage
- Winner Management
- Preferences
- Empty States
- Dialogs and status messages

Language preferences are stored locally.

---

## Online Demo / 在线体验

GitHub Pages:

https://lyonli666-sudo.github.io/

---

## Run Locally / 本地运行

Lucky Draw is designed as a **single standalone HTML file**.

No server, build tool, Node.js, npm, package manager, or installation is required.

### Steps / 使用步骤

1. Download the HTML file.  
   下载 HTML 文件。

2. Double-click the file.  
   双击打开。

3. Open it with Chrome, Microsoft Edge, Firefox, or Safari.  
   使用现代浏览器运行。

4. Import participants.  
   导入参会者名单。

5. Import prizes.  
   导入奖品清单。

6. Review the imported data.  
   核对参会者及奖品数据。

7. Start the draw.  
   开始抽奖。

For live events, the latest versions of **Google Chrome** or **Microsoft Edge** are recommended.

---

## Participant File Format / 参会者文件格式

TXT and CSV are supported.

### TXT

One participant per line.

每行一个姓名，支持中英文。

```text
Mia Xu
Alex Lu
张三
李四
```

### CSV

The participant name should be placed in the first column.

姓名放在第一列，支持表头，建议使用 UTF-8 编码。

```csv
Name
Mia Xu
Alex Lu
张三
李四
```

---

## Prize File Format / 奖品文件格式

Prize data is imported by column position.

奖品清单按照列位置读取：

```text
Column 1 / 第1列：Order / 顺序
Column 2 / 第2列：Prize Tier / 奖项
Column 3 / 第3列：Product / 产品
Column 4 / 第4列：Quantity / 数量
```

Example:

```csv
Order,Prize Tier,Product,Quantity
1,First Prize,iPad,1
2,Second Prize,Headphones,3
3,Third Prize,Gift Card,10
```

---

## Data & Privacy / 数据与隐私

Lucky Draw runs entirely inside the browser.

Lucky Draw 的主要数据处理均在浏览器本地完成。

Participant lists, prize information and draw data do not require a dedicated backend server to operate.

因此非常适合需要快速部署、离线运行或现场使用的企业活动。

Before using the application on a shared or public computer, remember to reset event data after the event.

---

## Browser Support / 浏览器支持

Recommended:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

For the best live-event experience, use an up-to-date desktop browser.

---

## License

This project is intended for event and internal business use.

Check the repository license before redistribution or modification.
