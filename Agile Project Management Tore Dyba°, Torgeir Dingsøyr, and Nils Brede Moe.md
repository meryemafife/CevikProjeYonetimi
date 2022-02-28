# Agile Project Management 
Tore Dyba°, Torgeir Dingsøyr, and Nils Brede Moe

### Özet
Çevik yazılım geliştirme, yazılım projelerini planlamak ve yönetmek için yeni bir yaklaşımı temsil eder. 
Ön planlara ve sıkı kontrole daha az önem verir. Genellikle resmi olmayan işbirliğine, koordinasyona ve öğrenmeye dayanır. 
Bu çalışma, kapsamlı endüstriyel projeler için çevik proje yönetiminin bir karakterizasyonunu ve tanımını sağlamayı amaçlamıştır. İş süreçlerinin doğrudan denetlenmesi ve standardizasyonuna odaklanan geleneksel yönetimden, fırsatları ve faydaları, aynı zamanda karmaşıklığı ve zorlukları da dahil olmak üzere kendi kendini yöneten ekiplere daha yeni, çevik odaklanmaya geçişin arkasındaki koşulları açıklar. Çalışmanın ana katkısı, çevik proje yönetiminin dört ilkesidir: minimum kritik belirtim, özerk ekipler, tekrardan dolayı fazlalık, geri bildirim ve öğrenme.

## 1. Giriş
Bir projeyi oluşturan benzersiz ve karmaşık süreçleri yönetmek, belirli yönetim faaliyetlerinin uygulanmasını içerir. Temel olarak proje yönetimi, projenin geliştirilmesi için gerekli olan faaliyetlerin planlanması, yürütülmesi ve izlenmesinden oluşur. Çoğunlukla yazılım projelerinin yüksek maliyetleri ve başarısızlık oranları olmaktadır. Bu durum araştırmacıları ve uygulayıcıları birkaç ilerlemeye rağmen çiddi bir şekilde meşgul etmektedir. Yazılım projelerinin etkin yönetimi hala kritik bir zorluktur. Bu zorluk, son on yılda çevik yazılım geliştirmeye büyük ilgi gösterilmesine neden olmuştur. Çevik bir dizi yöntem ortaya çıkmıştır.
Scrum en yaygın kullanılan yöntemlerin biridir. Çevik yazılım geliştirmede geliştiriciler, sistem kullanıcılarını temsil eden müşterilerle ekipmişcesine birlikte çalışmaktadırlar. Her geliştirme döngüsünde eklenecek özelliklere müşteri ve geliştirme ekibi ortaklaşa karar verebilmektedir. Ek olarak çevik bir proje yapısında proje yöneticisinin rolü, projeyle ilgili kararların alınmasında ekiple birlikte çalışma ve kolaylaştırma olarak tanımlanmaktadır.

Yazılım geliştirmede Birleşik Krallık hükümeti tarafından geliştirilen ve savunulan PRINCE2 gibi resmileştirilmiş, genel proje yönetimi metodolojileri aracılığıyla bu faaliyetleri standartlaştırmaya yönelik bir eğilim olmuştur. Proje yönetimi olgusunun küresel bir kavramı olmasına rağmen, birleşik bir proje yönetimi teorisi veya iyi tanımlanmış proje başarısı ölçüleri oluşamamaktadır.

Geleneksel proje yönetimi, 1950 - 1960 yılların sistem mühendisliği ve kalite disiplinlerinin türemiştir. Temel olarak geleneksel proje yönetimi, geliştirmeyi gereksinimler, tasarım, kodlama ve test gibi iyi tanımlanmış faaliyetlerin doğrusal bir dizisi olarak görmektedir. Projenin hedefi ve beklenen çözüm hakkında neredeyse mükemmel bilgiye sahip olduğunuzu varsaymaktadır. Sonuç olarak, kapsam, program veya kaynaklardaki sapmalara kolayca uyum sağlayamamaktadır. 

Donanım geliştirme, geleneksel yaklaşıma daha uyumlu görünmektedir. Fakat yazılım gibi doğası gereği daha soyut çalışmalarda tam bir netlik söz konusu olmadığı için geleneksel yöntemler yetersiz kalmaktadır. Bu yönetimsel zorluktan dolayı  “The Capability Maturity Model for Software” (CMM) olarak bilinen yazılım sürecini yönetmek ve iyileştirmek için bir çerçeve geliştirdi. PRINCE2 gibi çağdaş proje yönetimi metodolojileri, bu mühendislik geleneğini temel alan ve Scrum gibi reaktif ve uyarlanabilir yöntemlerle çelişen standartlaştırılmış, süreç odaklı proje yönetimi metodolojileridir. Çoğu kişinin unuttuğu şey, PRINCE kısaltmasının “Kontrollü Ortamda Proje” anlamına geldiğidir. Çoğu yazılım projesinin çalıştığı ortama eşit derecede uymaması şaşırtıcı olmamalıdır.

