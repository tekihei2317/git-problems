# 早送りでないマージ

## 準備

はじめに以下のリポジトリをクローンしてください。

```bash
git clone git@github.com:tekihei2317/git-problems_non-ff-merge.git
```

## 問題

gitのmergeコマンドを使って、以下のようなコミットグラフを作成してください。

```text
$ git log --all --graph --oneline
* 0fca72d (HEAD -> practice2) commit4
*   4990332 (main) commit3
|\
| * 87f630b (practice1) commit2
|/
* e513abf first commit
```

![](https://i.gyazo.com/0294723b013c522d6c89069b36342c8c.png)

## 正答条件

- グラフの形とコミットメッセージが正解と同じこと
- `practice1`ブランチがcommit2を指していること
- `main`ブランチがcommit3を指していること
- `practice2`ブランチがcommit4を指していること
