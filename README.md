This project demonstrates that composer 2 will delete a local path repository if it is used in conjunction with composer/installers.

Steps to reproduce:
1. clone this repo
2. composer install
3. composer update

After this runs, the core directory is removed.
