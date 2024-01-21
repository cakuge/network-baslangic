Ağ (network), birbirine bağlı bilgisayarların,cihazların veya sistemlerin arasında belirli kurallar ile veri ve bilgi paylaşımını sağlayan yapılardır. Ağlar sayesinde cihazlar arasında
Dosya paylaşabilir,diğer dosyalara erişim sağlayabilir veya yazıcılara kolayca erişebiliriz. Ya da hızlı bir biçimde iletişim kurabiliriz. 
Ayrıca ağlar uzaktan erişimi imkanını da sağlar. Yani bir şirketin çalışanların cihazları farklı konumlarda olsalar bile birbiriyle iletişimde&etkileşimde bulunmasını mümkün kılar.

Örneğin;
Sen ve arkadaşın beraber oyun oynamak istiyorsun. Ancak, arkadaşın senin evinde değil, kendi evinde. Bu durumda, ağlar sayesinde birlikte oyun oynayabilirsiniz. Ya da Ağlar sayesinde, dünyanın farklı yerlerinde bulunan insanlarla iletişim kurabilirsin. Örneğin, bir arkadaşın yurt dışında yaşıyorsa, onunka ağlar sayesinde sohbet edebilirsin.

Bunu tıpkı bir örümcek ağına benzetebilirsin.


Ağların günlük hayatımızdaki örnekleri:

* Evimizdeki Wi-Fi ağı
* Okulumuzdaki bilgisayar ağı
* İnternet

-------------------------------------------------------------------------------------------

Başlıca Ağ Donanımları

*NIC (Ethernet Card)*
Ethernet kartı, bir cihazı bir ağa bağlayan bir donanım parçasıdır. Bu kartlar verileri bir cihazdan diğer bir alıcıya göndermek için veya diğer bir göndericiden almak için kullanılır.Bir cihaz içerisinde 1 den fazla da bulunabilir. IP ve MAC adresi bilgilerini barındırır. Veri ve Elektrik sinyallerinin çevirisini yapar.


*Switch*
Switch, cihazlar arasında veri akışını kontrol eden, haberleşmesini sağlayan bir ağ donanımıdır. Çoğunlukla birden fazla
kablolu bağlantı noktası(port) bulunan bir kutudur.Bu noktalara cihazlar bağlanır ve switch, gelen verileri doğru MAC adresine sahip cihaza yönledirir. Bu sayede ağ trafiği verimi artmış ve yönetilmiş olur.

*Firewall*
Firewall, bir ağı veya cihazın sistemini çevreleyerek siber tehtidlere karşı koruma amacıyla kullanılan donanımdır. Güvenlik duvarı, gelen ve giden ağ trafiğini filtreleyerek, izin verilen trafiği geçirir ve izin verilmeyen trafiği engeller. Yazılımsal şekilde de firewallar vardır.

*Router*
Router, aynı ağ iletişim kurallarını kullanan iki veya daha fazla ağ arasında veri çerçevelerinin iletimini sağlayan,IP çevirimi yapan[NAT]Ağ Donanımı.OSI yedi katman
modelinin üçünücüsü olan ağ katmanını kullanır.


--------------------------------------------------------------------------------------------

Ağ Mimarileri

Ağlar büyüklüklerine göre 2 ye ayrılır.
LAN(Local Area Network) ve WAN(Wide Area Network). 2 sini inceleyecek olursak;

LAN(İç Ağ):Çok hızlı ve WAN'a göre daha güvenli olan,aynı fiziksel konumda bulunan, cihazları birbirine bağlayan bir ağdır. Ofis,ev veya okul gibi küçük ağları kapsadığından lokal(yerel) ağlardır. Kablolu ve kablosuz(Wi-Fi)olarak 2 şekilde kurulabilir.

WAN(Dış Ağ): coğrafi olarak birbirinden uzak konumlardaki cihazlarının oluşturduğu LAN'ları birbirine bağlayan bir ağıdır. Genellikle bir şehir,ülke veya kıta gibi geniş alanları kapsar. 

----------------------------------------------------------------------------------------------

Ağ Protokolleri:

Ağ protokolü, iki veya daha fazla bilgisayar arasındaki iletişimi sağlamak amacıyla kullanılan kurallar dizisidir. Ağ protokolleri, verilerin nasıl paketleneceğini, nasıl yönlendirileceğini ve nasıl alınacağını belirtir.Ağların verimli ve güvenli bir şekilde çalışmasını sağlarlar.

Uygulamalar arasında iletişim kurmak için HTTPS,FTP,SMTP
Verilerin güvenilirbir şekilde iletilmesini sağlamak için, TCP ve UDP
Verilerin bir ağdan diğerine yönlendirilmesi için IP 
En yaygın kullanılan protokollerdir.

-------------------------------------------------------------------------------------------------

OSI Referans Modeli

