# python-accupass-scraper #

## 專案介紹 ##

本專案使用Selenium套件，來開發Python動態網頁爬蟲，爬取[Accupass活動通](https://www.accupass.com/)網站的Python活動資訊，包含名稱、觀看人數、喜歡人數及售票狀態，並且整合Pandas套件，將Python網頁爬蟲取得的資料存入Pandas DataFrame，篩選「熱銷中」的Python活動資訊，以及依據觀看人數來排序資料，最後利用Pandas DataFrame的to_excel()方法(Method)匯出Excel檔案，可以搭配[解析Python網頁爬蟲如何有效整合Pandas套件提升資料處理效率](https://www.learncodewithmike.com/2020/11/python-web-scraping-with-pandas.html)部落格文章來進行學習。

## 前置作業 ##

將專案複製(Clone)下來後，假設沒有pipenv套件管理工具，可以透過以下指令來進行安裝：

`$ pip install pipenv`

有了pipenv套件管理工具後，就可以執行以下指令，來安裝專案所需的套件：

`$ pipenv install --ignore-pipfile`

接著，登入虛擬環境：

`$ pipenv shell`

登入後，就能夠執行scraper.py範例程式。