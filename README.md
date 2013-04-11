# PostgreSQL ile Programlama

*PostgreSQL ile Programlama*, PostgreSQL veritabanına C, PHP ve Python programlama dilleri kullanılarak nasıl bağlanılacağı hakkında incelemede bulunan oldukça kapsamlı bir kitap projesidir.

Kitap içerisinde herbir arayüz, kendi başlığı altında tanıtım uygulamaları ve sağladığı kütüphane fonksiyonları ile ayrıntılı olarak incelenmektedir. İncelenen arayüzler tarafından sağlanan fonksiyonlar için bölüm sonlarında örnekler yer almaktadır. Yazılacak programlarda güvenlik konusu ayrı bir bölüm altında ele alınmaktadır. İlgili arayüzler hakkında sık karşılaşılan problemler bölümünde bir çok problem uygulamalı olarak ele alınmıştır.

Volkan YAZICI <volkan.yazici@gmail.com>
2006-02-14 22:25:01 EET

# Hakkında

2005 senesinde [Devrim Gündüz](http://www.gunduz.org/) ile birlikte PostgreSQL hakkında bir kitap yazma projesi üzerinde çalışmaya başladık. Kitap, *yönetim* ve *programlama* olarak iki bölümden oluşacaktı ve ben programlama kısmını üstlenmiştim. Yaşanan aksiliklerden ötürü kitabın yönetim ile ilgili kısmı tamamlanamayıp, kitap bir türlü baskıya hazır hale getirilemedi. Kitabın yazımında herhangi bir ticari kaygı güdülmediğinden ötürü, ben de kendime ait bu bölümü GNU Özgür Belgeleme Lisansı altında ücretsiz olarak yayınlama kararı aldım.

Proje, başka bir kitabın parçası olarak düşünüldüğünden, okuyucunun da kolaylıkla fark edebileceği gibi hitap edişlerde ve olmayan bölümlere referanslarda bazen komik durumlar ortaya çıkabiliyor. Fakat bu ufak sorunların böyle büyük bir projeye gölge düşüremeyeceği ve zamanla giderileceği görüşündeyim.

# Teşekkürler

- Neil Conway'e (PostgreSQL ve libpq kütüphanesinin iç işleyişi hakkında yardımlarından dolayı),
- PostgreSQL hakkındaki her türlü soruma büyük bir çaba ve içtenlikle cevap verdikleri için irc.freenode.net sunucusundaki tüm #postgresql ailesine - özellikle AndrewSN'ye.

# Yasal Uyarı

Bu kitabın, PostgreSQL ile Programlama, telif hakkı &copy; 2006 Volkan YAZICI'ya aittir. Bu belgeyi, Free Software Foundation tarafından yayınlanmış bulunan GNU Özgür Belgeleme Lisansının 1.1 ya da daha sonraki sürümünün koşullarına bağlı kalarak kopyalayabilir, dağıtabilir ve/veya değiştirebilirsiniz. Bu lisansın bir kopyasını [http://www.gnu.org/copyleft/fdl.html](http://www.gnu.org/copyleft/fdl.html) adresinde bulabilirsiniz.

Bu belgedeki bilgilerin kullanımından doğacak sorumluluklar, ve olası zararlardan belge yazarı sorumlu tutulamaz. Bu belgedeki bilgileri uygulama sorumluluğu uygulayana aittir.

Tüm telif hakları aksi özellikle belirtilmediği sürece sahibine aittir. Belge içinde geçen herhangi bir terim bir ticarî isim yada kuruma itibar kazandırma olarak algılanmamalıdır. Bir ürün ya da markanın kullanılmış olması ona onay verildiği anlamında görülmemelidir.
