# 早送りマージ

## 準備

リポジトリをクローンしたあと、`practice`ブランチをチェックアウトして作成してください。

```bash
git clone git@github.com:tekihei2317/git-problems_ff-merge.git
git checkout practice
```

## 問題

gitのmergeコマンドを使って、以下のようなコミットグラフを作成してください。

```text
$ git log --graph --oneline
* 62bc92c (HEAD -> main, practice) commit3
* 5d880f6 commit2
* 1029658 (origin/practice, origin/main, origin/HEAD) first commit
```

![](https://i.gyazo.com/5c9085de938782ed25545b0ae110c39d.png)

## 正答条件

- グラフの形とコミットメッセージが正解と同じこと
- `main`ブランチがcommit3を指していること
- `practice`ブランチがcommit3を指していること
