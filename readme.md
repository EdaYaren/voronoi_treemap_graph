# Treemap 

Treemap, hiyerarşik verilerin görselleştirilmesi için kullanılan bir tekniktir. Alan dolgu yöntemini kullanarak, her bir öğe, toplam verinin bir oranını temsil eden dikdörtgenler olarak gösterilir. Bu dikdörtgenlerin boyutu, temsil ettikleri veri miktarına orantılıdır. Treemap'ler, özellikle büyük veri setlerini görselleştirmek ve verilerin hiyerarşik yapısını kolayca anlamak için kullanışlıdır.


## Voronoi Treemap 

Voronoi Treemap, klasik treemap yönteminin bir çeşididir. Voronoi diyagramları kullanılarak oluşturulan bu haritalar, her bir hücrenin alanının veri değerine orantılı olduğu bir yapı sunar. Bu yöntem, verilerin daha organik ve estetik bir biçimde görselleştirilmesini sağlar.

## Proje Hakkında

Bu proje, ağaç haritalarının tarihçesi, tanımı, kullanım alanları, avantajları ve dezavantajlarını ele alır. Ağaç haritaları, hiyerarşik veri kümelerini görselleştirmek için kullanılan güçlü araçlardır ve büyük miktarda veriyi kompakt ve görsel olarak çekici bir şekilde düzenler.

## İçindekiler

- [Treemap](#Treemap)
  - [Tarihçe](#Tarihçe)
  - [Tanım](#Tanım)
  - [Kullanım Alanları](#kullanım-alanları)
  - [Avantajları ve Dezavantajları](#avantajları-ve-dezavantajları)
  - [Örnek Grafikler](#Örnek-Grafikler)
- [Veri](#Veri)
- [R Kodlarının Açıklanması](#r-kodlarının-açıklanması)
- [Sonuçlar](#sonuçlar)



## Veri Kümesi

Bu projede kullanılan [veri seti](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016), 1985'den 2016'ya kadar uzanan bir zaman diliminde, ülkelere ait intihar oranlarına ilişkin bilgileri içermektedir. Bu veri seti, analiz ve görselleştirme için kullanılmıştır.

### Kullanılan Değişkenler

- **Ülke:** Veri setindeki her gözlem için ülke adı.
- **Yıl:** İlgili intihar verisinin yılı.
- **Cinsiyet:** İntihar eden bireylerin cinsiyeti (Erkek/Kadın).
- **Yaş Grubu:** İntihar eden bireylerin yaş grubu.
- **İntihar Oranı:** İntihar sayısının nüfusa oranı (100.000 kişi başına düşen intihar sayısı).

## Sonuç Grafiği

Sonuç grafiği, projede kullanılan veri setini ve analiz edilen değişkenleri görselleştirmek için oluşturulmuştur. Grafikte en fazla intihar oranına sahip olan 1999 yılına ait 5 yaş grubu için 10 ülkedeki kadın ve erkek intihar oranlarına dair voronoi ağaç haritası verilmiştir.





