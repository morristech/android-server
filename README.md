# Servers for Android
Servers running natively on Android. Currently project consists of applications which are free, without ads, stable and pure:

Server for PHP (PHP), download: https://play.google.com/store/apps/details?id=com.esminis.server.php
MariaDB Server (MariaDB), download: https://play.google.com/store/apps/details?id=com.esminis.server.mariadb
moNERIngAo Server (MongoDB), download: https://play.google.com/store/apps/details?id=com.esminis.server.mongodb
HTTP Server powered by Apache (Apache HTTP), download: https://play.google.com/store/apps/details?id=com.esminis.server.apache
More to come...
Official Facebook page: https://www.facebook.com/esminis.server

Features - common to all server apps
Switch server version and build any time you want (you can download install package to switch server version offline)
Server log, with possibility to export it
Configuration options:
Network (IPv4 and IPv6 are supported):
Interface / address - wlan, lo, all, ...
Server port - 1024+
Data directory - contains document root, config, ... (depending on server)
Start server on Android device boot
Notifications:
Enable notification - show it when server is running
Use low priority notification (usually it will be visible only in drawer)
External intents - control servers from other applications with Android Intents
Multilingual interface - English, Spanish, Portuguese (Brazilian), French, German, Russian, Chinese, Hindi, Bengali, ... translations supplied by community
Stable, pure, free and without ads
Author
Tautvydas Andrikys https://esminis.com

License
Source code is licensed under the Apache License, Version 2.0 You may obtain a copy of the License at: http://www.apache.org/licenses/LICENSE-2.0

Server for PHP
PHP server for Android

Features
PHP 5.4+, 7+
php.ini - is in path [document root]/config/php.ini and you can modify it as you want
Configuration optionsDocument root/
PHP extensions - most of them can be enabled/disabled any time you want
Router script
PHP extensions (configurable - can be enabled/disabled)
apcu - APCu
bbcode - BBCode
bcmath - BC Math
bz2 - Bzip 2
calendar - Calendar
ctype - Ctype
dba - DBA
eio - Eio
ev - Ev
exif - EXIF
fileinfo - Fileinfo
ftp - FTP
gd - GD
gender - Gender
gettext - Gettext
gmp - GMP
recode - GNU Recode
iconv - iconv
id3 - ID3
imagick - ImageMagick
inotify - Inotify
judy - Judy Arrays
ldap - LDAP
lzf - LZF
mailparse - Mailparse
mcrypt - Mcrypt
mongodb - MongoDB driver
mysql - Mysql
mysqli - Mysqli
oauth - OAuth
odbc - ODBC
zend_opcache - OPcache
pdo_mysql - PDO MySQL
pdo_odbc - PDO ODBC
pdo_pgsql - PDO PostgreSQL
phalcon - Phalcon
phar - Phar
posix - POSIX
pgsql - PostgreSQL
pspell - Pspell
quickhash - Quickhash
rar - RAR
rpmreader - RPM Reader
soap - SOAP
spl_types - SPL Types
ssh2 - SSH 2
stats - Statistics
tidy - Tidy
tokenizer - Tokenizer
uopz - User operations for Zend
weakref - Weakref
xdebug - Xdebug
xdiff - XDiff
xmldiff - XMLDiff
xsl - XSL
yaf - Yet Another Framework
yar - Yet another RPC framework
yaml - YAML
zip - ZIP
zlib - Zlib
PHP extensions (built-in - cannot be disabled)
cli_server - SAPI CLI
core - Core
curl - cURL
date - Date/Time
dom - DOM
ereg - POSIX Regex
filter - Filter
hash - Hash and Mhash
intl - Intl
json - JSON
libxml - LibXml
mbstring - MBString
mysqlnd - Mysqlnd
openssl - OpenSSL
pcre - PCRE
pdo - PDO
pdo_sqlite - PDO Sqlite
reflection - Reflection
session - Session
simplexml - SimpleXML
sockets - Sockets
spl - SPL
sqlite3 - SQLite3
standard - Standard
wddx - WDDX
xml - XML
xmlreader - XML Reader
xmlrpc - XML-RPC
xmlwriter - XML Writer
How to
PHP - connect to MariaDB Server using Adminer

MariaDB Server
MariaDB server for Android

Features
MariaDB 10+
my.cnf - is in path [data directory]/my.cnf and you can modify it as you want
moNERIngAo Server
MongoDB server for Android

Features
MongoDB 2.6+
mongod.cnf - is in path [data directory]/mongod.cnf and you can modify it as you want
How to
MongoDB - Create root user

HTTP Server powered by Apache
Apache HTTP server for Android

Features
Apache 2.2+
httpd.conf - is in path [data directory]/conf/httpd.conf
How to
Apache HTTP - PHP as CGI
Apache HTTP - HTTPS with SSL

Source code
Apps were open source recently, but due to some angry comments (received on reddit) access to source code was closed.

In future access to source code might be reopened - still deciding about this.

! Possibility of Servers for Android getting banned on Play Store
Due to recent changes in Google Developer Policy apps can get banned in near future, quote of important addition:

https://play.google.com/about/privacy-security/malicious-behavior/

The following are explicitly prohibited: 

Apps or SDKs that download executable code, such as dex files or native code, from a source other than Google Play
This is a problem because binaries of servers are downloaded not from Play Store (Google does not provide functionality to download binaries from Play Store).

Solution to this issue is that in next release one or more server versions will be bundled with APK, with possibility to download other versions. This means that app size will greatly increase and might reach 100 Mb. This solution means that there is possibility of application getting banned by Google - in such case ability to download binaries will be removed.
