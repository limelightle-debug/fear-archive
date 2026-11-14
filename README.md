# fear-archive

恐怖新聞（limelightle-debug/fear-index）の過去号。出てから半年のあいだ保管する。

- `index.json`：号の一覧（新しい順）
- `<id>.json`：その号が読んだデータ一式
- `img/<id>.jpg`：その号の紙面の画像（`.t.jpg` は一覧の小さい画像）
- `series/`：長い履歴の古い行の蓄積

`.github/workflows/archive.yml` が15分おきに新しい号を見つけて保管し、半年を過ぎた号を消す。
このリポジトリはいつも1つのコミットだけを持つ（毎回作り直して force push する）ので、履歴で重くならない。
