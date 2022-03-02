# Agile Project Management 
Tore Dyba°, Torgeir Dingsøyr, and Nils Brede Moe

### Özet
Çevik yazılım geliştirme, yazılım projelerini planlamak ve yönetmek için yeni bir yaklaşımı temsil eder. 
Ön planlara ve sıkı kontrole daha az önem verir. Genellikle resmi olmayan işbirliğine, koordinasyona ve öğrenmeye dayanır. 
Bu çalışma, kapsamlı endüstriyel projeler için çevik proje yönetiminin bir karakterizasyonunu ve tanımını sağlamayı amaçlamıştır. İş süreçlerinin doğrudan denetlenmesi ve standardizasyonuna odaklanan geleneksel yönetimden, fırsatları ve faydaları, aynı zamanda karmaşıklığı ve zorlukları da dahil olmak üzere kendi kendini yöneten ekiplere daha yeni, çevik odaklanmaya geçişin arkasındaki koşulları açıklar. Çalışmanın ana katkısı, çevik proje yönetiminin dört ilkesidir: minimum kritik belirtim, özerk ekipler, tekrardan dolayı fazlalık, geri bildirim ve öğrenme.

## 1. Giriş
Bir projeyi oluşturan benzersiz ve karmaşık süreçleri yönetmek, belirli yönetim faaliyetlerinin uygulanmasını içerir. Temel olarak proje yönetimi, projenin geliştirilmesi için gerekli olan faaliyetlerin planlanması, yürütülmesi ve izlenmesinden oluşur. Çoğunlukla yazılım projelerinin yüksek maliyetleri ve başarısızlık oranları olmaktadır. Bu durum araştırmacıları ve uygulayıcıları birkaç ilerlemeye rağmen çiddi bir şekilde meşgul etmektedir. Yazılım projelerinin etkin yönetimi hala kritik bir zorluktur. Bu zorluk, son on yılda çevik yazılım geliştirmeye büyük ilgi gösterilmesine neden olmuştur. Çevik bir dizi yöntem ortaya çıkmıştır.(Dingsøyr et al. 2012)
Scrum en yaygın kullanılan yöntemlerin biridir. Çevik yazılım geliştirmede geliştiriciler, sistem kullanıcılarını temsil eden müşterilerle ekipmişcesine birlikte çalışmaktadırlar. Her geliştirme döngüsünde eklenecek özelliklere müşteri ve geliştirme ekibi ortaklaşa karar verebilmektedir(Schwaber and Beedle 2001). Ek olarak çevik bir proje yapısında proje yöneticisinin rolü, projeyle ilgili kararların alınmasında ekiple birlikte çalışma ve kolaylaştırma olarak tanımlanmaktadır.(Abramson et al. 2010)

Yazılım geliştirmede Birleşik Krallık hükümeti tarafından geliştirilen ve savunulan PRINCE2 gibi resmileştirilmiş, genel proje yönetimi metodolojileri aracılığıyla bu faaliyetleri standartlaştırmaya yönelik bir eğilim olmuştur. Proje yönetimi olgusunun küresel bir kavramı olmasına rağmen, birleşik bir proje yönetimi teorisi veya iyi tanımlanmış proje başarısı ölçüleri oluşamamaktadır.(Garel 2013)

Geleneksel proje yönetimi, 1950 - 1960 yılların sistem mühendisliği ve kalite disiplinlerinin türemiştir. Temel olarak geleneksel proje yönetimi, geliştirmeyi gereksinimler, tasarım, kodlama ve test gibi iyi tanımlanmış faaliyetlerin doğrusal bir dizisi olarak görmektedir. Projenin hedefi ve beklenen çözüm hakkında neredeyse mükemmel bilgiye sahip olduğunuzu varsaymaktadır. Sonuç olarak, kapsam, program veya kaynaklardaki sapmalara kolayca uyum sağlayamamaktadır.(Pich et al. 2002)

