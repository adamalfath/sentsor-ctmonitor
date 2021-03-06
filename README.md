# SENTSOR Current Transformer (CT) Monitor
## Introduction
SENTSOR CT Monitor merupakan perangkat interface untuk DAQ, logging, dan monitoring konsumsi arus listrik AC via Current Transformer. Perangkat ini juga sudah _IoT Ready_, dengan demikian user dapat mengetahui nilai sensor secara realtime melalui web dashboard yang disediakan.

## Features
- **Current Transformer DAQ**: support maksimal untuk secondary CT 5A.
- **Local Timestamp**: RTC akurat tersinkronisasi dengan NTP.
- **Local Datalogging**: file CSV tersimpan diperangkat lokal dalam MicroSD Card.
- **Remote Monitoring**: perangkat terhubung dengan jaringan menggunakan protokol MQTT via WiFi.
- **Local Monitoring**: disediakan koneksi RS485 untuk keperluan interkoneksi data secara lokal.
- **Local AP Config**: tersedia access point local untuk konfigurasi CT ratio, sensing interval, log interval, wireless setting, dll.
- **Web Dashboard**: visualisasi time-series data.
- **Report Generator**: mengirimkan report data (ex: min/max/average value, active time, operational time, alarm) untuk interval yang ditentukan via E-mail.
- **Industrial Design**: enclosure rating IP51 (ekivalen, proteksi terhadap debu dan tetesan air), temperatur kerja -20°C sampai 85°C, tested 24/7 +1000h and still counting.

## Gallery
_Hardware:_  
<img src="https://github.com/adamalfath/sentsor-ctmonitor/blob/master/media/ctmonitor-img0.jpg" width="400"> <img src="https://github.com/adamalfath/sentsor-ctmonitor/blob/master/media/ctmonitor-img1.jpg" width="400">  
<img src="https://github.com/adamalfath/sentsor-ctmonitor/blob/master/media/ctmonitor-img2.jpg" width="400"> <img src="https://github.com/adamalfath/sentsor-ctmonitor/blob/master/media/ctmonitor-img3.jpg" width="400">  
<img src="https://github.com/adamalfath/sentsor-ctmonitor/blob/master/media/ctmonitor-img4.jpg" width="400"> <img src="https://github.com/adamalfath/sentsor-ctmonitor/blob/master/media/ctmonitor-img5.jpg" width="400">  
<img src="https://github.com/adamalfath/sentsor-ctmonitor/blob/master/media/ctmonitor-img6.jpg" width="400"> <img src="https://github.com/adamalfath/sentsor-ctmonitor/blob/master/media/ctmonitor-img7.jpg" width="400">

_Dashboard:_  
<img src="https://github.com/adamalfath/sentsor-ctmonitor/blob/master/media/ctmonitor-web-ss.png" width="804">

## Support Open-Source Hardware & SENTSOR!
Bila kalian tertarik dengan produk-produk SENTSOR, kalian bisa cek marketplace ataupun memberikan donasi pada link berikut:  

[![Store](https://img.shields.io/badge/marketplace-Tokopedia-brightgreen.svg)](https://www.tokopedia.com/gerai-sagalarupa/etalase/sentsor-product)  [![Donate](https://img.shields.io/badge/donate-PayPal-blue.svg)](https://www.paypal.me/adamalfath)  

Support kalian akan sangat membantu untuk pengembangan open-source hardware dari SENTSOR selanjutnya.

## Information
SENTSOR  
Author: Adam Alfath  
Contact: adam.alfath23@gmail.com  
Web: [sentsor.net](http://www.sentsor.net)  
Repo: [SENTSOR Main Repo](http://github.com/adamalfath/sentsor)

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png"/></a><br/>
SENTSOR CT-Monitor is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.