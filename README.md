## Usage

git clone git@github.com:diogogomes77/drupal-gerc.git

cd drupal-gerc

sudo chmod 777 drupal -R

docker-compose exec php composer install

---

cat backup1.sql | docker-compose exec -T php drush sql-cli

http://drupal.docker.localhost:8000

admin/admin
