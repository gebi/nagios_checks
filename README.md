nagios_checks
=============

Internal nagios checks, mostly derived from public sources but some slight modifications.

check_gitolite
--------------

    - Run git fsck --full --strict on all repositories of an gitolite container


check_apachestatus_auto.pl
--------------------------

    - Do not count openslots because apache proxy error freezes whole process, not only the connection/thread
    - Change absolut warn/critical to percent handling
