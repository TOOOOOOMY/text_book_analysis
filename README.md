# text_book_analysis
## 書籍リスト
・今回解析した[403冊](https://github.com/TOOOOOOMY/text_book_analysis/blob/master/Free%2BEnglish%2Btextbooks.csv)のリスト  
・配布元の[Free access to a range of essential textbooks from all disciplines](https://www.springernature.com/gp/librarians/news-events/all-news-articles/industry-news-initiatives/free-access-to-textbooks-for-institutions-affected-by-coronaviru/17855960)


## 単語リストの解説
今回は21ジャンル403冊、単語にして約63万種類あるため、単語の出現率をジャンル単位で計算し90%以上の出現率を持つものをまとめました。
  
↓↓出現頻度をまとめたグラフ
![fig1](https://user-images.githubusercontent.com/45617592/81488644-68480c00-92a6-11ea-85fa-19db01c96fbf.png)
  
|出現率  |出現分類  | 単語数 | ファイルリンク |
|---|---|---|---|
|100 %| 21/21 | 3512 | [Common 21/21](https://docs.google.com/spreadsheets/d/1e99DbmBRLsQP073bfnXxPmM1TaD6jPzQpMEiVGuoA0o/edit?usp=sharing) |
| 95 %| 20/21 | 1610 | [Common 20/21](https://docs.google.com/spreadsheets/d/1DGoYGkHHtz4ZaUBWVltsJbkSYE9l4HPcCwwwLtCz47c/edit?usp=sharing) |
| 90 %| 19/21 | 1353 | [Common 19/21](https://docs.google.com/spreadsheets/d/1kVb9K8UWWfUE4DjAVS67-FPjlPfPjUumocPakwqda0o/edit?usp=sharing) |

### 注意点
改行や計算式に含まれている文字の関係で変な文字列が単語として載っていたり、Google Spreadsheetの翻訳機能が変な翻訳をしている可能性があります。  
もし発見した場合は、GitHubの[issue](https://github.com/TOOOOOOMY/text_book_analysis/issues/1)~~またはこちらのGoogleフォーム~~から連絡をいただけると助かります。  
人名や超基本な単語など、単語帳としてふさわしくない単語があった場合でも連絡いただけるとありがたいです。

## 解析に使用したツール
言語：Python  
環境：[Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)  
ライブラリ：[Spacy](https://spacy.io/)、[pdfminer.six](https://github.com/pdfminer/pdfminer.six)

