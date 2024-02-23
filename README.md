In  Ci4 the index file is in public folder where also find .htaccess file
if you using xampp server
1) go to ci4 folder ->app ->config- > app file  see
2) public string $baseURL = 'http://localhost/ci4';
3) then go to url type  http://localhost/ci4
4) if it is showing error like (opps somthing ,..)
5) then open xampp server -> config->php.ini file and type
6)  extension=intl
7)  save the php ini file rerun apache server ...it will work
   
