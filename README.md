*[English](README.en.md)*

# NcCycleSense — 下載

NC 程式的加工週期時間預估。**NC 碼永不上傳**，計算全部在你的電腦上完成。

產品說明與線上版（不用安裝，拖進去就算）：<https://nccyclesense.com>

## 下載

安裝檔在右邊的 **Releases**。最新版：

<https://github.com/ming0393639/NcCycleSense-releases/releases/latest>

| | |
|---|---|
| 系統 | Windows 10 / 11（64 位元） |
| 相依 | WebView2（Windows 10/11 多半已內建） |
| 安裝位置 | `%LOCALAPPDATA%\NcCycleSense\`（不需要管理員權限） |

安裝檔裡有**兩顆執行檔**：`NcCycleSense.exe`（圖形介面）與 `nccs.exe`
（命令列）。兩顆算出來的工時逐位元相同 —— 打包前驗過。

> ⚠️ 安裝檔尚未做程式碼簽章，Windows 會顯示「不明的發行者」。
> 點「其他資訊」→「仍要執行」。

## 舊版都留著，而且會一直留著

**你買的那一版永遠可以用。** 更新期過後發行的版本會降級成免費層執行，
而那時你要能退回你買的那一版 —— 所以這一頁上的每一個版本都不會被移除。

每個版本旁邊的日期就是它的發行日，拿它跟你的更新期比對即可。

## 授權

沒有啟用檔時是**免費層**，引擎完整（五軸、巨集、固定循環、3D 軌跡）。

買了 Pro 之後在 <https://nccyclesense.com/account.html> 下載 `license.nccs`，
用任何方式搬到那台電腦再匯入 —— **驗證完全離線，不需要連網**。
氣隙環境要的正是這一點。

## 這裡沒有原始碼

這個 repo 只放安裝檔。可稽核性的說明（引擎不含任何第三方程式碼、
瀏覽器版可以在開發者工具的網路分頁自行確認沒有上傳）見
<https://nccyclesense.com/legal.html#audit>。
