pgbackup
========

CLI for backing up remote PostgreSQL databases locally or AWS S3.

Preparing for Development
-------------------------

1. Ensure ``pip`` and ``pipenv`` are installed 
2. Clone repository: ``git clone git@gitbub.com:example/backup``
3. ``cd`` into repository
4. Fetch development dependencies ``make install``
5. Activate virtualenv: ``pipenv shell``

Usage
----

Pass in a full database URL, the storage driver and destination. 

S3 Exampe w/ bucket name:

::
    $make 

If virtualenv isn't active then use:

::
    $pipenv run make
