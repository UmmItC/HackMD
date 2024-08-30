# 你是誰?

我是一位 GNU/Linux 用戶，也是一位 FOSS 用戶愛好者

我幾乎完全不再使用 Closed-Source 軟體，除了社交平台之外，我決定所有東西都只使用開源的軟體。

## 什麼是 FOSS?

FOSS 的全名是 Free and Open-Source Software。

## 文章目的

這篇文章目的是在幫助大家更快了解有哪些好用的 FOSS 軟體，讓你可以尋找取代品，向 Closed-Source 軟體說再見。

:::info
:information_source: 不定期更新 XD
:::

本列表中的軟體大多數都是由 GitLab、GitHub、Codeberg、Gitea 和 F-Droid 的開源平台中找出的。

F-Droid 提供了很多優秀的開源軟體，你也可以使用額外的 Repository 來加入其他你喜愛的軟體。

在此也不會依賴 Google Play 下載軟體。

## 不要用什麼

拒絕使用 IOS、macOS（OSX）和 Windows。
要實現更理想的環境，建議使用 Android、GNU/Linux 或 Linux 系統。

簡單來說：

- 手機選擇 Google Pixel（並進行 De-google 系統操作）
- 電腦選擇 GNU/Linux（任選一個發行版）
- 電腦硬件選擇 AMD 或 Intel
- 筆記型電腦選擇 Framework Laptop

# Android 用家

首先，下載一個客戶端吧，沒有它會很麻煩。F-Droid 提供了很多不錯的開源軟體，請先下載其中一個客戶端就好 :)

有很多不同的 F-Droid 客戶端可供下載，而官方的就是叫 F-Droid，其他的還有：

- F-Droid
- Droid-ify
- Neo Store

這三款客戶端功能基本相同，你可以通過它們來下載 F-Droid 的軟體。

## F-Droid 客戶端選擇

上面提到的三個 Client 中，我個人推介使用 Droid-ify。它非常輕量，功能簡單明瞭，對我來說完全足夠。

另外，F-Droid 的介面有點舊，而 Neo Store 自從去年 UI 大改版後，程式變得很慢，經常卡頓。所以呢，我不建議你使用 Neo Store。

總結來說，建議使用 Droid-ify。

直接去 F-Droid 官網下載 APK，然後用這個 Client 來下載其他軟體：

https://f-droid.org/en/packages/com.looker.droidify/

### 來下載啦

好了，基本上從日常到進階的軟體都可以在這裡找到！我現在會慢慢跟你介紹更多。


## 電郵保護

什麼是電郵保護？大家可能一直在使用同一個真實的 Email 地址，其實你應該把你的 Email 轉成一個用來 Forward 的地址。真實的地址不應該公開，即使被公開了，你也能在控制下直接刪除你的 alias，這樣就不會有真實 email 被洩漏的風險了。

### SimpleLogin (Email Protect)

SimpleLogin 是一個電子郵件轉發服務，它能將你的所有電子郵件包裝起來。簡單來說，就是 Email Forwarding。你無需使用真實的電郵地址來收發郵件，防止暴露真實的電郵地址。

### Addy (Email Protect)

前名為 Anonaddy, 同樣用於保護你的電子郵件, 也是一個電子郵件轉發服務。現在改名為 Addy.io

## 電郵服務

在電郵服務方面，基本上沒有一個是完全開源的。即使像 Proton 這樣的服務，實際上也只開放了客戶端的部分，後端的代碼並未公開哦！

### Protonmail

加密電子郵件。不是完全開放源碼，只有客戶端的部分公開了。

### Tuta

曾經叫做 Tutaota，最近幾年經歷了不少變化。現在改名為 tuta

是一個加密電子郵件服務，提供類似的加密電郵服務。同樣地，它也不是完全開源的，只有客戶端的部分公開了。

## Browser

平常上網的東西超級重要，下面幾個推薦的瀏覽器可以考慮使用。

### Librewolf (沒有電話版)

首先，必須提到這個，Librewolf 是 Firefox 的定制版本。它去除了 Firefox 本來的一些 Tracker，並內建了 uBlock Origin。Fingerprint 等不同的隱私問題都已經幫你解決好了。

不同於 Firefox，Librewolf 的特點就是幾乎沒有任何 Tracker，Librewolf 的開發者也說了會盡量去除所有不必要的垃圾。

雖然如此，Librewolf 用起上來可能會令你有時侯覺得不方便，比如時間方面，因為 Fingerprint 已經被處理過，Librewolf 的時間不會顯示你電腦的時間，雖然你可以可以手動關閉這選項啦 :)

另外，User-Agent 也被修改了，所以會被當成其他瀏覽器。
從隱私的角度來看，這絕對是首選！（你看我寫了那麼多字介紹這個就知道啦 XD）

### Firefox

如上所述，雖然不太推薦你使用 Firefox，但對於普通用戶來說，它其實已經很夠用了。如果你追求徹底的 non-tracking，那麼還是使用 Librewolf 吧。

Again, Firefox 真的很多垃圾連線請求, 想知道的話可以直接載個 Mitmproxy, 設定再放 `localhost:8080` 了解。

### Mull（只有手機版）

簡單來說，Mull 基本上是最接近 Librewolf 保護程度的手機版，也是 Firefox 的定制版本，去除了 Firefox 原本的一些 Tracker。

## Google Play 客戶端

好吧，你可能真的想下載一些 Google Play 上的程式。在這裡有一個方法可以讓你不使用 Google Play 的同時，仍然下載 Google Play 的 apps。