Donanım geliştirme, geleneksel yaklaşıma daha uyumlu görünmektedir. Fakat yazılım gibi doğası gereği daha soyut çalışmalarda tam bir netlik söz konusu olmadığı için geleneksel yöntemler yetersiz kalmaktadır. Bu yönetimsel zorluktan dolayı  “The Capability Maturity Model for Software” (CMM) olarak bilinen yazılım sürecini yönetmek ve iyileştirmek için bir çerçeve geliştirdi. PRINCE2 gibi çağdaş proje yönetimi metodolojileri, bu mühendislik geleneğini temel alan ve Scrum gibi reaktif ve uyarlanabilir yöntemlerle çelişen standartlaştırılmış, süreç odaklı proje yönetimi metodolojileridir. Çoğu kişinin unuttuğu şey, PRINCE kısaltmasının “Kontrollü Ortamda Proje” anlamına geldiğidir. Çoğu yazılım projesinin çalıştığı ortama eşit derecede uymaması şaşırtıcı olmamalıdır.(Woodfield 1979)

Yazılım projelerinin yönetimi için karmaşıklık ve belirsizlik önemli sorunlar doğurmaktadır. Proje karmaşıklığı, yazılım projesinin birçok farklı eylemi ve durumu ile çevresel parametrelerinin etkileşime girmesi anlamına gelir. Bu yüzden eylemlerin etkilerinin değerlendirilmesi zordur. Yazılım geliştirmenin klasik problemlerinin çoğu, karmaşıklıktan ve boyutla birlikte üstel artışından kaynaklanmaktadır; örneğin, problem karmaşıklığındaki her %25'lik artış için, yazılım çözümünün karmaşıklığında %100'lük bir artış olduğu tahmin edilmektedir. Diğer bir zorluk ise, çoğu yazılım problemini anlamak için gereken bilginin, kişinin onları çözme fikrine bağlı olmasıdır.(De Meyer et al. 2002) Yazılım projelerinin uğraştığı problemler benzersiz olma ve formüle edilmesi zor olma eğilimindedir. Ayrıca geliştiriciler neyin çözülmesi gerektiğine daha iyi anladıkça çözümler gelişmektedir. Planlamaya geliştiricinin yetenekleri ve performansını dahil ettiğinizde yönetim probleminin zorluğu ortaya çıkmaktadır. Sorunun karmaşıklığına ve çözümüne ek olarak, hızlı değişen ve son derece belirsiz ortam, örneğin pazar türbülansı ve müşteri gereksinimlerindeki ve proje hedeflerindeki değişikliklerdir. Bu nedenle, gelecekteki olaylarla ilgili varsayımlarımızın ve tahminlerimizin doğası gereği belirsiz olacağını kabul etmek gerekir. Yazılım projelerini yönetirken, geçmiş eğilimleri tahmin etme veya geçmiş deneyimlere çok fazla güvenme konusunda son derece dikkatli olmamız gerekir. Eğilimler tükeniyor ve gelecek, beklenmedik gelişmelerin yanı sıra öngörülemeyen insan davranışlarıyla doludur. 

Bir projede var olan belirsizlik ne kadar büyük olursa, ekibin sabit bir faaliyetler dizisine dayanan geleneksel yaklaşımlardan, faaliyetleri ve hatta proje planının yapısını yarı yolda yeniden tanımlamaya izin veren yaklaşımlara o kadar fazla geçmesi gerekir. Bu nedenle, proje karmaşıklığı ve belirsizliği arttıkça, yöneticilerin geleneksel risk yönetiminin ötesine geçmesi gerekir; planlamaya daha az, daha çok esneklik ve öğrenmeye yönelik rolleri ve teknikleri benimsemek gerekmektedir. 

## 2. Gelenekselden Çevik Proje Yönetimine

Çevik proje yönetimi özünde karmaşıklığın ve belirsizliğin bir proje üzerindeki etkisini yönetmekle ilgilidir.

