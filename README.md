1. How to compile on linux:
	* apt-get install autoconf build-essential pkg-config automake libboost-all-dev libgmp3-dev libxml2-dev liblua5.1-0-dev libmysqlclient-dev libssl-dev libsqlite3-dev
	* cd /3777updates-master
	* chmod -R 777 src
	* cd src
	* ./autogen.sh
	* ./configure --enable-mysql --enable-root-permission --enable-server-diag
	* ./build.sh
