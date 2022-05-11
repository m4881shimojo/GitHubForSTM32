# GitHubForSTM32
 作成したSTM32nucleoF446REのプログラムを置きます。まだ練習バージョンです。
 STM32は初心者、gitHubは超初心者です。
 
 STM32の開発結果をGitHubに記録するために始めました。
 修正履歴が残せて便利と思ったのですが、例えばbuildでのERROR表示など余計なファイルがたくさん発生しました。
 そこで、.gitignoreで除外しましたが適切な除外ファイルか否かの判断は初心者には困難です。
 このため、最終ファイルのみを置くことにしました。 
(ネット上では.gitignoreのリストはありますが、現状では使いません)
 
push_print
blueBottonを押すと、prinfコマンドで押した回数をプリント出力する。
出力先は、teraTermである。BlackBottonを押すとリセットされる。
割込み処理と、(デバックの時役立つと思い)printf出力を行う。
詳細はpush_Printf_Readme.pdfを参照してください。