- Planlama ve yürütme arasında çok daha kısa bir zaman dilimine duyulan ihtiyaç
- Bir eylemin planlanması, uygulanmasının tüm ayrıntılarını sağlamaz
- Çevreyi anlamlandırmak için yaratıcılık ve öğrenmenin gerekli olduğu

Çevik proje yönetimi, uygulamalarda olduğu kadar yönetim rollerinde de değişiklikler getirir. Örneğin Scrum, yazılım projelerinde üç rol tanımlar: geliştirme ekibi üyeleri, bir scrum master ve ürün sahibi.(Dybå 2000; Conboy et al. 2011)

Scrum master görevi, geliştirme ekibinin toplantılarını organize etmek ve ekibin karşılaştıkları engellerin üstesinden gelmesini sağlamaktır. 

Ürün sahibinin görevi, geliştirilecek olanı önceliklendirmektir. 

Bunun dışında takımın kendi kendini yönetmesi gerekir. Bununla birlikte, uygulamada, birçok şirket aynı zamanda, bir ürün sahibine gereksinimler üzerinde çalışmasına yardımcı olmak ve dahili ve harici raporlama gibi yazılım geliştirme ile doğrudan ilgili olanlar dışındaki diğer konuları ele almak için bir proje yöneticisi atamaktadır. 

İşin temel felsefesi geleneksel gelişimden çevik gelişime geçiş, standart süreçlerden ziyade insanlara ve onların yaratıcılığına güvenerek karmaşıklık ve öngörülemezlik ile başa çıkmayı ve böylece komuta ve kontrolden ortak karara geçmeyi hedeflemektedir. (Kozlowski and Bell 2003)

Çevik yazılım geliştirmenin tanıtılmasıyla birlikte, kendi kendini yöneten yazılım ekipleri yaygın olarak tavsiye edilir hale geldi. Yazılım geliştirmeyi kendi kendini yöneten ekiplerde organize etmek, artan verimlilik, yenilikçilik ve çalışan memnuniyeti gibi birçok avantaja sahip olsa da, bireyleri bir araya getirmek ve bu tür ekiplerde nasıl verimli çalışacaklarını otomatik olarak bilmelerini beklemek yeterli değildir(Kirkman and Rosen 1999). Kendi kendini yöneten takımlara liderlik etmenin geleneksel takımlara liderlik etmekten daha zor olduğu söylenebilir, çünkü proje yöneticisinin paylaşılan liderliği (merkezi liderliğin tersi), paylaşılan karar vermeyi, paylaşılan zihinsel modelleri ve sürekli bir öğrenme ve iyileştirme sürecini etkinleştirmesi gerekir. Ayrıca, ekip üyelerinin çeşitli işler yapmak için çapraz eğitim almış olması, işlevsel fazlalığı ve dolayısıyla ekibin personel eksikliğiyle başa çıkma esnekliğini artırır. Kendi kendini yöneten ekiplerin faydaları üzerine birkaç çalışma olmasına rağmen, bu tür ekiplerin üretkenlik, işten ayrılma ve aykırı tutumlar gibi ölçümler bakımından beklenildiği gibi olumlu sonuçlar alınmamıştır.(Dingsøyr and Lindsjørn 2013)

Kendi kendini yöneten çevik bir ekip oluşturmayı ve sürdürmeyi başarmak için proje yöneticisi tüm bu koşulları sağlamalıdır. Çevik bir proje yöneticisi olarak başarılı olabilmek için farklı özerklik düzeylerini anlamak da önemlidir. Çevik bir ekibin hem ekip hem de bireysel seviyelerde özerkliğe ihtiyacı vardır. 

