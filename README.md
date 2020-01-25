**Bu çalışma Dr. Şadi Evren Şeker'in Python ile Makine Öğrenmesi eğitim setinden yararlanılarak hazırlanmıştır.**

Sürümler: 
 - Conda -> 4.7.12

 - Python -> 3.7

# MAKİNE ÖĞRENMESİ
```En basit tabiriyle makine öğrenmesi; bilgisayarların direkt programlanmadan, kendilerine insan gözlemlerinin bilgi ve veri formunda verilmesiyle, insanlar gibi davranıp öğrenmesi bilimidir.  ```

Günümüzde Makine Öğrenmesi için birçok algoritma ve metodoloji mevcuttur. Temelde öğrenme yöntemine göre 3 gruba ayrılır: 

 1. Gözetimli (Supervised) Öğrenme
 2. Gözetimsiz (Unsupervised) Öğrenme
 3. Takviyeli (Reinforcement) Öğrenme

## Gözetimli Öğrenme
``` Girdi değişkenlerini (X), çıktı değişkenlerine (Y) eşleme işlevini öğrenmek için etiketli eğitim verileri kullanılır. Eğitim verisi hem girdilerden hem de çıktılardan oluşur. Bu fonksiyon, sınıflandırma veya regresyon algoritmaları ile belirlenebilir.```
 1. Sınıflandırma: Kategoriler halinde çıktı değişkenlerinin olduğu belirli bir örneğin sonucunu öngörmektir. Kadın ve erkek, hasta ve sağlıklı...
 2. Regresyon: Verilen değişkenin gerçek değerler biçiminde olduğu belirli bir örneğin sonucunu öngörmektir. Belirli bir bölgenin yağış miktarı ya da bir insan boyu...
## Gözetimsiz Öğrenme
```Gözetimsiz öğrenme, gözetimli öğrenmeden farklı olarak, verileri sebep-sonuç ya da giriş-çıkış şeklinde etiketlemeden, veri içerisinde var olan ilişkilerin ve yapıların öğrenilmesidir. Burada giriş verisinin hangi sınıfa ait olduğu belirsizdir. Gözetimsiz öğrenmenin iki önemli yaklaşımı boyut indirgeme ve kümelemedir.``` 
 1. Kümeleme: Farklı bir kümedeki örnekleri ayırıp birbirine benzeyen örnekleri bir arada toplamaya denir.
 2. Boyut İndirgeme: Önemli bilgilerin hala iletildiğini garanti ederken bir veri kümesinin değişkenlerinin sayısını azaltmak anlamına gelir. Boyut azaltma, öznitelik çıkarımı ve özellik seçimi yöntemleri kullanılarak yapılabilir.

## Takviyeli Öğrenme
```Pekiştirmeli öğrenme, davranışçılıktan esinlenen, öznelerin bir örtamda en yüksek ödül miktarına ulaşabilmesi için hangi eylemleri yapması gerektiğiyle ilgilenen bir makine öğrenmesi yaklaşımıdır.```
Bu problem, genelliğinden ötürü 
 - Oyun Kuramı
 - Kontrol Kuramı
 - Robotik
 - Yönetlem Araştırması
 - Bilgi Kuramı
 - Benzetim Tabanlı Eniyileme
 - İstatistik gibi birçok diğer dalda da çalışılmaktadır.
 
 Takviyeli öğrenmede bir eğitmen bulunur fakat gözetimli öğrenmedeki gibi sisteme çok detay vermez veya veremez. Bunun yerine öğrenen sistem bir karar verdiğinde bu kararın doğru olduğu durumlar için sistemi ödüllendirir ve yanlışlar için de cezalandırır. Amaç, öğrenen sistemin denediği olası durumların hedef olup olmadığının kontrolü ve denenen doğru veya yanlış tüm durumların hatırlanmasıdır. 



