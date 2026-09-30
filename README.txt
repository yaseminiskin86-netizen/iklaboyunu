İKLAB ÇARKIFELEK OYUNU - FHD AKILLI TAHTA SÜRÜMÜ

Ana çözünürlük: 1920x1080 (Full HD / 1080p)
Ana dosya: index.html
Yönetim paneli: admin.html

Bu sürümde:
- Tüm oyun sahnesi 1920x1080 tasarım alanında sabit oranla çalışır.
- Daha küçük ekranlarda tüm sahne orantılı olarak küçülür; buton ve içerik yerleşimleri birbirine göre kaymaz.
- Soru kartı dışındaki beyaz zemin şeffaflaştırılmıştır.
- Arapça seçenekler büyütülmüş ve soru kartına orantılı yerleştirilmiştir.
- Kontrol Et butonları soru kartı içinde görünür kalacak şekilde sabitlenmiştir.
- Alt puan/hak/öğrenci alanları FHD sahne içinde görünür tutulur.
- İklabı Bul bölümünde metin Amasya font ailesi önceliği ile gösterilir (cihazda Amasya kurulu değilse uygun Arapça fallback font kullanılır).
- İklabı Bul bölümünde öğrenci doğru bölgeyi fare veya akıllı tahta üzerinde sürükleyerek metin seçimiyle işaretler.
- Ses kaydı bölümü tarayıcı mikrofon izni gerektirir; HTTPS veya localhost önerilir.

v12 - DONMA / KİLİTLENME DÜZELTMELERİ
- ANA SORUN: Dönen kare çark resminin saydam köşeleri, çark belirli açılarda durduğunda
  "Çarkı Çevir" butonunun üstüne biniyor ve dokunuşları yutuyordu (oyun donmuş gibi görünüyordu).
  Çark, gösterge ve başlık resimleri artık dokunuş almaz; buton her zaman üstte.
- Çark butonu görev sürerken kapalıdır; yalnızca "Devam Et" sonrasında (veya Tekrar diliminde) açılır.
  Görev ortasında çevirmek görevi silip durumları karıştırıyordu.
- İklabı Bul: tarayıcının metin seçimi akıllı tahtada parmakla sürüklemeyle çalışmıyordu,
  "Kontrol Et" hiç aktif olmuyordu. Seçim artık fare, kalem ve parmakla aynı şekilde çalışır.
  Değerlendirme harf konumuna göre yapılır (ilk kelimedeki ب ile yanlışlıkla doğru sayılmaz).
- Tüm görseller oyun açılışında önceden yüklenip çözülür; başlık ve buton görselleri ekran boyutuna
  küçültüldü (toplam görsel boyutu ~24 MB -> ~11 MB). Bölüm geçişlerindeki takılma giderildi.
- Dönen çarktaki gölge filtresi ve her dilimde yapılan zorunlu yeniden yerleşim kaldırıldı (akıcı dönüş).
- Ana sayfa onayı tarayıcı confirm() yerine oyun içi pencere ile sorulur.
- Hızlı Cevap: yanlış denemeden sonra süre artık durmuyor.
- Mikrofon: izin beklenirken çift tıklama iki kayıt başlatmıyor; görev değişince mikrofon kapanıyor.
- Beklenmeyen bir hata dönen çarkı iki dilim arasında durdurmuyor.
- Uzun geri bildirim metinleri butonların arkasına taşmıyor.

v13 - INTRO VİDEOSU
- İntro videosu (assets/video/intro.mp4) oyundan önce tam ekran ve sesli oynar.
- Açılışta "OYUNU BAŞLAT" butonu çıkar; basınca intro sesli oynar.
- Video bitince doğrudan ad-soyad ekranına geçilir (ikinci buton yok).
- Sağ altta "Geç" butonu ile intro atlanabilir. Ad-soyad ekranında "İntroyu tekrar izle" bağlantısı vardır.
- MP4 oynatamayan tarayıcılar (bazı Pardus/ETAP tahtalar) için WebM kopyası (intro.webm) eklendi.
- Video açılmazsa veya takılırsa oyun donmaz; ad-soyad ekranı kendiliğinden açılır.
