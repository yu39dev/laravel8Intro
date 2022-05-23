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
隠しファイルのzprofileを開き、（ない場合は作成）
<br>
export PATH=コピーしたPATH/bin:$PATH
<br>
で通せる
<br>
例）export PATH=/Applications/MAMP/bin/php/php7.3.29/bin:$PATH
<br>
ターミナルを再起動し、php -vを実行。バージョン名が表示されれば完了
<br>
<br>
