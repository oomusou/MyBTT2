# MyBTT2 Preset for BetterTouchTool

***Sam Xiao, May.02, 2023***

## Overview

Touch Bar 是 MacBook 很偉大的發明，但也是被誤解最深的發明，隨著 M1 Macbook Pro 14" 改模具後，Touch Bar 已經被移除，到目前為止剩下 M2 MacBook Pro 13" 系列仍保有 Touch Bar，MyBTT2 為我所整理的 BetterTouchTool 的 preset。

## Version

macOS Ventura
BetterTouchTool 4.068
MyBTT2 1.0
2018 MacBook Pro 15"
2020 MacBook Pro 13"
2022 M2 MacBook Pro 13"

## Touch Bar

觸控一直是最直覺的操作方式，但 MacBook 要如何支援觸控呢？最簡單方式當然是直接在螢幕支援觸控，但由於 MacBook 的主力操作方式仍在鍵盤與觸控板，不斷地移動雙手去觸控螢幕並沒有效率，但若將觸控改放在鍵盤上方就方便多了。

那原本 `F1` ~ `F12` 呢？

事實上 macOS 的 app 的熱鍵除了 Adobe 系列外幾乎不使用 `F1` ~ `F12`，因此鍵盤上放著 `F1` ~ `F12` 不用也是可惜，至少在我的 workflow 都用不到 `F1` ~ `F12`，因此我在 M2 MacBook Air 2022 還特別使用 Karabiner 將 `F1` ~ `F12` 客製化成 app switcher，可見 `F1` ~ `F12` 的位置在 MacBook 上的確可以改放其他裝置增進使用效率。

## Philosophy

既然 `F1` ~ `F12` 的空間是可以拿來利用，那要做什麼呢？Touch Bar 的理念就是結合觸控與第二螢幕概念，讓你不僅可以觸控，app 還可以依照需求自行改變 Touch Bar 功能，這原本是個很棒的概念，但自從 2016 年 Touch Bar 問世到現在 7 年來，能真正發揮 Touch Bar 的 app 並不多，大概也只有 Apple 本家的 Safari、Final Cut Pro、Logic Pro，其他 app 幾乎看不到善用 Touch Bar，這也導致大部分用戶覺得 Touch Bar 可有可無，甚至指定不想買 Touch Bar 機種。

## Feature

![touchbar001](images/touchbar001.png)

真正能發揮 Touch Bar 威力的其實是 BetterTouchTool，他提供了各種 widget 客製化，以上為我所客製化的 Touch Bar。

* **Now Playing Widget**：可以顯示目前 Spotify 與 YouTube 所播放的 `title`，也可對 Spotify 與 YouTube 加以 `play/pause`
* **Dock Widget**：Touch Bar 最好用的方式就是用來當 app switcher，可自行將常用的 app 放在 Touch Bar 上直接啟動與切換，依序為：
  * **Finder**：macOS 內建的檔案總管
  * **Telegram** / **ChatGPT**：SNS 兼 ChatGPT client
  * **Safari**：macOS 內建的瀏覽器，主要用來看 YouTube 與查資料
  * **ImageOptim**：將 jpg/png 加以壓縮
  * **iTerm2**：CLI terminal
  * **Visual Studio Code**：JavaScript Playground
  * **Sublime Text**：Markdown 編輯器
  * **ForkLift**：取代 Finder 的檔案總管
  * **Typora**：Markdown 編輯器
  * **Moji辞書**：日華字典
  * **WebStorm**：JavaScript IDE
  * **Gitfox**：Git client
  * **Spotify**：聽音樂
  * **Reeder**：RSS Reader
  * **Chrome**：用來測試開發結果的瀏覽器
  * **Firefox**：點燈坊主力瀏覽器
* **Capture Text**：快速呼叫 `TextSniper` 對 `YouTube` 、`Moji 辞書` 或任意 app 內的文字加以 capture，這對學習日文特別方便
* **Capture Screen**：呼叫 `CleanShot X` 對整個畫面加以 capture
* **Mute**：快速切換 Mute / Unmute，這在公開場合尤其方便 

* **Display Sleep**：快速關閉螢幕顯示加以省電，也是每天必用功能

* **Two Finger Swipe Left**：兩指直接向左滑聲音變小

* **Two Finger Swipe Right**：兩指直接向右滑聲音變大

![touchbar004](images/touchbar002.png)

按下 `⌃` 才會出現的 Touch Bar，專門用來控制各種設定：

* **Battery Widget**：顯示目前電池的各種資訊
* **Brightness Down**：控制亮度減少
* **Brightness Up**：控制亮度增加
* **Emoji**：顯示各種 Emoji
* **Keyboard Light Down**：控制鍵盤亮度減少
* **Keyboard Light Up**：控制鍵盤亮度增加
* **Date / Time Widget**：顯示目前日期時間

## Conclusion

* Touch Bar 其實非常好用，只可惜大部分人依賴 `F1` ~ `F12`，且又沒對其客製化，因此沒有炸出 Touch Bar 潛力，本人原本是入手 M2 MacBook Air 2022 13"，但因為 Touch Bar 實在太好用了，因此又再入手 M2 MacBook Pro 2022 13"
* 在 MacBook Pro 配合 BetterTouchTool 能將 16 個最常用的 app 放在 Touch Bar 上；但 MacBook Air 配合 Karabiner 最多也只能將 12 個最常用的 app 放在 `F1` ~ `F12` 上