Proje yöneticisi şunları sağlamalıdır:
- Ekip, çalışma stratejilerini ve süreçlerini, proje hedeflerini ve kaynak tahsisini tanımlama yetkisine sahiptir.
- Tüm ekip üyeleri ortaklaşa karar verme yetkisini paylaşır.
- Bir ekip üyesi, verilen görevi yerine getirme konusunda biraz özgür olmalıdır. 

## 3. Ortak Karar Verme 
![Şekil 1](/week-1/agile01.png)

*Şekil 1* gösterldiği gibi geleneksel geliştirmede karar verme hiyerarşik komuta ve kontrol yapısı tarafından yönetilirken, çevik geliştirme ekibinde yetkilendirme ve ortak karar verme her düzeyde teşvik edilir(Moe et al. 2012). Çoğu organizasyonda, karar vermenin bu iki yolunun bir karışımını bulacaksınız.(Aurum et al. 2006)

Çevik ekiplerde uyarlanabilirlik esastır. Çevik ekiplerde ortak karar vermenin çeşitli faydaları olsa da, bazı zorluklar da vardır.
- Farklı geçmişlere ve hedeflere sahip paydaşları içeren ortak karar verme yaklaşımı, kararların çoğundan proje yöneticisinin sorumlu olduğu geleneksel yaklaşımdan daha sorunludur.
- Ortak karar vermenin faydalarına rağmen, uyum, etkisiz veya işlevsiz karar vermenin bir kaynağı olarak belirtilmiştir. Takım uyumuyla ilgili belki de en çok belirtilen sorun grup düşüncesidir.
- Her kararın her ekip üyesinin eşit katılımıyla ortaklaşa alınması gerekmediğini, bunun yerine ekibin yetkiyi ekip içindeki bireylere veya alt gruplara devredebileceğini anlamak önemlidir. Buradaki zorluk, hangi ekip üyesinin hangi kararlara dahil olması gerektiğini anlamaktır.
- Ekipte acemiler varsa, çevik proje yöneticisinin acemileri uzman olana kadar aşamalardan nasıl geçireceğini belirlemesi gerekir.
- Ekiplerin bu tür toplantılarda etkili karar alma süreçleri gerçekleştirmesini sağlamak için proje yöneticisinin ekip üyelerinin ortak bir zihinsel model geliştirdiğinden emin olması gerekir; yani, görevleri çözmek için ihtiyaç duyulan bilgi ve gereksinimlerden ve neyden kimin sorumlu olduğu konusunda ortak bir anlayışa sahip olmalıdırlar.

Çevik proje yönetiminde, ortak karar verme için önemli bir forum, günlük işlerin koordine edilmesi ve planlanmasıyla ilgili olduğu için stand-up toplantısıdır. Toplantının kısa olması gerekiyor ve toplantının amacı iletişimi geliştirmek, hızlı karar vermeyi vurgulamak, teşvik etmek, engelleri belirleyip ortadan kaldırmaktır. Günlük toplantı, çevik ekibi üyelerinin karmaşık, dinamik ve gerçek zamanlı bir ortamda kararlar almak için deneyimlerini kullandıkları bir yerdir.(Lipshitz et al. 2001)

Çevik projelerde artan bağlılık durumlarından kaçınmak için, ekip toplantılarının kararları savunmak için bir yer haline gelmemesini sağlamak önemlidir. Takımların sadece kendi iç süreçlerini izlemeleri gerekmiyor, aynı zamanda takım toplantılarına hangi takım dışı üyelerin katılmasına veya gözlemlenmesine izin verildiğini de düşünmeleri gerekiyor. Ekip üyeleri, örneğin günlük toplantılarda ekip dışından kişilerin bulunması nedeniyle kararlarını savunmaya başlarsa veya yaptıklarına ilişkin ayrıntılı raporlar verirse, ekip dışındaki bu kişilerin düzenli olarak katılmamaları daha doğru olmaktadır.(Bjørnson and Dingsøyr 2008)

## 4. Çevik Proje Kick-off

