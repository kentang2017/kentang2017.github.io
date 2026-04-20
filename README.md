# ⭐ 堅占星 Kin Astro — 二十九體系占星排盤平台

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-brightgreen?logo=github)](https://kentang2017.github.io/)
[![Streamlit App](https://img.shields.io/badge/Streamlit-App-ff4b4b?logo=streamlit)](https://kinastro.streamlit.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/kentang2017/kinastro/blob/main/LICENSE)

> 融合全球 **二十九種** 中外古今占星體系的線上排盤平台，支援 AI 智慧分析、中英雙語介面，免費開源。
>
> The online astrology charting platform that unites **29 systems** — Chinese, Western, Asian, Middle-Eastern & Ancient — with AI analysis, bilingual UI, and open-source code.

| 🔮 線上使用 Live App | 📦 原始碼 Source Code | 🌐 所有專案 All Projects |
|:---:|:---:|:---:|
| [kinastro.streamlit.app](https://kinastro.streamlit.app) | [kentang2017/kinastro](https://github.com/kentang2017/kinastro) | [kentang2017.github.io](https://kentang2017.github.io) |

---

## ✨ 特色亮點 Highlights

| 功能 | 說明 |
|------|------|
| 🔮 **二十九體系合一** | 三式、中國、西方、亞洲、中東、古代文明——在同一介面切換，無需來回換工具 |
| 🪐 **精密天文計算** | 採用瑞士星曆表 Swiss Ephemeris (pyswisseph) 進行高精度行星運算 |
| 🤖 **AI 智慧分析** | 整合 Cerebras AI，一鍵生成命盤深度解讀報告 |
| 🌏 **全球化城市支援** | 內建全球主要城市座標，亦支援自訂經緯度 |
| 🌐 **中英雙語介面** | 完整中文與英文雙語支援 |
| 📱 **響應式設計** | 桌面、平板、手機皆可流暢使用 |
| 🔌 **REST API 後端** | FastAPI 提供所有體系的 JSON 計算 API，可獨立部署 |
| 💾 **儲存與匯出** | 支援 TXT、CSV、PDF 三種格式匯出分析結果 |
| 🆓 **開源免費** | MIT 授權，完整原始碼公開 |

---

## 🧭 二十九種占星體系 29 Astrology Systems

### 三式 San Shi (Three Divinations)

| 體系 | 英文名 | 關鍵特色 |
|------|--------|----------|
| 六壬祿命 | Da Liu Ren / Six Ren Destiny | 四課三傳、十二宮、論命分析（身命判斷、女命專論、二十四格、十六局、流年月令） |
| 太乙命法 | Taiyi Life Method | 命宮身宮、陽九百六行限、出身卦、五柱卦象分析 |
| 奇門祿命 | Qimen Destiny Analysis | 六親分析、八門八神九星、格局推斷 |

### 中國 Chinese

| 體系 | 英文名 | 關鍵特色 |
|------|--------|----------|
| 七政四餘 | Chinese Traditional Astrology | 恆星黃道、本命盤、神煞、年限大運、張果星宗（1060 條星宮語句、128 格局）、擇日 |
| 紫微斗數 | Zi Wei Dou Shu | 農曆排盤、十四主星、十二宮位、五行局 |
| 策天飛星紫微斗數 | Ce Tian 18 Flying Stars | 明代古法前身、十八飛星、飛星四化、單宮獨斷 |
| 萬化仙禽 | WanHua XianQin | 二十八宿禽星排盤、吞啗合戰、相胎賦、貴賤格 |
| 十二星次 | Twelve Ci / Jupiter Stations | 木星分野系統、SVG 環形盤視覺化 |
| 達摩一掌經 | Damo One Palm Scripture | 十二宮掌紋、前世今生六道、互動手掌 SVG |

### 西方 Western

| 體系 | 英文名 | 關鍵特色 |
|------|--------|----------|
| 西洋占星 | Western Astrology | 本命盤輪圖、行星過運、太陽回歸、合盤比較、Ptolemy 尊貴、恆星合相、小行星 |
| 希臘占星 | Hellenistic Astrology | Greek Lots、Egyptian Bounds、Annual Profections、Zodiacal Releasing、Valens Synkrasis |
| 卡巴拉占星 | Kabbalah Astrology | 生命之樹、二十二希伯來字母、塔羅大牌對應 |
| 猶太 Mazzalot | Jewish Mazzalot Astrology | 大衛之星盤、十二支派、希伯來字母對應 |
| Astrocartography | Astrocartography / Relocation | AC/MC/IC/DC 搬遷線、Plotly 互動地圖 |

### 亞洲 Asian

| 體系 | 英文名 | 關鍵特色 |
|------|--------|----------|
| 印度占星 Jyotish | Vedic Astrology | 南/北印度盤、Vimshottari 大運、Ashtakavarga、Yogas、BPHS、16 Varga 分盤 |
| 納迪占星 | Nadi Astrology | 三大脈輪、27 星宿、納迪宮分 |
| Jaimini 占星 | Jaimini Astrology | Chara Karaka、Rashi Drishti、Argala、Arudha Pada、Chara Dasha |
| 宿曜道 | Japanese Sukkayodo | 空海大師傳入、二十八宿、六曜 |
| 泰國占星 | Thai Astrology | 泰式方盤、九宮格、พรหมชาติ 命理 |
| 緬甸 Mahabote | Myanmar Astrology | 星期制占星、八方位、行星大運 |
| 祖爾海 | Mongolian Zurkhai | 蒙古傳統、12 生肖、五行擇吉 |
| 巴厘 Wariga | Balinese Wariga Calendar | Wuku 210 天週期、Wewaran 九層週期、Neptu 數值、吉凶判斷 |
| 藏傳時輪金剛 | Tibetan Kalachakra | Mewa 九宮、Parkha 八卦、五力系統 |

### 中東 Middle East

| 體系 | 英文名 | 關鍵特色 |
|------|--------|----------|
| 阿拉伯占星 | Arabic Astrology | 阿拉伯點、Picatrix 星體魔法、太陽知識大全、MS164 手稿 |
| 也門占星 | Yemeni / Rasulid | 28 月宿護符魔法、Anwāʼ 天氣預兆、Firdaria 週期 |

### 古代文明 Ancient Civilizations

| 體系 | 英文名 | 關鍵特色 |
|------|--------|----------|
| 瑪雅占星 | Maya Astrology | Tzolkin 神聖曆、Haab 民用曆、Long Count 長紀年 |
| 阿茲特克占星 | Aztec Astrology | Tonalpohualli 占卜曆、Trecena 13 天週期、守護神祇 |
| 古埃及十度區間 | Egyptian Decans | 36 Decans、塔羅對應、Dendera 輪盤圖 |
| 巴比倫占星 | Babylonian Astrology | MUL.APIN 星表、K.8538 星盤、Enūma Anu Enlil 預兆 |

---

## 🛠️ 技術棧 Tech Stack

| 技術 | 用途 |
|------|------|
| 🐍 Python 3.9+ | 核心語言 |
| 🎈 Streamlit | 前端互動介面 |
| ⚡ FastAPI | REST API 後端 |
| 🪐 Swiss Ephemeris (pyswisseph) | 高精度天文計算 |
| 🤖 Cerebras AI | AI 智慧分析 |
| 📊 Plotly | 互動地圖與圖表 |
| 📄 fpdf2 | PDF 匯出 |

---

## 🚀 快速開始 Quick Start

直接在瀏覽器中使用，無需安裝：

👉 **<https://kinastro.streamlit.app>**

如需本地部署或查看原始碼，請前往：

👉 **<https://github.com/kentang2017/kinastro>**

---

## 📂 本倉庫 About This Repository

本倉庫 (`kentang2017.github.io`) 是 GitHub Pages 站點，包含：

| 檔案 | 說明 |
|------|------|
| [`index.html`](https://kentang2017.github.io/) | 堅占星 Kin Astro 官方介紹頁 |
| [`kentang2017.html`](https://kentang2017.github.io/kentang2017.html) | 所有開源專案總覽 |

---

## 📬 聯絡方式 Contact

| 管道 | 連結 |
|------|------|
| GitHub | [@kentang2017](https://github.com/kentang2017) |
| 微信 WeChat | `gnatnek` |
| 公眾號 | 探究三式 |
| 贊助 Sponsor | [github.com/sponsors/kentang2017](https://github.com/sponsors/kentang2017) |

---

## 📄 授權 License

MIT License — 自由使用、修改與擴展。
