iOS Developer Roadmap
Güncelleme tarihi: 31 May 2020

Merhaba Arkadaşlar, sizlere bir iOS Developer’ın yol haritasından bahsetmek istiyorum.


Nedir Bu RoadMap?
RoadMap, genel çerçevede başarılı bir geliştiricinin temel yetkinlikleridir. iOS Platformunu tam olarak anlamak, temel metodolojisini kavramak isteyen tüm geliştiricilerin bilmesi gereken bir yol haritasıdır.


Kimler İçin?
Uzman bir iOS geliştiricisi olmak isteyenler

Mülakatlara hazırlananlar

İOS geliştiricisi olmak isteyen herkes içindir


DİYAGRAM
Öncelikle diyagramımıza bir göz atalım. Ardından temel adımları incelemeye başlayalım.




IDE

iOS geliştirmede kullandığımız IDE Xcode olarak karşımıza çıkmaktadır. Sadece MacOS işletim sistemlerinde çalışan Xcode'u, tüm geliştirme sürecinde kullanıyor olacağız. 


Language

Native geliştirmede Apple bize 2 seçenek sunmaktadır: Objective-C ve 2014'de çıkarılan Swift. Swift bir fonksiyonel programlama dilidir. Objective-C ise nesne tabanlı bir programla dilidir.


Memory Management

Bellek yönetimi bize, programımızın çalışma sürecince bellekten yer ayırma, kullanma ve işimiz bittiğinde belleği boşaltma adımlarını sağlar. İyi yazılmış bir program bellekte mümkün olduğunca az yer kaplamalıdır. Nesnelerin yaşam döngülerini kontrol etmemize ve artık işlevi biten görevleri serbest bırakmamıza yardımcı olur. 


MultiThreading ve Concurrency

Bu terimleri çevirmek biraz yanlış olsa da çoklu kullanım ve eşzamanlılık olarak çevirebiliriz. Aslında bizim için anlaşılması gereken önemli ve derinlemesine konulardır. Kısıtlı olan işlemcilerimizi en performanslı şekilde kullanarak, en kısa zamanda işlemlerimizi bitirmemiz gerekir. Eşzamanlılık ve çoklu kullanım kavramları genelde birbirine çok karışan hatta birbiri yerine kullanılan kavramlardır. 


Bu ikisinin farkını size şöyle bir örnekle anlatmak istiyorum:

Elimizde A konumundan B konumuna taşınacak kutularımız olsun. Eğer birden çok işçimiz varsa ve her işçimiz 1 kutu taşıyabiliyorsa bu çoklu kullanım(Paralellik) oluyor. Yine birden çok işçimizin olduğunu varsayalım fakat işçilerimizin birden çok kutu taşıyor olsun, bu da eşzamanlılık oluyor. Fazlasıyla karmaşık geldiğinin farkındayım, yakın zamanda daha detaylı bir mobi ile bu konuyu anlatacağım.  


Cocoa Touch

Temelde bir uygulama programlama arayüzüdür. Hareketleri algılama, animasyonlar gibi eylemleri yönetmemizi sağlar. UIKit kullanıcı etkileşimi (UX/UI) tarafında çalışırken, Foundation ise nesne davranışları ve yönetimini sağlayan bir backend olarak çalışır. 


Software Architecture

iOS ekosistemi katmanlı bir mimariye sahiptir. İşletim sistemi, yazdığımız uygulamarla donanım arasında bir köprü olarak çalışır. Yazılım mimarileri de bu katmanları yönetmemize ve erişimleri sağlamamıza imkan verir. Bu konu da oldukça ilgi çekici ve uzun bir konudur. MVC, MVP, MVVM, Viper, SOLID gibi mimarilere daha ayrıntılı bir mobi'de bahsedeceğiz. 


Version Control System 

VCS, uygulamamızın sürümlerini kontrol altına almamızı, eski sürümlerdeki dosyaları kaydetmemizi, değişikleri takip edebilmemizi sağlar. Ekip çalışmalarındaki iş bölümlerinde ortak bir noktadan çalışabilmemize de olanak sağlar. 


Test

Uygulamalarımızın testlerinin yapıldığı kısımlardır. Temelde Unit Test olarak geçer. İçerisinde XC Test ve UI Test olarak dallanır. Bu neymiş böyle diyerek içine girip, sonra da aşık olup vazgeçemediğim TDD metodolojisi de burada geliştirilmektedir. Bu konuda da güzel bir mobi yayınlayacağım :) 


Build - Deployment

Son birkaç adım artık. Geliştirdiğimiz uygulamamızı inşa edip dağıtma işlemlerini bu adımda gerçekleştiririz. 


AppStore

iTunes bağlantımızı da hazırladıktan sonra artık tek yapmamız gereken uygulamamızı AppStore hesabımızda yayınlamak. Tabiki reject yemezsek :) Apple'ın bu reject politikasını anlayana kadar  biraz hayattan soğuyabilirsiniz ama sabredip kavrayınca çok daha hızlı ilerleyen bir adım olduğunu göreceksiniz. 


Tebrikler artık yayınlanmış kaliteli bir uygulamamız var...


Diyagram çizmeyi biraz unutmuşum sanırım :) Fazlasıyla eksikleri var deyişinizi duyar gibiyim. Ancak bu kadarını sığdırabildim :)  Teknik detaylara girip yazıyı uzatıp sizleri sıkmak istemedim.
