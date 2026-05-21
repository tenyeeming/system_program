# 系統程式教學網站

> 國立暨南國際大學 資訊管理學系 大二下  
> 課程：系統程式 System Programming  
> 教授：江美玲（Mei-Ling Chiang）  
> 教科書：Beck（SIC / SIC-XE 架構）

---

## 網站結構

| 檔案 | 主題 | 說明 |
|------|------|------|
| `index.html` | 課程目錄 | 8 張課程卡片（CSS Grid 排版） |
| `style.css` | 共用樣式 | CSS 變數、SVG 圖解容器、測驗元件、課堂練習樣式 |
| `lesson1.html` | 數值系統 | 進位轉換、2's Complement、IEEE 754 |
| `lesson2.html` | SIC 機器架構 | 5 個暫存器、24-bit 指令、Fetch-Decode-Execute |
| `lesson3.html` | SIC/XE 架構 | 9 暫存器、4 種指令格式、nixbpe 旗標 |
| `lesson4.html` | 組合語言程式設計 | 偽指令、COPY 程式範例 |
| `lesson5.html` | Two-Pass 組譯器 | OPTAB / SYMTAB / LOCCTR、H-T-E records |
| `lesson6.html` | One-Pass & Multi-Pass | Forward Reference 問題、EQU 限制 |
| `lesson7.html` | SIC/XE 定址模式 | PC-relative、Base-relative、Immediate、Indirect、Format 2/4、完整 SIC/XE 範例 |
| `lesson8.html` | 程式重定位 | Relocatable vs Absolute、M record、總複習表 |

---

## 網站特色

- 每課均有 **inline SVG 圖解**（視覺化暫存器、指令格式、演算法流程）
- 彩色提示框：`info`（藍）/ `warning`（橘）/ `tip`（綠）
- **課堂練習**（綠色區塊）：整合 10 張課堂作業手寫題，含可折疊解答
- 上下課導覽按鈕 + 頂部快速跳轉 nav bar

---

## 課堂練習涵蓋範圍

| 課次 | 練習題內容 |
|------|-----------|
| lesson1 | 進位轉換（38、388、38.75）、2's Complement 快速法、記憶體位址計算 |
| lesson2 | SIC Indexed Addressing 手動追蹤（Memory Table）|
| lesson3 | if-else 條件式翻譯成 SIC / SIC-XE 組合語言 |
| lesson4 | ALPHA=BETA×GAMMA+8、char 陣列迴圈、int 陣列迴圈 |
| lesson5 | SUM 程式完整 Loc+Object Code 表、TEST 程式 SYMTAB、T record 格式說明 |
| lesson6 | Two-Pass PROG 程式符號表、One-Pass 正向參考處理 |
| lesson7 | 定址模式 Object Code 對照（byte1 高 nibble 速查）、Format 2/4 完整計算、SIC/XE 完整範例（2026/04/30）|
| lesson8 | TEST 程式 Absolute vs Relocatable 版本、M record 辨識練習、Loc+ObjCode+M record 對照表 |

---

## 製作紀錄

| 日期 | 項目 |
|------|------|
| 2026-05-14 | 建立完整 8 堂課 HTML 教學網站（lesson1～lesson8） |
| 2026-05-14 | 修 lesson2.html：SW 暫存器截斷 bug、補術語說明表 |
| 2026-05-19 | 整合 10 張課堂作業手寫圖，轉為課堂練習加入 lesson1～6、8 |
| 2026-05-19 | 新增 style.css 課堂練習綠色樣式（`.practice-section`、`.practice`） |
| 2026-05-19 | 課堂作業圖片全部改為語意化中文檔名 |
| 2026-05-19 | 新手友善修訂：重寫 LDCH/STCH 說明、T record 格式速查框、2's Complement 快速法圖解 |
| 2026-05-21 | lesson5：LOCCTR 節補 Loc+Object Code 對照表（SUM 程式）、Pass 1 Loc 增加量速查表 |
| 2026-05-21 | lesson7：定址模式總覽補格式/Loc+幾 SVG 圖；PC-relative 範例表補 Object Code 欄；Base-relative 答案補 Object Code |
| 2026-05-21 | lesson7：新增 Format 2 暫存器編號表、Format 4 結構圖與計算範例、SIC vs SIC/XE RSUB 差異 |
| 2026-05-21 | lesson7：新增完整 SIC/XE 課堂作業範例（2026/04/30），涵蓋所有格式與定址組合 |
| 2026-05-21 | lesson7：新增各定址模式 Object Code 對照表（byte0/byte1 高 nibble 速查圖） |
| 2026-05-21 | lesson8：M record 教學段補 Loc+Object Code+是否需要 M record 對照表 |

---

## 待辦 / 備注

- [ ] 若有新章節，依序新增 lesson9.html