Yazılım projelerinin yönetimi için karmaşıklık ve belirsizlik önemli sorunlar doğurmaktadır. Proje karmaşıklığı, yazılım projesinin birçok farklı eylemi ve durumu ile çevresel parametrelerinin etkileşime girmesi anlamına gelir. Bu yüzden eylemlerin etkilerinin değerlendirilmesi zordur. Yazılım geliştirmenin klasik problemlerinin çoğu, karmaşıklıktan ve boyutla birlikte üstel artışından kaynaklanmaktadır; örneğin, problem karmaşıklığındaki her %25'lik artış için, yazılım çözümünün karmaşıklığında %100'lük bir artış olduğu tahmin edilmektedir. Diğer bir zorluk ise, çoğu yazılım problemini anlamak için gereken bilginin, kişinin onları çözme fikrine bağlı olmasıdır. Yazılım projelerinin uğraştığı problemler benzersiz olma ve formüle edilmesi zor olma eğilimindedir. Ayrıca geliştiriciler neyin çözülmesi gerektiğine daha iyi anladıkça çözümler gelişmektedir. Planlamaya geliştiricinin yetenekleri ve performansını dahil ettiğinizde yönetim probleminin zorluğu ortaya çıkmaktadır. Sorunun karmaşıklığına ve çözümüne ek olarak, hızlı değişen ve son derece belirsiz ortam, örneğin pazar türbülansı ve müşteri gereksinimlerindeki ve proje hedeflerindeki değişikliklerdir. Bu nedenle, gelecekteki olaylarla ilgili varsayımlarımızın ve tahminlerimizin doğası gereği belirsiz olacağını kabul etmek gerekir. Yazılım projelerini yönetirken, geçmiş eğilimleri tahmin etme veya geçmiş deneyimlere çok fazla güvenme konusunda son derece dikkatli olmamız gerekir. Eğilimler tükeniyor ve gelecek, beklenmedik gelişmelerin yanı sıra öngörülemeyen insan davranışlarıyla doludur. 

Bir projede var olan belirsizlik ne kadar büyük olursa, ekibin sabit bir faaliyetler dizisine dayanan geleneksel yaklaşımlardan, faaliyetleri ve hatta proje planının yapısını yarı yolda yeniden tanımlamaya izin veren yaklaşımlara o kadar fazla geçmesi gerekir. Bu nedenle, proje karmaşıklığı ve belirsizliği arttıkça, yöneticilerin geleneksel risk yönetiminin ötesine geçmesi gerekir; planlamaya daha az, daha çok esneklik ve öğrenmeye yönelik rolleri ve teknikleri benimsemek gerekmektedir. 

## 2. Gelenekselden Çevik Proje Yönetimine

Çevik proje yönetimi özünde karmaşıklığın ve belirsizliğin bir proje üzerindeki etkisini yönetmekle ilgilidir.

- Planlama ve yürütme arasında çok daha kısa bir zaman dilimine duyulan ihtiyaç
- Bir eylemin planlanması, uygulanmasının tüm ayrıntılarını sağlamaz
- Çevreyi anlamlandırmak için yaratıcılık ve öğrenmenin gerekli olduğu

Çevik proje yönetimi, uygulamalarda olduğu kadar yönetim rollerinde de değişiklikler getirir. Örneğin Scrum, yazılım projelerinde üç rol tanımlar: geliştirme ekibi üyeleri, bir scrum master ve ürün sahibi.

Scrum master görevi, geliştirme ekibinin toplantılarını organize etmek ve ekibin karşılaştıkları engellerin üstesinden gelmesini sağlamaktır. 

Ürün sahibinin görevi, geliştirilecek olanı önceliklendirmektir. 

Bunun dışında takımın kendi kendini yönetmesi gerekir. Bununla birlikte, uygulamada, birçok şirket aynı zamanda, bir ürün sahibine gereksinimler üzerinde çalışmasına yardımcı olmak ve dahili ve harici raporlama gibi yazılım geliştirme ile doğrudan ilgili olanlar dışındaki diğer konuları ele almak için bir proje yöneticisi atamaktadır. 