### Aurora Store

Aurora Store 是一個很好的解決方案，它可以讓你在沒有 Google 帳號的情況下下載 Google Play 上的應用。這樣你就可以避開 Google Play，但仍然能夠安裝你需要的應用程式。

## Proton

Proton，這個可以說是 Google 的加密安全版。但要注意，它並不是全部開源的，後端代碼沒有公開，只有客戶端的源代碼是公開的。

真要說的話，這是最接近 Google 那些軟體的替代品了，雖然只有部分工具上架了 F-Droid ...

- **Proton Mail**：加密電子郵件。
- **Proton Drive**：文件和照片存儲。
- **Proton Pass**：密碼管理器。
- **Proton Calendar**：日曆。
- **Proton Wallet**：錢包。

## TOTP

在日常使用中，兩步驟驗證非常重要。選擇開源加密的 TOTP 方案會更可靠。

### Ente Auth

這是目前唯一一個地球上提供線上加密服務的 TOTP 解決方案。
它不僅提供加密功能，還支援即時同步。

### Aegis

如果你需要離線使用，Aegis 是不錯的選擇。
它支援密碼保護，只有在輸入正確的密碼後才能解鎖你的 vault。

如果你想要更輕鬆方便的選擇，可以用 Ente Auth。
如果你更偏好離線使用，那麼可以用 Aegis。

## Google Photos

Google Photos 沒有端到端加密（e2ee），所以完全不推介使用。以下是一些可以取代 Google Photos 的選擇。

### Ente Photos

Ente Photos 提供端到端加密，界面美觀且功能強大，是首選。

不過，它的價格可能會讓你猶豫 ... 畢竟，習慣了便宜的 Google 服務，再看到這個價格可能會覺得有點貴。

### Stingle Photos

Stingle Photos 的界面稍微有點過時，比較下的話 Ente Photos 會更直觀和美，但它同樣提供端到端加密。價格方面也不算便宜。如果必須在兩者之間選擇，我會推薦 Ente Photos。

Stingle Photos 可以當作備用選擇，但如果追求更好的使用體驗和功能，還是 Ente Photos 更合適。

## Android Custom ROM

如果你想徹底「De-google」，最好的選擇就是一部 Google Pixel。

是的，你實際上是買了 Google 的手機，再進行「De-google」的操作，感覺有點搞笑? XD，但這確實是最理想的做法 XD

Google Pixel 擁有強大的硬件安全性，然後再安裝其他操作系統，實現更高的保護。

### GrapheneOS

GrapheneOS 是我的首選，提供超高的安全性和強大的保護。它內建自動重新啟動功能，並且在不使用 Wi-Fi 的時候會自動關閉，進一步增強了安全性。

結合 Google Pixel 的硬件安全性和 GrapheneOS 的系統保護，這種搭配是最理想的選擇。

:::success
:warning: GrapheneOS 只支援 Google Pixel 裝置。
:::

### LineageOS

LineageOS 支援 Google Pixel，安裝它也是不錯的選擇。

它更適合用來翻新舊的手機，同樣也是「De-google」的一個選項。不過，如果在 GrapheneOS 和 LineageOS 之間做選擇，我會推薦 GrapheneOS。

:::success
:information_source: LineageOS 支援更多裝置，但大多數是比較舊的型號。
:::

## 社交平台

我希望越來越多人能夠轉向開源的社交平台，而不是使用 Meta 的 Facebook、Instagram 等。

畢竟，如果大家都不使用這些開源平台，那麼社交的樂趣也會大打折扣，單打獨鬥的社交平台實在有點無趣 :(

### Mastodon

Mastodon 是一個去中心化的社交媒體平台，類似於 Twitter 或 Threads，但它不依賴於單一伺服器。用戶可以在不同的伺服器（稱為實例）上註冊，這些伺服器彼此之間可以互通，形成一個聯邦式的社交網絡。這意味著你可以自由選擇加入符合你興趣和價值觀的實例，同時與其他實例的用戶進行互動。

### Pixelfed

Pixelfed 是一個去中心化的社交分享平台，類似於 Instagram。也是一個聯邦式的社交網絡。
提供一個開放的環境，讓用戶能夠安全地分享圖片和影片。Pixelfed 允許用戶在不同的實例上創建帳號，這些實例之間可以互通。

### Lemmy

Lemmy 是一個去中心化的討論和社群平台，類似於 Reddit。它使用聯邦化的模式，讓用戶可以在不同的實例上參與討論，這些實例之間可以互相連接。

# 還沒寫完

實在太多了, 有興趣直接查名稱看看什麼是什麼就好 :D

... More coming

Amaze
Amaze Utilties
App Manager
Apps -  Graphene
Auditor Graphene
Aurora Store
Auth - Ente
Aves Libre
Binary Eye
Calculator - Graphene
Camera - Graphene
Coffee
DroidFS
DuckDuckGo
Element
Joplin
KeePassDX
LibreTube
LocalSend
Mastodon
MEGA
mpv
Mull
Mullvad
NewPipe
NextCloud
Notesnook
Odysee
PCAPdroid
PDF Viewer - Graphene
Permission Pilot
Quillpad
Safe Notes
Scrambled Exif
SimpleX
Tracker Control
Termux
UntrackMe
URL Cleaner
Vanadium
ViMusic
RiMusic
VLC
Wire
Xtra
CuteCalc
File Manager
microG
Molly
Muzei
Revanced
YTDLnis
