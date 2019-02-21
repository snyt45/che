# che
Call your multiple cheat sheets from the command line anytime and anywhere to become a cheetah.

![cheetah](https://user-images.githubusercontent.com/18102695/53196507-97e80580-365b-11e9-90a5-2f53fb07f882.jpg)

## Why che?
Why `cheetah`? Too long

`cheeta` is still long

`cheet` easy to understand, but still long

`chee` long

`che` It is just right for me

## Description
ターミナル上でチートシート(.txt)を開く､削除､追加の3つの機能が簡単に使えます｡

## Demo
30秒以内に収めたい｡
★che
 vimとマークダウンとMacと削除用(test)のチートシートを用意｡
 vimのチートーシートを開き､コマンドを確認する
 そのときに､新しく覚えたコマンドを入力し､保存後に閉じる｡

che add
 新しくチートシートを追加したいときに使う｡
 slackのコマンドを追加したい｡
 slackのチートを追加し､新しく覚えたコマンドを入力し､保存後に閉じる

che delete
 不要になったチートシート(test)を削除する｡
 削除後､もう一度openで確認する｡

## Usage
cheはコマンドラインから実行されます｡

che
che add
che delete

開くファイルは､ただのテキストファイルなので見やすいように煮るなり焼くなりしてください｡

## DIRECTORY STRUCTURES
~/<br>
└ dotfiles/ # ユーザーの設定ファイル<br>
　　└ cheatsheets/ # チートシート一覧

## Install
使用前に､チートシートを管理するディレクトリとシェルスクリプトを管理するディレクトリが必要です｡
シェルスクリプトを管理するディレクトリはパスを通す必要があります(パスが通っている場所にcheを置けばどこからでも動作します) ｡

どこでも良いので､シェルスクリプト置き場にダウンロード（おすすめの管理ディレクトリは､~/bin/）｡
$ git clone 

上記のシェルスクリプト置き場をサーチパスに追加
$ PATH

## Licence

[MIT](https://github.com/snyt45/che/blob/master/LICENSE)

## Author

[Yuta Sano](https://github.com/snyt45)

## inspire

[mattn/cho](https://github.com/mattn/cho)
