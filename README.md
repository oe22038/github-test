# GitHub 運用テスト
例えとして、弁当を作ってみます

<details><summary>主なコマンド</summary>

#### リポジトリをクローン
```
git clone {リポジトリのurl}
```

#### 作業ブランチを作って切り替え
```
git checkout -b {作りたいブランチ名（feature/xxxx）}
```
- ブランチ作成だけ
    `git branch {作りたいブランチ名（feature/xxxx）}`
- ブランチの切り替え：
    `git chekuout {作りたいブランチ名（feature/xxxx）}`

</details>

## GitHub Flow
今回使うブランチ戦略。**Pull Request**を使う

* `main`ブランチ
    安定ブランチ。常にリリース可能なソースコードを管理。    

* `develop`ブランチ
	`main`ブランチから派生したブランチ。開発中の各ブランチの`merge`先。

* `feature/xxxx`ブランチ
    開発する機能に応じて作成。（xxxx: 開発する機能の内容）

## 運用テスト