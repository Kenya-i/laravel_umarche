## udemy Laravel 講座

## ダウンロード方法

git clone
git clone https://github.com/Kenya-i/laravel_umarche.git

git clone ブランチ名を指定してダウンロードする場合
git clone -b ブランチ名 https://github.com/Kenya-i/laravel_umarche.git

もしくはzipファイルでダウンロードしてください

## インストール方法



## インストール後の実施事項

画像のダミーデータは public/images フォルダ内に sample1.jpg
~sample6.jpg として保存しています。

php artisan storage:link で
storage フォルダにリンク後、

storage/app/public/products フォルダ内に
保存すると表示されます。
(products フォルダがない場合は作成してください。)

ショップの画像も表示する場合は、
storage/app/public/shops フォルダ内を作成し
画像を保存してください。
