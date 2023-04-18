#  NLayer App
Bu proje Udemy aracılığı ile **Fatih Çakıroğlu** hocanın **AspNet Core Web/API+Çok Katmanlı Mimari|Best Practices-Net6** kursu ile geliştirilmiştir


<details>

<summary>Proje Katmanları</summary>

![image](https://user-images.githubusercontent.com/77438994/232701842-2e927cb5-5cc4-4384-96e2-6eccd9323633.png)


1. API Katmanı
     - API katman bir diğer adı ile kullanıcı arayüzü katmanıdır içerisinde servis katmanı ile haberleşebilmek için controllerlar mevcuttur.

2. Caching Katmanı
     - Caching katmanı bir çok kez istenen itemları bilgisayar belleğine kaydeder ve database ile daha az iletişime geçmemize fayda sağlar.

3. Core  Katmanı
     - Farklı projelerde kendimizi tekrar etmemek adına ortak alan kodların yazıldığı katmandır bu katmanın içerisinde Interface,Model ve UnitOfWork mevcuttur.

4. Repository  Katmanı
     - Bu katmanda Service Katmanı  ile entegre olunması gerektmekte ve yukarıda belirtilen Interfacelerin implemente metotlarını içerisinde Service Katmanı ile bağlantılı olarak tasarlanmaktadır.

5. Service Katmanı
     - Bu katmanda Repository katmanı ile içiçe olup projenin iş kodlarının yazıldığı esas yerdir.
5. Web Katmanı
     - Bu katmanda projenin aslında görsel tarafıdır kullanıcıya gösterilen kısımdır içerisinde bir çok layoutlar bulunur.
</details>

<details>

<summary>Proje İçi Görüntüler</summary>

![image](https://user-images.githubusercontent.com/77438994/232711328-dc1fbeb8-f558-4477-b807-1c08a39b7021.png)

![image](https://user-images.githubusercontent.com/77438994/232711642-064ccc9d-fa15-41d8-9fb3-6df608f91320.png)

![image](https://user-images.githubusercontent.com/77438994/232712636-e887f998-e3f0-469f-bea2-460287bad808.png)
</details>

<details>
<summary>Proje İçi Fonksiyonalite</summary>

1. Ürün Listeler
     - Products sekmesine tıklanıldığı zaman gelen liste ekranıdır tum urunler kategorilerine göre listelenmektedir
     
    

2. Ürün Ekler
     - Yeni bir ürün eklenmek istediğinde ulaşılacak ekran
3. Ürün Günceller
     - Varolan bir ürünü güncellemek istendiğinde güncellemeyi gerçekleştirdiğimiz ekran
4. Ürün Siler
     - Varolan bir ürünü silmek  istendiğinde silmeyi gerçekleştirdiğimiz ekran

</details>

<details>

<summary>Projede Nelere Yer Verildi?</summary>
<ul>
<li>N katmanlı mimari ile uygulama nasıl inşa edilir ?</li>
<li>Generic Repository çok katmanlı mimariye nasıl implement edilir ?</li>
<li>UnitOfWork çok katmanlı mimariye nasıl implement edilir ?</li>
<li>Migration işlemleri nasıl gerçekleştirilir ?</li>
<li>Hata yönetimi Global olarak nasıl ele alınır ?</li>
<li>Action Methodlar içerisinde kod tekrarlarından nasıl kaçınılır ?</li>
<li>AutoMapper kütüphanesi çok katmanlı mimaride nasıl kullanılır ?</li>
<li>Çok katmanlı Mimari ile Entity Framework nasıl kullanılır ?</li>
<li>Global hata yönetimi nasıl ele alınır ?</li>
<li>Bir Mvc projesi ile api projesi nasıl haberleştirilir?</li>

</ul>

</details>

