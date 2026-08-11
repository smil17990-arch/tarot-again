# TAROT // AGAIN

絵を描かないタロット「TAROT // QUESTION」の、気分で何度でも引き直せるカジュアル版です。

「1日1問」の記録版はこちら → [TAROT // QUESTION](https://github.com/smil17990-arch/tarot-question)

original series "TAROT // QUESTION" by [無限納豆](https://note.com/vortex951)（文：Claude）

## 1日1問版との違い

|  | 1日1問版(TAROT // QUESTION) | TAROT // AGAIN(この版) |
|---|---|---|
| 抽選 | 日付固定(1日1枚) | 完全ランダム、何度でも |
| 記録 | ジャーナル保存あり | 保存なし、その場限り |
| コンセプト | 1つの問いとじっくり向き合う | 気軽にインスピレーションを得る |

同じ22枚・同じ幾何学デザインを使っていますが、「今日はこの1枚」という重みを持たせたい場合は1日1問版を、気分転換やちょっとした思考のきっかけが欲しい場合はTAROT // AGAINを使い分けてください。

## 使い方

`index.html` をブラウザで開くだけで動きます。ビルド不要。

## 機能

- ボタンを押すたびに22枚からランダムに1枚選び直す(直前と同じ札が連続しにくい調整つき)
- カードを引くと、幾何学図形 → カード名 → 日本語の問い、の順に約2.3秒かけて静かに現れる演出
- 「22の問いを見る」から大アルカナ22枚の一覧(番号・英語名・日本語の問い)を閲覧でき、各項目から直接そのカードを表示できる
- データは一切保存しない

## GitHub Pages で公開する

1. 新しいリポジトリを作成(例: `tarot-again`)
2. `index.html` と `README.md` をアップロード
3. Settings → Pages で Source を `Deploy from a branch`、Branch を `main` / `/(root)` に設定 → Save
4. `https://smil17990-arch.github.io/tarot-again/` で公開されます

## 仕組みメモ

外部API・サーバーなし、追跡なし、新規ライブラリの追加もなし。GitHub Pagesだけで完結する構成です。