Bilgisayar ağlarını tanımlamak ve anlamak için kullanılan bir çerçevedir. 1984 yılında Uluslararası standartlar örgütü(ISO) tarafından geliştirilmiştir. OSI modeli,
ağ iletişimini 7 katmana ayırır.

Layer 7 – Application  (Uygulama Katmanı)
Layer 6 – Presentation  (Sunum Katmanı)
Layer 5 – Session  (Oturum Katmanı)
Layer 4 – Transport  (Taşıma Katmanı)
Layer 3 – Network  (Ağ katmanı)
Layer 2 – Data Link  (Veri Bağlantı Katmanı)
Layer 1 – Physical  (Fiziksel Katman) şeklindedir.


Uygulama katmanı(Layer7): Kullanıcının bilgisayarla buluştuğu katmandır. veriler gözle görülür ve insan tarafından anlaşılır hale gelen katmandır.E-posta,
dosya transferi , tarayıcılar vs. gibi ağla ilgili arayüzler uygulama katmanı ile iletişime geçmektedir.
Kullanıcının google.com'u çağırdığını Presentation(Sunum katmanı) katmanına bildirir veya Presentation katmanından gelen paketi de uygulamada açıp kullanıcıya gösterir.

Sunum Katmanı(Layer6): Uygulama katmanından gelen kullanıcının isteklerini yorumlayıp, alt katmanlara gönderilmesi için, burada hazırlanılır yani çevirici katmandır. Gönderilecek verinin, alt katmanına iletirken Çevirme ,kodlama, şifreleme, sıkıştırma gibi işlevleri yerine getirir. Kısacası verileri formatını ve içeriğini işler.

Oturum Katmanı(Layer5): Bankacılık uygulamalarında kullandığımız SSL (Secure Socket Layer) teknolojisi, oturum katmanı bazında yapılan şifrelemeye dayanır. Bu teknoloji, oturum katmanının önemli bir temel teşkil ettiği teknoloji olarak oturum katmanına örnektir. ayrıca herhangi bir çökme durumuna sebep olacak uzunluktaki veri gönderimi sürelerinde, sürenin çökme eşiğini aştığı anda verilerin olduğu yerde kalmasını ve gönderim yeniden başladığında kaldığı yerden devam etmesini sağlayan noktaları belirleme ve yönetme
gibi çok ciddi ve önemli işlevleri vardır. Kısacası veri alışverişini kontrol eder.

Taşıma Katmanı(Layer4) : Taşıma katmanı,oturum katmanından gelen veriyi segmentlere ayırır yani parçalara böler. Segmentlere ayırılmış veri bir müddet bu şekilde taşınır. Ardından tekrar bir araya getirilir ve bütün bir parçaya dönüşür ve Ağ katmanına transfer edilir.
Verinin segmentlere ayrılmasının sebebi, segmentlerden herhangi birinin  kaybı gibi bir durumda kaybolan parçanın küçük boyutlu olmasından dolayı yerine getirilmesinin kolay olmasıdır. Katman, her segmente bir sıra numara verir ve kaybında bu numaraları alıcı katmana iletip tamamlanmasını ister.Bu katmanda TCP, UDP , SSL protokolleri çalışır. Kısacası Verilerin güvenilri bir şekilde iletilmesini sağlar.

Ağ Katmanı(Layer3): Ağ katmanına adresleme ve yönlendirme katmanı da diyebiliriz. Çünkü totalde yaptığı iş budur. Veriyi göndereceği adresi ve verinin geldiği adresi belirler ve cihazları yönetir. Bunu yaparken ağ trafiğini düzenler, cihazların lokasyonlarını belirler ve verinin gönderilmesi için en iyi yolu seçer. En iyi yol seçimi bu katmanda çalışan Router ile yapılır. Kısacası verileri, bir ağdan diğerine yönlendirir bu yüzden IP adresi burada girilir.

Veri Bağlantı Katmanı(Layer2): Öncelikli işi, bir üstünde bulunan ağ katmanından gelen mesajları fiziksel katmana göndereceği için Bit’lere dönüştürmesidir.
Veri bağlantı katmanı, aynı zamanda fiziksel katmandan aldığı verilerde bir hata olduğunu tespit ederse yine kendi alt katmanlarından biri olan MAC(Media Access Control)katmanı ile bu hatalı verileri paketler ve fiziksel katmana geri postalar.Veri Bağlantı Katmanının ağdaki cihazları kontrol etme, tanımlama ve ağı kullanan cihazı tespit etme gibi görevleri de vardır.

Fiziksel Katman(Layer1): Kendine gelen verileri Bit olarak alır. Göndereceği verileri hakeza Bit gönderir. Bitler 0 ve 1 rakamlarından oluşan rakam sıralamalarıdır. Öreğin 00101000001101010101 gibi.Fiziksel katman işte bu rakamları elektrik, ses, ışık sinyallerine dönüştürmekle yükümlüdür.
