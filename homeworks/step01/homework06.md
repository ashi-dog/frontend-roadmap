# 周遊列國

你的好麻吉小立是一個很愛到處旅遊的人，在前一陣子才靠著便宜的 bug 機票以及特價的商務艙玩遍了許多地方。不過小立一直有個困擾，那就是他希望了解更多跟國家有關的知識，因此他來請你幫忙寫一個搜尋國家資訊的小程式。

這個程式很簡單，只要輸入國家的英文名字，就能夠查詢符合的國家的資訊，會輸出以下幾項：

1. 國家名稱
2. 首都
3. 使用的貨幣名稱
4. 電話國碼

請參考以下範例：

```js
node hw3.js tai

============
國家：Taiwan
首都：Taipei
貨幣：TWD
國碼：886
============
國家：United Kingdom of Great Britain and Northern Ireland
首都：London
貨幣：GBP
國碼：44
============
國家：Lao People's Democratic Republic
首都：Vientiane
貨幣：LAK
國碼：856
```

另外，如果沒有找到任何符合的國家，請輸出：「找不到國家資訊」。

相關的資訊都可以在這個佛心的 API 找到：<https://restcountries.eu/#api-endpoints-name>

<details>
  <summary>提示 #1</summary>

在 terminal 輸入 `node hw3.js tai` 該如何拿到 `tai` 這個值呢?

</details>

<details>
  <summary>提示 #2</summary>

觀察 API 的 response 來決定怎麼取得你要的資訊

</details>

<details>
  <summary>提示 #3</summary>

API 網址：`https://restcountries.eu/rest/v2/name/{name}`

</details>
