# eStab Docker Compose

Dieses compose-File stellt eine komplette eStab Umgebung bereit.

Unbedingt die Datei `db_password.txt` erstellten und mit einem beliebigen Kennwort versehen. Dadurch wird die Datenbankverbindung automatisch gesetzt und hergestellt. Zeitgleich handelt es sich um das `root`Kennwort der MariaDB Datenbank.

Es werden folgende Container hochgefahren:
- eStab (Über Port 80)
- MariaDB
- Adminer (Web DB Admin, Port 8080)