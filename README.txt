小小夢魔：星光存錢冒險 — Godot Web build

本機預覽（Windows）：
1. 在此資料夾開啟 PowerShell。
2. 執行：python -m http.server 8000
   若系統找不到 python，可改用本機 Blender 附帶的 Python：
   C:\blender\5.3\python\bin\python.exe -m http.server 8000 --bind 127.0.0.1
3. 在瀏覽器前往：http://localhost:8000
4. 按 Ctrl+C 停止本機伺服器。

也可將此資料夾所有內容上傳至支援 HTTPS 的靜態網站主機。請保留檔名和目錄結構。
請勿直接以 file:// 開啟 index.html；Godot WebAssembly 需要透過網頁伺服器載入。

Godot 4.7.2，WebGL 2 相容渲染，單執行緒版本。
網頁包約 50 MB，首次載入時間會依網路速度而異。
此包尚未部署到公開網站。
