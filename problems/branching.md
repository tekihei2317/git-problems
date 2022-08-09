# ブランチの作成とコミット

## 準備

```bash
git clone git@github.com:tekihei2317/git-problems_commit.git
```

## 問題

`practice`ブランチを作成してコミットして、以下のようなコミットグラフを作成してください。

```text
$ git log --all --graph --oneline
* fd0ea24 (HEAD -> main) commit4
| * a1b7cf9 (practice) commit3
|/
* 1adc8e4 commit2
* c74468a first commit
```

## 正答条件

- グラフの形とコミットメッセージが正解と同じこと
- practiceブランチがcommit3を指していること
- mainブランチがcommit4を指していること
