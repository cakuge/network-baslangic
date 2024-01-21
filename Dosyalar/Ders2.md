TCP / UDP Protokolleri

![udp-tcp-header-image](https://github.com/cakuge/network-baslangic/assets/93228791/bbbad55e-62ff-4426-8f60-9dcf017067fa)


TCP (Transmission Control Protocol), 

bilgisayarlar arası veri iletişiminde kayıpsız veri gönderimi sağlayan bir protokoldür. TCP/IP protokol takımının taşıma katmanı protokollerinden birisidir. TCP, bağlantı tabanlı (connection-oriented) bir protokoldür. Bu, iki bilgisayarın veri alışverişine başlamadan önce birbirleriyle bağlantı kurmaları gerektiği anlamına gelir. Bu bağlantı, üçlü el sıkışma (three-way handshake) adı verilen bir süreçle kurulur.

![maxresdefault](https://github.com/cakuge/network-baslangic/assets/93228791/f7aeeda9-432f-4235-8f9e-e72fd256b50f)


TCP'nin temel özellikleri ise:

* Bağlantı tabanlı
* Güvenli
* Kayıpsız veri aktarımı
* Sıra koruması
* Hatalı paketlerin yeniden gönderilmesi

TCP, bilgisayarlar arası veri iletişiminde en yaygın kullanılan protokollerden biridir. Veri kaybını önleme ve güvenilir veri aktarımı sağlama gibi özellikleriyle internetin temelini oluşturmaktadır.

TCP protokolünün kullanıldığı bazı örnek yerler ise;

* Web sayfalarının görüntülenmesi
* Dosyaların aktarılması
* E-postaların gönderilmesi
* Sohbet programlarıdır.

--------------------------------------------------------------------------------------------------------------------

UDP (User Datagram Protocol),

![F7AJp-What-Is-UDP-how-does-it-work-and-what-are-its-benefits](https://github.com/cakuge/network-baslangic/assets/93228791/926fc461-6e7d-4e29-a09b-ff75047fc3b0)

TCP/IP protokol takımının iki aktarım katmanı protokolünden birisidir. Verileri bağlantı kurmadan yollar. UDP, bağlantısız (connectionless) bir protokoldür. Bu, iki bilgisayarın veri alışverişine başlamadan önce birbirleriyle bağlantı kurmaları gerekmediği anlamına gelir. Bu sayede, UDP daha hızlıdır ve TCP'ye göre daha az kaynak kullanır.

Temel özellikleri ise;

* UDP, verileri küçük paketlere böler ve bu paketleri gönderen bilgisayardan alıcı bilgisayara gönderir. Alıcı bilgisayar, paketleri tekrar birleştirerek orijinal veriyi elde eder.
* UDP, veri kaybını önlemek için herhangi bir mekanizma kullanmaz. Bu, UDP'nin TCP'ye göre daha güvenilmez bir protokol olduğu anlamına gelir.
* UDP, gerçek zamanlı uygulamalar için uygun bir protokoldür. Bu uygulamalarda, veri kaybına karşı daha az hassasiyet vardır.

UDP'nin bazı kullanım örnekleri şunlardır:

* Ses ve görüntü aktarımı
* Oyunlar
* DNS
* SNMP
* DHCP
* NTP

|Özellik               |            TCP            |           UDP          |
|----------------------|---------------------------|------------------------|
|Bağlantı              |Bağlantılı                 |Bağlantısız             |
|Güvenilirlik          |Güvenli                    |Güvensiz                |
|Kayıpsız Veri Aktarımı|Kayıpsız                   |Kayıplı                 |
Hız                    |Daha yavaş                 |Daha hızlı              |
Kaynak Kullanımı       |Daha fazla kaynak kullanır |Daha az kaynak kullanır |

--------------------------------------------------------------------------------------------------------------------

Portlar

![COMMON-TCP-IP-WELL-KNOWN-PORT-NUMBERS-TABLE](https://github.com/cakuge/network-baslangic/assets/93228791/df8db842-9561-4cc2-8595-cc4b257d8e0f)

- Portlar, bilgisayarların giriş kapılarıdır.
- TCP ve UDP bağlantılar, veriyi üst katmanlara taşımak veya uygulamaya iletmek için port numaraları kullanırlar.
- Port numaraları, aynı anda yapılan farklı iletişimleri ayırt etmek için kullanılırlar.
- Her application katmanı servisi, belirli bir porttan sunulur.
- Bir bilgisayarda 65535 adet port vardır. 0'dan 1023 e kadar olan bağlantı noktaları, well-known bağlantı noktaları olarak bilinir ve belirli bir hizmet için rezerve edilmiştir.
- Bağlantı noktaları taşıma katmanında (Layer 4) kullanılır.