İşin temel felsefesi geleneksel gelişimden çevik gelişime geçiş, standart süreçlerden ziyade insanlara ve onların yaratıcılığına güvenerek karmaşıklık ve öngörülemezlik ile başa çıkmayı ve böylece komuta ve kontrolden ortak karara geçmeyi hedeflemektedir. 

Çevik yazılım geliştirmenin tanıtılmasıyla birlikte, kendi kendini yöneten yazılım ekipleri yaygın olarak tavsiye edilir hale geldi. Yazılım geliştirmeyi kendi kendini yöneten ekiplerde organize etmek, artan verimlilik, yenilikçilik ve çalışan memnuniyeti gibi birçok avantaja sahip olsa da, bireyleri bir araya getirmek ve bu tür ekiplerde nasıl verimli çalışacaklarını otomatik olarak bilmelerini beklemek yeterli değildir. Kendi kendini yöneten takımlara liderlik etmenin geleneksel takımlara liderlik etmekten daha zor olduğu söylenebilir, çünkü proje yöneticisinin paylaşılan liderliği (merkezi liderliğin tersi), paylaşılan karar vermeyi, paylaşılan zihinsel modelleri ve sürekli bir öğrenme ve iyileştirme sürecini etkinleştirmesi gerekir. Ayrıca, ekip üyelerinin çeşitli işler yapmak için çapraz eğitim almış olması, işlevsel fazlalığı ve dolayısıyla ekibin personel eksikliğiyle başa çıkma esnekliğini artırır. Kendi kendini yöneten ekiplerin faydaları üzerine birkaç çalışma olmasına rağmen, bu tür ekiplerin üretkenlik, işten ayrılma ve aykırı tutumlar gibi ölçümler bakımından beklenildiği gibi olumlu sonuçlar alınmamıştır.

Kendi kendini yöneten çevik bir ekip oluşturmayı ve sürdürmeyi başarmak için proje yöneticisi tüm bu koşulları sağlamalıdır. Çevik bir proje yöneticisi olarak başarılı olabilmek için farklı özerklik düzeylerini anlamak da önemlidir. Çevik bir ekibin hem ekip hem de bireysel seviyelerde özerkliğe ihtiyacı vardır. 

Proje yöneticisi şunları sağlamalıdır:
- Ekip, çalışma stratejilerini ve süreçlerini, proje hedeflerini ve kaynak tahsisini tanımlama yetkisine sahiptir.
- Tüm ekip üyeleri ortaklaşa karar verme yetkisini paylaşır.
- Bir ekip üyesi, verilen görevi yerine getirme konusunda biraz özgür olmalıdır. 

## 3. Ortak Karar Verme 
![Fig 1](/week-1/agile01.png)



## Araştırılacak Konular
- PRINCE2 (yapılandırılmış bir proje yönetimi yöntemi ve uygulayıcı sertifika programıdır. PRINCE2, projeleri yönetilebilir ve kontrol edilebilir aşamalara ayırmayı vurgular. Birleşik Krallık, Batı Avrupa ülkeleri ve Avustralya dahil olmak üzere dünya çapında birçok ülkede benimsenmiştir.)

## Önemli Noktalar
- Savunma sanayisi genellikle hem donanım hem yazılım bir anda içeren projelere sahip bir yapısı vardır. 
- Çevik Yazılım Geliştirme Manifestosu http://agilemanifesto.org/

## Ana Zorluklar
- Bireysel ve ekip özerkliği arasındaki çatışma, iyi işleyen çevik ekipler kurmayı zorlaştırır.
- Bireyler bağımsızsa ve çoğunlukla kendi programlarına ve kendi görevlerini yerine getirmeye odaklanırlarsa, grup üyeleri arasında daha az etkileşim olacak ve bu da ekip çalışmasının etkinliğini tehdit edecektir.
- Ekiplerin kendi kendilerini yönetmesi bazen katı bir hal alabilir bu da motivasyonu düşürmektedir. 

## Oluşan Sorular
- Bireysellik ve kendi kendin yönetme çevik yönetimde önemli bir kazanımdır. Çevik bir proje yöneticisi, çevik yazılım ekiplerinde ekip düzeyinde özerklik ile bireysel düzeyde özerkliği nasıl dengeleyebilir?
- Ekiplerdeki özerklik ve bireysellik özellikle sabit kapsam ve son teslim tarihlerine sahip pazar odaklı çevik projelerde geliştirme yapıldığında nasıl kontrol altında tutulabilecektir?
- Çevik proje yönetiminde ekip liderlerinin takım etkinliğini artırmak için ne yapmaları gerekmektedir?
- 
