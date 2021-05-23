# Q-Learning
YazLab 5. Proje

### Daha fazla bilgi için --> [Proje Raporu](https://github.com/mustafayigit34/Q-Learning/blob/main/Rapor.pdf)

Q-Learning algoritması ile 50x50'lik matris içerisinde engeller arasında optimum yolu bulma.

## Giriş
Bu projede ilk olarak açılan arayüzde kullanıcıdan başlangıç ve bitiş konumları-na atama yapmak için veri alındı. Daha sonra ise alınan bu veriler doğrultusunda rastgele engellerden ve geçişlerden oluşan bir çevre (matris) tanımlandı ve bunun ar-dından rastgele oluşturulan çevreye göre bir ödül tablosu (reward table) oluşturuldu. Elde ettiğimiz çevre ve ödül tablosu üze-rinden Q-Learning algoritması kullanılarak Q-table dolduruldu. Algoritma, geliştirici-ler tarafından belirlenen süre boyunca ça-lıştırıldı ve doldurulan Q-table doğrultu-sunda optimum yol (rota) bulunarak arayüz üzerinde bu yol gösterildi. Ardından da bö-lüm başına elde edilen ödül ve atılan adım sayısına bağlı olarak iki adet grafik çizdi-rildi. En son ise engellerin, geçişlerin ve başlangıç-bitiş noktalarının konumları “engel.txt” içerisine yazdırıldı.

## Proje İsterleri
Burada robotun Q learning algoritması kullanarak engel sütunlarından kaçması ve beyaz alanlardan
geçerek doğru yol alması gerekiyor. Aşağıdaki verilen matrisleri gerçek ortamdaki bir yol olarak düşünün.
Robotumuz mavi kareden başlayıp kırmızı kutulara çarpmadan bitiş kısmına en kısa(maliyetle) yoldan
ulaşırsa başarılı sayılacaktır.
Ajan, herhangi bir beyaz kareden başlayarak sağa, sola, aşağı, yukarı ve çapraz hareket edebilir. Atılan 
adımlar belirleyici olmalı ve engele çarpışmadıkça başarılı olur. Robot en son duvara geldiğinde robot 
sadece aşağı hareket ederek istenilen noktaya “37” gelecektir. Sonuç olarak robot başlangıç noktasından 
istenilen hedefe gelinceye kadar hiçbir engele çarpmadan ve en kısa yolu bularak ödülü alır. Rr: ajan[1,2,8] karelere 
çarparsa işlem bitirir. Aksi takdirde, diğer her kareden herhangi bir işlem yapmak rs ödüllendirilir.
