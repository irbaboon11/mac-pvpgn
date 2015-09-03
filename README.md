# mac-pvpgn 
* not lua , not db ( default file db )

wget http://sourceforge.net/projects/pvpgn.berlios/files/pvpgn-1.8.5.tar.gz

tar xf pvpgn-1.8.5.tar

cd pvpgn-1.8.5/src

./configure --prefix=/usr/local/pvpgn

make && make install

cd /usr/local/pvpgn

wget http://pvpgn.harpywar.com/pvpgn/pvpgn-support-1.2.tar.gz

tar xf pvpgn-support-1.2.tar.gz

mv pvpgn-suppoert-1.2/* ./var/files/

-- execute

/usr/local/pvpgn/sbin/bnetd
