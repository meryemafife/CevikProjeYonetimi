# Agile Project Management

### Rashina Hoda ,Prof. James Noble ,Dr. Stuart Marshall

## Özet 

eXtreme Programlama (XP) ve Scrum gibi çeşitli çevik çerçeveler kullanılarak geliştirilen yazılım projelerinin yönetimi ile ilgili olan 'Çevik Proje Yönetimi'. Bu makale, çevik proje yönetimi üzerine önerilen araştırmaları özetlemektedir. Özellikle proje yöneticisinin rolünü, çevik bir çerçeveye geçiş sürecini ve sorunlarını ve dış kaynaklı çevik projelerin yönetimini keşfetmeyi umuyoruz.

### 1. Giriş

Bu yeni kurulumda, üç ana endişe alanı buluyoruz ve bunları araştırmamızın ana amaçları olarak keşfetmek istiyoruz.
Araştırmanın amacı, XP, Scrum, Crystal vb. gibi çevik yazılım metodolojilerini kullanan şirketler, uygulayıcılar veya danışmanlar içindeki 'Çevik Proje Yönetimi'ni araştırmaktır. 
- Çevik bir projede proje yöneticisinin rolü.
- Çevik bir çerçeveye geçiş süreci ve sorunları.
- Off-shore veya outsourced çevik yazılım projelerinin yönetimi.

Örneğin, yöneticinin çevik ilkeleri hayata geçirmeye çalışırken karşılaştığı baskı türlerini mevcuttur. 'Kendi kendini yöneten ekipler' [1] kavramının yönetimler açısından kabulu. Dış kaynak kullanımı yaygın bir uygulama haline geldikçe, başka zorlu sorularla karşı karşıyayız.   Makale ile bazı yönetimsel sorulara cevap bulmaya çalışılmıştır. Ayrıca  XP ve Scrum gibi çevik metodolojilerinin temelleri açıklanmıştır.

### 2. Agile Methods

Çevik metodolojiler, değişen gereksinimlere dinamik olarak uyum sağlayan ve daha iyi risk yönetimi sağlayan yinelemeli ve artımlı geliştirme stilini takip eder. Çevik manifesto [2] tarafından tanımlanan çevikliğin dört temel ilkesi şunlardır:
1. süreç ve araçlar üzerinden bireyler ve etkileşimler,
2. kapsamlı belgeler üzerinde çalışan yazılım,
3. sözleşme müzakeresi üzerinde müşteri işbirliği,
4. bir planı izleyerek değişime yanıt vermek.

Geleneksel yazılım geliştirme yöntemleri ile çevik çalışma tarzı arasında farklılıklar vardır. Öne çıkanlardan bazıları Tablo 1'de vurgulanmıştır.

| Kategoriler       | Geleneksel                             | Çevik |
| -----------       | -----------                            | -----------                    |
| Geliştirme Modeli | Traditional                            | Iterative                      |
| Yönetim           | Kontrol                                | Kolaylaştırma                  |
| Müşteri katılımı  | Gereksinim toplama ve teslim aşamaları | Yerinde ve sürekli dahil       |
| Geliştiriciler    | Ekipler içinde bireysel olarak çalışın | İşbirlikçi veya çiftler halinde|
| Teknoloji         | Yok                                    | Nesneye yönelimli              |
| Ürün Özellikleri  | Hepsi dahil                            | En önemli ilk                  |
| Test              | Geliştirme döngüsünün sonu             | İteratif                       |
| Dökümantasyon     | Kapsamlı                               | Sadece gerektiğinde            |

Müşteri gereksinimlerinin projenin tüm uzunluğu boyunca sabit kaldığını gerçekçi olmayan bir şekilde varsayan geleneksel geliştirme modelini benimserler. 
Çevik metodolojiler ise müşteri memnuniyetine odaklanır ve bu nedenle sadece ihtiyaç duyulan işlevselliklere odaklanılan yinelemeli geliştirme tarzıyla değişikliklere izin verir. 
Bir yinelemede yalnızca bir avuç dolusu görev başarıldığından, işlevleri gerektiği gibi değiştirmek ve ilişkili riskleri daha iyi yönetmek daha kolaydır. Crystal, Feature Driven Development (FDD), Dynamic Systems Development Method (DSDM) ve Adaptive Software Development gibi çevik metodolojilerin birçok versiyonu vardır. Daha çok XP ve Scrum odaklanmılmıştır.

