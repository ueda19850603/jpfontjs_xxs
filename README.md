# Vertial File System in pdfmake

> このプログラムはttfフォントデータを、PDFMakeで扱えるようにjs化したものです。
非常に少ない範囲の文字しか含んでいません。小学生レベル

主に無料プランなど制限付きとして提供します

このフォントデータはIPAフォントを利用しています
https://ipafont.ipa.go.jp/old/ipafont/download.html

IPAフォントをPDFMakeによってコンバートし、膨大な文字コードから、サブセットデータだけ抜き出しています。
サブセットに含まれる文字はsubset.txtを参照してください

> 使い方
yarn add ueda19850603/jpfontjs_xs
