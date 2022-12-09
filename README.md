# SAP Practicum Soru Seti

1. SAP ERP sistemine hangi uygulama ile erişim sağlanmaktadır?

   SAP sisteminde NSP aracığıyla sunucu ile uygulama arasında erişim sağlanıyor. 

2. SAP Editor ekranına hangi işlem kodu ile erişilmektedir?

   SE38 işlem kodu ile erişmekteyiz.

3. Genel olarak bir değişken tanımlamak istediğinde, değişkenin isim standardı nasıl olmalıdır? Örnek verebilir misiniz?

   data ifadesini kullanarak değişken tanımlıyoruz; data: gv_urun. g ifadesi global değişken anlamı temsil ediyor, v ise değişken tanımladığımız anlamına geliyor.

4. Birden fazla değeri bir küme altında tutmak isterseniz hangi yapıyı kurmanız gerekir?

   stucture yapısı kullanarak küme oluşturabiliyoruz.

5. Structure ,data element , tablo gibi yapılar SAP de hangi işlem kodundan oluşturulmaktadır ?

6. Ekranda ürün kodu ve stok alanım parametre olarak bulunsun. Bu parametreler ile program içerisinde EB10000001, EB10000002, EB10000003, EB10000004, EB10000005, EB10000006, EB10000007 ürünleri internal tabloya ekleyip ardından parametreler ile filtre özelliğini kullanarak bir kod satırı yazar mısınız?

7. Maddede yapılan çalışmalara ek olarak toplam ürün stoğunu görmemizi sağlayan bir kod satırı yazabilir misiniz?
PARAMETERS: p_urunkd type 2SD_ST_URUN-urunkodu,

​						   p_urunst type 2SD_ST_URUN-stok

8. Stoğu sıfır olan ürünleri gösteren bir rapor yazabilir misiniz ? (6. Maddedeki ürünlerin 2 tanesine stok olarak 0 değeri atayın.)

