# laravel-doc
Document for Settings and deployment Laravel

##インストール

#laravel
http://qiita.com/yafuu822/items/6c8c3937bfc104b66297

##AWS


##atom
インストール・パッケージ
git-plus


##Github Desktop

##Ubuntu
http://qiita.com/rakuraku0615/items/1dab3ebcaa0a720b18c4

http://qiita.com/kenichiro-yamato/items/5e04d4a0dacf940ffc6c

##SSL Let's encrypt
http://qiita.com/MashMorgan/items/56498f276c54406b1928

certbot-auto certonly --webroot -w /var/www/html -d laravel.j-code.org --email koichii@live.jp --debug

larravel 入れてると、.welknown に書き込むんで検証できない様子。一旦とめる。
laravel と共存するためには、一工夫必要。

ssl.conf が出来てなかったので、ごにょごにょやってたら、できた。
