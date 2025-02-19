# ATOK Tango Syntax

VS Code 用 ATOK 単語ファイルおよび用例ファイルのシンタックスハイライトです。

![screenshot_tango](https://raw.githubusercontent.com/artakase/vscode-atok-tango-syntax/main/images/screenshot_tango.png)

![screenshot_yorei](https://raw.githubusercontent.com/artakase/vscode-atok-tango-syntax/main/images/screenshot_yorei.png)

## 使い方

ATOK 単語ファイルまたは用例ファイルを開き、言語モードから `ATOK Tango` を選択してください。

先頭の行が次の通りであるファイルは単語ファイルです。
```
!!ATOK_TANGO_TEXT_HEADER_1
```
先頭の行がそれ以外でも、この拡張機能は単語ファイルとしてハイライトします。

先頭の行が次の通りであるファイルは用例ファイルとしてハイライトします。
```
!!ATOK_YOREI_TEXT_HEADER_1
```

単語ファイルを一つのフォルダーにまとめ、ワークスペース設定で `*.txt` ファイルを ATOK 単語ファイルに関連付けると便利です。

```json
{
    "files.associations": {
        "*.txt": "atoktango"
    }
}
```
