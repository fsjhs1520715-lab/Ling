# ⚡ CyberType 疾速打字界 (Bilingual Cyberpunk Typing Platform)

![CyberType Banner](https://img.shields.org/badge/CyberType-%E7%96%BE%E9%80%9F%E6%89%93%E5%AD%97%E7%95%8C-ec4899?style=for-the-badge&logo=gamepad)
![Language](https://img.shields.org/badge/Language-HTML5%20%7C%20TailwindCSS%20%7C%20JavaScript-06b6d4?style=for-the-badge)
![License](https://img.shields.org/badge/License-MIT-8b5cf6?style=for-the-badge)
![Status](https://img.shields.org/badge/Status-Completed-10b981?style=for-the-badge)

> 🎮 **「讓每一次鍵盤敲擊，都成為一場繽紛熱血的賽博冒險！」**
> 
> **CyberType 疾速打字界** 是一款結合 **二次元可愛 (Cute) × 賽博龐克 (Cool)** 雙重風格的一頁式雙語遊戲化打字學習平台。支援 **英文全鍵盤指法特訓** 與 **台灣繁體中文注音符號（ㄅㄆㄇㄈ）盲打**，並融入 RPG Boss 討伐戰、Arcade 街機隕石落塊與自訂程式碼特訓！

---

## 📖 專案目錄
- [專案簡介 (About)](#-專案簡介-about)
- [開發緣由與動機 (Motivation)](#-開發緣由與動機-motivation)
- [核心遊戲特色 (Key Features)](#-核心遊戲特色-key-features)
- [研發歷程 (Development Timeline)](#-研發歷程-development-timeline)
- [遊戲模式介紹 (Game Modes)](#-遊戲模式介紹-game-modes)
- [技術架構與特點 (Technical Stack)](#-技術架構與特點-technical-stack)
- [快速開始 (Quick Start)](#-快速開始-quick-start)

---

## 💡 專案簡介 (About)

在數位化時代，高效的打字能力與標準盲打指法是程式開發、文字創作與日常溝通的核心基礎。然而傳統的打字練習工具往往枯燥乏味，難以維持學習者的長期動力。

**CyberType 疾速打字界** 旨在翻轉傳統教學體驗：
* 🎨 **可愛與帥氣交織**：結合圓潤繽紛的馬卡龍視覺元素與冷艷帥氣的賽博龐克 Console 介面。
* 🔤 **雙語盲打支援**：獨創英文字母與注音符號對映演算法，幫助使用者掌握正確盲打指法。
* ⚔️ **遊戲化沉浸體驗**：導入實時 WPM/ACC 數據計算、Combo 連擊爆擊、Boss 討伐血條與 Suno AI 原創主題曲。

---

## 🎯 開發緣由與動機 (Motivation)

### 1. 解決繁體中文盲打練習資源匱乏
現有許多優質打字平台僅支援英文，缺乏專為繁體中文注音符號（ㄅㄆㄇㄈ）打造且介面現代化的盲打訓練工具。

### 2. 突破傳統練習的乏味感
透過「遊戲化機制（Gamification）」，將重複的指法訓練轉化為打怪討伐 Boss、街機防禦與經驗升級系統，提升自主學習的樂趣與成就感。

### 3. 一頁式整合與無縫跨平台體驗
打造無需下載、開啟瀏覽器即可順暢遊玩與檢視開發成果的一頁式 Web 應用程式，並整合音樂展示與歷史歷程。

---

## ✨ 核心遊戲特色 (Key Features)

### 1. 🔤 雙語盲打與即時指法輔助 (Bilingual Assist)
* **英文模式**：從基準鍵（F, J, A-L）延伸至上排與下排鍵盤特訓。
* **注音模式**：將實體鍵盤與注音符號精準對應，提供即時手型提示（例如：提示用「左手食指」敲擊鍵盤）。

### 2. 👾 RPG Boss 討伐戰 (Boss Battle)
* 進入 Boss 關卡時，畫面將出現數位破壞者血條。
* 每一次正確的擊鍵都會對 Boss 造成傷害，維持 High Combo 更可觸發高額爆擊傷害！

### 3. ☄️ Arcade 街機隕石落塊模式 (Arcade Defense)
* 字母從天而降！使用者需要在字塊觸碰下方危險警戒線之前，迅速輸入對應鍵盤予以擊毀，考驗瞬間反應力。

### 4. 💻 程式碼與自訂文章工作坊 (Code Workshop)
* 內建 JavaScript、Python、HTML 常用語法範例。
* 支援自由貼上任何英文或中文練習文本，隨時生成專屬特訓關卡。

### 5. 🎵 Suno AI 原創概念主題曲《指尖的光芒》
* 專屬創作之暖心抒情搖滾主題曲，整合 Suno AI 官方線上收聽與音樂歌詞介紹。

---

## 🚀 研發歷程 (Development Timeline)

```
[階段一：美學與定位] ➔ [階段二：雙語架構與演算法] ➔ [階段三：主題曲與遊戲化] ➔ [階段四：整合與發布]
```

- **Phase 1: 視覺風格定位 (Aesthetics & Conceptualization)**
  - 確立「可愛 Q 版 (Cute)」與「賽博龐克 (Cool Cyberpunk)」雙重美學調性。
  - 設計高對比、清爽明亮且兼具質感調性的卡片式 UI/UX。

- **Phase 2: 核心引擎與雙語對映 (Core Typing Engine)**
  - 開發純 JavaScript 鍵盤事件監聽器（Keyboard Event Engine）。
  - 建立繁體中文注音符號 (Zhuyin) 與 QWERTY 實體按鍵的映射關聯矩陣。

- **Phase 3: 遊戲化與多媒體融合 (Gamification & AI Integration)**
  - 導入 Web Audio API 實時音效合成器（打擊音效、錯誤警報與勝利樂章）。
  - 使用 Suno AI 製作專屬二次元搖滾主題曲《指尖的光芒》。
  - 開發 Boss HP 計算、Combo Fever Overdrive 與 Arcade 隕石降落物理循環。

- **Phase 4: 響應式優化與發布 (Responsive & Showcase Release)**
  - 使用 TailwindCSS 進行全平台響應式版面佈局（Responsive Layout）。
  - 整合專案開發歷程、遊戲平台與試玩展示區塊於一頁式網頁中。

---

## 🎮 遊戲模式介紹 (Game Modes)

| 模式名稱 | 說明 | 適合對象 |
| :--- | :--- | :--- |
| **關卡地圖 (Stage Map)** | 循序漸進解鎖的主線關卡，包含基礎指法與階段性 Boss | 打字新手與進階練習者 |
| **Arcade 街機隕石** | 動態字母掉落防禦機制，強調即時反應速度 | 追求刺激與眼手協調者 |
| **程式碼特訓 (Code Mode)** | 提供 JS/Python/HTML 語法與自訂文章練打 | 程式開發者與自由練習者 |

---

## 🛠️ 技術架構與特點 (Technical Stack)

- **Frontend Core**: HTML5 / JavaScript (ES6+)
- **Styling**: Tailwind CSS / Google Fonts (Inter, Noto Sans TC, JetBrains Mono, Fredoka)
- **Icons**: FontAwesome 6.4
- **Audio Engine**: Web Audio API (Procedural Sound Synthesis) & HTML5 Audio
- **Graphics & FX**: HTML5 Canvas (Particle System)

---

## ⚡ 快速開始 (Quick Start)

本專案為純前端一頁式網頁應用，**無需安裝任何建置工具或後端環境**：

1. **複製本專案 (Clone Repository)**
   ```bash
   git clone https://github.com/your-username/CyberType.git
   ```

2. **開啟網頁 (Open File)**
   直接雙擊 `index.html` 檔案或利用瀏覽器開啟即可立即體驗！

---

## 📄 授權條款 (License)

本專案採用 **MIT License** 授權條款。詳情請參閱 `LICENSE` 檔案。

---

<p center align="center">
  <b>CyberType 疾速打字界</b> — 讓打字成為指尖上的藝術！ ✨
</p>
# Ling
