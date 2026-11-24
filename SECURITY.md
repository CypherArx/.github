# Security policy

CypherArx is pre-alpha. It has not been reviewed by anyone else, and it should not hold real
passwords yet. Reports are welcome all the same.

## Reporting a vulnerability

Please do not open a public issue for a vulnerability. Use GitHub's private reporting
instead: on the repository the problem is in
([cypherarx-core](https://github.com/CypherArx/cypherarx-core/security/advisories/new) or
[cypherarx-gui](https://github.com/CypherArx/cypherarx-gui/security/advisories/new)), open
the **Security** tab and choose **Report a vulnerability**. The report is visible only to
the maintainer.

It helps to include:

- which repository and commit you looked at;
- what an attacker needs (the vault file, the same user account, physical access, …);
- what they gain;
- steps or code that show it, if you have them.

## What to expect

The project is maintained by one person in their spare time. There is no promised response
time. A report will be read, and the reporter will be told whether it is accepted and, when
it is fixed, in which commit.

## Known limits

The cryptographic design lists what it does not protect against (software running as the
same user while the vault is unlocked, a weak master password, rolling the file back, and
others): see [docs/crypto.md](https://github.com/CypherArx/cypherarx-core/blob/main/docs/crypto.md).
A report that restates one of those is not a vulnerability, but a report that shows the
design fails at something it claims is.

---

# セキュリティポリシー（日本語）

CypherArx はプレアルファです。ほかの誰のレビューも受けておらず、まだ本物のパスワードを
入れるべきではありません。それでも、報告は歓迎します。

## 脆弱性の報告

脆弱性については、公開のイシューを立てないでください。代わりに、GitHub の非公開の報告を
使ってください。問題のあるリポジトリ
（[cypherarx-core](https://github.com/CypherArx/cypherarx-core/security/advisories/new) または
[cypherarx-gui](https://github.com/CypherArx/cypherarx-gui/security/advisories/new)）の
**Security** タブを開き、**Report a vulnerability** を選びます。報告は、メンテナーにだけ
見えます。

次のことが書いてあると助かります。

- どのリポジトリの、どのコミットを見たか
- 攻撃者に何が必要か（金庫のファイル、同じユーザーのアカウント、物理的な接触など）
- 攻撃者が何を得るか
- それを示す手順やコード（あれば）

## 報告のあと

このプロジェクトは、1 人が空いた時間に維持しています。返答までの時間は約束できません。
報告は読みます。受け付けるかどうかと、直したときはどのコミットで直したかを、報告した方に
伝えます。

## 分かっている限界

暗号の設計の文書に、守らないものを挙げてあります（金庫を開いている間に同じユーザーで動く
ソフトウェア、弱いマスターパスワード、ファイルの巻き戻しなど）。
[docs/crypto.ja.md](https://github.com/CypherArx/cypherarx-core/blob/main/docs/crypto.ja.md) を
参照してください。そこに挙げたことの言い直しは脆弱性ではありません。設計が「守る」と述べて
いることを守れていないと示す報告は、脆弱性です。
