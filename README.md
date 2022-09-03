# Minecraft サーバ管理ダッシュボード

自鯖で使うためのMinecraftサーバ管理ダッシュボードです。
DockerコンテナでMinecraftサーバを運用している前提です。

## 言語 / フレームワーク

- C#
  - dotnet 6
  - Razor Pages

## 提供機能 (予定)

- サーバ立ち上げ
  - 関連フォルダ作成
  - dockerコンテナの起動
  - プロキシ(bungeecord)への登録
- サーバ管理
  - サーバコンテナの起動・停止・再起動
  - 関連URL設定 (dynmap etc.)
- サーバ情報取得APIの提供
  - 起動状態
  - 説明
  - 関連URL
- Discord通知
- DBバックアップ

---

- スケジューリング
  - 起動・停止・再起動
- ワールドデータのバックアップ
  - バックアップの管理
- ログファイル閲覧
- docker build
- サーバプラグイン管理
- 管理者コンソール遠隔操作

## License

[MIT License](./LICENSE)

## Author

- Oyakodon ([@oyakodon](https://github.com/oyakodon))
