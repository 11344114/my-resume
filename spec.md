# Resume-Style Portfolio Website Spec

## 1. 目標
建立一個可部署到 GitHub Pages 的單頁履歷型 portfolio 網站。網站設計要符合 Apple Liquid Glass 風格，並支援手機與電腦版響應式顯示。

## 2. 技術限制
- 單一 `index.html` 檔案
- 所有 CSS 需內嵌於 `<style>` 標籤
- 不使用 React / Vue / 或任何打包工具
- 只使用原生 HTML、CSS、少量 JavaScript

## 3. 設計風格
- Apple Liquid Glass / 流體玻璃風格
- 透明素材、柔和毛玻璃、淺色霧面底
- 以白、灰、淡藍、淡紫做為主色基調
- 使用流線型圓角卡片與模糊背景
- 字體保留簡潔大方、階層清晰，搭配適合履歷的現代質感

## 4. 導覽與資訊架構
### 固定元素
- 頂部浮動 TOC 導覽列
  - 快速跳轉到每個區塊
  - 透明/磨砂背景
  - 於捲動時保持可見

### 八大區塊（依序）
1. Hero
   - 頭像
   - 名字
   - 一句話定位
   - 求職方向 pills
2. About 關於我
   - 2-3 段自我介紹
   - 求職方向 / 所在地 / 語言
3. Skills 核心技能
   - 分成多組技能分類
   - 每組採用 tag 雲呈現
4. Education 學歷
   - timeline 樣式
5. Experience 經歷
   - timeline 樣式
   - 含數字化成果呈現
6. Awards 競賽獎項
   - 卡片 grid
   - 含獎項 emoji badge
7. Projects 作品集
   - 卡片 grid
8. Contact 聯絡
   - 4 顆按鈕：Email / GitHub / LinkedIn / IG

## 5. 內容與 UX 要點
- 手機版首頁先呈現 Hero，再依序顯示各區塊
- 內容卡片要有明顯分隔與視覺層次
- Timeline 須清楚標示年份、職稱、內容
- Experience 需強調成果數字、專案影響
- Awards 卡片應該有 emoji badge，增加視覺亮點
- Contact 區塊按鈕需顯示圖示與文字

## 6. 互動與動畫
- 導覽列點擊平滑捲動
- 卡片與按鈕可加入輕微 hover 動畫
- hero 區塊或背景可用柔和漸層與透明浮層

## 7. 範例內容（假資料）
- 名字：王小明
- 學校：中原大學資管系
- 求職目標：AI 工程師
- 公司類型：FinTech / 顧問業 / 科技業

## 8. 後續開發流程
1. 等待使用者確認 `spec.md`
2. 依照規格建立 `index.html`
3. 進行手機與桌面版檢查
4. 調整 Apple Liquid Glass 細節

---

> 註：此規格為初版設計，內容可依使用者需求調整。若你確認無誤，我會直接開始建立 `index.html`。