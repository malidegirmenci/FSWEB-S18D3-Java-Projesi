# SQL Sorgu Alıştırmaları

Bu hafta SQL sorguları üzerine çalışıyorsunuz. Bugünkü alıştırmada sizin için hazırladığımız veritabanında aşağıda istediğimiz sonuçları elde etmenize yarayan SQL sorgularını oluşturacaksınız.

## Proje Kurulumu
Projeyi forklayın ve clonlayın. Tamamladığınızda da pushlayın.

### Kütüphane Bilgi Sistemi

Bu veritabanı, bir okulun kütüphanesinden öğrencilerin aldıkları kitapların bilgisini barındırmaktadır.

#### Tablolar 
`ogrenci` tablosu öğrencilerin listesini tutar.
`islem` tablosu öğrencilerin kütüphaneden aldıkları kitapların bilgilerini tutar
`kitap` tablosu kütüphanedeki kitapların bilgisini tutar
`yazar` tablosu kitapların yazarları bilgisini tutar
`tur` tablosu kitapların türlerini tutar.

Tablo ilişiklerini görmek için [ktphn.png] dosyasına göz atın.

Yazdığınız sorguları buradan test edebilirsiniz: [https://ergineer.com/assets/materials/fkg36so5-kutuphanebilgisistemi-sql/]


##### Görevler
Aşağıda istenilen sonuçlara ulaşabilmek için gerekli SQL sorgularını yazın. 


MIN-MAX, COUNT-AVG-SUM, GROUP BY, JOINS (INNER, OUTER, LEFT, RIGHT
	#ilk 3 soruyu join kullanmadan yazın.  
 
	1) Öğrencinin adını, soyadını ve kitap aldığı tarihleri listeleyin.  
	

	
	2) Fıkra ve hikaye türündeki kitapların adını ve türünü listeleyin.
	
	
	3) 10B veya 10C sınıfındaki öğrencilerin numarasını, adını, soyadını ve okuduğu kitapları listeleyin.
	
	#join ile yazın
	4) Öğrencinin adını, soyadını ve kitap aldığı tarihleri listeleyin.
	
	
	5) Fıkra ve hikaye türündeki kitapların adını ve türünü listeleyin.
	
	
	6) 10B veya 10C sınıfındaki öğrencilerin numarasını, adını, soyadını ve okuduğu kitapları, öğrenci adına göre listeleyin.
	
	
	7) Kitap alan öğrencinin adı, soyadı, kitap aldığı tarih listelensin. Kitap almayan öğrencilerinde listede görünsün.
	
	
	8) Kitap almayan öğrencileri listeleyin.
	
	
	9) Alınan kitapların kitap numarasını, adını ve kaç defa alındığını kitap numaralarına göre artan sırada listeleyiniz.
	
	
	10) Alınan kitapların kitap numarasını, adını kaç defa alındığını (alınmayan kitapların yanında 0 olsun) listeleyin.


	11) Öğrencilerin adı soyadı ve aldıkları kitabın adı listelensin.
	
	
	12) Her öğrencinin adı, soyadı, kitabın adı, yazarın adı soyad ve kitabın türünü ve kitabın alındığı tarihi listeleyiniz. Kitap almayan öğrenciler de listede görünsün.
	
	
	13) 10A veya 10B sınıfındaki öğrencilerin adı soyadı ve okuduğu kitap sayısını getirin.
	
	
	14) Tüm kitapların ortalama sayfa sayısını bulunuz.
	#AVG
	
	15) Sayfa sayısı ortalama sayfanın üzerindeki kitapları listeleyin.
	
	
	16) Öğrenci tablosundaki öğrenci sayısını gösterin
	
	
	17) Öğrenci tablosundaki toplam öğrenci sayısını toplam sayı takma(alias kullanımı) adı ile listeleyin.
	
	
	18) Öğrenci tablosunda kaç farklı isimde öğrenci olduğunu listeleyiniz.
	
	
	19) En fazla sayfa sayısı olan kitabın sayfa sayısını listeleyiniz.
	
	
	20) En fazla sayfası olan kitabın adını ve sayfa sayısını listeleyiniz.
	
	
	21) En az sayfa sayısı olan kitabın sayfa sayısını listeleyiniz.
	
	
	22) En az sayfası olan kitabın adını ve sayfa sayısını listeleyiniz.
	
	
	23) Dram türündeki en fazla sayfası olan kitabın sayfa sayısını bulunuz.
	
	
	24) numarası 15 olan öğrencinin okuduğu toplam sayfa sayısını bulunuz.
	
	
	25) İsme göre öğrenci sayılarının adedini bulunuz.(Örn: ali 5 tane, ahmet 8 tane )

	
	26) Her sınıftaki öğrenci sayısını bulunuz.
	
	
	27) Her sınıftaki erkek ve kız öğrenci sayısını bulunuz.
	
	
	28) Her öğrencinin adını, soyadını ve okuduğu toplam sayfa sayısını büyükten küçüğe doğru listeleyiniz.
	
	
	29) Her öğrencinin okuduğu kitap sayısını getiriniz.
