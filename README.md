# KomandaBlog-Forest

Войдите на сервер Ghost и перейдите к каталогу themes:

cd /var/www/ghost/content/themes/

Для установки темы в этот каталог используйте git.

Примечание: Чтобы установить git, используйте:

apt-get update && apt-get install git-core -y

Затем клонируйте тему с GitHub:

git clone https://github.com/RuslanGalimov/KomandaBlog-Forest.git

Передайте права на файлы пользователю и группе Ghost:

chown -R ghost:ghost N-Coded

Перезапустите Ghost, чтобы обновить содержимое каталога themes:

service ghost restart

Затем зайти через браузер в админ-настройки блога http://blog.komanda-app.ru/ghost/
Выбрать пункт меню General.
Выбрать из списка тем новою, только что добавленную.
