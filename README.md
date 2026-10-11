# A11y Roasts · 真实产品无障碍找茬

> 每天挑一个真实产品界面，找 3 个无障碍问题 + 修复方案。
> One real product interface a day, 3 accessibility issues + fixes. 中英双语。

攒下来就是作品集 More work 区的一个轻量 case —— "accessibility audit" 是很少 designer 能拿出来的硬货。
Compounded into a lightweight portfolio case for the "More work" section — an "accessibility audit" is hard proof few designers can show.

## 每期固定格式 · Format

- 3 个问题，每节含：现象 What / 用户影响 Impact / WCAG 依据 / 修复方案 Fix
- 附：其他发现 Honorable mentions ＋ 验证通过项 Verified passing
- 🎙️ 面试怎么讲 / How to say it in an interview（一句话）

## 方法 · Method

真机浏览器走查（managed browser）：纯键盘 Tab 全程 → DevTools Accessibility tree 取证（accessible name、heading 层级、图片 alt、表单 label）→ 疑似低对比度记录。不编造问题；审不出 3 个真问题就换产品。
Real-browser audits: full keyboard walkthrough → Accessibility-tree forensics → contrast notes. No invented issues; if a page doesn't yield 3 real ones, switch products.

## 结构 · Structure

- `index.html` — 首页：每天一张卡片（中英切换）
- `roasts/<date>-<slug>/index.html` — 每一期，中英双语

## 本地预览 · Preview locally

```bash
npm install
npm run dev
```

或在 StackBlitz 打开（GitHub 每次 push 后自动同步）：

`stackblitz.com/github/cjwmay/a11y-roasts`
