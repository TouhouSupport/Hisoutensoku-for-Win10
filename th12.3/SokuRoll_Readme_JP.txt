------------------------------------------------------------------
SOKUROLL
------------------------------------------------------------------

最新版はこちら:
http://hisouten.koumakan.jp/wiki/Misc_tools#SokuRoll

コンタクト情報:
ユーザー名Fireseal をIRCchの #hisouten@irc.rizon.net で探してください. いる時間はだいたいこの辺→ 8pm UTC+1 .
もしくはこちらにメールをお願いします. SokuRoll@gmail.com



------------------------------------------------------------------
インストール方法
------------------------------------------------------------------
U非想天則をversion 1.10aにしてください.
解凍して出てきた全ファイルを非想天則フォルダのth123.exeのある場所にすべてコピーすればインストール完了です.



------------------------------------------------------------------
コンフィグ方法
------------------------------------------------------------------
SokuRoll.iniをメモ帳などで開き, 変えたい値を変更してください.
変更できる値は3つあります:
-ChangeTitle 非想天則のウィンドウバー上の名前を変更するかどうか選択できます.デフォルトで変更するようになっておりこの状態ならsokurollが正常に起動されたかどうかが分かりやすくなっています.ただし他のツールを使う場合に名前を変更していると認識しない場合があるのでそのような時はオフにして試してみてください.0でオフ　1でオン
-InitialDelay 対戦時のディレイ値を指定できます.この設定はホストのもののみが適用されます. またディレイ値は対戦中でもテンキーの+-キーを押すことで上下させることができます.
-MaximumRollback 最大ロールバック可能フレーム数を指定します. この値を大きくするとゲームが重くなり, 4より大きく設定するとプレイが困難になります.



------------------------------------------------------------------
SOKUROLLの使い方
------------------------------------------------------------------
まず普通に非想天則を起動し, 非想天則が起動している状態でSokuRollLoader.exeを起動してください.
何かエラーが発生した場合はエラーメッセージが表示され,正常に起動した場合はsokurollのウィンドウは即座に閉じられます.
なので正常な場合は起動したけど何も起こってないと思うかもしれません.

sokurollが正常に起動したかどうか確かめるには2つの手段があります:
	-もし SokuRoll.iniでChangeTitle=1にしてタイトル表示を許可しているならば, 非想天則のタイトルのversionが1.10ac+Rとなっていれば成功です.
	-もし SokuRoll.iniでChangeTitle=0にしてタイトル表示を許可していないならば, もう一度SokuRollLoader.exeを起動するとRollback already loadedと表示されたウィンドウが出れば成功です.

SokuRollLoader.exeを起動したらあとは通常通りネット対戦をプレイすればOKです.
ロールバックが発生するのはネット対戦回りのものだけとなっています.
ホストのディレイやロールバック設定が対戦時クライアントにも適用されます.

対戦中にホストはテンキーの+-を押すことでディレイ値を操作できます.
なのでホストクライアント両者ともに非想天則のコンフィグでFPSを表示するようにしておくと調整がしやすくてお勧めです.



------------------------------------------------------------------
現在同時に使えると判明しているツール,パッチ
------------------------------------------------------------------
英語化パッチ, tsk, Soku Macro, SWRSToys は動作するようです.
tskを動かすときはSokuRollLoader.exeの前に起動するか,SokuRoll.iniをChangeTitle=0としてタイトルを変更させないようにしましょう. 
他のツールでもChangeTitle=0設定でタイトル変更なしにしておいた方がいいかもしれません.



------------------------------------------------------------------
パフォーマンス
------------------------------------------------------------------
最大ロールバックフレームを高くするとプレイがどんどん快適でなくなります, なおその目安はCPUやメモリに依存します.
一部パチュリーの日月符「ロイヤルダイアモンドリング」のような大量の弾幕スペルを使用するとゲームが遅くなることがあります, 


------------------------------------------------------------------
バグ報告、コメント先
------------------------------------------------------------------
ユーザー名Fireseal をIRCchの #hisouten@irc.rizon.net で探してください. いる時間はだいたいこの辺→ 8pm UTC+1 .
もしくはこちらにメールをお願いします. SokuRoll@gmail.com




------------------------------------------------------------------
既存のバグ，問題
------------------------------------------------------------------
観戦が正常にできない場合がある


------------------------------------------------------------------
CREDITS
------------------------------------------------------------------
-Nothing Then for helping test many, many of the early versions.
-PhoenixM for helping to gather testers.
-Xia for providing hosting.
-All the beta testers for putting up with the crashes
-Mauve for showing it could be done, and his articles which provided some nice sanity checks.
-Tukiyo for translating the readme to japanese.