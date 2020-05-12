# 機能の紹介

## 自分のアバターを読み込む

macOSの方は、 `/Applications/Koigao/`、Windowsの方は `Koigao.exe` が入っているフォルダを開きます。(以下、「最初のフォルダ」と呼びます)

その中の `models` というフォルダに、ご自身のvrmファイルを入れます。

最初のフォルダにある、 `config.json` を開きます。
その中の以下の記述を、ご自身のvrmファイルの名前に変更します。

```
"vrmFileName": "data.vrm",
```
↓(例)利用したいファイル名に書き換える
```
"vrmFileName": "hirarichan.vrm",
```

その際、`"` や `,` などの記号を誤って消してしまったり、増やしてしまったりしないようにご注意ください。

変更を保存後、PC用アプリを再起動するとモデルが読み込まれます。VRoidStudio製のモデルを基準に開発しているため、フルスクラッチのモデルや外部ツールで改造されたVRoidStudio製モデルなどは読み込まれなかったり、一部のボーンが動かなかったりする場合があります。完全動作のお約束はできかねますが、ご連絡いただければサポートできるかどうかの調査をいたします。

## 背景の色を変える

「自分のアバターを読み込む」で編集したのと同じ、 `config.json` を開きます。以下の項目を編集すると、背景色を変更することができます。

```
"backgroundColorRed": 0,
"backgroundColorGreen": 255,
"backgroundColorBlue": 0,
```

RGB値をそれぞれ0~255の範囲で指定してください。