Geri bildirim, ürün ve kişisel becerilerde ve ayrıca geliştirme sürecinde değişikliklere yol açabilecek öğrenme fırsatlarını temsil eder. Çevik geliştirmede “çalışan yazılım” ve “bireyler ve etkileşimler” üzerine odaklanıldığında bilgi, geleneksel yazılım geliştirmeden çok farklı bir şekilde yönetilir. Öğrenmek zor ama çok önemli.(Besner and Hobbs 2008)

Kick-off, proje yönetiminin en çok kullanılan araçlarından biridir. Kick-off ​​toplantısındaki tipik faaliyetler, proje için bir vizyon tanımlamak, roller, proje paydaşları oluşturmak ve projeyi planlamaktır. Normalde çevik bir ekip, birkaç yineleme için kaba bir plan ve bir sonraki için ayrıntılı bir plan yapacaktır. Ayrıntılı plan, ürün sahibinin geliştirilecek özelliklere öncelik vermesini sağlayarak Kick-off yapılabilir. Ekip için “plan” daha sonra öncelikli özelliklerin bir listesidir ve özellikleri geliştirme görevlerini kimin gerçekleştireceğine yineleme sırasında karar verilir. (Fægri 2010)

Geri bildirim ve öğrenmeyi mümkün kılmak için Kick-off ​​toplantısında önemli olan  paylaşılan zihinsel modelleri iyi tasarlamaktır. Paylaşılan zihinsel modeller,  görevler, teknoloji, ekip üyelerinin becerileri ve etkileşimler hakkındaki bilgileri içerir(Molokken-Ostvold et al. 2008). Planlama pokeri tekniği, paylaşılan zihinsel modelleri geliştirmenin bir yoludur. Tahmin tartışmaları, ekip üyesi becerilerini göstermenin yanı sıra eldeki görevler, geliştirmede kullanılan teknoloji hakkında bilgi sağlayabilir. 

*Planlama pokeri* şu şekilde gerçekleştirilir: Her bireye, genellikle 0, 1, 2, 3, 5, 8, 13, 20, 40 ve 1 olmak üzere bir Fibonacci dizisinde gevşek değerlere sahip bir dizi oyun kartı verilir. Her görev için, bireyler iş miktarını temsil eden bir karta karar verirler; bu, saat sayısı veya standart bir göreve göre olabilir. Tüm ekip üyeleri kartlarını gösterir ve en yüksek ve en düşük tahmine sahip kişiden gerekçelerini açıklaması istenir. Uzlaşma sağlanana kadar süreç tekrarlanır veya fikir birliği mümkün değilse, çoğunluk oyu veya oyların ortalamasına göre bir sayı belirlenir. Çok fazla farklılık varsa, bir görevi tahmin edilmesi daha kolay olan daha küçük görevlere ayırmak da gerekli olabilir. Çevik yöntemler basit ve hatırlaması kolaydır, bu da paylaşılan bir zihinsel model olarak çalışmayı kolaylaştırır(Fægri 2010).

## 5. Retrospektif

Retrospective toplu bir öğrenme etkinliğidir(Birk et al. 2002).

Ana motivasyon, projeye katılan bireyler ve muhtemelen bir bütün olarak kuruluş için gelecekteki uygulamaları iyileştirmek için neler olduğu üzerinde düşünmektir(Dingsøyr 2005).

Araştırmacılar *reflective practice* terimini kullanırlar. Bu "son zamanlarda ne olduğu hakkında kişinin yakın çevresinde kendisinin ve diğerlerinin anlamı üzerine düşünmek için periyodik olarak geri adım atma uygulamasıdır. Gelecekteki eylemler için bir temel sağlayarak hem kendisinin hem de başkalarının deneyimlediğini aydınlatır"(Dybå et al. 2014). Retrospektif, planların, gözlemlerin ve elde edilen uygulamaların ortaya çıkarılmasını ve açık sonuçlarını içerir. 

