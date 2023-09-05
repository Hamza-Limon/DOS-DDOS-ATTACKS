# DOS VE DDOS NEDİR?

### DoS (Denial of Service - Hizmet Engelleme):

- DoS saldırıları, bir hizmeti veya kaynağı kullanılamaz hale getirmeyi amaçlar.
- Saldırganlar, ağdaki bir hizmete (örneğin, web sunucusuna) çok fazla istek göndererek kaynakları tüketirler.
- Saldırının amacı, hizmetin normal kullanıcılar için kullanılamaz hale gelmesini sağlamaktır.
- DoS saldırıları, genellikle tek bir saldırgan tarafından gerçekleştirilir.

### DDoS (Distributed Denial of Service - Dağıtık Hizmet Engelleme):

- DDoS saldırıları, birden fazla kaynaktan gelerek hedef sistem üzerine büyük miktarda trafik yollar ve kaynakları aşırı yükler.
- Saldırganlar, botnet adı verilen köle bilgisayarlar veya diğer enfekte cihazlar aracılığıyla saldırılarını koordine ederler.
- DDoS saldırılarının amacı, hedefin normal hizmetlerini sağlaması veya kullanılabilirliğini engellemektir.
- DDoS saldırıları, genellikle daha karmaşıktır ve daha fazla kaynağı gerektirir.
- Özetle, DoS, tek bir kaynaktan gelen saldırılarla bir hizmeti engellemeye odaklanırken, DDoS, birden fazla kaynaktan gelen koordine edilmiş saldırılarla daha büyük ve güçlü hedeflere yönelik hizmet engellemeyi amaçlar. DDoS saldırıları daha yaygın ve etkili olabilir, çünkü saldırganlar daha fazla kaynağa ve koordinasyona sahip olabilirler.

#### DDoS saldırılarının ana bileşenleri ve detayları şunlardır:

- Dağıtılmış Yapı: DDoS saldırıları, çok sayıda farklı kaynaktan gelir. Saldırıyı gerçekleştirenler, genellikle botnet adı verilen köleci ağlar oluştururlar. Bu botnetler, virüsler, kötü amaçlı yazılımlar veya zayıf güvenlikli cihazlar aracılığıyla ele geçirilmiş binlerce bilgisayardan oluşur. Bu botnetler, saldırıları koordine etmek için kullanılır.

#### Saldırı Çeşitleri

##### TCP Üzeri Saldırılar:

Saldırganlar, TCP (Transmission Control Protocol) bağlantılarına yoğun istekler göndererek sunucunun kaynaklarını tüketmeye çalışır. Bu, sunucunun yeni bağlantıları kabul etmesini zorlaştırır.

##### UDP Üzeri Saldırılar:

Saldırganlar, UDP (User Datagram Protocol) paketlerini hedef sunucuya göndererek ağı ve sunucuyu yoğunlaştırır. Bu tür saldırılar, genellikle DNS amplifikasyon saldırıları olarak bilinir.

##### HTTP (Web) Saldırıları:

Bu tür saldırılarda, hedeflenen web sunucusuna yoğun talepler gönderilir, bu da sunucunun yanıt veremediği veya yavaşladığı anlamına gelir. Bu, çevrimiçi hizmetlerin kullanılabilirliğini ciddi şekilde etkileyebilir.

##### Amacı ve Etkisi:

DDoS saldırılarının temel amacı, hedeflenen hizmetin veya sunucunun çevrimdışı kalmasını sağlamaktır. Bu, finans kurumları, çevrimiçi ticaret siteleri, kamu hizmet sağlayıcıları ve diğer önemli kuruluşlar için büyük bir sorundur, çünkü kullanılabilirliklerini ciddi şekilde etkiler. Saldırılar ayrıca kuruluşların itibarını ve müşteri güvenini zedeler.

##### Savunma Yöntemleri:

