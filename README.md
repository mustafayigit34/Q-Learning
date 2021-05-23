# Q-Learning
YazLab 5. Proje

### Daha fazla bilgi için --> [Proje Raporu](https://github.com/mustafayigit34/Q-Learning/blob/main/Rapor.pdf)

Q-Learning algoritması ile 50x50'lik matris içerisinde engeller arasında optimum yolu bulma.

## Giriş
Bu projede ilk olarak açılan arayüzde kullanıcıdan başlangıç ve bitiş konumları-na atama yapmak için veri alındı. Daha sonra ise alınan bu veriler doğrultusunda rastgele engellerden ve geçişlerden oluşan bir çevre (matris) tanımlandı ve bunun ar-dından rastgele oluşturulan çevreye göre bir ödül tablosu (reward table) oluşturuldu. Elde ettiğimiz çevre ve ödül tablosu üze-rinden Q-Learning algoritması kullanılarak Q-table dolduruldu. Algoritma, geliştirici-ler tarafından belirlenen süre boyunca ça-lıştırıldı ve doldurulan Q-table doğrultu-sunda optimum yol (rota) bulunarak arayüz üzerinde bu yol gösterildi. Ardından da bö-lüm başına elde edilen ödül ve atılan adım sayısına bağlı olarak iki adet grafik çizdi-rildi. En son ise engellerin, geçişlerin ve başlangıç-bitiş noktalarının konumları “engel.txt” içerisine yazdırıldı.
