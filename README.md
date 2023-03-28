# testweb
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://atama026huang.github.io/testweb/index.html$1 [R,L]
