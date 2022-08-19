# machine-learning-practice

## Fasttext使用

### ファイル

classify_text_with_fasttext.ipynb

### 調査結果

既存モデルを使用するとエラーが発生し、Vectorファイルから生成したモデルを使用するとセッションがクラッシュする。  
既存モデル使用時のエラーメッセージについては、本README執筆時は取得環境が無かったため、とりあえず未記載。

## BERT使用

### ファイル

classify_text_with_bert.ipynb

### 調査結果

そもそもBERTは感情分析は行えるが、文書に対するトピックラベリングが行えない。  
よって、今回は採用しない。
