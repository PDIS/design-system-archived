# 文字屬性 (Typography)


## 字體 (Typeface)

沒有規定字體，但建議不採用標楷體。

根據國發會網站管理規範指出：政府機關的文件習慣以標楷體編排，但小字型的標楷體 在螢幕顯示往往不夠清楚，建議網頁設計者或網頁內容維護者在製作網頁時，取消原訂公文的標楷體格式，檔案或列印版本的公文則另行提供。

本設計系統採用的中文字體是 [Noto Sans TC](https://fonts.google.com/noto/specimen/Noto+Sans+TC?query=Noto+Sans)，英文字體則是 [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans?query=Noto+Sans)。



## 字型 (Font)


### 標題 (Heading)
are used in product-based UI designs such as panels, cards, and menus.
![](https://i.imgur.com/sakrJ0R.png)


:::warning
[will update]
ps. What are the heading line height settings in Bootstrap?
line-height: 1.5;
:::

### 段落 (Paragraph)
The default paragraph font size is 16px on large screens and 14px on small screens.
![](https://i.imgur.com/WjYWk1X.png)


:::warning
[will update]
ps. What are the paragraph line height settings in Bootstrap? 1.5
:::
```
$line-height-1:            1;
$line-height-base:            1.5; ***
$line-height-sm:              1.25;
$line-height-lg:              2;

"line-height": (
      property: line-height,
      class: lh,
      values: (
        1: 1,
        sm: $line-height-sm,
        base: $line-height-base,
        lg: $line-height-lg,
      )
    ),
```


### 字重 (Font weight)
As with the font size, you can add a font weight override class to any other typographic class or element to change the font weight to regular or bold weight.

#### Bold text

You can use bold to emphasise particular words in a transaction. Use it to highlight critical information that users need to refer to or you’ve seen them miss.

For example, “Your reference number is ABC12345678. Use this to track your application. Updates will be sent to name@example.com“

Use bold sparingly. Overuse will make it difficult for users to know which parts of your content they need to pay the most attention to.
![](https://i.imgur.com/8HMPKoe.png)



### 顏色 (Color)
![](https://i.imgur.com/9CERV1v.png)

### 連結 (Links)
連結的部分沿用 Bootstrap 5，在 hover 時就原有顏色加上一個 shade percentage。
![](https://i.imgur.com/UFUHY3b.png)
![](https://i.imgur.com/MUhoduJ.png)

:::warning
[will update]
Links are underlined by default (not just on hover), unless they’re part of specific components.
應該會拿掉這張圖
:::

### 列表 (Lists)
Bulleted lists are used when items should be grouped together but have no inherent order. When using a bulleted list, it is recommended that the text for each bullet is not longer than two sentences.

#### 項目符號列表 (unordered list)
![](https://i.imgur.com/yEzTwvl.png)

#### 編號列表 (Numbered)
![](https://i.imgur.com/mqr2hPb.png)

### 所有字型大小 (All font sizes)
![](https://i.imgur.com/0j3Twki.png)






