## 第一週主線作業

第一週我們介紹了如何實作關注點分離，小明從好友那邊拿到一份 Todo 工具，但打開一看發現 Todo 工具邏輯有些混亂，並且要新增功能異常困難，請協助小明來修復這份版型。

![](https://i.imgur.com/uin7dNI.png)

- 範例版型(非關注點分離)：https://codepen.io/hsiangfeng/pen/mdVyLmJ
- 官方範例解答：https://codepen.io/hsiangfeng/pen/ExPaLZd
- gh-page：https://hexschool.github.io/js-training-task/index.html
- GitHub：https://github.com/hexschool/js-training-task/tree/master/week1
- 
### 使用者故事

- 用戶可以新增 Todo，新增後移除 input 的項目
- 用戶可以刪除、完成 Todo
- 用戶可以一鍵刪除所有任務

### 任務說明：
- 將範例程式碼改為「關注點分離的形式」

課程任務均有提供完整範例程式碼，如果開發上不是很順利可以參考範例程式碼來撰寫。
使用範例程式碼注意事項：
- **禁止直接使用範例程式碼提交**
- 如欲參考範例程式碼，請避免複製貼上，請自行重新撰寫
- 參考範例程式碼，請在繳交作業時附註：「本作業有參考範例程式碼」
- 參考範例程式碼，請在原始碼內補上註解，讓自己加深學習印象
```js
// 當判斷式接收到 sayYouLoveMe() 回傳 true 的結果時，則會運行接下來的陳述片段
if (sayYouLoveMe()) { console.log('說你愛我') };
```

### 提交難度挑戰：
- LV1：參考範例程式碼，並重新撰寫及補上註解（禁止複製範例程式碼）
- LV2：僅使用課程版型，並重新撰寫 Todo List 功能
- LV3：不使用課程版型完成此功能

## 第二週主線任務

第二週開始要接觸到課程的 API，是**非常重要的一個章節**，這份 API 會一直跟到直播班結束，同學們可用此份 API 建立屬於自己的電商資料，請務必在本週的時間內完成。

- 課程 API 相關網址：
    - 註冊連結：https://course-ec-api.hexschool.io/
    - 測試管理平台：https://course-ec-api.hexschool.io/dashboard
    - API 文件：https://course-ec-api.hexschool.io/document#products
- 課程 API 完整說明（長度 40mins）：https://courses.hexschool.com/courses/924133/lectures/21092725
- 使用第二週介紹的物件模組概念，讀取個人的資料 API（必須使用 this 運行）並以列表呈現
範例原始碼：https://codepen.io/hsiangfeng/pen/BajWqjJ


### 使用者故事

- 讀取遠端資料，並以列表呈現

### 任務說明：
- 請參閱[課程 API 介紹影片](https://courses.hexschool.com/courses/924133/lectures/21092725)，建立屬於自己的資料列表

課程任務均有提供完整範例程式碼，如果開發上不是很順利可以參考範例程式碼來撰寫。
範例程式碼：https://codepen.io/hsiangfeng/pen/BajWqjJ

使用範例程式碼注意事項：
- 禁止直接使用範例程式碼提交
- 如欲參考範例程式碼，請避免複製貼上，請自己一個字一個字重新撰寫
- 使用範例程式碼，請在繳交作業時附註：「本作業有使用範例程式碼」
- 使用範例程式碼，請在原始碼內補上註解，讓自己加深學習印象
- 此章節 API **請取得前台的資料即可，不需要使用後台的驗證 API**（請不要將個人 Token 提交）
```js
// 當判斷式接收到 sayYouLoveMe() 回傳 true 的結果時，則會運行接下來的陳述片段
if (sayYouLoveMe()) { console.log('說你愛我') };
```

### 提交難度挑戰：
- LV1：建立自己的資料內容，並且前端可取得資料即算完成（僅需要使用 `console.log` 呈現）
- LV2：使用課程版型，並且完整呈現列表
- LV3：依據自己的主題，建立合適的列表版型

# 第三週主線任務 - 產品管理頁面
第三週開始我們會開始接觸 Vue.js，在此階段同學可多練習 Vue.js 的各項語法及指令，目標先以完成一頁式的產品新增、刪除、修改的頁面（先不串接 API）。

![](https://i.imgur.com/oBgmStb.png)

![](https://i.imgur.com/pqo5PuX.jpg)


- 範例頁面 gh-page：https://hexschool.github.io/js-training-task/
- 範例程式碼 GitHub：https://github.com/hexschool/js-training-task

### 使用者故事

- 可以新增、編輯、刪除商品
- 商品啟用、關閉可以使用不同的顏色標示
- 商品欄位如下（請注意型別）
	- title：商品名稱 - string
	- category：商品分類 - string
	- content：商品敘述 - string
	- description：商品說明 - string
	- imageUrl：商品圖片 - string
	- enabled：是否上架 - boolean
	- origin_price：原價 - number(integer)
	- price：售價 - number(integer)
	- unit：單位 - string

### 任務說明：
- 依據使用者需求完成此作業

課程任務均有提供完整範例程式碼，如果開發上不是很順利可以參考範例程式碼來撰寫。
使用範例程式碼注意事項：
- **禁止直接使用範例程式碼提交**
- 如欲參考範例程式碼，請避免複製貼上，請自行重新撰寫
- 參考範例程式碼，請在繳交作業時附註：「本作業有參考範例程式碼」
- 參考範例程式碼，請在原始碼內補上註解，讓自己加深學習印象
```js
// 當判斷式接收到 sayYouLoveMe() 回傳 true 的結果時，則會運行接下來的陳述片段
if (sayYouLoveMe()) { console.log('說你愛我') };
```

### 提交難度挑戰：
- LV1：參考範例程式碼，並重新撰寫及補上註解（禁止複製範例程式碼）
- LV2：重新撰寫產品管理頁面
- LV3：產品內新增一個物件欄位 options，新增更多不同的設定在其中

options 範例：
```
options: {
  stars: 5,
  comments: [{
    name: '小明',
    avator: 'img url...',
    comment: '漂亮阿姨的餃子最好吃了'
  }]
}
```

## 第四週主線任務 - Vue 與 API 串接
第四週將會結合二、三週的概念，將課程的 API 結合 Vue 的介面進行開發。

![](https://i.imgur.com/JkK44CY.png)
![](https://i.imgur.com/zZyDS8l.png)

- 範例頁面 gh-page：https://hexschool.github.io/js-training-task/
- 範例程式碼 GitHub：https://github.com/hexschool/js-training-task


> 可選擇完成 “week4Pagination” 的版本即可，範例：第四週 - 元件化(只有分頁元件版本)

> 範例下載後，並替換成自己的 UUID 即可運作（需修改的[UUID 位置](https://github.com/hexschool/js-training-task/blob/master/week4/Products.html#L430)），如果有運行上的困難可聯絡講師或助教。

本週與上週的觀念重點差異：
- 第三週：物件參考觀念
- 第四週：實際串接 API 的差異

### 使用者故事

- **須製作登入驗證(繳交作業時不用付上帳號密碼，很重要)**
- **串接 API 並可以新增、編輯、刪除商品**
- 商品啟用、關閉可以使用不同的顏色標示

### 任務說明：

- 觀看登入開發的[影音課程](https://courses.hexschool.com/courses/924133/lectures/22245849)，並實作登入的功能
- 依據使用者需求完成此範例

課程任務均有提供完整範例程式碼，如果開發上不是很順利可以參考範例程式碼來撰寫。
使用範例程式碼注意事項：
- **禁止直接使用範例程式碼提交**
- 如欲參考範例程式碼，請避免複製貼上，請自行重新撰寫
- 參考範例程式碼，請在繳交作業時附註：「本作業有參考範例程式碼」
- 參考範例程式碼，請在原始碼內補上註解，讓自己加深學習印象
```js
// 當判斷式接收到 sayYouLoveMe() 回傳 true 的結果時，則會運行接下來的陳述片段
if (sayYouLoveMe()) { console.log('說你愛我') };
```

### 提交難度挑戰：
- LV1：參考範例程式碼，並重新撰寫及補上註解（禁止複製範例程式碼）
- LV2：依據條件開發完成，並至少有另外套用一個元件（至少加上分頁的元件）
- LV3：依據條件開發完成：
	- 至少套用兩個以上的元件且皆使用 import 方式載入
	- 加入 API 中的 options 的開發（需將該文字轉字串才可加入）

```js
// 範例 options
{
    "title": "Abysswalker",
    // ...
    "unit": "Item",
    "options": "{\"message\": \"Hello World!\"}"
}
```

### 加碼挑戰

部分同學反應，看到需求就不知道如何著手，因此分享「拆解」這一個小技巧，將複雜需求轉變為數個小部分，接下來再逐一執行（[分享文章](https://www.facebook.com/groups/110635703123103/permalink/702325553954112/)）：

以此範例來說：
- 登入頁面
  - 製作頁面
  - 套用 Vue.js
  - 實作登入
  - 將 Cookie 寫入並驗證
- 產品列表頁面
  - 先透過 Ajax 取得遠端資料（確認資料結構）
  - ...

本章節可先**試著撰寫拆解細節，然後發送給予助教、講師查看**，然後再開始實作，實作時依據自己撰寫的拆解流程開發，如果發現有問題再慢慢調整並持續進行。

拆解重點：
- 以一個行為、方法、流程進行拆解
- 每個行為開發時間約 20min ~ 1hr，如果超過 1hr 請再細分
- 拆解的內容並非不可變，開發過程如果遇到問題，可再重新修正、補充
- 先拆解再進行開發上的排序，影響「資料結構」的先開發
- 順序定好後，請**先定義「資料結構」或與「資料結構」具相關性的先開發**

作業繳交：請同學也將拆解的結果及心得附在程式勇者村，讓我們了解此方法對於大家的幫助喔

繳交範例：
```
編號：xxx
作業連結：https....

製作前的拆解：
- 依序撰寫...

製作後重新調整的拆解：
- 依序撰寫...

拆解心得：
```
