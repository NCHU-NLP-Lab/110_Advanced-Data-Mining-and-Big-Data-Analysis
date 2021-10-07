## KCM作業繳交說明

- 網站已上線提供測試，有10題，下周上課會公布正式20題，一題5分，回傳的前十名與標準答案有5個以上重疊即拿到分數。
- 題目範例:['臺灣','美國']
- 答案範例 : [["日本", "香港", "中國大陸", "分佈", "中國", "中華民國", "日治", "臺北市", "名稱", 
"臺北"],["非建制地區", "城市", "人口普查", "加拿大", "英國", "地區", "加利福尼亞州", "國家", "伊利諾伊州", "公司"]]

---

- 評分網站: <https://admbda.nlpnchu.org/scoring/>
- 測試用題目:['臺灣', '美國', '大學', '肺炎','天安門','歌手','中國','蔡英文','立法院','颱風']
- 參考答案: testCase_answer.json

#### 繳交答案網站使用說明
- 第一格填入課程代號+ilearing上的分組(Ex:6648_5,7748_1)，第二格填入你程式跑出的答案
- **答案請使用規定之JSON格式，例如:題目兩題各回傳關聯度最高的前兩名，格式應為 [["第一題第一名關鍵字", "第一題第二名關鍵字"],["第二題第一名關鍵字","第二題第二名關鍵字"]]**

#### wiki資料下載
提供50000筆維基百科條目的JSON檔，請使用此資料來完成作業。

```
pip install gdown
gdown --id 1rQnbaOiqoN40AzHVq_IrRW4ki-rFPRxZ
```

#### 可參考資源
1.https://colab.research.google.com/github/astg606/py_materials/blob/master/useful_modules/introduction_json.ipynb (JSON格式介紹)

2.https://github.com/fxsjy/jieba (結巴斷詞)

3.https://github.com/UDICatNCHU/UdicOpenData (斷詞工具)