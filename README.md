# sonokr Homebrew Tap

[ScreenBar](https://github.com/sonokr/screenbar-releases)などのmacOSアプリを配布するためのHomebrew Tapです。

## ScreenBar

**現在は配布準備中です。インストールできるCaskはまだありません。**

署名・公証済みのアプリを公開し、Homebrew経由の導入を確認してから、次のコマンドで使える形にする予定です。

```sh
brew install --cask sonokr/tap/screenbar
```

アプリのダウンロードと変更内容は[ScreenBar Releases](https://github.com/sonokr/screenbar-releases/releases)で案内します。アプリ本体のソースはこのTapには含めません。

## 定義の更新

公開済みの配布ZIPに対応するバージョン・ダウンロードURL・SHA-256を確認してから、`Casks/` に定義を追加・更新します。未公開のURL、仮のチェックサム、未公証のプレビューを、導入可能な公開版として登録しません。
