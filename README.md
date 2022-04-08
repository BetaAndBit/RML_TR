# Sorumlu Makine Öğrenmesi Rehberi

## The Hitchhiker’s Guide to Responsible Machine Learning - Turkish Edition

Tahmin modellerini sorumlu bir yaklaşımla nasıl kurabiliriz?} Bu, farklı deneyim seviyelerindeki veri bilimciler tarafından bana sıklıkla sorulan bir sorudur. Görünüşte basit ama aynı zamanda zorlayıcı, çünkü ele alınması gereken farklı paydaşlara ait birkaç ortogonal konu ve bakış açısı var.

Model geliştiriciler, model eğitiminin otomasyonuna, performansının izlenmesine, hata ayıklamaya ve MLOps ile ilgili diğer konulara odaklanır. Tahmin modelleri kullanıcıları açıklanabilirlik, şeffaflık ve güvenlikle daha fazla ilgilenirken, adalet, önyargı, etik ise çoğunlukla toplumu ilgilendiren konulardır. Düzenleyiciler, özellikle büyük ölçekli etkileri olan model kullanımlarının sonuçları ile ilgilenmektedir.

Bu bakış açılarını dikkate alarak, Sorumlu Makine Öğrenmesi (RML) ile ilgili üç temel unsura odaklanıyoruz.

* **Algoritmalar** - Genellikle, verideki karmaşık ilişkileri ortaya çıkarmak için gelişmiş ve esnek makine öğrenmesi algoritmaları kullanmanız gerekir. Ancak, nasıl çalıştıkları anlaşılmadan kullanılmamalıdır. Do\-la\-yı\-sıy\-la sorumlu modelleme hakkında bir tartışma, karmaşık modellerin nasıl çalıştığı konusuna mutlaka değinmelidir.

* **Yazılım** - Gelişmiş modellerin eğitimi, yoğun hesaplama gerektiren bir süreçtir. Verimli eğitime izin veren paketler, birer mühendislik harikasıdır. Profesyoneller iyi araçlar kullanır, bu nedenle sorumlu modellemeyle ilgili bir hikaye yazılırsa, mutlaka iyi yazılımla ilgili bir bölüm içermelidir.

* **Süreç** - Tahmin modelleri kurmak yalnızca araçlarla ilgili değil, aynı zamanda planlama, lojistik, iletişim, teslim tarihleri ve hedeflerle de ilgilidir. Veri ve model keşfi süreci tekrarlı bir süreçtir, her tekrarda olduğu gibi, giderek daha iyi modellere ulaşırız. Araçları ne zaman ve nasıl kullanacağınızı bilmiyorsanız, yalnızca araçları kullanabilmek yeterli olmaz. Bu nedenle sorumlu modellemeden önce modelleme süreçlerin ele alınması gerekiyor.

Bu kitap, bahsedilen bu yönleri aynı anda bir araya getiren bir içeriğe sahiptir. İçeriği, bazı modern makine öğrenmesi yöntemlerini ve çalışma mekanizmalarından oluşmaktadır. Yöntemler, R dilinde\cite{Rcran} yazılmış örnek kodlarla desteklenmiştir. Beta ve Bit adlı iki karakterin maceralarını anlatan bir çizgi roman ile anlatım hikayeleştirilmiştir. Bu etkileşim, farklı bir model denemek, keşif için başka bir yöntem denemek, veya başka verileri aramak gibi analistlerin sıklıkla karşı karşıya kaldıkları, modeller nasıl karşılaştırılır veya nasıl doğrulanır gibi soruları ele alır.

Model geliştirme sorumlu ve zorlu bir iştir, aynı zamanda heyecan verici bir maceradır. Bazen ders kitapları sadece teknik tarafa odaklanır ve tüm eğlenceyi kaybeder.
Bu kitapta eğlenceli bir içerikle karşılaşacaksınız.


## Materiales 

* Flipbook: https://betaandbit.github.io/RML_TR/
* Tekrarlanabilir örnekler: [html](https://htmlpreview.github.io/?https://github.com/BetaAndBit/RML/blob/main/data/modelsXAI.html)
* Tekrarlanabilir örnekler: [Rmd](data/modelsXAI.Rmd)
* Veri: [covid_spring.csv](data/covid_spring.csv)
* Veri: [covid_summer.csv](data/covid_summer.csv)


