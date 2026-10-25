[![License](https://img.shields.io/badge/license-MIT-greeeen)](LICENSE)


## テキストチェッカー
ローカルのテキストファイルを開いて文字列を検索・確認するだけのビューアです。編集や保存はできません。HTML1枚で動作し、ファイルは端末内だけで処理されます。 (外部に送信されません)

※想定する使用シーンはスマホです。

### 機能
- **ファイルを開く**: ボタン、またはドラッグ&ドロップ。txt、html、md、json、csv、ソースコードなどのテキスト系に対応
- **文字コードの切り替え**: UTF-8 / Shift_JIS / EUC-JP / UTF-16 LE
- **検索**: 大文字小文字を区別しない。正規表現のオン/オフ切り替えに対応
- **マーク表示**: 該当箇所と該当行をハイライト。現在位置は別色で表示
- **該当数の表示**: 「3 / 12件(45行目・該当8行)」の形式
- **ジャンプ**: 「前へ」「次へ」ボタン、または Enter / Shift+Enter で該当箇所へ移動
- **行番号表示**

### 使い方
`index.html` をブラウザで開く、または GitHub Pages で公開して利用します。サーバー不要です。

### 注意
- 数十MBを超える巨大ファイルは表示が重くなります
- PDFやWordなどのバイナリ形式は対象外です


⚠️COPYRIGHT<br>
All non-code text authored by the repository owner is licensed under CC BY-NC-ND 4.0.
