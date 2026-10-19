# 01. テスト・lint・フォーマッターを回す

[← 目次に戻る](../README.md)

開発リポジトリで「チェック系コマンドを探して、実行して、直す」ときの定型。

---

## 1-1. テスト・lint・フォーマッターを探して実行して直して

```text
Find the commands for tests, lint, and formatting in this repo. Run them, and fix any issues.
```

- 🔗 `Fin(d) the commands for tes(ts), lin(t), an(d) forma[d]ing‿in this repo. Run‿them, an(d) fix‿any‿issues.`
- 🗣 ファイン ザ カマンズ ファ テス、リン、アン フォーマリンギン ディス リーポウ。ラネム、アン フィクセニー イシューズ
- 💡 `them` は弱く `'em`（エム）になり、`Run‿'em` = ラネム。

## 1-2. テストを実行して、何が落ちたか教えて

```text
Run the tests and tell me what fails.
```

- 🔗 `Run the tes(ts)‿an(d) tell me wha(t) fails.`
- 🗣 ラン ザ テスツン テルミー ワッ フェイルズ

## 1-3. lint が通るか確認してくれる？

```text
Can you check if the lint passes?
```

- 🔗 `Can‿you check‿if the lint passes?`
- 🗣 キャニュ チェキフ ザ リン パスィズ

## 1-4. コミット前にフォーマッターをかけよう

```text
Let's run the formatter before we commit.
```

- 🔗 `Le(t)'s run the forma[d]er before we commi(t).`
- 🗣 レッツ ラン ザ フォーマラー ビフォー ウィ カミッ

## 1-5. ローカルでビルドが通ることを確認して

```text
Make sure the build passes locally.
```

- 🔗 `Make sure the buil(d) passes locally.`
- 🗣 メイク シュア ザ ビル パスィズ ロウカリー

## 1-6. 自分の環境では通るのに CI で落ちる

```text
The tests pass on my machine, but they fail in CI.
```

- 🔗 `The tes(ts) pass‿on my machine, bu(t) they fail‿in C‿I.`
- 🗣 ザ テス パソン マイ マシーン、バッ ゼイ フェイリン スィーアイ

## 1-7. 全部まとめて実行できるコマンドはある？

```text
Is there a single command that runs everything?
```

- 🔗 `Is‿there‿a single command tha(t) runs‿everything?`
- 🗣 イズゼアラ スィングル カマンド ザッ ランゼヴリスィン

## 1-8. 挙動は変えずに、lint エラーだけ直して

```text
Don't change the behavior. Just fix the lint errors.
```

- 🔗 `Don'(t) change the behavior. Jus(t) fix the lint‿errors.`
- 🗣 ドウン チェインジ ザ ビヘイヴィア。ジャス フィックス ザ リンテラーズ
- 💡 `lint‿errors` は t が次の母音とつながるので消えない。

## 1-9. バグを再現するテストを追加して

```text
Add a test that reproduces the bug.
```

- 🔗 `Add‿a tes(t) tha(t) reproduces the bug.`
- 🗣 アダ テス ザッ リプロデュースィズ ザ バグ

## 1-10. 落ちているテストだけ実行して

```text
Run only the failing test.
```

- 🔗 `Run‿only the failing test.`
- 🗣 ラノウンリー ザ フェイリン テスト

## 1-11. 警告は出るけど、エラーはない

```text
There are some warnings, but no errors.
```

- 🔗 `There‿are some warnings, bu(t) no‿errors.`
- 🗣 ゼアラー サム ウォーニングズ、バッ ノウエラーズ

## 1-12. 全部通った。テスト・lint・フォーマット、全部グリーン

```text
Everything passes. Tests, lint, and formatting are all green.
```

- 🔗 `Everything passes. Tes(ts), lin(t), an(d) forma[d]ing‿are‿all green.`
- 🗣 エヴリスィン パスィズ。テス、リン、アン フォーマリンガロール グリーン
