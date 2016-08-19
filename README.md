# XLS2NSF

## 機能

- エクセルシートファイル（\*.xls / \*.xlsx）をノーツデータベース(\*.nsf）に変換します。

## 仕様

- エクセルファイル内の１シートを、ノーツの１つのビューとして変換します（複数シートに対応しています）。

- エクセル内の数式には未対応です（式言語によって表示されている値は、その値を持つセルとして変換します）。

- 各シートの A1 列にはデータが含まれている必要があります。また１行目を B 列、C 列と順に調べてデータが含まれていなくなる列までを変換対象とします（例えば１行目は D1 セルまでデータが含まれて E1 セルで初めてデータが空だった場合、２行目以降も D 列までを対象に変換します）。

- 同様に A 列を２行目、３行目と順に調べて、データが含まれていなくなるセルの行までを変換対象とします。

- 変換後、ノーツのビュー画面から直接値を編集することができます。

- ノーツクライアントが必要です。

## 準備

- あらかじめテンプレートファイル（xls2nsf.ntf）をノーツクライアントのデータディレクトリに保存してください。

- その後、プログラムファイル（xls2nsf.nsf）をノーツクライアントから開いて使ってください。


## 使い方

- プログラムファイルを開くと「XLS2NSF の使い方」ページが表示されます。同ページ内のボタンをクリックして、変換するエクセルシートファイルを指定するだけです。

- 変換に成功すると、ワークスペース上に指定したファイル名を持つノーツデータベースが新規に作成されるので、それを開いて内容を確認してください。

## Copyright

- 2016 dotnsf@gmail.com(c) all rights reserved.


