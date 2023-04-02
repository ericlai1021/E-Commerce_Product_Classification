1. 原始檔案
    -  廠商提供商品資訊
    - 自定義斷詞字典: dict.txt (用於 XGBClassifier.ipynb), dict.txt.big(用於 vpon_fasttext.ipynb)
    - 去除停用字檔案: stop_words.txt (用於 XGBClassifier.ipynb)

2. 資料前處理：
	
    `$python3 preproc.py`
	
    - 輸出檔案：result_online.csv, result_onlinie_cat2.csv

3. VPON專案 (Fasttext部分)

    - 模型訓練: vpon_fasttext.ipynb (逐步執行)

4. VPON專案 (XGBClassifier部分)

    - 模型訓練: XGBClassifier.ipynb (逐步執行)
