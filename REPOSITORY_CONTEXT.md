# Repository Context

## 目的

このRepositoryは、スマイル商事合同会社（Smile Company LLC）の対外公開用Repositoryです。

人間とAIの協働方法、Repository Context、公開記事、テンプレート、実践例を、第三者が読んだり試したりできる形で公開します。

## 現在地

- Public Repositoryを作成済み
- Repository Context汎用最小版のテンプレートを公開済み
- Zenn用の初回記事原稿を作成済み
- Zenn記事は未公開（`published: false`）
- ライセンスは未設定

## 公開物

### Repository Context minimal starter

`repository-context-minimal/`

```text
README.md
AGENTS.md
REPOSITORY_CONTEXT.md
NEXT.md
HISTORY.md
```

### Zenn記事

`articles/`

初回原稿：

- `articles/repository-context-minimal.md`

## 正本と役割

このRepositoryは、外部公開してよい成果物の配布・公開用です。

内部の制作過程や非公開情報をそのまま正本化する場所ではありません。公開する内容は、安全確認した派生物としてここへ配置します。

Repository Contextの一般向け解説ページ：

- https://smilecompany.llc/methods/repository-context/

## 採用済み判断

- 公開Repositoryと内部制作環境を分ける。
- ZennにはWebページの完全転載ではなく、読者向けに再構成した派生記事を出す。
- Zenn記事は公開判断まで `published: false` とする。
- Repository Context最小版は4ファイル構成から始める。
- この公開Repository自体もRepository Context方式で運用する。

## 未決事項

- ZennとのGitHub連携設定
- 初回Zenn記事の最終レビューと公開判断
- 公開テンプレートのライセンス
- 今後の英語版、zip、Template Repository化

## してはいけないこと

- secret、password、API token、credentialを入れない
- 個人情報、顧客情報、私的メッセージを入れない
- 内部用ログや非公開原本をそのまま公開しない
- 明示的な承認なしに外部公開状態を変更しない

## 次に読むもの

1. `AGENTS.md`
2. `NEXT.md`
3. `HISTORY.md`
4. `repository-context-minimal/README.md`
5. `articles/repository-context-minimal.md`

## 更新履歴

- 2026-09-13：初期作成。公開Repositoryの役割、RC最小版、Zenn記事draft、公開境界を定義。
