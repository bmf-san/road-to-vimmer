# Lesson 9
## コマンド
:s/thee/the カーソルのある行で最初に見つかったワードを置換
:s/thee/the/g カーソルのある行全体で見つかったワードを置換
:1,100s/thee/the/g 1から100行目内で見つかった全てのワードを置換
:%s/thee/the/g ファイル全体から見つかったワードを全て置換
:%s/thee/the/gc ファイル全体から見つかったワードを確認しながら全て置換

## 練習
次のテキストの誤りを修正しなさい
atommerはvimmerに変えなさい。

私を名前はatommerです。
atommerを好きです。
将来がatommerになりたいです。
atommerが尊いです。

## 答え
私を名前はatommerです。
atommerを好きです。
将来がatommerになりたいです。
atommerが尊いです。
