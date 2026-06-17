# DevSecOps 30日チャレンジ

## 言語

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![DevSecOps 30日チャレンジ](https://course-cover.labex.io/30-days-of-devsecops-challenges.png?lang=ja)](https://labex.io/ja/courses/30-days-of-devsecops-challenges)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ja/courses/30-days-of-devsecops-challenges)

DevSecOps の Linux と Docker セキュリティラボから選んだ 30 日間のチャレンジです。ホスト露出監査から、権限、シークレット、サービス ID、コンテナ堅牢化、Compose 分離、イメージ管理、インシデント清理へ進みます。

![devops](https://img.shields.io/badge/devops-whitesmoke?style=for-the-badge&logo=devops)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## 演習

|   インデックス | 名前                            | 難易度   | 練習                                                                                                                                                        |
|----------|-------------------------------|-------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 🎯 🆓 リスニングサービスの監査              | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-audit-listening-services-662167?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>              |
|       02 | 🎯 🆓 不要なパブリックポートの削除            | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-remove-unnecessary-public-port-662316?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>        |
|       03 | 🎯 🆓 管理インターフェースをローカルホストに制限する   | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-restrict-admin-interface-to-localhost-662317?course=30-days-of-devsecops-challenges'>チャレンジを開始</a> |
|       04 | 🎯 🆓 Web ディレクトリリスティングの無効化      | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-disable-web-directory-listing-662309?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>         |
|       05 | 🎯 🆓 公開されたバックアップアーカイブの削除       | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-remove-exposed-backup-archive-662313?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>         |
|       06 | 🎯 🆓 安全でないシークレットファイルの権限を修正する   | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-fix-unsafe-secret-file-permissions-662310?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>    |
|       07 | 🎯 🆓 ワールド書き込み可能な Web ディレクトリの修正 | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-fix-world-writable-web-directory-662311?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>      |
|       08 | 🎯  専用サービスユーザー                 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/dedicated-service-user-662278?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                      |
|       09 | 🎯  サービス環境ファイル                 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/service-env-file-662284?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                            |
|       10 | 🎯  ログ書き込みの境界設定                | 中級    | <a target='_blank' href='https://labex.io/ja/labs/log-write-boundary-662281?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                          |
|       11 | 🎯  ハードコードされた認証情報の削除           | 中級    | <a target='_blank' href='https://labex.io/ja/labs/linux-remove-hardcoded-credentials-662314?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>          |
|       12 | 🎯  プロセス環境変数のシークレット管理          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/process-env-secret-662282?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                          |
|       13 | 🎯  過剰な権限を持つ sudo ルールの削除       | 中級    | <a target='_blank' href='https://labex.io/ja/labs/linux-remove-over-permissive-sudo-rule-662315?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>      |
|       14 | 🎯  安全なスクリプトの PATH             | 中級    | <a target='_blank' href='https://labex.io/ja/labs/safe-script-path-662283?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                            |
|       15 | 🎯  root 権限で実行される Cron ジョブの堅牢化 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/linux-harden-root-run-cron-job-662312?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>              |
|       16 | 🎯  Compose Handoff Audit      | 中級    | <a target='_blank' href='https://labex.io/ja/labs/compose-handoff-audit-662564?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                       |
|       17 | 🎯  サポートポータルの監査                | 初級    | <a target='_blank' href='https://labex.io/ja/labs/support-portal-audit-662472?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                        |
|       18 | 🎯  メトリクスエンドポイントの公開            | 初級    | <a target='_blank' href='https://labex.io/ja/labs/metrics-endpoint-exposure-662477?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                   |
|       19 | 🎯  ローカルデバッグコンソール              | 初級    | <a target='_blank' href='https://labex.io/ja/labs/local-debug-console-662476?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                         |
|       20 | 🎯  内部データベースへのアクセス             | 中級    | <a target='_blank' href='https://labex.io/ja/labs/internal-database-access-662567?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                    |
|       21 | 🎯  読み取り専用設定マウント               | 中級    | <a target='_blank' href='https://labex.io/ja/labs/read-only-config-mount-662479?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                      |
|       22 | 🎯  非ルートユーザーによる画像ワーカーの実行       | 中級    | <a target='_blank' href='https://labex.io/ja/labs/non-root-image-worker-662478?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                       |
|       23 | 🎯  最小権限のログコレクター               | 中級    | <a target='_blank' href='https://labex.io/ja/labs/least-privilege-log-collector-662475?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>               |
|       24 | 🎯  Webhook Docker Socket      | 中級    | <a target='_blank' href='https://labex.io/ja/labs/webhook-docker-socket-662481?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                       |
|       25 | 🎯  Compose シークレットのスコープ制限      | 中級    | <a target='_blank' href='https://labex.io/ja/labs/scoped-compose-secret-662569?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                       |
|       26 | 🎯  サービスネットワークの分割              | 中級    | <a target='_blank' href='https://labex.io/ja/labs/split-service-networks-662571?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                      |
|       27 | 🎯  環境変数内の API トークン            | 中級    | <a target='_blank' href='https://labex.io/ja/labs/api-token-in-env-662473?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                            |
|       28 | 🎯  ビルドトークンの漏洩対策               | 中級    | <a target='_blank' href='https://labex.io/ja/labs/build-token-leak-662474?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                            |
|       29 | 🎯  より安全なワーカーイメージ              | 中級    | <a target='_blank' href='https://labex.io/ja/labs/safer-worker-image-662480?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                          |
|       30 | 🎯  インシデントデバッグのクリーンアップ         | 上級    | <a target='_blank' href='https://labex.io/ja/labs/incident-debug-cleanup-662566?course=30-days-of-devsecops-challenges'>チャレンジを開始</a>                      |

## LabEx について

[LabEx](https://labex.io) は、コーディングとテクノロジーに特化したインタラクティブな実践学習プラットフォームです。ラボ、AI 支援、仮想マシンを組み合わせて、ビデオなしの実践的な学習体験を提供します。動画なしの独自の実践ラボによる厳格な「実践による学習」アプローチ、ブラウザ内のインタラクティブなオンライン環境で自動化されたステップバイステップのチェック機能、スキルツリーベースのシステムによる構造化されたコンテンツ組織、30 のスキルツリーと 6,000 以上のラボを含む成長し続ける学習リソースにより、[LabEx](https://labex.io) は包括的な実践教育を提供します。プラットフォームには、最新の AI モデルを基盤とした学習アシスタント Labby が含まれており、対話型学習体験を提供します。

## その他

- 🔗 [ プログラミングコース](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [ プログラミングプロジェクト](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [ 無料チュートリアル](https://github.com/labex-labs/devops-free-tutorials)

