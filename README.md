# spespetime

## Installation

`icon` を `resources/icon/icon`に入れてください。
画像通知を使用する場合は`images` のディレクトリを `resources/images` に入れてください。

以下の指定をすると `git pull` するだけで基本のファイルを更新できます。
[timeline フォルダの場所を変えたい](https://github.com/anoyetta/ACT.Hojoring/wiki/SpespeTime#timeline-%E3%83%95%E3%82%A9%E3%83%AB%E3%83%80%E3%81%AE%E5%A0%B4%E6%89%80%E3%82%92%E5%A4%89%E3%81%88%E3%81%9F%E3%81%84)

## 絶アレキ

画像通知を使用しない場合はファイル内を変更してください。

```git
- <default target-element="ImageNotice" target-attr="enabled" value="true" />
+ <default target-element="ImageNotice" target-attr="enabled" value="false" />
```

## 絶竜詩戦争

画像通知を使うため`images` の中身の画像をディレクトリを `resources/images` に入れてください。
