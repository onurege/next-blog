BİLGİSAYAR MÜHENDİSLİĞİ TASARIM ÇALIŞMASI PROJESİ
--next--blog--
1. Program akışı ve Next, tailwindcss kurulumu ve vercel ile deploy etmek
2. Layout ve giriş sayfamızı tasarlayalım
3. Blog listesi ve detay sayfası
4. Yorum kutusu ve auth0 entegrasyonu
5. Giriş yapmış kullanıcının yorumunu redis'e kaydedelim (with upstash)
6. Sayfaya yapılacak yorumları listeleyelim (with upstash)

1. kısım yapılanlar 
- auto setup yerine manuel setup tercih edildi.
- terminale yarn init --yes komutu verilerek package.json dosyası kuruldu
- nextjs.org/docs linki üzerinden next.js ve react.js kurulumu terminal üzerinden yapıldı
- kurulumun devamı için package.json dosyasına next.js'in dökümantasyon sayfasındaki scripts kısmı eklendi.
- ve projeyi ayağa kaldırmak için terminale yarn dev komutu verildi
- ve pages klasörü bulunamadı hatası alındı.
- pages klasörü ve içine index.js dosyası oluşturuldu. Dökümantasyon sayfası içerisinde bulunan HomePage fonksiyonu index.js
dosyasının içine eklendi.
- tailwindcss.com/docs üzerinden tailwind css kurulumu yapıldı.
- tailwindin yeni çıkarmış olduğu "jit(just-in-time)" paketi kuruldu.
