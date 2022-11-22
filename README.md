
# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
リモートリポジトリ：ネット上に配置して複数人で共有するためのリポジトリ。
ローカルリポジトリ：開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ。


## プッシュとマージの違いは何でしょうか？
push:該当のブランチに対して変更を反映させる
merge:各ブランチをメインに運用するブランチへ反映させる


## コミットとプッシュの違い
commit：ローカルリポジトリに変更を反映させること
push：リモートリポジトリに変更を反映させること


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
一目で変更内容がわかるようにする


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
プルリクエストでマージをする際はは他人からのコードレビューを挟み、バグなどの発生を抑える


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
・先にマージされた変更内容を取り込む
・後にマージしようとしている変更内容を取り込む
・どちらの変更内容も取り込む