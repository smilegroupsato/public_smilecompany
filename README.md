# public_smilecompany

スマイル商事合同会社（Smile Company LLC）の公開用Repositoryです。

人間とAIが、単発のチャットではなく継続する仕事として協働するための方法、公開記事、テンプレート、実践例を掲載します。

## 公開しているもの

### Repository Context

AIとの仕事をチャットの中に置きっぱなしにせず、別セッションや別のAIでも作業を再開できるように、目的・正本・現在地・判断・次アクションをRepository側へ残す方法です。

最小版は4つのMarkdownファイルから始められます。

```text
AGENTS.md
REPOSITORY_CONTEXT.md
NEXT.md
HISTORY.md
```

テンプレート：

- [`repository-context-minimal/`](./repository-context-minimal/)
- 解説ページ：https://smilecompany.llc/methods/repository-context/

### Zenn記事

Zenn向けの記事原稿は [`articles/`](./articles/) で管理します。

初回記事：

- [`articles/repository-context-minimal.md`](./articles/repository-context-minimal.md)

Zenn連携前・公開判断前の記事は `published: false` とします。

## このRepository自身もRepository Contextで運用しています

説明用テンプレートを置くだけでなく、このRepositoryのルートにも実運用中の4ファイルを置いています。

- [`AGENTS.md`](./AGENTS.md)：公開RepositoryでAIが守るルール
- [`REPOSITORY_CONTEXT.md`](./REPOSITORY_CONTEXT.md)：このRepositoryの目的・現在地・判断
- [`NEXT.md`](./NEXT.md)：次アクションと保留
- [`HISTORY.md`](./HISTORY.md)：完了事項と採用済み判断

テンプレートと実運用例を見比べられるようにしています。

## このRepositoryの位置づけ

このRepositoryは、対外公開してよい派生物だけを置く場所です。

内部の企画、顧客情報、個人情報、契約・会計原本、credential、secret、非公開Repositoryの内部情報は置きません。

```text
内部の制作・正本
        ↓ 公開判断・安全加工
public_smilecompany
        ├─ 公開テンプレート
        ├─ 公開記事
        └─ 公開実践例
```

## リンク

- Smile Company LLC：https://smilecompany.llc/
- Repository Context：https://smilecompany.llc/methods/repository-context/

## Status

- Repository Context minimal starter: public
- Public Repository itself: Repository Context active
- Zenn first article: draft
- License: 未設定（公開物の再利用条件は別途明記予定）
