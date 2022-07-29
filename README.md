# プロキシカード自動生成プログラム
### 概要
　このプログラムはネット上から「Magic the Gathering」の指定カードの画像を取得し、外部アプリを利用してリサイズ、pdfとして保存までを行うプログラムです。

### 使い方
  1. cards.txtファイルに作りたいカードを一枚ずつ改行して入力して保存してください。
  2. exe.pyを実行してください
  3. ダウンロードフォルダにpdfとしてカード画像が保存されます

### 環境
  * python: 3.7.4
  * chrome driver: 78.0.3904.70

### 使用外部ライブラリ
  * BeautifulSoup 4.8.0
  * requests 2.22.0
  * selenium 3.141.0
  * chromedriver_binary


