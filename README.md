# eng — エンジニアの英語定型フレーズ集

エンジニアが**毎日のように使う英語の定型文**を、
コピペで使えて・何度も音読できる形でまとめたリポジトリです。

- 📋 **コピペ用**：英文はコードブロックに入っているので、右上のコピーボタンでそのまま AI やチャットに貼れる
- 🔗 **リンキング**：音のつながり・脱落を記号で表示（[記号の読み方](#記号の読み方)）
- 🔁 **反復**：1フレーズ = 1ブロック。上から順に音読・シャドーイングできる

## 目次

| # | カテゴリ | ファイル |
|---|---|---|
| 1 | テスト・lint・フォーマッターを回す | [phrases/01-run-checks.md](phrases/01-run-checks.md) |
| 2 | AI（Claude など）への指示 | [phrases/02-ai-prompts.md](phrases/02-ai-prompts.md) |
| 3 | デバッグ・不具合調査 | [phrases/03-debugging.md](phrases/03-debugging.md) |
| 4 | Git・プルリクエスト・レビュー | [phrases/04-git-and-pr.md](phrases/04-git-and-pr.md) |
| 5 | 朝会・ミーティング | [phrases/05-meetings.md](phrases/05-meetings.md) |

- 📘 [リンキングのルール一覧](guides/linking-rules.md)
- 🔁 [練習メニュー（毎日の回し方）](guides/practice-routine.md)
- ✏️ [新しいフレーズを追加するときのテンプレート](guides/phrase-template.md)

## 記号の読み方

| 記号 | 意味 | 例 | 聞こえ方 |
|---|---|---|---|
| `‿` | 前後の音がつながる | `check‿it‿out` | チェキラウ(ト) |
| `(t)` | その音はほぼ消える | `jus(t) fix` | ジャス フィックス |
| `[d]` | t がやわらかい d / ラ行っぽくなる（フラップ T） | `ge[d]‿it` | ゲリッ(ト) |
| `[n]` | nt の t が消えて n だけ残る | `wa[n]‿to` | ワナ |

- カタカナは**リズムの目安**です。正確な音は AI や辞書の音声で確認してください。
- アメリカ英語寄りの発音で表記しています。

## AI に聞くときのコピペ用プロンプト

フレーズを貼り付ける前に、下のどれかを一緒に送ると練習になります。

```text
Check the linking and pronunciation of this sentence. Show where the sounds connect, which sounds drop, and which words are stressed. Answer in Japanese.
```

```text
Give me 5 natural variations of this sentence that an engineer would actually say at work. Keep them short.
```

```text
Quiz me. Show me the Japanese meaning one by one, and I'll answer in English. Correct my answer each time.
```

```text
Is this sentence natural for a message to a coworker on Slack? If not, rewrite it and explain why in Japanese.
```
