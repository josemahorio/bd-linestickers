_歡迎 [加入Discord伺服器](https://discordapp.com/invite/wCX6K8q) 有任何問題都可以敲我或是 [在Github上回報issue](https://github.com/awaken1ng/bd-linestickers/issues)_

# BetterDiscord LINE 貼圖插件
在BetterDiscord中的表情選單增加額外的Line貼圖分頁
[![](https://camo.githubusercontent.com/6b145ba99071dd660d1ac866cc507e74de704874/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3233313434323233333138343734373534302f3332333539363635363935343137393538352f756e6b6e6f776e2e706e67)](https://github.com/awaken1ng/bd-linestickers#installation)
[![](https://camo.githubusercontent.com/84a146ee8b202df573c4c4303759ea19a8b150ee/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3233313434323233333138343734373534302f3332333539363637393032303431323932382f756e6b6e6f776e2e706e67)](https://github.com/awaken1ng/bd-linestickers#installation)

*※若想要開啟暗色的主題，請到BetterDiscord設定中選取*

## 安裝

* 安裝[BetterDiscord](https://betterdiscord.net/)
* 安裝插件
	* 開啟資料夾`C:\Users\<user>\AppData\Roaming\BetterDiscord\plugins`
  * 將[`lineemotes.plugin.js`](https://raw.githubusercontent.com/awaken1ng/bd-linestickers/master/dist/lineemotes.plugin.js)下載複製到上述資料夾
*  重新啟動Discord (*Ctrl + R 或是 自行重新啟動*)
* 確認插件安裝正確
  * 開啟 `使用者設定` - `BetterDiscord` - `Plugins`你應該可以看到插件在清單當中，將框框打勾以啟動插件
* 打開表情選單，你應該能看到多出一個Line分頁

## 刪除或重新命名貼圖

滑鼠移動到標題右方，可以看到兩個圖示
![](https://camo.githubusercontent.com/1cf0df3ea7383c2ab2798705d5f29b18eb841ab5/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3330363032303830333534363434373837322f3334353934333731343336353137373835362f756e6b6e6f776e2e706e67)

### 刪除

點擊`X`符號並確認刪除

![](https://camo.githubusercontent.com/badffdb26d735d0d0807333d5dd3c8e4d60ffebd/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3330363032303830333534363434373837322f3334353934343033343730393334303138312f756e6b6e6f776e2e706e67)

### 重新命名 

點擊`筆`的符號來修改名稱，再按下`Enter`保存修改
*※你也可以直接手動編輯`%appdata%\BetterDiscord\plugins\lineemotes.config.json`檔案，修改完畢後，請確認Discord完全關閉並重新啟動*

## 新增貼圖

### 獲得貼圖

你可以前往[LINE Store](https://store.line.me/home/en)來找喜歡的貼圖

*※ 你不需要購買這些貼圖即可使用*

想要增加貼圖包必須要有：
* 貼圖包的標題名稱
* 貼圖包中第一個貼圖的ID
* 貼圖包內貼圖的總數量

有兩種方法可以新增貼圖:
* 透過表情選單的Line分頁
* 透過Discord控制台

### 透過表情選單的Line分頁

* 按下分頁下方的`+`

  ![](https://camo.githubusercontent.com/c1f110a58855ef1f197fae9f3fc5f17feee2ba79/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3233313434323233333138343734373534302f3332333630313937353139373330323738352f756e6b6e6f776e2e706e67)

* 會顯示下圖中的表格

  ![](https://camo.githubusercontent.com/b679d291fabdb1fc8a6ce36917d68275f31a963c/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3233313434323233333138343734373534302f3332333630323130313939313234333737382f756e6b6e6f776e2e706e67)

* 輸入貼圖標題、貼圖總數量以及貼圖包中第一個貼圖的ID，再按下`Add`按鈕

  ![](https://camo.githubusercontent.com/756765fef0bc6a58ea242015d0bab7481c210e5a/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3233313434323233333138343734373534302f3332333630323332323536313137313435382f756e6b6e6f776e2e706e67)
  
### 透過Discord控制台

* 按下`Ctrl + Shift + I`開啟Discord控制台

* 在控制台中，執行以下指令：``lineemotes.appendPack(`[貼圖標題名稱]`, [貼圖包中第一個貼圖的ID], [貼圖包內貼圖的總數量])``
<br> *※ 舉例 ``lineemotes.appendPack(`Miko sister of fox`, 1133826, 40)``*

### 取得貼圖標題名稱, 貼圖包中第一個貼圖的ID, 貼圖包內貼圖的總數量

#### Grease/Tampermonkey 腳本
[![](https://camo.githubusercontent.com/90e0741670663dbc6e414478d793b5a50ffbb2cb/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3233313434323233333138343734373534302f3331303138363631353934313336353736302f756e6b6e6f776e2e706e67)](https://greasyfork.org/en/scripts/23630)

如果你是使用 [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)或是[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)你可以[下載腳本](https://greasyfork.org/en/scripts/23630)，它會在Line Store頁面中顯示貼圖標題名稱, 貼圖包中第一個貼圖的ID, 貼圖包內貼圖的總數量

#### 控制台中使用Javascript指令
類似於上述的腳本，你可以在你的瀏覽器中的控制台，執行下方的Javascript指令，它也會輸出跟腳本一樣的資訊
*※ 你可以在網頁任意處按`右鍵`來開啟`開發者工具(檢查)`或是按下快捷鍵`Ctrl + Shift + I`來開啟開發者工具*

```
console.log('Title: ' + $('.mdCMN08Ttl').text() + '\nFirst sticker ID: ' + $('.mdCMN09Image').first().css('background-image').slice($('.mdCMN09Image').first().css('background-image').search('/products/') + 10).slice(0, $('.mdCMN09Image').first().css('background-image').slice($('.mdCMN09Image').first().css('background-image').search('/products/') + 10).search('/android/')).slice($('.mdCMN09Image').first().css('background-image').slice($('.mdCMN09Image').first().css('background-image').search('/products/') + 10).slice(0, $('.mdCMN09Image').first().css('background-image').slice($('.mdCMN09Image').first().css('background-image').search('/products/') + 10).search('/android/')).lastIndexOf('/') + 1) + '\nLength: ' + $('.mdCMN09Li').length.toString() + '\nAppend string:\n' + 'lineemotes.appendPack(`' + $('.mdCMN08Ttl').text() + '`, ' + $('.mdCMN09Image').first().css('background-image').slice($('.mdCMN09Image').first().css('background-image').search('/products/') + 10).slice(0, $('.mdCMN09Image').first().css('background-image').slice($('.mdCMN09Image').first().css('background-image').search('/products/') + 10).search('/android/')).slice($('.mdCMN09Image').first().css('background-image').slice($('.mdCMN09Image').first().css('background-image').search('/products/') + 10).slice(0, $('.mdCMN09Image').first().css('background-image').slice($('.mdCMN09Image').first().css('background-image').search('/products/') + 10).search('/android/')).lastIndexOf('/') + 1) + ', ' + $('.mdCMN09Li').length.toString() + ')')
```
#### 手動方式
##### 貼圖包中第一個貼圖的ID
ID可以再貼圖的網址當中找到，可以在貼圖上按`右鍵`->`檢查/檢查元素`找到貼圖的網址

![](https://camo.githubusercontent.com/78635b5611f1cb82378737c741dd3a3c255569e7/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3233313434323233333138343734373534302f3331303139333031353831353739383738362f756e6b6e6f776e2e706e67)

##### 貼圖包內貼圖的總數量
就...數吧 =P

預設的貼圖數量是40個，大部分貼圖包的標準數量都是40個，但是有些貼圖(通常是有動畫的貼圖)除外

## 調整分頁大小

你可以再控制台中輸入下列的指令調整Line分頁的大小：

`lineemotes.menu.setWidth(width)`

`lineemotes.menu.setHeight(height)`

`lineemotes.menu.setSize(width, height)`

*※ 舉例 `lineemotes.menu.setSize(494, 326)`*

## 新增上述方法無法用的貼圖
[![](https://camo.githubusercontent.com/6a6c9d4febc36ae58e9e0f7577aab1756a020f70/68747470733a2f2f696d616765732d312e646973636f72646170702e6e65742f2e654a774e7955734f7779414d414e47376341444d78355130743045456b61674a52746852466c5876586d6235357176756361705637534b64563444743445786a30797730556932364574577a704836777a6e5242456b6c3576306f54427563746f6e50653277556a786f426d556c6a4d793367625a2d453948397a74302d687075726571666e384642434c532e72394b32513273713566664d526b786a6f466175426d7a30663755)](https://store.line.me/stickershop/product/2999/ja)

有些貼圖可能會出現上述的訊息

為了得到貼圖的ID只能透過Line程式使用的API來下載貼圖包，
可以使用下列的範本
`https://dl.stickershop.line.naver.jp/products/0/0/1/<貼圖ID>/android/stickers.zip`

舉例 `https://dl.stickershop.line.naver.jp/products/0/0/1/2999/android/stickers.zip`

*注意! 你可以在貼圖的網址中找到貼圖包的ID*
![](https://camo.githubusercontent.com/fe841f6288a0dd1c28c161494ed36d4a97f6acca/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3233313434323233333138343734373534302f3331303139343039333631333531343737342f756e6b6e6f776e2e706e67)

用你習慣的解壓所程式來解壓，找到貼圖ID最小的即是貼圖包中第一個貼圖ID

*※ 假設貼圖數量是40個，如果解壓縮出來的檔案數量並非83個(40個貼圖，40個縮圖，2個分類圖示，1個貼圖的資訊檔)，那就手動設定適當的貼圖數量*
