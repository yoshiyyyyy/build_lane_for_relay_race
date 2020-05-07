Name: リレーのレーン決めスクリプト
====


## Overview: Excelのデータを入出力するスクリプトです。高校で陸上の顧問をやっている義兄のリクエストで、神奈川県内の親善試合用に作成しました。今までは各校の先生が名前とタイムを書いた紙を持参してみんなで集まってレーン决めをしていたとのことで、時間も労力もかかって大変だったみたい。スクリプトなら1クリック、さらばヒューマンエラー。

## Description:　Excelにシートを２つ用意。sheet1には生徒の名前と50m走のタイムを入力しておき、sheet2は出力ファイルのため無記入。今回は8レーンを想定し、50mのタイムの早い生徒から4,5,3,6,2,7,1,8の順に"氏名と50m走のタイム"を配置していきます。配置する総生徒数に応じて7レーンの組も出力されます。

## Demo:　※sheet1の氏名は架空のものです。タイムも数字の大小だけ比較したかったのでテキトーです。

<img width="166" alt="スクリーンショット 2020-05-07 11 40 44" src="https://user-images.githubusercontent.com/48376024/81249156-ed3de600-9058-11ea-9b61-c427fc625782.png">
<img width="953" alt="スクリーンショット 2020-05-07 11 40 30" src="https://user-images.githubusercontent.com/48376024/81249239-2a09dd00-9059-11ea-86e0-290ed1a55992.png">




## Requirement
Python 3.8.2
pip 19.2.3

## Usage

①BuildLane.pyと同じディレクトリにNewLane.xlsxを用意。
②NewLane.pyにsheet2を追加。seet1には氏名とタイムを記入。
③BuildLane.pyのコメントアウトにあるように、sheet1の対象とするセルの範囲に合わせて"B255"の数字を調整。
④実行。


## Licence
https://github.com/yoshiyyyyy//blob/master/LICENSE

## Author
[yoshiyyyyy] https://github.com/yoshiyyyyy/


