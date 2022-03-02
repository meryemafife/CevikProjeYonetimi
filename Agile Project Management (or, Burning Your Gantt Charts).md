# Agile Project Management(or, Burning Your Gantt Charts)
## Embedded Systems Conference Boston (Boston, Massachusetts) ESC 247-267, October 2008
### Michael Karlesky & Mark Vander Voord


## Özet 

Değişikliği benimse. Programlar, bütçeler, rekabetçi ortamlar ve gereksinimler değişir. Geliştirme sırasında beklenmedik, zor sorunlar keşfedilir. Geleneksel gömülü proje yönetimi genellikle değişikliği ortadan kaldırmaya ve belirsizliği önceden tasarlamaya dayanır; böyle bir yaklaşım fantezidir. Çevik Proje Yönetimi, yaygın, kalıcı sorunlara çözümler sunar: zayıf tahminler, kayan zaman çizelgeleri, neredeyse bitmiş durumda çürüyen ürünler ve nadiren gerçeği yansıtan Gantt çizelgeleri. 

Burada tartışıyoruz: 
- müşteri 
- özellik 
- done
- önceliklendirme
- yinelemeler
- tahmin
- tükenmişlik çizelgeleri
- belgeler
- risk
- kapsam yönetimi.

### 1. Giriş

Projeler değişir. Bu basit gerçek, temelde proje yöneticilerinin ve yazılım geliştiricilerin planlama eksikliğinden veya beceriksizliğinden kaynaklanmıyor. Aksine, değişim, büyüyen herhangi bir varlığın doğal bir özelliğidir. Bütçeler değişir. Kaynaklar değişir. Programlar değişir. Rekabet değişir. Müşteri ihtiyaçları değişir.

1. “Geleneksel proje yönetimi” ile esas olarak yazılım geliştirmenin üretimin özel bir versiyonu veya bir inşaat projesi olarak görüldüğü herhangi bir metodolojiye atıfta bulunuyoruz. Bu tür proje yönetimi, kritik yol analizi (genellikle Gantt çizelgeleri ile temsil edilir) yoluyla planlanan sıralı tasarım, uygulama ve test aşamaları ("şelale" yaklaşımı) ile tanımlanır. 
2. Yalnızca gereksinimlerinde herhangi bir değişkenlik veya bilinmeyen içeren projeleri ele alıyoruz. İyi tanımlanmış veri manipülasyonu veya I/O dönüşümleri ile sınırlı belirli “kara kutu” projeleri, burada tanımladığımız felsefe ve tekniklerin alanına girmeyebilir. Yeni ürün geliştirme, Ar-Ge geliştirme ve kullanıcı arayüzü çalışması gerektiren projeler (yani gömülü yazılım projelerinin çoğunluğu) Çevik proje yönetimi için çok uygundur.

### 2. Geleneksel Proje Yönetimi vs Çevik Proje Yönetimine Genel Bakış