DDoS saldırılarına karşı savunma yöntemleri geliştirilmiştir. Bunlar, trafik analizi, filtreleme, yük dengeleme, siber güvenlik duvarları ve CDN (İçerik Dağıtım Ağı) gibi teknolojileri içerir. Bu savunma yöntemleri, hedeflenen sistemleri saldırılardan korumak veya etkilerini minimize etmek için kullanılır.

> DDoS saldırıları, siber güvenlik uzmanları ve ağ yöneticileri için sürekli bir tehdit oluşturur. Bu nedenle, güvenlik önlemlerinin ve hızlı tepki planlarının oluşturulması önemlidir.

Siber suçluların bir web sitesini veya çevrimiçi hizmeti erişilemez noktaya nasıl getirebildiğini hiç merak ettiniz mi? Bugün DNS saldırısının nasıl çalıştığını açıklayacağız


# DNS (Domain Name System)

İnternet üzerindeki alan adlarını IP adreslerine çeviren bir hizmettir. DNS flood saldırısı, hedeflenen bir DNS sunucusunu hedefleyen ve ağırlıklı olarak DNS isteklerini manipüle etmeye çalışan bir tür DDoS (Dağıtılmış Hizmet Engelleme Saldırısı) saldırısıdır. Bu tür saldırılarda, saldırganlar genellikle çok sayıda istemciyi kullanarak hedef DNS sunucusuna yoğun ve istenmeyen DNS sorguları gönderirler. Bu sorgular, sunucunun kaynaklarını tüketir ve sunucunun normal DNS hizmetini kesintiye uğratır.

DNS flood saldırılarının ana özellikleri ve detayları şunlar olabilir:

- Yüksek Trafik: Saldırganlar, hedef DNS sunucusuna büyük miktarda trafik göndererek saldırıyı gerçekleştirirler. Bu trafik, sunucunun kaynaklarını tüketir ve yanıtları geciktirir veya kesintiye uğratır.

- DNS İstek Manipülasyonu: Saldırganlar, sahte veya bozuk DNS istekleri gönderebilirler. Bu istekler, sunucunun yanıtlarını beklemesi veya işlemesi gereken ek kaynaklar kullanmasına neden olabilir.

- Amacı ve Etkisi: DNS flood saldırılarının temel amacı, hedef DNS sunucusunun normal işleyişini bozmak veya hedeflenen alan adlarına erişimi engellemektir. Bu, hedeflenen web sitelerinin, e-posta sunucularının veya diğer online hizmetlerin kullanılabilirliğini ciddi şekilde etkileyebilir.

- Zayıf Noktalar: DNS sunucuları ve hizmet sağlayıcıları genellikle bu tür saldırılara karşı savunmasız olabilirler. Bu, DNS sunucularının yetersiz yapılandırılması veya yetersiz güvenlik önlemleri nedeniyle gerçekleşebilir.

- Savunma Yöntemleri: DNS flood saldırılarına karşı korunma yöntemleri arasında trafik filtreleme, yük dengelemesi, rate limiting (istek hız sınırlama), DNS güvenlik duvarları ve DNS sorgu izleme ve analizi gibi önlemler bulunur. Bu yöntemler, istenmeyen DNS isteklerini saptamak ve engellemek için kullanılır.

> DNS flood saldırıları, hizmet kesintilerine neden olabileceği ve siber güvenlik tehditleri oluşturabileceği için ciddi bir sorundur. Bu nedenle, DNS sunucularının güvenlik açıkları kapatılmalı ve saldırıları tespit etmek ve savunmak için uygun önlemler alınmalıdır.



> Siber suçluların bir web sitesini veya çevrimiçi hizmeti erişilemez noktaya nasıl getirebildiğini hiç merak ettiniz mi? Bugün DNS Flood saldırısının nasıl çalıştığını açıklayacağız


![moved](https://github.com/Hamza-Limon/DOS-DDOS-ATTACKS/assets/140405710/6f0fe804-f5ec-493e-98bf-95a8c920212b)



