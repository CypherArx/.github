# CypherArx

CypherArx is a password manager for data that the usual "site, user name, password" list
cannot hold: accounts with things below them, any number of labelled values, and several
identities on the same service. Everything is kept in one local file and is never sent
anywhere.

**CypherArx is pre-alpha. It has not been reviewed by anyone else, and the vault format may
change without notice. Do not keep real passwords in it yet.**

| Repository | What it is |
|---|---|
| [cypherarx-core](https://github.com/CypherArx/cypherarx-core) | The C++ library: cryptography, storage, the data model, password generation, one-time passwords, import. No user interface and no command-line tool. |
| [cypherarx-gui](https://github.com/CypherArx/cypherarx-gui) | The desktop application, built on the core. It currently runs on Windows. |

The design is written down in the core's `docs/`:

- [Design](https://github.com/CypherArx/cypherarx-core/blob/main/docs/design.md): purpose, structure, principles
- [Cryptographic design](https://github.com/CypherArx/cypherarx-core/blob/main/docs/crypto.md): keys, what is encrypted, what the file shows, what is not protected
- [Data model](https://github.com/CypherArx/cypherarx-core/blob/main/docs/data-model.md): tables, the two-parent model of entries, the schema

Both repositories are licensed under the Apache License 2.0.

---

# CypherArx（日本語）

CypherArx は、よくある「サイト、ユーザー名、パスワード」の一覧では持てないデータのための
パスワードマネージャーです。アカウントの下に属するもの、ラベルの付いたいくつもの値、同じ
サービスにある複数の名義を扱えます。すべてを手元の 1 つのファイルに持ち、どこにも送りません。

**CypherArx はプレアルファです。ほかの誰のレビューも受けておらず、金庫の形式は予告なく変わる
ことがあります。まだ本物のパスワードを入れないでください。**

| リポジトリ | 内容 |
|---|---|
| [cypherarx-core](https://github.com/CypherArx/cypherarx-core) | C++ のライブラリ。暗号、保存、データモデル、パスワードの生成、ワンタイムパスワード、インポート。画面もコマンドラインのツールもありません。 |
| [cypherarx-gui](https://github.com/CypherArx/cypherarx-gui) | コアの上に作ったデスクトップのアプリケーション。今は Windows で動きます。 |

設計は、コアの `docs/` に書いてあります。

- [設計](https://github.com/CypherArx/cypherarx-core/blob/main/docs/design.ja.md): 目的、構造、原則
- [暗号の設計](https://github.com/CypherArx/cypherarx-core/blob/main/docs/crypto.ja.md): 鍵、何を暗号化するか、ファイルから分かること、守らないもの
- [データモデル](https://github.com/CypherArx/cypherarx-core/blob/main/docs/data-model.ja.md): テーブル、エントリが 2 つの親を持つモデル、スキーマ

どちらのリポジトリも、ライセンスは Apache License 2.0 です。
