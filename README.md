# UTorrent-Kali
Install Utorrent libssl1.0.0 kali linux

## Masuk Kedalam Website Utorrent
    - Pilih versi torrent yang akan di gunakan
    
    - https://www.utorrent.com/downloads/linux

## Install Command
    1. cd ~/Downloads/
    
    2. sudo tar -xvzf utserver.tar.gz -C /opt/
    
    3. sudo chmod -R 755 /opt/utorrent-server-alpha-v3_3/
    
    4. sudo ln -s /opt/utorrent-server-alpha-v3_3/utserver /usr/bin/utserver
    
## Run Command
    1. utserver -settingspath /opt/utorrent-server-alpha-v3_3/
    
    2. sudo apt-get install libssl1.0.0
    
    3. localhost:8080/gui

## Tambahkan Repository
    Repository bersifat optional atau tidak diwajibkan, repository ini bertujuan untuk menambahkan
    libssl1.0.0 jika belum terinstall
    
    - sudo nano /etc/apt/source.list
    
    - Paste the Jessie APT Repository: "deb http://security.debian.org/debian-security jessie/updates main"

## Reff
    * https://www.utorrent.com/
    
    * https://askubuntu.com/questions/1261614/ubuntu-20-04-libssl-so-1-0-0-cannot-open-shared-object-file-no-such-file-or-d
    
    * https://www.youtube.com/watch?v=bNCFOKBw7uI&ab_channel=TheFreakLesson
