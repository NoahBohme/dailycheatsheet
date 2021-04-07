###### Zip a file

zip -r ./newzipfile.zip ./olddir

###### WGET from FTP

wget -r ftp://username:password@hostserver/directoryname

###### GZIP a file or dir

tar -czvf newzip.tar.gz ./file

###### UNGZIP a file or dir

tar -xzvf archive.tar.gz

###### Add a PGP key

mkdir ~/.ssh/

sudo echo "token" >> ~/.ssh/authorized_keys

