# GitHubForSTM32
 作成したSTM32nucleoF446REのプログラムを置く。まだ練習バージョンである。
 STM32は初心者、gitHubは超初心者です。
 STM32の開発結果をGitHubに記録するために始めた。
 修正履歴が残せて便利と思ったが、例えばbildでのERROR表示など余計なファイルがたくさん発生した。
 このため、.gitignoreで除外するも、適切な除外ファイル判定が不明なので、最終ファイルのみを置くことにした。
 /*ネット上では.gitignoreのリストはあるので行える。ただし現状では興味ない*/
 
push_print
blueBottonを押すと、prinfコマンドで押した回数をプリント出力する。
出力先は、teraTermである。BlackBottonを押すとリセットされる。
割込み処理と、デバックの時役立つと思いprintf出力を行った。

