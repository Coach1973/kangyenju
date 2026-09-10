康燕居 KANG YEN JU — 品牌官網檔案包
===================================

【檔案結構】
kangyenju/
├─ index.html              首頁（單一檔案，樣式與腳本皆內嵌）
├─ wild_nest_story.mp4     野生洞燕採收精華影片（28 秒，無聲）
├─ assets/
│   ├─ cliff_wide.jpg          首屏主視覺（絕壁採燕實拍）
│   ├─ img_dried_nest.jpg      乾燕盞
│   ├─ img_tcm_still.jpg       燉盅與藥材靜物
│   ├─ img_swiftlet_house.jpg  東南亞燕屋
│   ├─ step_cave.jpg           採收四步 ①尋窩
│   ├─ step_scaffold.jpg       採收四步 ②搭架
│   ├─ step_cut.jpg            採收四步 ③割採
│   ├─ step_bowl.jpg           採收四步 ④成盞
│   ├─ video_cover.jpg         影片封面
│   ├─ wild_story_poster.jpg   採收圖解長圖（原尺寸，1200×3375）
│   ├─ wild_story_poster_web.jpg 採收圖解長圖（網頁壓縮版）
│   ├─ hero_cliff_16x9.jpg     備用橫幅（16:9，社群／廣告用）
│   └─ step_hang.jpg           備用素材
└─ README.txt             本說明


【怎麼上線】
1. 把整個 kangyenju 資料夾內容（不含本資料夾本身）上傳到網站根目錄。
2. index.html 必須與 assets/ 資料夾、wild_nest_story.mp4 維持相同的相對位置，
   不要單獨搬移或改名，否則圖片與影片會失效。
3. 直接以瀏覽器開啟 index.html 即可預覽，不需要任何伺服器環境。

適用於：一般虛擬主機、Cloudflare Pages、Netlify、GitHub Pages、
以及任何支援上傳靜態檔案的空間。


【字型說明】
頁面使用 Google Fonts 的「Noto Serif TC」與「Noto Sans TC」，
連線狀態下會自動載入。若需完全離線使用，請自行下載字型檔並改為本機路徑。


【要修改內容時】
- 聯絡資訊：搜尋「中壢門市總部」即可找到門市卡片與頁尾兩處。
- 電話連結：格式為 <a href="tel:0976730778">，改號碼時兩處都要一起改。
- 影片：更換 wild_nest_story.mp4 後，建議一併更換 assets/video_cover.jpg 封面。
- 顏色與字級：集中在 index.html 開頭的 :root 區塊，改一處即全站套用。


【內容合規提醒】
頁尾已附「資訊說明」聲明：本頁中醫相關敘述屬傳統食療觀點介紹，
非醫療效能宣稱。若日後增修文案，請避免使用療效、治癒、預防疾病等字眼，
以符合食品標示相關規範。
