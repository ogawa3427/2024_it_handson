# IT班体験会
このREADMEを読むことでサイト制作に関する一通りの手順が学べます。
## 目次
### [1_始めに](#1-始めに)
### [2_環境構築](#2-環境構築)
### [3_HTMLについて](#3-HTMLについて)
### [4_CSSについて](#4-CSSについて)
### [5_JavaScriptについて](#5-JavaScriptについて)
### [6_実際にページを作ってみよう](#6-実際にページを作ってみよう)
### [7_作ったページを公開してみよう](#7-作ったページを公開してみよう)
### [8_最後に](#8-最後に)
### [9_補足](#9-補足)
　　
## 1. 始めに
この体験会はHTMLもCSSも触ったことのない完全に初心者に向けたウェブサイト作成チュートリアルとなっています。既にnode.js等のフレームワークを触るくらい習熟しているような方は[補足](#9-補足)の部分だけ見ていただけるとIT班の今の環境が大体わかるのでそちらを参照してください。
## 2. 環境構築
ウェブサイトを作る時、またそれ以外の開発を行う際に主に使われている環境を構築しましょう。IT班では主にVisualStudioCode(以下VScodeと略します)というエディターを利用してコードを書いています。
>[!Note]
エディターとはコードを書くために利用するソフトウェアのことで、基本的にプログラムを書く際はエディターを利用します。<br>エディターにはコーディングを行う際に便利な機能が詰まっています。
### VSCodeのインストールとセットアップ
VScodeのインストールと初期設定の方法を説明します。
1. [このページ](https://code.visualstudio.com/download)を開きwindows用のボタンを押してインストーラをダウンロードします。
2. ダウンロードしたインストーラを実行します。
>[!Note]
「デスクトップ上にアイコンを作成する」にチェックを入れ、途中で出てくる使用許諾契約書は同意してください。<br>それ以外は触らずに次へを押してインストールは完了してください。
3. 拡張機能ボタンをクリックする。
4. 検索欄に"Japanese Language Pack for Visual Studio Code"と入力し出てきたものを選択します。
5. 選択したものをInstallします。
![Image1](/Images/tutorial1.jpg)
6. 3~5までと同じ手順で以下の三つをインストールしてください。
    - HTML CSS Support
        - 機能：CSSファイルにあるクラス定義からHTMLのクラスを入力する際に、自動補完をしてくれる。
    - HTMLHint
        - 機能：HTMLの構文チェックを行ってくれる。
    - Live Server
        - 機能：HTMLとCSSのファイルからプレビューをリアルタイムで表示してくれる。
7. VScodeを再起動してください。これで環境構築は完了です。
>[!Note]
ここまでの手順でインストールしたものは拡張機能と言ってその名の通りVScodeの機能を拡張するものでコードの補完や構文ミスを指摘してくれる機能を付ける等の拡張機能があります。今回提示したもの以外にも様々な拡張機能があるのでぜひ入れてみてください。
## 3. HTMLについて
