# OCR_meter
### 概要
・ Tesseract OCR（OCRのツールの一種）を使用  
・ Pythonライブラリである `pyocr` を使うことでPythonからも扱うことができる  
・ 訓練データ作成にはjTessBoxEditorを使用

### 訓練データ作成方法
1. 学習データ作成  
  参照：https://www.tdi.co.jp/miso/tesseract-ocr  
  学習データの作成

2. 学習の実行
  参照：https://www.tdi.co.jp/miso/tesseract-ocr  
  学習の実行

3. 学習データの反映  
  `Tesseract/share/tessdata/` 内に2.で作成したtraineddataを格納
