******可只執行【titanic.R】就好，【titanic_environment.RData】為非必要********

【titanic.R】
1112決策支援期末報告-鐵達尼號存活分析-預測存活率
按照此檔案內的程式碼執行 可獲得執行結果 

【titanic_environment.RData】
步驟：
> setwd("E:/1112課程/決策支援與商業智慧/期末專題報告/titanic/R") #請改成存放titanic_environment.RData的路徑下
> load("titanic_environment.RData") #載入titanic_environment.RData環境

----------------------------------------------------------------------------------------------------

.RData為保存工作環境的二進制文件格式，可保存當前的所有對象、變量、函數和數據集。

保存環境：
save.image("my_environment.RData")

保存一個名為my_data的數據框：
save(my_data, file = "my_data.RData")

加載環境：
load("my_environment.RData")

清空R環境(請確保你已經保存了需要保留的任何數據或代碼，因為一旦清空了環境，所有的對象和變量將無法恢復)：
rm(list = ls())

尋找目前工作目錄：
getwd()

更改目前的工作目錄位址：
setwd("E:/1112課程/決策支援與商業智慧/期末專題報告/titanic/R")

載入環境：
load("/full/path/to/my_data.RData")