- Kerth, bir retrospektifin bir topluluğun üyelerinin iyileştirme ihtiyacını anlamalarına ve onları değişmeye motive etmelerine yardımcı olabileceğini savunuyor. Retrospektif, topluluğun “yazılım sürecinin ustası” olmasına yardımcı olur (Kerth 2001). 
- Retrospektiflerin öğrenmeyi, büyümeyi ve katılımcı olgunluğunu teşvik ettiği ve başarıyı kutlamak için bir fırsat sağladığı iddia edilmektedir.
- Derby ve Larsen ayrıca retrospektiflerin üretkenliği, yeteneği, kaliteyi ve kapasiteyi artırdığını öne sürüyorlar; amaç “bütün takım halinde öğrenme”dir (Derby ve Larsen 2006).

Retrospektif amacı değişikliklerle ilgili kararlar bu temelde alınır ve bir sonraki yinelemede görevler olarak planlanır.

Birçok ekip, işbirliği, koordinasyon ve iletişim için merkezi bir unsur olarak görsel panoları, kanbanları, 3 veya “bilgi yayıcılarını” kullanır (Sharp ve Robinson 2010).
Fiziksel bir pano, genellikle alternatif olan elektronik bir sistemin aksine bilgi miktarını sınırlamayı kolaylaştırır.
Kart gibi fiziksel eserler, sorumluluk simgelerini temsil eder ve hareketli eserlerin, birçok ekibin kullandığı alternatif olan elektronik manipülasyon araçlarından daha fazla içgörü sağladığı bulunmuştur (Sharp ve diğerleri, 2006).

Bir görsel pano, bir projedeki yaygın sorunları keşfetmeyi kolaylaştırır: 
- tamamlanmayan görevler
- önemli tamamlanmayan görevler
- aynı anda çok fazla görev başlatılatılıyor


## Çevik Proje Yönetiminin İlkeleri

Yazılımın temel bir özelliği, fiziksel olmayan biçimidir; yazılım kodu, esasen sınırsız karmaşıklığa, esnekliğe ve revize edilebilirliğe sahip büyük bir soyut talimatlar kümesidir. Yazılım, doğrusal olmayan davranış sergiler ve doğa yasalarına uymaz(Fægri et al. 2010). Çevik proje yönetimi, yazılımın bu temel özelliklerini ele alır ve geleneksel proje yönetiminin iyi tanımlanmış faaliyetlerinin doğrusal dizisinden kopar.

> ### 1. Minimum Kritik Spesifikasyon
> - Kesinlikle gerekli olandan fazlasının belirtilmemelidir.
> - Ekibin genel başarı için neyin kritik olduğunu belirlemesini gerektirir.
> Bu, sistem gereksinimlerinin ne yapılması gerektiği konusunda kesin olması gerektiği, bunun nasıl yapılacağı hakkında değil ve kuralların, standartların ve önceden tanımlanmış prosedürlerin kullanımının mutlak bir minimumda tutulması gerektiği anlamına gelir. Odak, daha büyük sistem gereksinimleri ve sınır koşulları üzerinde olmalı ve mümkün olduğunca çok tasarım kararı işe en yakın olanlara bırakılmalıdır. Sistemin çözmeyi amaçladığı “sorunu” anlamak, proje başarısının anahtarlarından biridir. Projenin başlangıç ​​toplantısı bunu başarmak için çok önemlidir.

> ### 2. Otonom Ekip
> Bu ilke, özerk veya kendi kendini yöneten ekiplerin yenilikçi yazılım projelerinin başarısı için bir ön koşul olduğu öncülüne dayanmaktadır.Otonom ekiplerin üyeleri, kendi süreçlerini yönetmekten ve izlemekten ve görevleri yerine getirmekten sorumludur(Moe ve diğerleri 2009).Bireysel geliştiricilerin kendi çalışmaları ve kendi görevlerinin programlanması ve uygulanması üzerinde yeterli kontrole sahip olmalarını sağlamak zorunludur. Otonom ekiplerin başarılı olması için, yaratıcılığı ve kendiliğindenliği bozacak herhangi bir kontrolden kaçınarak tüm organizasyonda güven ve bağlılık oluşturmak gerekir. Şirketin kontrol ihtiyacı değil, ekibin sürekli öğrenme ihtiyacı odakta olmalıdır.

