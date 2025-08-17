# Otonom Hazine Avcısı Projesi

## Proje Amacı:
Otonom Hazine Avcısı, öğrencilerin nesneye yönelik programlama ve veri yapıları bilgilerini pekiştirmeyi amaçlayan bir projedir. Projeye dahil olan öğrenciler, otonom hareket eden bir karakterin, engellerle dolu bir harita üzerinde en kısa sürede tüm hazineleri toplamasını sağlayan bir algoritma tasarlamaktadır. Oyun boyunca karakterin hareketi, en kısa yol algoritması ile yönlendirilir.

## Proje Gereksinimleri:
- **Programlama Dili:** Java (NetBeans IDE 15 kullanılarak geliştirilmiştir.)
- **Kullanılan Algoritmalar:** Dijkstra Algoritması (En kısa yol hesaplamaları için)
- **Veri Yapıları:** Nesneye yönelik programlama ilkeleri, Encapsulation, Inheritance, Polymorphism, Abstraction

## Proje Özellikleri:
1. **Harita ve Engeller:** 
   - Dinamik harita oluşturulması (kullanıcı tarafından belirlenen boyutlarda)
   - Engellerin sabit (ağaç, kaya, duvar, dağ) ve hareketli (kuş, arı) türde olması
   - Hazinelerin (altın, gümüş, zümrüt, bakır) haritada yerleştirilmesi
   - Hareketli engellerin belirli bir alanda hareket etmesi
   - Oyuncunun sadece geçilebilen yolları izlemesi

2. **Oyuncu ve Hareket:**
   - Oyuncu, harita üzerindeki uygun bir noktada rastgele yerleştirilir
   - Oyuncu, harita üzerinde en kısa yolu takip ederek hazineleri toplar
   - Karakterin 3x3'lük bir alandaki görünüşü ile hareketi izlenebilir
   - Hazineler toplandıkça sırası ve konumu ekranda gösterilir

3. **Algoritmalar:**
   - Dijkstra algoritması kullanılarak karakterin en kısa yolu bulması sağlanır
   - Oyuncunun geçmesi gereken adımlar ve hangi nesneleri keşfettiği gösterilir

## Proje Adımları:
1. **Harita Oluşturma:** 
   - Programın ilk çalıştırılmasında, kullanıcıdan haritanın boyut bilgisi alınır. Harita, her seferinde yeniden üretilir.
   - Harita üzerinde rastgele yerleştirilen sabit ve hareketli engeller ile hazineler bulunur.
   
2. **Oyuncu Hareketi:** 
   - Oyuncu, belirlenen en kısa yola göre hareket eder. Her adımda, bir hücreyi keşfettiğinde o hücredeki nesne (hazine, engel) belirtilir.

3. **Hedef ve Çıktılar:** 
   - Karakter, en kısa sürede tüm hazineleri toplamak için hareket eder. Oyunun sonunda, karakterin öğrenmediği kareler sisli şekilde gösterilir.

## Teknolojiler:
- **Java:** Proje Java dilinde yazılmıştır ve NetBeans IDE üzerinde geliştirilmiştir.
- **Dijkstra Algoritması:** En kısa yol algoritması olarak kullanılmıştır.
- **Swing (JPanel):** GUI bileşenleri için kullanılmıştır.

## Kurulum ve Çalıştırma:
1. Projeyi **NetBeans IDE 15** üzerinde açın.
2. Programı çalıştırarak “Yeni Harita Oluştur” butonuna tıklayın.
3. “Başlat” butonuna tıklayarak oyunu başlatın ve karakterin hareketini gözlemleyin.

## Lisans:
Bu proje, **MIT Lisansı** ile lisanslanmıştır. Detaylar için [Lisans Dosyasına](LICENSE) bakınız.
