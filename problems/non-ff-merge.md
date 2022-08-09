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
