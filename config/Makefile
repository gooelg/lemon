install:
	/bin/cp -vf postgresql/* /var/lib/pgsql/data
	/usr/bin/chown postgres:postgres /var/lib/pgsql/data/postgresql.conf
	/usr/bin/chown postgres:postgres /var/lib/pgsql/data/pg_hba.conf
	/bin/cp -vf ../package/config/pgbouncer.ini /etc
	/usr/bin/mkdir -pv /etc/pgbouncer
	/bin/cp -vf ../package/config/userlist.txt /etc/pgbouncer
	/bin/cp -vf ../package/config/pgbouncer.conf /etc/tmpfiles.d
	/bin/cp -vf nginx/nginx.conf /etc/nginx
	/bin/cp -vf nginx/api.conf /etc/nginx/conf.d
	/bin/cp -vf nginx/lemon.conf /etc/nginx/conf.d
	/bin/cp -vf nginx/manage.conf /etc/nginx/conf.d
