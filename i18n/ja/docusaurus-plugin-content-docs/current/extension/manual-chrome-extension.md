# Chrome CRX プラグインのローカル インストール ガイド

## CRX パッケージをダウンロード

[GitHub Release](https://github.com/rockbenben/ChatGPT-Shortcut/releases/latest) から ChatGPT Shortcut crx インストール パッケージ (ChatGPT_Shortcut-crx-3.x.x.zip) をダウンロードし、解凍します (crx ファイルは解凍されたフォルダー内にあります)。

![](https://img.newzone.top/2024-08-12-21-47-10.png?imageMogr2/format/webp)

## 開発者モードを有効にする

Chrome の [拡張機能の管理] ページを開き、[開発者モード] を有効にします。

次のアドレスをコピーしてブラウザのアドレス バーに貼り付け、Enter キーを押して開きます。ページの右上隅で [開発者モード] を有効にします。

```txt
chrome://extensions
```

![](https://img.newzone.top/2024-08-12-22-05-52.png?imageMogr2/format/webp)

## プラグインをインストール

プラグインをインストール (注⚠️: .crx ファイルをドラッグする必要があります。[解凍された拡張機能を読み込む] をクリックしないでください)

![](https://img.newzone.top/2024-08-12-22-16-38.png?imageMogr2/format/webp)

インストールが成功したら、[プラグインの使用チュートリアル](./usage.md) を表示できます。

## インストールで問題がありますか？

1. Windows ユーザーは、ダウンロードしたインストール パッケージが解凍されているかどうか (ダブルクリックして開いていないかどうか) を確認してください。

2. 「開発者モード」は有効になっていますか？そうでない場合は、2 番目の手順を参照してください。

3. crx ファイルを「拡張機能」ページにドラッグしましたか？注意⚠️: [解凍された拡張機能を読み込む] をクリックしないでください。crx ファイルをドラッグする必要があります。

4. ブラウザで crx ファイルのインストールが許可されていませんか？zip ファイルをインストールしてみてください。[zip インストール手順を表示するには、ここをクリックしてください](./manual-chrome-extension-zip.md)。