####  *2.1 eXtreme Programming (XP)*

XP, iyi uygulamalardan oluşan bir koleksiyon derleyen ve onları en uç noktalara taşıyan Kent Beck [3] tarafından oluşturuldu. Çoğunlukla küçük ve orta ölçekli projeleri hedef almış ve dünya çapında hızlı bir kabul ve uygulama kazanmıştır. 

**Beş XP değeri** 
1. iletişim
2. basitlik
3. geri bildirim
4. cesaret
5. saygı

**Ayırt edici ilkeleri**
1. oyun planlama
2. küçük sürümler
3. metaforlar
4. basit tasarım
5. yeniden düzenleme
6. eşli programlama
7. test etme
8. ortak mülkiyet
9. 40 saatlik çalışma haftası
10. yerinde müşteri
11. kodlama standartları 
12. sürekli entegrasyon

Müşteriler, gerekli işlevlerin özelliklerini kullanıcı hikayeleri [4] şeklinde sağlar.Teknik olmayan formatlarda özlü bir şekilde yazılırlar ve herhangi bir tasarım detayından kaçınarak kullanıcının ihtiyaçlarına odaklanırlar. Geliştiricilerin uygulama süresini tahmin etmelerine ve sürüm planlamasına girmelerine yardımcı olurlar. 

Geliştiriciler çiftler halinde çalışır ve birim testleri gerçekleştirir ve sıklıkla kodu entegre eder.

Müşteri ideal olarak yerinde bulunur ve hızlı geri bildirim yoluyla geliştirme sürecine yakından katılır.

Test önemli bir bölümdür ve sıklıkla birim testleri ve kabul testi şeklinde yapılır.

Uzun dokümantasyondan kaçınılır ve optimizasyon en sona bırakılır. 

####  *2.2 Scrum*

Scrum, Jeff Sutherland tarafından geliştirilen ve Ken Schwaber tarafından resmileştirilen başka bir çevik geliştirme metodolojisidir.

Bu sürece dahil olan roller Ürün Sahibi, Scrum Master ve takımdır. 
Ürün Sahibi, doğru iş bakış açısını sürdürmekten sorumludur. Scrum Master, Ürün Sahibi ile birlikte çalışır ve ekibi kolaylaştırır. Takım yedi (artı/eksi iki) üyeden oluşmalıdır. 
Faaliyetler arasında sprint planning, sprint review, ve scrum meeting yer alır.
Bir sprint, genellikle bir dizi seçilmiş hikaye üzerinde çalışıldığı 2 ila 4 haftalık geliştirme süresidir. 

Sprint review, önceki sprint'i elde edilen görevler açısından gözden geçirir ve bir sonraki sprint ayrıntıları tanımlanır.

Scrum Master, her üyenin görevlerini ve endişelerini kısaca açıkladığı günlük 15 dakikalık bir toplantıya öncülük eder.

Üretilen eserler **Product Backlog**, **Sprint Backlog** ve **Burndown Chart** olarak adlandırılır. 

**Product backlog** listesi, müşteriye [5] teslim edilen değere göre öncelik verilen ürün özelliklerinin bir listesidir ve Ürün Sahibi tarafından korunur. 

**Sprint backlog** listesi, bir özelliği uygulamak için ihtiyaç duyulan geliştirme görevlerini ifade eder ve **Product Backlog** listesinin bir alt kümesidir. 

**Burndown Chart**, bir sprintte kalan toplam işi gösterir.

### 3. ÇEVİK PROJE YÖNETİMİ

Proje yönetimi, herhangi bir yazılım geliştirme sürecinin ayrılmaz ve vazgeçilmez bir parçasıdır. Ekipleri yönetmek, müşteri ilişkileri, maliyet azaltma, risk yönetimi, proje zaman çizelgesini ve bütçeyi korumak proje yönetiminin püf noktasını oluşturur. Bu temel görevler aynı kalsa da, yürütme ayrıntıları her çevik çerçeve için biraz farklıdır. **Büyük ölçüde farklı olan şey, düşünme şeklidir.**

