# Meson-Network-3.0 Testnet

Ciddi Yatırımcıları Var / Meson Network 3.0 Ödüllü Testnet

<img width="1395" alt="meson" src="https://user-images.githubusercontent.com/98783018/177622076-c12fad62-7348-4f90-9df2-03698f015029.png">

Meson toplam arzı 100M ve  %1'i testnet katılımcılarına dağıtılacak. Her testnette olduğu gibi yüksek beklentiye girmemenizi tavsiye ederim

Meson Node Puan: 7/10

Meson Node Kurulum Videosu:https://youtu.be/yXwXbUXo4oo

**Minimum Sistem Gereksinimleri**

İşlemci:2

Ram:2GB

Hafıza: 20

İlk önce şuradan websiteye girip kayıt olalım: https://dashboard.meson.network/register

<img width="800" alt="1" src="https://user-images.githubusercontent.com/98783018/178104767-98f3a236-e1aa-48af-9b5c-deab7b3cb850.png">

Kuruluma Başlayalım

Güncelleme

```
sudo apt-get update -y && sudo apt-get install wget -y
```

```
wget 'https://staticassets.meson.network/public/meson_cdn/v3.1.18/meson_cdn-linux-amd64.tar.gz' && tar -zxf meson_cdn-linux-amd64.tar.gz && rm -f meson_cdn-linux-amd64.tar.gz && cd ./meson_cdn-linux-amd64 && sudo ./service install meson_cdn
```

443 Portunu Açalım

```
sudo ufw allow 443
```

Node Durumunu Kontrol edelim

```
sudo ./service status meson_cdn
```

Logları Kontrol Edelim

```
sudo ./meson_cdn log
```




