# University-PL-Tiny

## status
作成期間：2019.10~2020.1　3回生秋学期

## about
京都産業大学 コンピュータ理工学部 2019年度秋 開講の「プログラミング言語」の長期課題「Tiny」を解いたプログラム。
「Tiny」はちょっぽけなプログラミング言語である。本課題では「Tiny」の開発を行った。

## program
### tiny

## 実行方法
### Makefile
Tinyプログラムはそのままだと実行できない。以下のコマンドで「src.txt」に書いたTinyプログラムを仮想マシンが実行可能なプログラム「tmp.txt」にする。

```
$make src
```

次に以下のコマンドで仮想マシンをダウンロードし、仮想マシンを起動する。仮想マシンが起動した後に「tmp.txt」を選択することでTinyプログラムを実行することが可能である。

```
$make vm
```
