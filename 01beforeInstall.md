laravelのインストールのためにmacにphpとcomposerがインストールされている必要がある
<br>
そのためターミナルにてインストールされているか確認
<br>
<br>
php -v
<br>
composer -v
<br>
<br>
二つのコマンドを実行し、バージョンが表示されればlaravelのインストールが実行できる
<br>
command not found が出た場合はインストールしてないか、PATHを通してない場合がある。以下で対応
<br>
<br>
php
<br>
当方ではphpの学習の際、mampを使用したので、mampに標準でインストールされているphpにPATHを通すことにする
<br>
また、使用するlaravelのバージョンによって対応しているphpも異なるのでこちらについても要チェック
<br>
/Applications/MAMP/bin/php/php＋使用するバージョンのフォルダまで持っていく
<br>
binフォルダ内ののphpと書いてあるunix実行ファイルと書いてあるところまでPATHをコピー。
<br>
隠しファイルのzprofileを開き、（ない場合は作成。）export PATH=コピーしたPATH/bin:$PATHで通せる
<br>
例）export PATH=/Applications/MAMP/bin/php/php7.3.29/bin:$PATH
<br>
ターミナルを再起動し、php -vを実行。バージョン名が表示されれば完了
<br>
<br>
composerを使うにはphpが必須なのでphpがインストールされていることを確認する。
<br>
composerのインストールはいくつかあるが今回はhomebrewを用いてインストールする
<br>
<br>
homebrewのインストール
<br>
homebrewの公式ページからスクリプトをコピー。ターミナルに貼り付け、インストール開始。
<br>
pcによってはパスが通ってない場合があり、インストールの最後にwarningかエラーを吐く場合がある。落ち着いてnext　stepを参照し、パスを通す
<br>
brew -vでバージョンが表示されたら完了
