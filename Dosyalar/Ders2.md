TCP / UDP Protokolleri


TCP (Transmission Control Protocol), 

bilgisayarlar arası veri iletişiminde kayıpsız veri gönderimi sağlayan bir protokoldür. TCP/IP protokol takımının taşıma katmanı protokollerinden birisidir. TCP, bağlantı tabanlı (connection-oriented) bir protokoldür. Bu, iki bilgisayarın veri alışverişine başlamadan önce birbirleriyle bağlantı kurmaları gerektiği anlamına gelir. Bu bağlantı, üçlü el sıkışma (three-way handshake) adı verilen bir süreçle kurulur.

img

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


UDP (User Datagram Protocol),

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

