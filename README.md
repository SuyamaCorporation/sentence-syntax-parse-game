# 英文 構文解析 品詞ラベル付けゲーム

英文の各単語に品詞ラベルをクリックで付けるゲーム。

## 機能
- 20文収録（単純文から複雑文まで）
- 8品詞（Noun/Verb/Adjective/Adverb/Preposition/Article/Conjunction/Pronoun）
- 単語クリック → 品詞ボタンで割り当て
- 正解率・累積スコア表示
- よくある間違いパターン解説（例: "quickly" は Adverb not Adjective）
- 色分けフィードバック（正解=緑、不正解=赤+正解表示）

## 技術
- 静的SPA（単一index.html）
- Tailwind CSS CDN
- localStorage不使用
- XSS対策: textContent使用
