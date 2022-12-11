# ProstateCancer-InDepthUnderstanding-Visualizations :surfing_woman:

## tiff formatı nedir ve neden kullanılır? 

Etiketli Görüntü Dosyası Formatı (TIFF), 1986'da Aldus (artık Adobe'nin bir parçası) tarafından geliştirilen, değişken çözünürlüklü bir bit eşlemli görüntü formatıdır.
- TIFF dosyaları büyüktür ve çok yüksek kalitededir.
- Dört tür temel TIFF görüntüsü mevcuttur: iki düzeyli (siyah beyaz), gri tonlamalı, palet (yani dizine alınmış) ve RGB (yani gerçek renk).
- RGB görüntüleri 16,7 milyon renge kadar saklayabilir. Palet ve gri tonlamalı görüntüler 256 renk veya tonla sınırlıdır. TIFF'in ortak bir uzantısı da CMYK görüntülere izin verir.
- TIFF dosyalarını sıkıştırmak için Huffman ve LZW algoritmaları dahil olmak üzere bir dizi yöntem kullanılabilir. Sıkıştırılmış bile olsa, TIFF dosyaları genellikle benzer GIF veya JPEG dosyalarından çok daha büyüktür.
- Dosyalar çok büyük olduğundan ve her bir TIFF dosya türünün pek çok olası varyasyonu olduğundan, birkaç web tarayıcısı bunları eklentiler olmadan görüntüleyebilir.


## Görüntü seviyeleri nedir?

Bazı görüntü formatlarında, görüntü verilerinin sabit miktarda olası yoğunlukları vardır. Örneğin bir görüntü uint8 (işaretsiz tamsayı 8 bit) olarak tanımlanabilir, bu da her pikselin 0-255 arasında bir değere (yoğunluğa) sahip olabileceği ve her yoğunluğun o aralıkta bir tam sayı (tam sayı) olduğu anlamına gelir. 

Böylece 256 olası yoğunluk seviyesi verir. Bunu yorumlamanın başka bir yolu da katmanlardır. RGB (kırmızı yeşil mavi) tipi bir görüntü, rengi tanımlamak için üç katman kullanır (tek bir katman, büyük ölçekli bir görüntüyü tanımlar,
bazı görüntü türleri 3'ten fazla katman içerir). 


Benzer şekilde gri tonlama için iki seviye olabilir, yani siyah ve beyaz :yin_yang:

## Görüntü işlemede Aşağı örnekleme ve Yukarı örnekleme nedir?

Aşağı örnekleme ve yukarı örnekleme, görüntü görüntüleme, sıkıştırma ve aşamalı aktarım uygulamalarıyla birlikte iki temel ve yaygın olarak kullanılan görüntü işlemleridir.
Aşağı örnekleme, aynı iki boyutlu (2B) gösterimi korurken uzamsal çözünürlüğün azaltılmasıdır.

Genellikle görüntülerin depolama ve/veya iletim gereksinimlerini azaltmak için kullanılır. Örnekleme, bir görüntünün 2B temsilini korurken uzamsal çözünürlüğün artmasıdır.

Genellikle bir görüntünün küçük bir bölgesini yakınlaştırmak ve nispeten büyük bir çerçeve üzerinde düşük çözünürlüklü bir görüntü görüntülendiğinde ortaya çıkan pikselleşme etkisini ortadan kaldırmak için kullanılır.

# Gleason skor nedir?

- Prostat kanseri hücrelerinin derecesini değerlendirmek için kullanılan en yaygın ölçeğe Gleason skoru denir. 
- Gleason puanlaması iki sayıyı birleştirir ve 2'den (agresif olmayan kanser) 10'a (çok agresif kanser) kadar değişebilir, ancak aralığın alt kısmı o kadar sık kullanılmaz.


![gleasonscore](https://user-images.githubusercontent.com/78857072/206928920-bf98f6e3-d02e-478e-b003-eca68f4ed96b.png)

# ISUP derecesi nedir?¶
- Uluslararası Ürolojik Patoloji Derneği'nin (ISUP) güncel yönergelerine göre, Gleason skorları aşağıdaki kurala göre 1'den 5'e kadar bir ölçekte bir ISUP derecesinde özetlenir:

    - Gleason puanı 6 = ISUP derecesi 1
    - Gleason puanı 7 (3 + 4) = ISUP derecesi 2
    - Gleason puanı 7 (4 + 3) = ISUP derecesi 3
    - Gleason puanı 8 = ISUP derecesi 4
    - Gleason puanı 9-10 = ISUP derecesi 5
    - Numunede kanser yoksa, bu yarışmada ISUP derece 0 etiketini kullanırız.
    
    ![isup_grade](https://user-images.githubusercontent.com/78857072/206929004-311fd43c-19eb-49f8-80c3-5b0734b01e4f.png)



