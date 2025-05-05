# Stok Takip Sistemi

# ▶︎ Stok Yönetimi Bölümü: 

Stok yönetimi bölümünde bulunan ürün işlemi bölümünde ürün adını yazıyoruz, sonrasında kategori yönetimi kısmından eklediğimiz kategorilerden herhangi birini seçiyoruz ve ne kadar stokla başlamasını istiyorsak miktar kısmına yazıyoruz. Yazdığımız miktar sadece sayılardan oluşmalıdır. Bilgileri doldurduktan sonra Ekle / Stok Artır butonuna basıyoruz ve ürün eklemiş oluyoruz.

Stok yönetimi bölümünde bulunan sipariş ver bölümünde eklediğimiz ürünü seçiyor ve sipariş vermek istediğimiz miktarı giriyoruz. Sipariş verdikten sonra ürünün mevcut stoğundan girdiğimiz stok kadar düşüyor.

Stok yönetimi bölümünde bulunan stok güncelle bölümünden ise seçtiğimiz ürünün stoğunu güncelleyebiliyoruz. Güncelleyeceğimiz ürün stoğu bölümüne sadece sayılar yazılmalıdır, harf kabul edilmemektedir.
Programın Stok Yönetimi kısmı bu şekilde gözükmektedir.

En son olarak eğer bir ürünü silmek istiyorsak ürünü seçiyor ve sonrasında "Seçili Ürünü Sil" butonuna basıyoruz ve ürünü silmiş oluyoruz.

![image](https://github.com/user-attachments/assets/4ae160a5-b0cc-4084-b412-6c0f79f8c122)

# ▶︎ Kategori Yönetimi Bölümü:

Bu bölümde ise, ürün işlemmi yaparken (ürün eklerken) seçmemiz gereken kategorileri ekliyoruz / yönetiyoruz. 

Yeni kategori bölümünden eklemek istediğimiz Kategorinin adını yazıyoruz ve ekliyoruz.

Eğer eklediğimiz kategoriyi silmek istersek kategoriyi seçiyoruz ve "Seçili Kategoriyi Sil" butonuna basıp siliyoruz.

![image](https://github.com/user-attachments/assets/6b5c6b7e-dc6e-4295-8b12-7a690391a038)


# ▶︎ İşlem Geçmişi Bölümü:

Bu bölümde daha önceki bölümlerde yapmış olduğumuz tüm işlemlerin kayıtı tutulmaktadır. İstediğaimiz zaman bu kayıtları İşlem Geçmişi bölümünden görüntüleyebilmekteyiz.

Eğer istersek işlem kayıtlarını da "Geçmişi Temizle" butonuna tıklayarak temizleyebiliriz.

![image](https://github.com/user-attachments/assets/3db5faf8-1112-462a-b39c-67243b7caca8)


# ▶︎ Programdaki Veriler

Veriler her işlem yapıldığında kaydedilmektedir. Bu verileri programın çalıştığı klasörün içerisine data adında bir klasör açarak bu açtığı klasörün içine de stok_yonetim_verileri.json adında bir dosya açıyor ve buraya uygulamada yapılan işlemleri anlık olarak kaydediyor. Uygulama her açıldığında bu verileri çekerek entegre ediyor ve veri kaybı yaşanmamasını sağlıyor.
