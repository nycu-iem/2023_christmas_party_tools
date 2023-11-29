# 2023耶舞 Sérendipité 小工具

## 匯出保險資料

為了節省資料處理時間，行政組利用 python 小工具做了一系列資料處理。

為了確保各工作人員、與會者的資料安全的儲存。

所有輸入資料皆稱為 input.csv

所有輸出資料皆稱為 output.csv

### 與會者

匯入資料為 .csv .xlsx

檔案放在資料夾 /attendee


```python
# Column Name
Index(['時間戳記', '已繳費', '票的類型', '姓名', '電子郵件信箱', '學號', '系所', '身分證字號', '出生年月日', '是否搭車（需加150元）', '姓名 ', '電子郵件信箱.1', '學號 ', '系所 ', '身分證字號 ', '出生年月日 ', '是否搭車（需加150元）.1', '姓名.1', '電子郵件信箱.2', '學號 .1', '系所.1', '身分證字號 .1', '出生年月日.1', '是否搭車', '姓名.2', '電子郵件信箱.3', '學號.1', '系所.2', '身分證字號.1', '出生年月日.2', '是否搭車（需加150元）.2', 'Unnamed: 31'], dtype='object')
```

### 工人

匯入資料為 .csv

檔案放在資料夾 /worker 中

column name
```python
# Column Name
Index(['時間戳記', '職位 (ex. 組長、工人)', '組別(ex. XX組)', '姓名', '手機號碼', 'LINE 暱稱', 'Email', '身分證字號', '生日(以民國表示) ex: 92/01/01', '想說ㄉ話'], dtype='object')
```

### 綜合

匯入資料為 .csv

Not finished