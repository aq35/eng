# 02. AI（Claude など）への指示

[← 目次に戻る](../README.md)

AI コーディングアシスタントにそのまま貼れる指示文。
声に出して読む練習にも使える短さにしています。

---

## 2-1. ⭐ テスト・lint・フォーマッターを探して、実行して、ズレや不具合を直して

日本語の元の指示：
> 開発のリポジトリでは、テストコードの実行コマンド、lint、フォーマッターが実行できるはず。探して、実行して、ズレや不具合ないか調べて、直して。

```text
This repo should have commands for running tests, lint, and the formatter. Find them, run them, check for anything that's off or broken, and fix it.
```

チャンク（区切り）ごとに練習：

| 英語 | 🔗 リンキング | 🗣 カタカナ |
|---|---|---|
| This repo should have commands | `This repo shoul(d)‿have commands` | ディス リーポウ シュダヴ カマンズ |
| for running tests, lint, and the formatter. | `fer running tes(ts), lin(t), an(d) the forma[d]er.` | ファ ラニン テス、リン、アン ザ フォーマラー |
| Find them, run them, | `Fin(d)‿them, run‿them,` | ファインデム、ラネム |
| check for anything that's off or broken, | `check fer‿anything tha(t)'s‿off‿or broken,` | チェック ファレニスィン ザッツォフォア ブロウクン |
| and fix it. | `an(d) fix‿it.` | アン フィクシッ |

- 💡 `should have` は「シュダヴ」。`should've` と縮めて言うことが多い。
- 💡 `that's off` = 「なんかズレてる・おかしい」の口語。`inconsistent` より軽く言える。

## 2-2. まだ何も変えないで。先に計画を教えて

```text
Don't change anything yet. Just tell me your plan first.
```

- 🔗 `Don'(t) change‿anything ye(t). Jus(t) tell me your plan first.`
- 🗣 ドウン チェインジェニスィン イェッ。ジャス テルミー ユア プラン ファースト

## 2-3. コードベースを読んで、どう動いているか説明して

```text
Read the codebase and explain how it works.
```

- 🔗 `Rea(d) the codebase‿an(d)‿explain how‿it works.`
- 🗣 リー ザ コウドベイサネクスプレイン ハウイッ ワークス

## 2-4. 変更は最小限にして

```text
Keep the change minimal.
```

- 🔗 `Kee(p) the change minimal.`
- 🗣 キー ザ チェインジ ミニマル

## 2-5. なぜこうなったのか説明して

```text
Explain why this happened.
```

- 🔗 `Explain why this happened.`
- 🗣 イクスプレイン ワイ ディス ハプンド

## 2-6. この関数のテストを書いてくれる？

```text
Can you write tests for this function?
```

- 🔗 `Can‿you wri(te) tes(ts) fer this function?`
- 🗣 キャニュ ライ テス ファ ディス ファンクション

## 2-7. 読みやすくなるようにリファクタして

```text
Refactor this to make it easier to read.
```

- 🔗 `Refactor this to make‿it‿easier to read.`
- 🗣 リファクター ディス トゥ メイキリーズィア トゥ リード

## 2-8. 見落としているエッジケースがないか確認して

```text
Check if there are any edge cases I missed.
```

- 🔗 `Check‿if there‿are‿any‿edge cases I missed.`
- 🗣 チェキフ ゼアラレニエッジ ケイスィズ アイ ミスト

## 2-9. 何を変更したかまとめて

```text
Summarize what you changed.
```

- 🔗 `Summarize wha(t)‿you changed.`
- 🗣 サマライズ ワッチュ チェインジド
- 💡 `what you` → t + y で「チュ」に変わる（ワッチュ）。

## 2-10. コミットしてプルリクエストを作って

```text
Commit it and open a pull request.
```

- 🔗 `Commi[d]‿it‿an(d)‿open‿a pull request.`
- 🗣 カミリッ アノウプナ プル リクエスト

## 2-11. わからなければ推測せずに聞いて

```text
If you're not sure, ask me instead of guessing.
```

- 🔗 `If you're no(t) sure, ask me‿instead‿of guessing.`
- 🗣 イフ ユア ナッ シュア、アスク ミー インステッダヴ ゲスィン

## 2-12. もう一度実行して、全部通るか確認して

```text
Run it again and make sure everything passes.
```

- 🔗 `Run‿it‿again‿an(d) make sure‿everything passes.`
- 🗣 ラニラゲン アン メイク シュアレヴリスィン パスィズ
