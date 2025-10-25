不联网、不上传；可随时导出快照 JSON 备份。  
*No network, no upload; export snapshots as JSON anytime.*

---

## 🏷️ 标签与汇总 / Labeling & Summary
- 点击左栏命中/疑似条目后，在右栏输入“一级/二级”（支持历史下拉），可选“覆盖分钟”。  
  *After selecting an entry, fill L1/L2 (history dropdowns), optional minute override.*
- 汇总默认“去重复 + 每个二级换行显示 + `* 二级：X 分钟`”，日块末尾显示“当日总时间”。  
  *Summary defaults to “unique + L2 per line `* L2: X minutes`”, with “Day total” at the end.*
- 可切换显示“带重复/去重复/两者”。  
  *Switch between with-duplicates / unique / both.*

---

## 📅 日期与星期 / Date & Weekday
仅在**行首**匹配以下格式用于日期分组：  
*Only **line-start** patterns are used for date grouping:*
- `HH:MM, Oct 21, 2025`（英文月份）  
  *`HH:MM, Oct 21, 2025` (English month)*
- `HH:MM, 2025年10月21日`（中文年月日）  
  *`HH:MM, 2025年10月21日` (Chinese date)*

汇总标题显示对应星期（中文或英文，随语言切换）。  
*Summary headers show weekday (CN/EN).*

---

## ⚙️ 关键词自定义 / Keyword Customization
- 标蓝左侧关键字（如 `【学习时间】` / `【工作时间】`）。  
  *Blue-hit left keywords (e.g., `【学习时间】` / `【工作时间】`).*
- 分钟表达式（正则）与后缀（如 “分钟 / minutes”）。  
  *Minute regex & suffix (e.g., “分钟 / minutes”).*
- 标绿普通关键字与“仅未命中标蓝时才标绿”。  
  *Green keywords + “only when not blue-hit”.*

保存即生效，并重新渲染高亮。  
*Saved settings apply immediately and re-render highlights.*

---

## 🕓 版本与历史 / Versions & History
- 手动保存标签快照（最多 5 个）与自动快照（最多 2 个）。  
  *Manual snapshots (up to 5) and auto-saves (up to 2).*
- 在“历史”中可恢复某个版本，或导出 JSON。  
  *Restore from “History” or export as JSON.*

---

## ➕ 追加与删除 / Append & Delete
- **追加粘贴**：将新文本接在旧日志尾部，**标签不丢失**。  
  *Append-paste: concatenates new text to the end **without losing labels**.*
- **删除末行**：预览 + 确认后删除最后 N 行，并自动清理孤儿标签。  
  *Delete tail lines: preview + confirm; prunes orphan labels automatically.*

---

## 🧭 兼容性 / Compatibility
推荐最新 Chrome / Edge / Firefox / Safari；移动端可用，但桌面体验更佳。  
*Latest Chrome/Edge/Firefox/Safari recommended; mobile works, desktop is better.*

---

## ⚠️ 已知限制 / Known Limitations
- 行内日期不参与分组，**只**使用行首时间戳。  
  *Inline dates are ignored; **only** line-start timestamps are used.*
- 如日志格式与示例差异很大，请在“定义关键词”里调整规则。  
  *If your log format differs a lot, adjust rules in “Define Keywords”.*

---

## 🤝 贡献 / Contributing
欢迎提交 Issue / PR，或分享你的规则与范例。  
*Issues/PRs welcome; please share your rules/samples.*

---

## 📜 许可 / License
本项目使用 **MIT License**。你可以自由地使用、修改、再发布，但需保留版权与许可声明，并署名 **Sam Zebrado**。  
*Released under the **MIT License**. You may use/modify/redistribute, but keep the copyright & license notice and credit **Sam Zebrado**.*

---

## 👤 作者 / Authors
作者：**Sam Zebrado**（项目维护） & **GPT-5 Thinking**（协作与实现建议）。  
*Authors: **Sam Zebrado** (maintainer) & **GPT-5 Thinking** (co-design & implementation guidance).*

---

## 🧩 结语：关于“弹幕式记录”的好处 / Closing: Why “danmu-style logging” helps
用一两句“弹幕”即时记录学习工作：它降低开工门槛，形成“开始—记要点—结束—回顾”的节律。  
*Short danmu notes lower activation energy and build a rhythm: start—note—finish—review.*  
把碎片时间沉淀成数据，用标签与汇总看见进步；焦虑更可控，复盘更具体。  
*Turn fragments into data; labels/summaries reveal progress, tame anxiety, and make reviews concrete.*  
长期坚持，你会更了解自己的节奏与注意力分布，工作心态更稳，人生规划更有锚点。  
*Over time you’ll understand your cadence and attention, steady your work attitude, and anchor long-term planning.*
