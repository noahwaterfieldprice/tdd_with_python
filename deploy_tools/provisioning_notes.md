Provisioning a new site
=======================

## Required packages:

* nginx
* Python 3
* Git
* pip
* virtualenv

e.g. on Ubuntu:
sudo apt-get installl nginx git python3 python3-pip
sudo pip3 install virtualenv

## Nginx
* see nginx.template.conf
* replace SITENAME with, eg, staging,my-domain.com

## Folder structure:
Assume we have a user account at /home/username

/home/username
|-- sites
   |-- SITENAME
      |-- database
      |-- source
      |-- static
      |-- virtualenv

