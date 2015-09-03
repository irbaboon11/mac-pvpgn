# mac-pvpgn 
* not lua , not db ( default file db )

wget http://sourceforge.net/projects/pvpgn.berlios/files/pvpgn-1.8.5.tar.gz/download

tar xf pvpgn-1.8.5.tar

cd pvpgn-1.8.5/src

./configure --prefix=/usr/local/pvpgn

make && make install

-- execute

/usr/local/pvpgn/sbin/bnetd
