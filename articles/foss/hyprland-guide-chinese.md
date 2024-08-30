# Who am I?

我是一個已經使用 GNU/Linux 超過 7 年的用戶。在使用 Hyprland 之前，我主要使用 KDE 和 GNOME。現在，我已經使用 Hyprland 大約一年半了，下面簡單介紹一下如何入門 Hyprland。

:::info
**:bulb: 這篇文章寫得非常隨意，沒有文筆可言 XDD (不定期更新 XDD)**
:::

# Hyprland 新手入門

Hyprland 是一款動態窗口管理器（Dynamic Window Manager），使用起來像拼圖一樣，你需要逐步完成設置，當一切都調整到位後，這種體驗會非常棒 :)

# 聲明

先說明一下，Hyprland 並不適合新手使用。這款窗口管理器主要面向 power user，如果你還不熟悉指令行操作，並習慣使用鼠標操作，那麼強行使用 Hyprland 可能會讓你感到非常痛苦。

Hyprland 僅僅是一個動態窗口管理器（DWM），與 KDE 或 GNOME 的桌面環境不同。

安裝完 Hyprland 後，你需要花很多時間來進行設置，比如配置快捷鍵、選擇電源管理工具、設置狀態欄等等。這些設置需要從頭開始配置。

雖然你可以直接使用別人的 dotfiles 來快速上手，但我寫這篇文章並不是為了推薦你去找現成的 dotfiles >_>

## Status Bar - Waybar

Waybar 是一個高度自定義的狀態欄，你需要寫一些 CSS 和配置文件來設置它的功能。

你可以在狀態欄上顯示很多信息，例如工作區、窗口標題、音量、CPU 使用率、RAM 使用量、網絡流量、今天的日期等等。這些只是冰山一角，你可以根據自己的需求自由配置。

你甚至可以寫一個每天自動運行的系統升級腳本，或者在狀態欄中添加一些圖標（如 Unicode），點擊後自動執行腳本，例如 `sudo pacman -Syu`。直接編寫 Bash 腳本來運行你想要的操作。

如果你之前習慣使用 KDE 或 GNOME，當你長時間使用 WM 或 DWM 後，你會發現 Dock 實際上沒有太大用處。程序通常會放在不同的工作區，Dock 反而顯得多餘。你可以通過切換工作區來獲得更多的空間，這樣更快速、更順暢。

## Power Management - Wlogout

在電源管理方面，你可以使用 Wlogout。這個工具同樣具有高度的自定義性，你可以自己寫 CSS 來設置樣式，也可以使用預設的樣式，效果也很美。配置文件可以根據你的需求進行調整。

## Lock Screen - Hyprlock

對於鎖畫面，你可以使用 Hyprlock。它可以與 Wlogout 配合使用，提供一個自定義的鎖屏界面。Hyprlock 同樣是高度自定義的，你可以更換背景圖片、添加文字、修改字體，甚至顯示當前時間。

## Screen Recording - wf-recorder

錄影方面，你可以使用 wf-recorder。由於我推薦的都是自己動手配置的方案，所以我不會推薦像 OBS 這樣的圖形界面工具了。wf-recorder 是一個基於命令行的錄影工具，適合那些喜歡用命令行進行操作的用戶。

## Notifications & Panel - Swaync, Mako, Dunst

對於通知，你可以使用 Hyprland 提供的 `hyprctl notify`，來配置在特定情況下顯示通知。例如，你可以設置在啟動某個應用程序時顯示通知。這部分完全由你自行定制。除此之外，你還可以考慮使用其他通知工具，如 Mako、Dunst 或 Swaync。

如果你需要更全面的功能，我會推薦使用 Swaync。它不僅提供了通知功能，還有一個面板，讓你可以自定義通知的顯示版面。

你可以用 CSS 和配置文件來完全自定義，打造出類似 Android 或 iOS 的通知界面，完全按照你的需求來設置。

## Terminal - Kitty

在終端方面，我推薦使用 Kitty。這是一款基於 GPU 的終端，比傳統的終端要快得多。它也是高度可自定義的，你可以設置字體、顏色等各種細節，例如終端內鏈接的背景顏色或字體顏色等等。

所有這些都可以通過編輯配置文件來完成，讓你可以根據自己的喜好來調整終端的外觀和功能。

## Application Launcher - Fuzzel, Wofi, Rofi

如果你想要一個簡單的應用啟動器，可以使用 Fuzzel。它非常簡潔，但如果你想要更多自定義選項，可以考慮使用 Wofi 或 Rofi。後者提供了更多的配置和 CSS 自定義功能，讓你可以打造更精美的啟動器。例如，你可以用 Rofi 設計一個 wallpaper picker，利用 ffmpeg 轉換縮圖，然後列出所有檔案。這部分需要你編寫自定義的 Bash 腳本來實現。

## Clipboard - Cliphist, Clipmenu

對於剪貼簿管理，你可以使用 Cliphist 與 dmenu（Clipmenu）來實現，並用 Rofi 作為菜單列表。這部分同樣需要用到 Bash 腳本來完成，讓你能夠有效地管理和使用剪貼簿內容。

## Screenshots - Hyprshot

在截圖方面，你可以使用 Hyprshot。

只需在 `hyprland.conf` 中設置相應的鍵位綁定，就可以輕鬆完成截圖操作。

## Wallpaper Engine - Swww

如果你想要一個功能強大的 Wallpaper picker，可以使用 Swww。它適合喜歡美觀和動畫效果的用戶。

你可以編寫 Bash 腳本來配合 Rofi 創建一個壁紙選擇菜單，這樣就能夠輕鬆地選擇和設置壁紙。若想擁有一個能夠選擇壁紙的工具，你仍然需要自己編寫 Bash 腳本來實現這些功能。
