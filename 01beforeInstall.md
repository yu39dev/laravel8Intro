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

composer
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
<br>
<br>
homebrewがインストールされていることを確認したら
<br>
brew install composer
<br>
を実行し、composerをインストール
<br>
composer -v
<br>
を実行し、バージョンが表示されれば完了
