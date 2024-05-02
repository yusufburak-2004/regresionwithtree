# Regresyon ile Ağaç Analizi

## Giriş

Bu depo, bağımsız özelliklere dayalı olarak sonuçları tahmin etmek için ağaç tabanlı regresyon analizinin kullanımını göstermektedir. Geleneksel regresyon yöntemleri yerine, ağaç tabanlı regresyon, her özelliğin tahmine nasıl katkıda bulunduğuna dair detaylı bir analiz sağlar.

## Açıklama

![Görsel 1](https://github.com/yusufburak-2004/regresionwithtree/assets/145719589/359a0d1c-d38f-4999-a79f-604d1a8242d2)

İlk görselde, her sütun büyüklük sırasına göre 10'un kuvvetleriyle gösterilir. Ancak, vektörel bir çarpım toplamı yapılır ve "displ" sütununa yazılır, ardından hedef değişkenle karşılaştırılır.

![Görsel 2](https://github.com/yusufburak-2004/regresionwithtree/assets/145719589/d9a0811b-c549-49bb-9fd5-358df0837168)

Burada, görüldüğü gibi ağırlık değeri, hak ettiğinden daha az katsayı alır. Normalde, bunu "ideal" ve "aşırılık" olmak üzere 2 sütuna bölerdik, ancak zaman yok! Bu yüzden **AGAÇ** dedik!!

![Görsel 3](https://github.com/yusufburak-2004/regresionwithtree/assets/145719589/c5902e1e-70c1-4790-bcd8-625975a71418)

Burada, her ağırlık 4-6 aralığına geldiğinde (ideal), sapmalar oluşur. Bu, ağaç regresyon analizinin ayrıntılı segmentasyonu sayesinde çözülür.

![Görsel 4](https://github.com/yusufburak-2004/regresionwithtree/assets/145719589/98e9152c-3f1f-4a82-a8bc-357f6e26a1c7)

Hata oranı da 10 kat daha düşüktür! Bu sayede her veri bağımsız sütunlara dönüştürülerek, ağaç regresyonu kullanarak güzel sonuç tahminleri yapılır! **Regresyonla uğraşmadan.**

---

Bu depo, ağaç tabanlı regresyonun özellikler ile hedef değişkenler arasındaki ilişki üzerinde detaylı bir bakış sunabileceğini ve sonuç olarak daha doğru tahminlere yol açabileceğini göstermektedir.