Proje yöneticisinin rolü, çevik metodolojilerin evrimi ile önemli değişiklikler geçirdi.

Sanjiv Augustine ve Susan Woodcock, proje yöneticisinin rolünü keşfediyor ve ilhamsız bir görev yöneticisine karşı vizyoner lider kavramını öneriyorlar. Geleneksel yönetim, yöneten ve emreden olarak görülürken, deneyimli çevik proje yöneticileri, 'hafif dokunuşlu' liderlikle 'kendi kendini yöneten ekipler' vaaz ediyor[1].

Mary Poppendieck *liderler gereklidir, yöneticiler isteğe bağlıdır.* fikrini savunuyor. Bu bir oksimoron mu? [8] burada Poppendieck, “Dolardan maksimum değeri almayı görev edinen yönetimden liderlik görevlerini ayırıyorum"



### Referanslar

[1] Augustine, S., Payne, B., Sencindiver, F., and Woodcock, S. 2005. Agile project management: steering from the edges. Commun. ACM 48, 12 (Dec. 2005), 85-89.

[2] http://agilemanifesto.org/ (Dec. 2007)

[3] Kent Beck, Extreme programming explained: embrace change, Addison-Wesley Longman Publishing Co., Inc., Boston, MA, 1999

[4] http://extremeprogramming.org/ (Dec. 2007)

[5] http://www.scrumalliance.org/view/scrum_framework (as of Dec. 2007)

[6] Strauss, Anselm and Glaser, Barney (1967). The Discovery of Grounded Theory: Strategies for Qualitative Research. Chicago: Adline.

[7] Strauss, Anselm and Corbin, Juliet (1990). Basics of Qualitative Research Grounded Theory Procedures and Techniques. Sage Publications.

[8] Anderson, L., Alleman, G. B., Beck, K., Blotner, J., Cunningham, W., Poppendieck, M., and Wirfs-Brock, R. 2003. Agile management - an oxymoron?: who needs managers anyway? OOPSLA '03. ACM, New York, NY, 275-277.

[9] Nerur, S., Mahapatra, R., and Mangalaraj, G. 2005. Challenges of migrating to agile methodologies. Commun. ACM 48, 5 (May. 2005), 72-78.

### Araştırılacaklar

- Agile Project and Agile People Management: Agile Management techniques
- Agile Software Management
- Agile Hardware Management
- Agile Methodologies
- Çevik ilkeleri hayata geçirmek için yöneticiler ve çalışanlar nasıl motive olabilir? Yeni bir sistemi ikna etmek ve kabul ettirmek zor olduğu görülmektedir.
- Kendi kendini yöneten ekipler kavramı tam olarak nasıldır? Yöneticinin buradaki konumlanması nasıl olacaktır?
- Çevik yönetici rolleri geleneksel yönetici rollerinden nasıl farklıdır?
- Kuruluşlar, çevik gibi radikal olarak yeni bir çerçeveye nasıl uyum sağlar? Yalnızca teknik becerilerin derecelendirilmesini mi yoksa bakış açısında ve kuruluşun çalışma biçiminde tam bir değişikliği mi kapsıyor?
- Dış kaynaklı veya off-shore projeler için çevik proje yönetimi ne kadar zor?
- Farklı kıtalara ve zaman dilimlerine yayılmış dağınık ekipleri senkronize etmeye çalışmaktan dolayı iletişim birincil bir endişe haline mi geliyor yoksa yönetim zarar görüyor mu?
- Çeviklik, projelerin ana şirketleri tarafından dışarıdan temin edildiği ekiplere mi yükleniyor yoksa çevik süreçleri izlemeyi özgürce mi seçiyorlar?
- Kullanıcı hikayeleri kısmı biraz karışık ve önemli bir yer kaplıyor. Daha detalı bakılabilir. 
- Savunma sanayi kapsamında müşteri tanımı ve ne kadar dahil olabileceği detaylı düşünülmelidir. 
- Çevik bir ortama geçişte insanlarla ilgili, süreçle ilgili ve teknolojik konularla ilgili zorlukları incelenmesi önemlidir.[9] bunu inceleyen bir makaledir.