> ### 3. Gereğinden Fazla Olma (Redundancy)
> Bu ilke, insanların yeni bilgi yaratması için ortak referanslara ihtiyaç duyduğunu göstermektedir. Bireylerin bilgi ve becerilerindeki örtüşmesi önemli bir gerekliliktir. Ekip içindeki redundancy seviyesi arttıkça, bireyler yeni bilgileri paylaşmayı daha kolay bulacak ve proje çalışmalarını daha etkin bir şekilde koordine edebilecektir. Projenin daha esnek ve uyarlanabilir hale gelmesi için ekibin her bir üyesinin birden fazla işlevde yetenekli olması gerektiğini ima eder, bu da bir işlevin farklı kişilerden yararlanarak birçok şekilde gerçekleştirilmesine olanak tanır. Çeşitli işler yapmak için çapraz eğitimli ekip üyeleriyle birlikte böyle bir fazlalığa sahip olmak, projenin işlevsel fazlalığını ve dolayısıyla ekibin personel eksikliğiyle başa çıkma esnekliğini artırır.

> ### Geribildirim ve Öğrenme
> Geri bildirim ve öğrenme olmadan çevik proje yönetimi mümkün değildir. Çevik projelerde önceden planlama yerine proje yürütmeye odaklanmak, öğrenme ile çalışmanın ve problem belirleme ile çözümün iç içe geçmesine yol açar(Rittel ve Webber 1973; Yeh 1991). Bu tür problemler için, sistemin çoğu inşa edilene ve kullanılana kadar gereksinimler tam olarak belirlenemez. Aynı zamanda ne kurulacağı belirtilmeden sistem kurulamaz. Proje, istenen bir sonuca ulaşmak için geri bildirim ve sürekli öğrenmeyi içselleştirilmiş bir alışkanlık haline getiren bir dizi adımda örtüşen ve paralel faaliyetlere izin vermelidir.

## Sonuç 
Çevik proje yönetimi ilkeleri, organizasyonlara ve sistemlere yeni ortaya çıkan özellikler sağlama potansiyeline sahiptir. Ancak, kuruluşlar bu ilkeleri benimsemede veya mevcut uygulamalarla bütünleştirmede dikkatli olmalıdır.

Çevik yönetim yöntemleri, görevlerde, insanların becerilerinde ve kullanılan teknolojide yüksek değişkenlik sergileyen projeler için idealdir.

Ayrıca, bürokrasi ve resmileştirme etrafında inşa edilenlerden daha fazla yenilikçiliğe yardımcı olan kuruluşlar için de uygundurlar.

Çevik yazılım projelerini yönetmedeki zorluk, önceden planlama ve öğrenme arasındaki dengeyi bulmaktır.

Düşük düzeyde karmaşıklık ve belirsizliğe sahip projeler daha fazla planlamaya izin verirken, yüksek düzeyde karmaşıklık ve belirsizliğe sahip projeler öğrenmeye daha fazla önem verilmesini gerektirir.


## Araştırılacak Konular
- PRINCE2 (yapılandırılmış bir proje yönetimi yöntemi ve uygulayıcı sertifika programıdır. PRINCE2, projeleri yönetilebilir ve kontrol edilebilir aşamalara ayırmayı vurgular. Birleşik Krallık, Batı Avrupa ülkeleri ve Avustralya dahil olmak üzere dünya çapında birçok ülkede benimsenmiştir.)
- the theory of naturalistic decision making (NDM) 
- Kick-off

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
  
