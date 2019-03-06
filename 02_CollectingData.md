# Collecting demographic data
* 背景：類似Bloomberg背後其實有非常龐大的技術和資料庫團隊在資源，編制和記者與編輯加起來一樣大，讓記者和編輯可以快速透過指令就可以查詢例如政治人物身家、擔任董事等。類似這種資料需要仰賴Bloombeg技術與資料團隊長期、不間斷、即時地蒐集資料並更新。
* 目的：透過資料蒐集練習R語言的撰寫，並與班上同學共享資料。

## 步驟
1. 開啟一個新的.rmd檔，檔名為r1234567.rmd（以學號命名）。
2. 上網找縣市為範圍的資料（有幾個縣市就要有幾個欄位），條件是三筆（自行想像），例如各縣市的面積。如果你覺得太無聊，可以找鄉鎮市等級的。這為單人作業，每個人要找到三筆以上，但建議可以小組合作，例如四個人找到12筆以上。這樣可以避免重複，各組也可以關注自己想要處理的資料對象。
3. 從網路上把數據複製下來，手動打或整理後貼到.rmd檔中。比方說`population <- c(123, 345, 5667)`
4. 把這些數據，包含縣市名稱`county <- c("台北市", "台北縣")`等合成一個`data.frame`。
5. 利用函式檢測你的資料的資料型態。
6. 利用save(df1, df2, df3, file = "r1234567.rda")將之儲存為rda檔。

## Part II Paid Maternal Leave
* 課前先到Youtube上觀看Paid Maternal leave的說明https://youtu.be/dZE2xsqYQqY。 上課時比較容易裡解操作的內容。

## 上傳
1. 把r1234567.rda檔上傳到https://drive.google.com/drive/folders/1u8OFb71LixRZMQjm4Zy7QqzafxT-rL-y?usp=sharing
2. 把r1234567.rmd檔和r1234567.nb.html或r1234567.html上傳到Ceiba的作業二，如果不知道怎麼產製.html檔的同學，可以觀看這支影片https://youtu.be/xVXUZShYfEI

## 問題
* 有程式技術問題可轉聯絡助教廖冠豪。
* 有作業或課程問題請優先聯絡助教許家瑜，可直接貼至[Dropbox Q&A](https://paper.dropbox.com/doc/R1072-QA--AXu~MLhqdA~eZs_aYA67wHWuAg-ldpdmVWiEDBLKyfCTIIhQ)中。
* 對課程進行如果有任何建議也可貼至Q&A中。
* 該作業預期會產生不一致的結果，這也是學習的一部分。

