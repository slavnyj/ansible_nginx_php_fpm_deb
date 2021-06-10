# ansible_nginx_php_fpm_deb
### Ansible roles for install Nginx with PHP-FPM on Debian

3. Самостоятельно напишите Ansible-роль, настраивающую связку nginx+php-fpm и выдающую при обращении к главной странице веб-сервера информацию о php (содержимое index.php — <?php phpinfo();?>).  
4. Дополните роль из п.3: пусть DocumentRoot будет в директории /opt/nginx/ansible. Используйте handler для перечитывания конфигурации nginx.
