# Useful commands

#### GIT
git update-index --assume-unchanged file_name <br />
git reset --hard commitId <br />
git push --force <br />
git reset HEAD~ <br />
git merge --abort <br />

#### PHP
php artisan migrate <br />
php artisan migrate:rollback <br />
php artisan cache:clear <br />

#### Django
python manage.py createsuperuser  <br />
python manage.py makemigrations <br />
python manage.py migrate <br />

##### To start with new db in project
Django's migration can be reset by deleting all migration files such as 0001_inital, 0002_delete_song, 0003_delete_album, etc. except the __init__.py files in each project app directory, then dropping the database and creating migration again.
