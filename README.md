tabulize ～from Excel to latex table～
====

tabulizeは，Microsoft Excelで作成した表をlatexのtable環境の書式に変換するExcel VBA関数です。

## インストール

1. 好きなディレクトリにクローンします。(C\Users\<ユーザー名>\AppData\Roaming\Microsoft\AddIns がおすすめ)
2. Excelを起動し，「ファイル」タブ→左下の「オプション」をクリック→「アドイン」タブ→下のほうにある「管理」ドロップダウンメニューがExcel アドインになっていることを確認して「設定」をクリック
3. 「参照」をクリック→クローンしたリポジトリ内のlatextools.xlamを開く
4. 「Latextools」のチェックボックスにチェックを入れる

## 使い方
```
=tabulize(A1:C5)
```
のようにセルに書き込むと，そのセルに`A1:C5`の表をlatexの表に変換した文字列が入ります。

これをlatexのコードにコピペするだけでOK。

