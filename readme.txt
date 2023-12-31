素早いキーボードランチャ [ CraftLaunch ]

-------------------------------------------------------
[著作者]       craftware
[連絡先]       chop@hh.iij4u.or.jp
[開発環境]     Visual C++  ver 6.0
[種別]         フリーウェア
[動作環境]     Windows95/98/NT/2000
[必要なDLL]    mfc60.dll , msvcrt.dll
[サポート]     http://hp.vector.co.jp/authors/VA012411/
-------------------------------------------------------


■ このソフトウェアについて

このソフトウェアは、キーボードだけでアプリケーションを立ちあげること
が出来る、キーボードランチャです。

Windowsをキーボード中心で操作している人にとって便利なソフトです。

    [特徴]
    ・キーボードでコマンドを打ち込むことで、アプリを実行
    ・コマンドを途中まで入力すれば、残りが補完されるので楽
    ・ファイル名も補完される
    ・入力ミスを自動的にキャンセルする設定が可能
    ・かなり自由にホットキーを設定できる（たとえばScrollLockだけでもOK）
    ・ウインドウサイズが小さく、邪魔にならない
    ・立ちあげ時以外は、ファイルアクセスをしないので、スピーディ
    ・時計や年月日表示機能がある( 書式はカスタマイズ可能 )
    ・メッセージを送って他のアプリを操作できる
    ・他のアプリを素早くアクティブにすることができる
    ・ファイラと連携して、ファイラの一部のように動作可能
    ・自由にキーアサインが可能
    ・表示フォントの設定が可能

どんなユーザ環境にも、耐えるインターフェイスを実現しています。


■ 使用例

コマンド補完機能が付いているので、[ NETSCAPE ] というコマンドにアクセス
する場合は、

    ------------------------------------------------------

   ホットキーを押す   設定したホットキーを押して、
                      CraftLaunchをアクティブに。
         ↓

        [ N ]         ユーザが最初の文字を入力すると、、、

         ↓           自動的に残りの文字が補完される

     [ NOTEPAD ]      コマンドの優先順位が高い、
        ^^^^^^        他のコマンドが補完されてしまっても、
         ↓           そのまま続けて [ E ] を入力すると、

     [ NETSCAPE ]     正しいコマンドが補完された。
         ^^^^^^
         ↓           正しければ、リターンキーを押す。

     Netscape起動     結果的に、4回のキー入力で
                      アプリケーションが立ち上がる。

    ------------------------------------------------------


■ 配布 / 保障について

・このソフトウェアを二次配布する場合は、作者に事前連絡してください。
・このソフトウェアを改造して配布してはいけません。

また、本ソフトウェアの使用によるいかなる損害も保障しかねますので、
プログラムの実行は本人の責任で行ってください。


■ ファイルとインストールについて

配布されたファイルを解凍すると以下のファイルとフォルダが作成されます。

clnch???.zip
    clnch.exe ----- ランチャ本体
    clnchcmd.exe -- コマンド設定ツール
    clnchopt.exe -- 動作オプション設定ツール
    readme.txt ---- この文書
    manual.txt ---- 説明書
    tips.txt ------ 便利な使い方集
    changes.txt --- バージョンアップ履歴


また、最初の起動で自動的に以下のファイルが作られます。

    clnch.opt ----- オプション設定データ
    clnch.cmd ----- コマンド設定データ
    clnch.his ----- コマンドの履歴


展開されたファイルを適当なフォルダにコピーしてください。
    (例) C:\ols\clnch


CraftLaunchの起動がうまくいかない場合は、最新の mfc42.dll msvcrt.dll
をインストールしてください。

http://www.vector.co.jp/soft/win95/util/se040499.html



■ アンインストール

インストールしたフォルダごと消してください。


■ サポート

詳しくはサポートホームページをご覧ください。
http://hp.vector.co.jp/authors/VA012411/
