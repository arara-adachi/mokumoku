＃月刊とりあえず作成
<pre>
ログ
19:14 adachi : もくもく、一夜限りのコラボレーションとメールが来ていたけどpublic repository どこかに作ってあるのでしょうか？
19:17 isono : まだつくってません
19:18 isono : もくもく自分でつくってもいいのよ？
19:21 nikado(nikado@irc.tinyspeck.com) がチャットに参加しました
19:21 adachi : とりあえず空のものなら一応あるのでご自由にどうぞ
19:21 adachi : https://github.com/arara-adachi/mokumoku.git 
19:21 adachi : 自分はmacならgit最初から入ってるだろと思ったらxcode入れてねとか言われてローカルに落とすところにすら進んでませんが
19:22 nikado : forkできないのでREADMEだけつくてもらっていいですか。
19:22 isono : そこは web でやってもいいと思うけど
19:23 adachi : 作って見たけどこれで大丈夫ですかね？
19:23 nikado : forkできました
19:24 nikado : ぷるりく書いて投げるよ
19:24 isono : きたわよ
19:26 nikado : いちおうやってみてほしかったことメモ:
19:26 nikado : redmine(subversion) -> チケットみて、機能を作ってコミット、本番適用前にコードレビュー
19:26 nikado : github(git) -> チケットみて、リポジトリをclone、クローンにブランチをきってコミット、クローンのブランチを元のひとにプルリクでレビュー依頼、レビューOKならマージ
19:26 nikado : こういうちがい。
19:27 nikado : レビューで指摘があるたびにコミットする代わりに、レビューがおわったブランチをマージする、という流れ
19:29 nikado : このレビュー相手探しにユーザ名がわかっているひといると楽なので、google spreadsheetにある人を使ってもらえれば。
19:29 nikado : (ひとりでレビューしてもいいけど。accelmail は普段一人レビューばっかりだったし
19:32 adachi : レビュアーってどこで設定できるんでしょう
19:36 nikado : pull request ボタンを押したあとに reviewerってところないでしょうか。
</pre>
