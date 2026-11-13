# sonokr Homebrew Tap

[ScreenBar](https://github.com/sonokr/screenbar-releases)などのmacOSアプリを配布するためのHomebrew Tapです。

## ScreenBar

**現在は配布準備中です。インストールできるCaskはまだありません。**

実機確認を終えた未公証の試験版を公開し、Homebrew経由の導入を確認してから、次のコマンドで使える形にする予定です。アドホック署名・未公証であることを明示し、初回起動時にmacOSの確認操作が必要になる場合があることを案内します。

```sh
brew install --cask sonokr/tap/screenbar
```

アプリのダウンロードと変更内容は[ScreenBar Releases](https://github.com/sonokr/screenbar-releases/releases)で案内します。アプリ本体のソースはこのTapには含めません。

## 定義の更新

公開済みの配布ZIPに対応するバージョン・ダウンロードURL・SHA-256を確認してから、`Casks/` に定義を追加・更新します。未公開のURLや仮のチェックサムを、導入可能な公開版として登録しません。未公証版にはその旨の案内を付け、quarantineの削除やシステム全体のセキュリティ設定変更を行う処理は入れません。
