# app-updates

個人配布中の3アプリ（bose/せどりブリッジ/家計簿）の**バージョン番号のみ**を公開する小さなマニフェストリポジトリです。

- アプリ本体のソースコードは非公開のままです（このリポジトリには含まれません）。
- 各アプリは起動時にこのリポジトリの `*.json` を認証なしで取得し、インストール済みバージョンより新しければ更新通知を表示します。
- 実際のAPKダウンロードは、各アプリの private リポジトリの Releases ページ（コラボレーター権限が必要）から行います。

| ファイル | 対象アプリ | リリースページ |
|---|---|---|
| `sedori.json` | せどりブリッジ (com.local.sedori) | https://github.com/threepong/android-sedori/releases/latest |
| `repair.json` | bose修理管理 (com.local.repair) | https://github.com/threepong/android-repair/releases/latest |
| `kakeibo.json` | 家計簿 (com.local.kakeibo) | https://github.com/threepong/android-kakeibo/releases/latest |

各JSONは対応するアプリのGitHub Actions（push to main）が自動更新します。手動編集は不要です。
