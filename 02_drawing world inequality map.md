# Description
1. 在World Inequality Data中有記錄每個國家的income，但在其資料表中只有國名和income，在meta table中有country code。請嘗試用rworldmap繪製income map。

# Hints
1. 你可以在此下載income data
  - https://www.worldpolicycenter.org/maps-data/data-download/gender-data-download
  - [Quick link for downloading the zipped file](https://www.dropbox.com/s/4fpqarbcen0z7ab/WORLD-MACHE_Dataset_Gender_6.8.15_0.zip?dl=0)

2. rworldmap也可以用iso2繪製世界地圖
`myMap <- joinCountryData2Map(ndata, joinCode = "ISO2", nameJoinColumn = "iso2")`

3. 用google sheet join metadata和data後另存為CSV以讀取。

4. 先把data與metadata兩個資料表最前面不屬於資料的header部分手動刪除

5. 使用`?mapCountryData`查詢如何繪製數值（連續變項）的顏色。

