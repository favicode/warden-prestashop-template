# warden-prestashop-template

Wordpress environment is used since it's closest to Prestashop by default,
so it's easier then creating custom Warden environment.

Default MySQL db/user/password is all "prestashop".

Admin folder is fixed to /admin/ so rename the folder if needed.

If you want different admin url/folder, change here and reboot Warden:

https://github.com/favicode/warden-prestashop-template/blob/master/.warden/nginx/prestashop.conf#L62

