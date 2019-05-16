# Analysis-Score-by-using-R

用R作成績分析



研習目的

阿簡生物筆記，2015年12月12日，用R作成績分析(2)-產出SP Table與視覺化呈現試題、學生與班級分析圖表

http://a-chien.blogspot.com/2015/12/r2-sp-table.html

for WINDOWS 10



微調程式碼

前面四行

setwd("/media/pancala/3T/試題分析/0test")

#windows 用以下路徑

#setwd("D:/test")  

cardReading <-read.table("test.txt",header=TRUE,row.names="學號",fill = TRUE , as.is=T )



微調程式碼

改成
#setwd("/media/pancala/3T/試題分析/0test")

#windows 用以下路徑 [增加最前面的註解#] 

setwd(“D:/test”) [刪除最前面的註解#]  

cardReading <-read.csv("test. csv",header=TRUE,row.names="學號",fill = TRUE , as.is=T )

最後一行加按一次ENTER



讀卡成績

備妥讀卡成績並修成如阿簡格式

資料中間與最後皆不留空格，Excel-消去資料中的空白字元(TRIM+SUBSTITUTE)

https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwi15KeexorhAhXFhrQKHX83AbYQFjAAegQICBAB&url=https://isvincent.pixnet.net/blog/post/36650324-excel-%E6%B6%88%E5%8E%BB%E8%B3%87%E6%96%252

檔案位置與檔名，D:\>test\test.csv



程式運作

下載R-3.6-win.exe
https://cran.r-project.org/bin/windows/base/R-3.6.0-win.exe

安裝完畢後並開啟

複製改好的全部程式碼

貼上R程式

ENTER

………………………………………..
………………………………………..

(分析結果會出現在資料夾D:\test)
