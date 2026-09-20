員工打卡 PWA

這是一個完整的 Progressive Web App（PWA）版本。

內容：
- 07:30 上班
- 12:00–13:00 午休
- 17:00 正常下班
- 18:30 起算加班
- 時薪 200 元
- 每日正常薪資 1,700 元
- 加班費：時薪 × 2 × 加班分鐘 ÷ 60
- 月曆、紀錄修改、月統計、設定
- 資料保存在手機瀏覽器 localStorage
- Service Worker 支援離線開啟（首次在線開啟後）

安裝到手機桌面：
1. 必須把整個資料夾放到 HTTPS 網站空間（例如 GitHub Pages、Cloudflare Pages、Netlify 等）。
2. 用 Chrome 開啟網站。
3. Chrome 選單 →「新增至主畫面」或「安裝應用程式」。
4. 安裝後會以獨立 App 視窗開啟。

注意：直接從手機的 content:// 或 file:// 開啟 HTML，通常不能完整安裝 PWA，也無法正常註冊 Service Worker。
