# GitHub 運用テスト

<details open><summary>主なコマンド</summary>

## リポジトリをクローン
```
git clone {リポジトリのurl}
```
<br>

## 作業ブランチを作って切り替え
```
git checkout -b {作りたいブランチ名（feature/xxxx）}
```

- ブランチ作成だけ
```
git branch {作りたいブランチ名（feature/xxxx）}
``` 

- ブランチの切り替え
```
git checkout {作りたいブランチ名（feature/xxxx）}
```

- 作業ブランチの確認
```
git branch
```

## リポジトリの変更を取り込む
```
git pull origin {リモートブランチ名}
```
<br>

## ファイル編集後
編集内容を確認
```
git status
```
<br>

変更を反映
```
git add {変更を反映させたいファイル名}
git commit -m "コミットメッセージ"
git push origin {変更を反映させたいリモートブランチ名}
```
</details>

# GitHub Flow
今回使うブランチ戦略。**Pull Request**を使う
<br>

* `main`ブランチ
    安定ブランチ。常にリリース可能なソースコードを管理。    

* `develop`ブランチ
	`main`ブランチから派生したブランチ。開発中の各ブランチの`merge`先。

* `feature/xxxx`ブランチ
    開発する機能に応じて作成。（xxxx: 開発する機能の内容）


# 運用テスト


