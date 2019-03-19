# crawler

In code **web_crawler_ETFs**, I crawl some information of ETFs (daily closing price and corresponding date) from website https://finance.yahoo.com/.

In code **web_crawler_financial_index**, I crawl information of LMCI from website https://fred.stlouisfed.org/series/FRBLMCI.

The code is written in [Python3](https://www.python.org) with [jupyter notebook](https://jupyter.org/).

## Installation
Download the repository
```bash
$ git clone https://github.com/EvaXunHsu/Ebooks-Crawler.git
```

## Modules
We use 
- **_datetime_** , **_time_** : 對時間做處理
- **_pytz_** : 因為ETFs的資料所對應的時區是EST，所以我的程式有考慮時區，使用了pytz
- **_json_** : request後，對JSON資料進行解碼，轉換為 Python 字典，便於操作資料
- **_pickle_** : 壓縮/保存/提取文件的模塊

## Packages
We use  
- **_requests_** ：它是一個Python HTTP庫，可使HTTP請求更簡單。
- **_pandas_** : 可以快速操作及分析資料；在本程式中用到了讀取檔案，資料篩選與合併等功能。

