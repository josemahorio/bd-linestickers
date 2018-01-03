同[中文解說](README_tw.md)
此為簡易的安裝流程

# 前言
基於原版的[Discord](https://discordapp.com)上安裝[BetterDiscord](https://betterdiscord.net/)
讓你的Discord有更多的功能，例如：修改布局、修改主題、增加插件功能等

本篇讓你的Discord可以使用LINE的貼圖，且不需要購買任何貼圖
*※ 目前沒有辦法使用有動畫的貼圖*

# 安裝插件流程

1. 安裝原版[Discord](https://discordapp.com)

2. 安裝[BetterDiscord](https://betterdiscord.net/)

3. 下載可以使用Line貼圖的插件[`lineemotes.plugin.js`](https://raw.githubusercontent.com/awaken1ng/bd-linestickers/master/dist/lineemotes.plugin.js)(按`右鍵` -> `另存連結為...`) 

4. 將第3步下載的檔案複製/移動到BetterDiscord管理插件的資料夾中
  * 位置類似於`C:\Users\<user>\AppData\Roaming\BetterDiscord\plugins`或參考下圖如何開啟管理插件的資料夾
  <img src="https://i.imgur.com/c1k56RE.png" width="600" />

5. 在列表中，勾選以啟動Line Stickers插件，如下圖
<img src="https://i.imgur.com/TKIcJHa.png" width="600" />

6. 進入Line Stickers插件設定，勾選隱藏貼圖URL，如下圖
<img src="https://i.imgur.com/Ce3KjZD.png" width="600" />
<img src="https://i.imgur.com/myUNa9Q.png" width="600" />

7. 完全關閉Discord，再重新啟動Discord

8. Discord的表情選單已經多出LINE的分頁，如下圖
<img src="https://i.imgur.com/Tww1hOh.png" width="600" />

# 新增貼圖流程

1. 使用[Chrome瀏覽器](https://www.google.com.tw/chrome/browser/desktop/index.html)或是[FireFox瀏覽器](https://www.mozilla.org/zh-TW/firefox/new/)

2. 安裝[Chrome擴充元件-Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)或是[FireFox擴充元件-Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
<img src="https://i.imgur.com/i44ywia.png" width="700" />

3. 前往安裝https://greasyfork.org/en/scripts/23630-line-append-string
<img src="https://i.imgur.com/q8lOMMe.png" width="700" />
<img src="https://i.imgur.com/rwFnbID.png" width="700" />

4. 前往Line貼圖商城，搜尋想要再Discord上使用的Line貼圖(請注意!!有動畫的貼圖會無法使用)

5. 在Line貼圖商城中會看到`Title`與`First sticker ID`與`Sticker count`
<img src="https://i.imgur.com/lpwWiNw.png" width="700" />

6. 開啟Discord，聊天室右下方的表情選單，點擊`+`，將第5步的`Title`與`First sticker ID`與`Sticker count`
填入對應的欄位中，再按下`Add`，即可新增完成
<img src="https://i.imgur.com/pgZ8lpN.png" width="300" />

# 刪除貼圖流程

1. 在Discord表情選單中，將滑鼠移動至貼圖名稱的右方

2. 點擊`X`，再點擊`YES`就可以刪除
<img src="https://i.imgur.com/PbSFSQp.png" width="600" />
