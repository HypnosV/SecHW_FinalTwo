# 紀錄助教批改回覆內容及修正記錄

## 2020-12-01 助教建議

以下針對 codepen 提供批改建議，

HTML：

1. class 命名可以再更符合語意些，比如：.h1 改名為 .logo；左側選單的 h2，標題可取為 .menu-title、其他項目則是 .menu-item。

2. HTML 第 5 行，結尾 " 重複多打了一次，要記得刪除哦～

3. option 選單項目、購物車 icon 皆為連結，要使用 a 連結包覆。

4. banner 圖片沒載入成功。

5. 「甜點類別」建議移出 ul 外，該元素也非連結，不需使用 a 標籤。

6. 「所有甜點 (48)」～「新品上市 (12)」不是標題，不建議使用 h2 標籤。

7. 呈上述，a 連結正確語法為 ```<a href="#"> </a>```，若沒加上 href=" "，就無法供使用者點擊。

8. 「焦糖瑪卡龍」可改用 h3 標籤。
</br></br>

CSS：

1. CSS 第 1 行 box-sizing 正確寫法應為 :

    ```bash
    *,*:before,*:after {
    box-sizing: border-box;
    }
    ```

2. ```.header``` 不要寫死高度，請改用 padding 推擠。```.addcart``` 也是。

3. ```.option``` 不要寫死寬度，可改在子層 a 連結使用 padding 推，能增加點擊範圍（a 連結要先加上 ```display: block```）

4. ```.menu .h2``` 的高度可移除，你已經有用 padding 哩。

5. 調整圖片尺寸時，可針對寬或高其中一項進行設定，圖片就會等比例縮放。```.product li img``` 的高度可移除。

6. ```.product-price .h2``` 也可賦予寬度，避免日後產品名稱增加時會造成破版，這邊建議與 ```.product-price span``` 相同使用 padding 推擠，較有一致性。

7. ```.page-option li``` 的寬高設定建議移至子層 a 連結，才能增加點擊範圍。

8. 連結都要加上 hover 效果，增進使用者體驗。

---
