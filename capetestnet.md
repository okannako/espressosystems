## Tavsiye Edilen Sistem Gereksinimleri
- İşlemleri hızlı bir şekilde halldebilmeniz için 4 CPU 8GB RAM olan bir sistemi tercih etmenizi tavsiye ediyorum.
- Ubuntu 20.04

## Ubuntu Masaüstü Kurulumu
```
sudo apt update
sudo apt-get dist-upgrade
sudo apt-get install ubuntu-desktop
wget https://download.nomachine.com/download/8.14/Linux/nomachine_8.14.2_1_amd64.deb
sudo dpkg -i nomachine_8.14.2_1_amd64.deb
sudo adduser kullanici
usermod -aG sudo kullanici
reboot
```

## Testnet Kurulumu
```
sudo curl -fsSL https://get.docker.com -o get-docker.sh && sh get-docker.sh
sudo apt install docker-compose
sudo curl https://www.espressosys.com/cape/docker-compose.yaml --output docker-compose.yaml
sudo docker-compose pull
sudo docker-compose up
```

## Testnet İşlemleri
- İşlemleri yaptıktan sonra tarayıcıya ``localhost`` yazarak videodaki adımları gerçekleştiriyoruz.
     - https://www.youtube.com/watch?v=CtR3B4qM8TI

## Ek İşlemler
- Videodan sonra ek adımlar yayınlanmıştı başka ayrıntıları da anlattığım bir flood hazırladım. Biraz uzun olduğundan 2 bölüm halinde yayınladım. Keyifli okumalar.
     - 1.Bölüm https://twitter.com/NakoTurk/status/1544006217827237891
     - 2.Bölüm https://twitter.com/NakoTurk/status/1544006373435998209
