# NCREE-summer-internship
2022 國研院暑期實習生-國家地震中心(震災風險評估技術研發)PYTHON程式能力考試題目

#1
下載人口消長資料 (社會經濟資料服務平台segis)
取得最近20年台灣地區(不計算離島)人口，每年的人口總數/出生總數/死亡總數(三個欄位)
自行定義CSV格式儲存以上的答案
繪製(人口總數/出生總數/死亡總數 )折線圖

#2
讀取import.csv
整理該檔案中各地址資料
並儲存特定欄位至另一名為export.csv

#3
請將txt檔(HOUF43D10.txt)中的地址部分擷取出來
計算所有地址用到的字符(數字符號變換為D, 英文符號變換為A，如: B101室 → ADDD室)頻率
儲存成一個txt檔，並將頻率大於2的字符與其頻率儲存成另一txt檔

#4
試撰寫一時間計算函數
輸入一時間（格式為YYYY-MM-DD HH:SS，如：2020-04-15 20:30）
並回覆該天是星期幾，再計算出該時刻至今經過幾個太陽日(Julian date)
不足一日時，需用浮點數表示之。

#5
試撰寫一網路爬蟲函數
輸入一個關鍵字後
回傳第一個google搜尋結果
即透過internet 傳送 request 給google 搜尋引擎，處理google的回傳結果後，將首個超連結回傳

#6
找出迴文數 (Palindromes)
輸入2位數以上的任意正整數n，和它逆序翻轉後形成的新數相加
如此循環下去，要加幾次才會得到迴文數?
若超過5000次還無法得到迴文數，則輸出"no"。
