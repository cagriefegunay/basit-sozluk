# Basit Sözlük

TDK Güncel Türkçe Sözlük'te yer alan kelimelerin anlamlarını Terminal üzerinden, tarayıcılarda gereksiz vakit harcamadan öğrenebileceğiniz basit bir betik.

## Nasıl?

[Burada](https://github.com/abdurrahmanekr/tdk-service/issues/3) anlatıldığı üzere kelimeler [TDK Güncel Türkçe Sözlük](https://sozluk.gov.tr)'te REST API ile aratılabilir ve çıktıları JSON formatında görüntülenir durumda. Neden bu özelliği kullanarak bir şeyler yapmayayım ki? 

Hem de tek satırda :D

## Kurulum

```bash
git clone https://github.com/cagriefegunay/basit-sozluk
cd basit-sozluk
chmod +x sozluk
sudo cp sozluk /usr/local/bin/
```
## Kullanım

```bash
sozluk <ARANACAK-KELIME>
```
Bu kadar.

![Ekran Görüntüsü](terminal.png

# Lisans

Bu proje, _GNU GPLv3_ ile Copyleft olarak bir özgür yazılım lisansı ile sunulmaktadır.
