## Tavsiye Edilen Sistem Gereksinimleri
- İşlemleri hızlı bir şekilde halldebilmeniz için 4 CPU 8GB RAM olan bir sistemi tercih etmenizi tavsiye ediyorum.
- Ubuntu 20.04

## Ubuntu Masaüstü Kurulumu
```
sudo apt update
sudo apt-get dist-upgrade
sudo apt-get install ubuntu-desktop
wget https://download.nomachine.com/download/7.9/Linux/nomachine_7.9.2_1_amd64.deb
sudo dpkg -i nomachine_7.9.2_1_amd64.deb
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
     - https://youtu.be/_L7r2InsIAg

