# kifuwarabe-collection

ただのメモ書きだぜ☆（＾～＾）

## 2014-11 KifuWarabe_DenouT2Ver

一番古い記録。 Git hub には上げてない。  

[同人サークル ぐれーすけーる ホームページ 将棋のページ](http://grayscale.iza-yoi.net/shogi/index.html)  
[Vector きふわらべ](https://www.vector.co.jp/soft/winnt/game/se508364.html)  

ログ・ファイルを消すコードも書いているが、消えている様子はない……☆（＾～＾）  
1対局するたびに ログ・ファイルが 1MB 以上増えていくのは 改修したい……☆（＾～＾）  

## 2015-05 KifuWarabe_v1.14

[Vector きふわらべ 第25回世界コンピュータ将棋選手権版](https://www.vector.co.jp/soft/dl/winnt/game/se510115.html)  

## 201511-SDT-Kifuwarakaku (Kifuwarabe_DenouT3)

いわゆる うそ学習きふわらべ☆（＾～＾）  
usi の直後に 実行ファイルが強制終了してしまう。なぜなのか☆（＾～＾）？  

Debug でも Release でもなく、 LEARN モードでしか動かない☆（＾～＾）？  
`LEARN | Any CPU | P500_ShogiEngine`  
将棋所の連続対局で ２局目の isready に反応しない☆（＾～＾）？ 連続体局の２局目、後手なのに先に指してしまう？  

バイナリ・フォルダはソースとは別のところに分けたい☆（＾～＾）  

## Kifuwarapery

## Kifuwarabe_WCSC26

きふわらぷりー。 いわゆる きふわるべ☆（＾～＾）  

Apery-SDT3 がベースで、本来 Visual Studio ではコンパイルできないんだが、  
わたしは改造して Visual Studio で動かすようにしたらしいぜ☆（＾～＾）  

* `Kifuwarapery.exe` と同じディレクトリーに `20151105` というディレクトリーを必ず作ってください。対局開始時に その中に評価値ファイルが動的に作成されます。  
  * しかし、この部分、わたしがいじってしまったので、 30分ぐらい かかるかも知れないぜ☆（＾～＾） ファイルを生成しているようなら放置しておけだぜ☆（＾～＾）
    * でもこの自動生成は１回やれば２回目から要らないはずなんで、対局前に１回やっておけだぜ☆（＾～＾）

## Kifuwarabe_CSharp

## Kifuwarabe_Uec9_Cgfthink

## Kifuwarabe_Uec9_Cgfgoban

## CgfThink_Kifuwarabe

## Kifuwarabe_Igo_Unity_Think

## Kifuwarabe_DenouT4

Debug でも Release でもなく、 LEARN モードでしか動かない☆（＾～＾）？  
`LEARN | Any CPU | P500_ShogiEngine`  
将棋所の連続対局で ２局目の isready に反応しない☆（＾～＾）？  

バイナリ・フォルダはソースとは別のところに分けたい☆（＾～＾）  

## Kifuwarabe_Igo_UEC10

## Kifuwarabe_WCSC27

どうぶつしょうぎ（shogi34）の大会バージョン。  

## Kifuwarabe_SDT5

飛車がパタパタするだけで、うまく指せない☆（＾～＾）  
Kifuwarabe_ShogiWinConsole が本体☆（＾～＾）  

## KifuwarabeLib_ShogiRust

## rust_kifuwarabe_position

## rust_kifuwarabe_movement

## rust_kifuwarabe_movement_picker

## rust_kifuwarabe_alpha_beta_search

## rust_kifuwarabe_shogi_client

## rust_kifuwarabe_usi

## 2018-09 Kifuwarabe_Shogi2018

Rename: kifuwarabe-shogi-2018  

何に使ったのか、使ってないのか不明☆（＾～＾）  
`cargo run` の途中で 自分の GitHub からライブラリをダウンロードできないのか、  
`Blocking waiting for file lock on build directory` で止まってしまう☆（＾～＾）  

## rust_kifuwarabe_shell_visualizer

## rust_kifuwarabe_state_transition_diagram

## rust_kifuwarabe_server

## rust_kifuwarabe_shell

## rust_kifuwarabe_shogi_server

## cgfgoban109_for_kifuwarabe2018

## rust_kifuwarabe_igo2018

## rust-kifuwarabe-server-wcsc29

## shogi-kifu-converter

## 2019-05 rust-kifuwarabe-wcsc29

`rust-kifuwarabe-wcsc29-lib` が本体☆（＾～＾）  
`cargo run` の途中で 自分の GitHub からライブラリをダウンロードできないのか、  
`Blocking waiting for file lock on build directory` で止まってしまう☆（＾～＾）  

## 2019-05 rust-kifuwarabe-wcsc29-lib

## kifuwarabe-air2019

## kifuwarabe-uec11-think

## kifuwarabe-uec11-server

## kifuwarabe-uec11-jungo

## rust-kifuwarabe-uec11-client

## runtime-kifuwarabe-go-board-gui

## KifuwarabeFighter2

## Kifuwarabe-go-board-gui

## きふわらべWCSC27

## Kifuwarabe_WCSC28

動くけど 見た感じランダム指しと違いが分からん……☆（＾～＾）  

		* Agree から指さないバグがある。たまに再起動が必要？
		* `isready` をもらってから `readyok` を返してない。

## kifuwarabe-wcsc29

いわゆる大橋流きふわらべ☆（＾～＾）  
コードが作りかけなので、復旧のめど立たず。  
構想がでかすぎて 復旧の目途が立たず☆（＾～＾） 使うと初手投了する☆（＾～＾）  

こいつは入り口☆（＾～＾）  
rust-kifuwarabe-wcsc29-lib が本体☆（＾～＾）  
その他に `kifuwarabe-wcsc29-exe-config.json` という設定ファイルに、 もっと上の立場から管理するための  
マスター設定ファイル を置くディレクトリー を設定することが必要☆（＾～＾）  

`kifuwarabe-wcsc29-shared` というディレクトリーを別途作ってそこに棋譜ファイルを大量に置けだぜ☆（＾～＾）  

## rust-kifuwarabe-wcsc30-tester

## kifuwarabe-draughts

## rust-kifuwarabe-wcsc30

## kifuwarabe2020-wcsodr1

このバージョンから 強制終了する☆（＾～＾）  
こいつから派生したやつも 強制終了するぜ☆（＾～＾）  

## kifuwarabe-tic-tac-toe

## kifuwarabe-connect-four

## kifuwarabe-dynamic-programming

## kifuwarabe-shogi-entry-model

kifuwarabe2020-wcsodr1 から分岐させたやつ☆（＾～＾）  
こいつが期待の星だったんだが、探索中に強制終了するんで使えない☆（＾～＾）  

## rust-kifuwarabe-wcsc30

きふわらべ将棋WCSC30 Build No.441.  
動きはするが☆（＾～＾）  
後手の香車が後ろ向いてると思ってるので 先手のきふわらべは 後手の香車の正面に飛車打ったりする☆（＾～＾）  

エンジン設定の例:  

```plain
DepthNotToGiveUp      [    7 ]    MaxDepth        [    5 ]
MinThinkSec           [    5 ]    MaxThinkSec     [   17 ]
KomawariWeightPer1000 [ 1000 ]    ManyWaysPer1000 [ 1000 ]
PromotionWeightPer1000[ 1000 ]
```

## rust-kifuwarabe-wcsc30-tester

なんだこりゃ☆（＾～＾）  
ユニットテストか何かを作ろうとしてたんだろうが☆（＾～＾）  

## kifuwarabe-shogi-2021

2020年11月に作り始めたばかり☆（＾～＾）  

## kifuwarabe-shogi-with-lesserpyon

2020年11月に作り始めたばかり☆（＾～＾）  

## Memo

* Usagi-cchi_SDT3_Kw VS Paon-paon_WCSC27_Kw で対局始まらず。 Paon-paon_WCSC27_Kw の方がサーバーからログアウト。
* Usagi-cchi_SDT3_Kw VS Paon-paon_WCSC27_Kw で対局始まらず。 Usagi-cchi_SDT3 の方がサーバーからログアウト。
* Bow-wow_SDT4_Kw VS AobaZero で Bow-wow_SDT4_Kw の方がサーバーからログアウト。
* Gao-gao_WCSC28_kw VS Bow-wow_SDT4_Kw で Bow-wow_SDT4_Kw の方がサーバーからログアウト。 `isready` をもらってから `readyok` を返してない。
* Poppo-poppo_WCSC30_kw VS Usagi-cchi_SDT3_Kw で対局始まらず。 Usagi-cchi_SDT3_Kw の方がサーバーからログアウト。 `isready` をもらってから `readyok` を返してない。
* Paon-paon_WCSC27_Kw が `<T:END Game_Summary` のあと何もせず終了。
