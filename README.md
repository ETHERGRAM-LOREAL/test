# eg-creators
演習用リポジトリ

## 注意事項
コミットの際は必ずコメントを残してください。
内容は任意でお任せしますが、「Gitのルール」にもあるように誰にでもわかるようなものにすること。

## 作業手順
### 1. リポジトリをクローンする
下記URLから演習課題のリポジトリをクローン。
```
https://github.com/YusunokiShogo/eg-creators.git
```
▼リポジトリ内ファイル構造
```
.
├── git_practice
│   ├── index.html
│   └── members
└── readme.md
```
<br><br>
### 2. 作業ブランチを作成
クローンが終了したら、masterブランチから新しく作業ブランチを作成。<br>
新しくブランチが作成されたこと必ず確認する。<br>
ブランチ名は下記の命名にすること。（Gitのルール「ブランチ名」を参照）
```
yymmdd_work_name ※日付はブランチ作成日
```
<br><br>
### 3. 新しいディレクトリとファイルを追加
`members` ディレクトリ直下に自分の名前のディレクトリを作成、さらにそのフォルダの中にtxtファイルを追加。<br>
ワークツリーにファイル追加の内容があることを確認したら、追加したファイルをステージしてコミット。<br>
ディレクトリ名とファイル名は下記の命名にすること。
```
▼ディレクトリ
myoji_namae ※姓と名はアンダースコアで区切る

▼ファイル
hello.txt
```
<br><br>
### 4. 追加したtxtファイルを編集 
追加したtxtファイルにテキストを追加。<br>
ワークツリーにファイル変更の内容があることを確認したら、変更したファイルをステージしてコミット。<br>
テキストは下記を追加する。
```
hello EG!
```
<br><br>
### 5. index.htmlにリンクパスを追加
`git_practice` ディレクトリ直下にある `index.html` にメンバーリストが空リンクで用意されているので、自分の名前のリンクに手順3.で追加したtxtファイルへのリンクパスを設定してください。<br>
設定後リンクが正しく飛ぶことを確認して、変更したファイルをステージしてコミット。<br>
<br>
### 6. コミットをリモートへプッシュ
コミットをリモートリポジトリへプッシュしてください。<br>
<br>
### 7. 作業ブランチをmasterブランチへマージ
作業ブランチからmasterブランチへチェックアウトしてください。<br>
チェックアウトできたら、作業ブランチをmasterブランチにマージしてください。<br>
マージできたら、マージした内容をコミットプッシュ。<br>
※マージ時にコミットコメントは自動で入るのでコメントはそのままで良いです。<br>
<br>
***
手順は以上です。<br>
不明点やコンフリクトで途中作業が進められなくなるようであれば柞木宛にチャットしてください。<br>
<br>
演習が完了したら、シートのステータスを変更してください。<br>
「質問」欄にはわからなかったことや質問があれば必ず記入すること。

