# Güncellemeler

> Bu döküman, ClassicUO'nun UOSoft fork'unda **toor\_root** tarafından yapılan güncellemelerin 13 Mart 2024 tarihi itibariyle sırasına göre, sadeleştirilmiş bir dökümüdür. Her madde, ilgili commit başlığından çıkarım yapılarak dökümente edilmiştir.

**Etiketler:**

&#x20;`[Add]` yeni özellik/dosya,&#x20;

`[Fix]` hata düzeltmesi,&#x20;

`[`🗑️`]` Kaldırma/kapatma,&#x20;

`[Refactor]` yeniden yazım/temizlik,&#x20;

`[`⚡`]` Performans

`[Build]` derleme-CI/CD-proje ayarları,&#x20;

`[i18n]` yerelleştirme,&#x20;

`[Security]` güvenlik (detaysız),&#x20;

`[Edit]` genel düzenleme.

{% updates format="full" %}
{% update date="2026-07-17" tags="Perf,Add,Fix,fix,add" %}
## 17 Temmuz 2026

* \[⚡] Evlerin ekrana sonradan girmesi davranışı eski haline döndürüldü (performans sorununa yol açabileceği not edildi). `85555a556`
* \[➕] Evlerin render sıralamasında yükseklik (Z) koordinatının da rol oynaması için test amaçlı bir tanım eklendi. `d3cbdbb8e`
* \[Perf] Evlerin çiziminde önbellek (cache) sistemi yazıldı; ayarlar ve profil ekranına eklendi. `57a6e34f4`
* \[🐞] Ultralight web arayüzü ikon düzeltmeleri yapıldı. `8b37bbb26`
{% endupdate %}

{% update date="2026-07-15" tags="Add,Edit,Fix" %}
## 15 Temmuz 2026

* \[Add] Ultralight tabanlı web arayüzü entegrasyonu başlatıldı (deneysel, test aşamasında). `eab272d71`
* \[Add] Pencerelere kilitli/kilitsiz gösterim butonu eklendi. `0d83eb662`
* \[Edit] Ultralight entegrasyonunda güncellemeler yapıldı. `b3aa41ca4`
* \[Edit] Ultralight web görünüm kontrolünde düzenleme yapıldı. `3f69eb36b`
* \[Edit] Web tabanlı durum çubuğu (StatusGumpWebUI) üzerinde düzenleme yapıldı. `2a07cd3cc`
* \[Edit] Ultralight test penceresinde düzenleme yapıldı. `b12d368a4`
* \[Add] Ultralight web arayüzü için özelleştirme (override) sistemi eklendi. `a769f8453`
* \[Edit] Ultralight web arayüzü güncellemeleri yapıldı. `30613f9e0`
* \[Add] Yazı tipi ikonları (FontIcon) desteği eklendi (deneysel). `60dd56108`
* \[Fix] Yazı tipi ikonlarındaki renk sorunu düzeltildi; web arayüzü güncellendi. `67e94fa21`
{% endupdate %}

{% update date="2026-07-12" tags="Edit" %}
## 12 Temmuz 2026

* \[Edit] Sayaç çubuğunda eşya miktarı 1 ise "1" yazacak şekilde ayarlandı. `c8bb887ad`
{% endupdate %}

{% update date="2026-07-01" tags="Add" %}
## 1 Temmuz 2026

* \[Add] Ortalama ping hesaplaması, kayan (rolling) pencere yöntemiyle daha doğru hale getirildi. `567e22647`
{% endupdate %}

{% update date="2026-06-23" tags="Edit" %}
## 23 Haziran 2026

* \[Edit] Durum yaşı (status age) gösterim biçimi, sunucu emülatör sürümüne göre güncellendi. `1cbf5f1bf`
{% endupdate %}

{% update date="2026-06-19" tags="Edit,Fix" %}
## 19 Haziran 2026

* \[Edit] API dosyasında yorum satırları güncellendi (kod bakımı). `aba96f102`
* \[Edit] API dosyasında yorum satırları tekrar güncellendi (kod bakımı). `63f080f4a`
* \[Fix] Ping (gecikme) ölçümü, paket bazlı zaman damgasıyla daha doğru hesaplanacak şekilde düzeltildi. `97516e983`
{% endupdate %}

{% update date="2026-06-18" tags="Edit,Fix,Build" %}
## 18 Haziran 2026

* \[Edit] Başlatıcı (Launcher) projesi üzerinde çalışıldı. `bacac3b86`
* \[Fix] UltimaLive harita bloklarının yeniden yüklenmesi, canlı harita parçalarının havuzlanmasını engelleyecek şekilde düzeltildi (ana projeden). `bc72f0239`
* \[Build] Başlatıcı derleme script'i eklendi. `311e276bc`
* \[Edit] Genel ayarlar dosyasında düzenleme yapıldı. `f231a317f`
{% endupdate %}

{% update date="2026-06-17" tags="Edit" %}
## 17 Haziran 2026

* \[Edit] Dünya haritası penceresinde düzenleme yapıldı. `d1f8819c5`
{% endupdate %}

{% update date="2026-06-12" tags="Fix,Edit" %}
## 12 Haziran 2026

* \[Fix] Bir önceki statik nesne sıralama düzeltmesi geri alındı (ana projeden, yan etkisi olduğu için). `002947e8d`
* \[Edit] Pencere başlık alanı genişletildi (ana projeden). `f6529cc2f`
* \[Edit] Oda üyesi can çubuğu renklendirildi. `fb47f77dd`
{% endupdate %}

{% update date="2026-06-11" tags="Add,Remove,Edit,Fix,Refactor" %}
## 11 Haziran 2026

* \[Add] Özel evlerde zemin katında (0. kat) yardımcı zemin ızgarası gösterimi eklendi (ana projeden). `5f6babe2b`
* \[Remove] Kitap penceresinde sayfa başına satır sayısı 8'den 10'a çıkarıldı (ana projeden). `9f05f3e9b`
* \[Edit] Takas penceresinde altın+platin toplam değerine göre girilebilecek para miktarı sınırlandırıldı (ana projeden). `806234fb6`
* \[Fix] Aynı yükseklikteki (Z) statik nesnelerin çizim sırası düzeltildi (ana projeden). `5cbb7af13`
* \[Fix] Şeffaflık dairesi aktifken zeminin solma efekti korunacak şekilde düzeltildi (ana projeden). `5de4fec09`
* \[Refactor] Kitap penceresinde sayfa gönderilmeden önce sondaki boş satırlar temizlendi (ana projeden). `7808db5a9`
* \[Edit] Kitap penceresinin metin rengi orijinal istemciyle eşleştirildi (ana projeden). `b60026eed`
* \[Add] Dünya haritasına araç çubuğu eklendi; oda üyesi zehirlenme durumu can çubuğunda gösterilecek. `57c34ff6a`
{% endupdate %}

{% update date="2026-06-05" tags="Add" %}
## 5 Haziran 2026

* \[Add] SphereNet sunucusu giriş listesine eklendi. `fc7fa0054`
{% endupdate %}

{% update date="2026-06-04" tags="Fix,Add,Security" %}
## 4 Haziran 2026

* \[Fix] Oda yönetim penceresindeki oda isimlerinin üst üste binmesi sorunu giderildi. `6a14ca832`
* \[Add] Oda yönetim penceresine sayfalama ve filtreleme/arama özelliği eklendi. `a8579a8b6`
* 🔒 \[Security] Sohbet kayıt sisteminde tespit edilen bir güvenlik açığı kapatıldı (detay paylaşılmıyor). `5ae218e20`
* 🔒 \[Security] Sohbet kayıt sisteminde tespit edilen ikinci bir güvenlik açığı kapatıldı (detay paylaşılmıyor). `875425650`
{% endupdate %}

{% update date="2026-06-02" tags="Fix,Edit,Add" %}
## 2 Haziran 2026

* \[Fix] Harita parçası (chunk) silinirken oluşan boş referans hatası giderildi (ana projeden). `523aedfc2`
* \[Edit] Ev özelleştirme yöneticisinde düzenleme yapıldı. `943b8f5d8`
* \[Add] Yeni bir sunucu (sphereNet) eklendi. `3c681d3b6`
* \[Add] Karakter ekranında katman bazlı ekipman gizleme mantığı ana projeden geri getirildi. `32b1a4ec0`
{% endupdate %}

{% update date="2026-06-01" tags="Edit,Add,Build,Remove,Fix" %}
## 1 Haziran 2026

* \[Edit] İstemci görev çubuğu (jumplist) menüsü güncellendi. `3c2ac3302`
* \[Add] Karakter oluşturma ekranına rastgele isim ve "hepsini rastgele yap" özelliği eklendi. `da773d6c7`
* \[Add] Aranabilir açılır liste bileşeni eklendi; karakter oluşturma/takas ekranındaki yetenek seçimlerinde kullanılmaya başlandı. `5bf05c06f`
* \[Build] Otomatik derleme hattı dosyası güncellendi. `d2204e111`
* \[Build] Otomatik derleme hattı ayarları güncellendi. `4fd1a4758`
* \[Build] Otomatik derleme hattı dosyası tekrar güncellendi. `3a3818a47`
* \[Remove] Derleme hattından Linux desteği geçici olarak devre dışı bırakıldı. `723f1e3a6`
* \[Fix] Karakter ekranında ekipman katman sıralaması, dünya grafiği yerine animasyon kimliğine göre düzeltildi (ana projeden). `e20ca11df`
* \[Build] Otomatik derleme hattı dosyası bir kez daha güncellendi. `e877e96f6`
{% endupdate %}

{% update date="2026-05-31" tags="Add,Build,Edit,Fix,Remove,Security" %}
## 31 Mayıs 2026

* \[Add] Pencere göz atma/inceleme aracı (GumpBrowser) eklendi. `52ff00b5f`
* \[Build] Kurulum dosyasına tarayıcı kimliği (UserAgent) bilgisi eklendi. `9dbf73f4a`
* \[Edit] Sohbet kayıt servisi API'ye bağlandı. `b790d699b`
* \[Fix] Büyücülük ustalık kitabı sayfası doldurma hatası düzeltildi (ana projeden). `338aeec18`
* \[Add] Karakter ekranı katman sıralaması, statik tablolar yerine grafik tabanlı hale getirildi (ana projeden). `0ebc4b3c1`
* \[Edit] Katman gizleme mantığı, çizim sırasının ifade edemediği durumlara indirgendi (ana projeden). `4e9caf685`
* \[Edit] Sohbet kayıt sistemi kullanımı API'ye bağlandı (yeni bir ayar ile açılıp kapatılabiliyor). `1ff972971`
* \[Remove] Kod temizliği yapıldı, ortam logları kapatıldı. `730d198e2`
* 🔒 \[Security] Hile tespit sisteminde touchpad kullanıcılarını yanlışlıkla işaretleyen bir hata düzeltildi (bu, touchpad kullanan oyuncuların haksız yere hile şüphesiyle karşılaşmasını önledi). `1467663f4`
{% endupdate %}

{% update date="2026-05-30" tags="Add" %}
## 30 Mayıs 2026

* \[Add] Taş savaş kılıcına yeni bir yetenek eklendi (ana projeden). `342f33e91`
{% endupdate %}

{% update date="2026-05-29" tags="Add,Edit,Build,Security" %}
## 29 Mayıs 2026

* \[Add] Yetenek ve büyü kullanımı için özel ilerleme çubuğu (progress bar) eklendi. `f7b6b0c92`
* \[Add] Pencere odağı alma davranışı (SDL3) eklendi. `589bb7b41`
* \[Add] Başlatıcıda pencere odağı davranışları eklendi. `e531dc631`
* \[Add] Bekleme süresi çubuğu (CooldownBar) güncellendi; maksimum sayı ayarı eklendi. `b0b22124c`
* \[Edit] Pencere odağı ayarları düzenlendi; istemci açıldığında odağı alması sağlandı. `d5f4cc69c`
* \[Build] Başlatıcı proje ayarları güncellendi. `4553d5304`
* \[Edit] Animasyonlu bekleme süresi çubuğu güncellendi. `6053d1794`
* 🔒 \[Security] Hile önleme tedbirleri güçlendirildi (detay paylaşılmıyor). `914abcf9f`
{% endupdate %}

{% update date="2026-05-28" tags="Add" %}
## 28 Mayıs 2026

* \[Add] Profil klasörüne "ÖNEMLİ! BENİ OKU.txt" adında bir bilgilendirme dosyası eklendi. `b1f64134b`
{% endupdate %}

{% update date="2026-05-27" tags="Add" %}
## 27 Mayıs 2026

* \[Add] Eski sayaç çubuğu (Legacy CounterBar) opsiyonel olarak eklendi (deneysel). `2d559b26a`
* \[Add] GhostMouse: fare hareketlerini kaydedip otomatik oynatan deneysel bir sistem eklendi. `5d914cc18`
{% endupdate %}

{% update date="2026-05-26" tags="Edit,Remove,Add,Fix" %}
## 26 Mayıs 2026

* \[Edit] Bilgi kutusu (TipNotice) penceresinde düzenleme yapıldı. `076cedf67`
* \[Remove] API ayarlarına genel yapılandırma eklendi; bir ayar boşsa devam etmeme davranışı kaldırıldı. `9c4df91ec`
* \[Add] Veri serileştirmeye genel yapılandırma tanımı eklendi. `354840dff`
* \[Fix] API başlığı eklenirken istemci sürümünün yanlış yerde ayarlanması düzeltildi. `4e45a4a8d`
* \[Edit] Komut yönetim sisteminde düzenleme yapıldı. `b500bf363`
* \[Edit] Sabit değerler dosyasında düzenleme yapıldı. `f52bb3063`
* \[Edit] Hareket/yürüme ile ilgili güncellemeler yapıldı. `7efdb4552`
* \[Add] Yapay zeka (Gemini) destekli yardım servisi eklendi. `49ffb0594`
* \[Add] GitBook tabanlı yapay zeka yardım servisi eklendi. `4a49da318`
* \[Edit] Yapay zeka (Gemini) yardım servisinde güncelleme yapıldı. `e08c76164`
* \[Edit] Bilgi kutusu penceresinde düzenleme yapıldı. `149b20d5a`
* \[Edit] Komut yönetim sisteminde düzenleme yapıldı. `768246a7b`
{% endupdate %}

{% update date="2026-05-24" tags="Edit,Security,Remove,Fix" %}
## 24 Mayıs 2026

* \[Edit] Genel ayarlar dosyasında düzenleme yapıldı. `5d35593aa`
* 🔒 \[Security] Güvenlik (anti-tamper) modülünde güncelleme yapıldı (detay paylaşılmıyor). `e34d84de4`
* \[Remove] "Denywalk" durumunda hava durumu sıfırlama kaldırıldı. `a0ba91ff3`
* \[Fix] Çoklu okuma sorunu düzeltildi (ana projeden). `5db17c992`
* \[Fix] HTML pencerelerinde satır sonundaki son karakterde bağlantı açılırken oluşan sınır hatası düzeltildi (ana projeden). `9c26ce933`
{% endupdate %}

{% update date="2026-05-23" tags="Remove,Build,Security,Edit,Fix,Add,Refactor" %}
## 23 Mayıs 2026

* \[Remove] Eski işlemcilerde (Sandy Bridge/Ivy Bridge/AMD FX serisi) çökmeye yol açan bir derleyici ayarı (AVX2) kaldırıldı. `06b0b8256`
* \[Build] .gitignore dosyası güncellendi. `1ea066a78`
* 🔒 \[Security] Güvenlik modülünde teknik bir bakım çalışması yapıldı (detay paylaşılmıyor). `107fea656`
* \[Build] .gitignore dosyası tekrar güncellendi. `0a5a9bcee`
* \[Build] Otomatik derleme hattı (CI) dosyası oluşturuldu. `7ea805c2b`
* \[Edit] Geliştirme ortamı ayarları güncellendi. `a3d68525c`
* \[Build] Otomatik derleme akışı ve istemci proje ayarları güncellendi. `f28a6062f`
* \[Build] .gitignore dosyası bir kez daha güncellendi. `fb36775e5`
* 🔒 \[Security] Güvenlik modülünde teknik düzeltmeler yapıldı (detay paylaşılmıyor). `12157f0a3`
* \[Build] Otomatik derleme hattı dosyası güncellendi. `e7d42d05f`
* \[Fix] Windows dışı platformlarda derleme hatası düzeltildi (macOS derleme görüntüsü güncellendi). `49238d7ee`
* \[Add] .NET sürüm hedeflemesi platformlar arası ortak hale getirildi. `b34f40dec`
* \[Build] Test projesi ayarları güncellendi. `9cad29b88`
* \[Build] Proje derleme ayarları güncellendi. `c9098d5ae`
* \[Fix] Otomatik derleme ayarlarında düzeltme yapıldı (Windows'a özel bir derleme hatası giderildi). `b6a1810bc`
* \[Refactor] Proje dosyalarındaki gereksiz derleme ayarları temizlendi. `835ff4220`
* \[Build] İstemci proje ayarları güncellendi. `021b9bcc9`
* \[Fix] Çoklu platform uyumluluğu için performans bilgi penceresi ve cihaz tanımlama kodu düzeltildi. `8a4efa27f`
* \[Fix] Çoklu platform uyumsuzlukları giderildi, bazı uyarılar susturuldu. `b71f629ad`
* \[Fix] Dosya yolu kod hatası (kaçış karakteri) düzeltildi. `824266bba`
* \[Build] Yeni sunucuya (nebulanewage) özel kurulum klasörü ayarlandı. `355162b09`
* \[Build] Başlatıcı proje ayarları güncellendi. `cb2888293`
* \[Edit] macOS/Linux başlatıcı kodunda düzenleme yapıldı. `9116f0f39`
* \[Build] Proje ayarında koşul değişikliği yapıldı. `8b946d15a`
* \[Edit] Ses sürücüsü ve sesli sohbet yöneticisi çoklu işletim sistemi desteği için güncellendi. `16d273bf2`
* \[Refactor] Kullanılmayan bir kod satırı temizlendi. `119c76dcd`
* \[Build] Otomatik derleme hattı dosyası tekrar güncellendi. `19a5d28e6`
* \[Add] Windows'a özgü kodlar ayrı bloklara alınarak diğer platformlarla uyumlu hale getirildi. `ddcf27988`
* \[Edit] Windows'a özgü sarmalama düzenlemesi yapıldı, eklenti sistemi çoklu platforma uyarlandı. `25d38fe92`
* \[Build] Otomatik derleme hattı dosyası bir kez daha güncellendi. `ee213fc70`
* \[Add] macOS/Linux dağıtım rehberi dosyası oluşturuldu. `df0d7afd8`
* \[Add] Yeni bir arayüz teknolojisi (Avalonia) ile başlatıcı projesi denemesi başlatıldı. `0626ea019`
* \[Build] İstemci proje ayarları tekrar güncellendi. `188a575bc`
* \[Fix] Etki (buff) çubuğu süre gösterimi düzeltildi. `7f44216cd`
* \[Build] .gitignore dosyası son kez güncellendi. `9c6fb1dac`
* \[Build] Derleme/test hattı dosyası güncellendi. `af7e2473c`
* \[Edit] Avalonia tabanlı başlatıcı güncellendi. `5d40c93e5`
* \[Edit] Ayar dosyası güncellendi. `caeb3f2b4`
* \[Build] Derleme/test hattı dosyası tekrar güncellendi. `01b62ca86`
{% endupdate %}

{% update date="2026-05-19" tags="Add" %}
## 19 Mayıs 2026

* \[Add] Yeni bir sunucu eklendi: nebulanewage. `e836eebae`
{% endupdate %}

{% update date="2026-05-18" tags="Add" %}
## 18 Mayıs 2026

* \[Add] Yeni bir sunucu eklendi. `eab3bebe8`
{% endupdate %}

{% update date="2026-05-15" tags="Add,Remove,Edit" %}
## 15 Mayıs 2026

* \[Add] Yetenek kullanımına gecikme parametresi eklendi; yetenek menüsünden hızlı yetenek kullanımı (spam) yalnızca belirli yerlerde sınırlandırıldı. `1517a3412`
* \[Remove] Çizilmeyen (no-draw) eşyalar için isim üstü gösterimi kaldırıldı (ana projeden). `e6c3c9146`
* \[Edit] Yetenek kullanım gecikmesi düzenlendi. `6eb17984a`
* \[Edit] Giriş tamamlama paket sıralaması değişti; yetenek pencereleri asenkron yükleyiciden hariç tutuldu. `8aafc60c0`
{% endupdate %}

{% update date="2026-05-12" tags="Add,Edit,Fix" %}
## 12 Mayıs 2026

* \[Add] Yorum satırı eklendi (kod bakımı). `515e8943b`
* \[Edit] Yürüme yöntemi, sunucu emülatör sürümüne göre kullanılacak şekilde geçici olarak ayarlandı. `e1d12db8d`
* \[Fix] Oyuncu güncellemesinde yön sırasının hatalı olabileceği tespit edilip düzeltildi. `0a514206a`
{% endupdate %}

{% update date="2026-05-11" tags="Refactor,Add,Edit,Fix,Remove,Build" %}
## 11 Mayıs 2026

* \[Refactor] Kod temizliği yapıldı. `5319c13ff`
* \[Refactor] Kod temizliği tekrar yapıldı. `b0bed05e7`
* \[Refactor] Kod temizliği bir kez daha yapıldı. `b83528559`
* \[Add] Dayanıklılık (Durability) yönetim sistemi eklendi. `02476641f`
* \[Add] Dayanıklılık takip penceresi eklendi. `c29b18e6a`
* \[Edit] Dayanıklılık yönetim sisteminde düzenleme yapıldı. `3ee9fb8b1`
* \[Add] Karakter ekranında küçültülmüş dayanıklılık penceresi gösterimi profil ayarı olarak eklendi. `1f3d833ff`
* \[Refactor] Kod temizliği yapıldı. `349d85591`
* \[Fix] Ana projeden bir düzeltme entegre edildi. `aeef3e679`
* \[Edit] Ayarlar penceresinde düzenleme yapıldı. `4a95a5a65`
* \[Edit] Hızlı dönüş özelliği API'ye bağlandı. `25592702c`
* \[Edit] Yürüme yöntemi güncellendi (deneysel, test amaçlı). `d12428eda`
* \[Remove] "56b" sürümü için deneysel yürüme davranışı kapatıldı. `46b2dda2b`
* \[Edit] Dosya bütünlük kontrolü (güncelleme sistemi) güncellendi. `df9a7058a`
* \[Build] Yeni kurulum/derleme dosyaları (.bat) eklendi. `5883c68b2`
* \[Fix] Ana projedeki hareket/yürüme değişikliği hatalı bulunduğu için düzeltilene kadar eski haline döndürüldü. `b66e3de5e`
* \[Add] Yorum satırı eklendi (kod bakımı). `62245062e`
{% endupdate %}

{% update date="2026-05-10" tags="Perf,Add,Fix,Edit" %}
## 10 Mayıs 2026

* \[Perf] Yürüme mantığı, tek bir sorguda toplanacak şekilde eski haline getirildi (performans/uyum). `5a1ccea2b`
* \[Add] Girişte donanım bilgisi gönderimine 1 saniyelik gecikme eklendi. `5d5e5e19a`
* \[Fix] Eski Sphere sunucu sürümleri için deneysel hareket/yürüme düzeltmeleri eklendi. `b4d9162ea`
* \[Fix] "56b" sürümü sunucular için hareket düzeltmeleri yapıldı. `c9db02162`
* \[Edit] Hata ayıklama (Debug) penceresinde düzenleme yapıldı. `04e142643`
* \[Edit] Makro ile görüş mesafesi (visual range) değişince sunucuya bildirim gönderilmesi sağlandı. `b47026b98`
* \[Add] Log kaydı eklendi. `6b05c373e`
{% endupdate %}

{% update date="2026-05-07" tags="Edit,Build" %}
## 7 Mayıs 2026

* \[Edit] Nebula sunucusuna özel istisna ayarları güncellendi. `b17558513`
* \[Build] Yeni bir istemci kurulumu oluşturuldu. `312ace6c5`
* \[Build] Derleme/yükleme script'i güncellendi. `4c70b7ed0`
{% endupdate %}

{% update date="2026-05-04" tags="Add,Edit,Build" %}
## 4 Mayıs 2026

* \[Add] Ziyaret edilen bağlantı önbelleği için testler eklendi. `670357619`
* \[Edit] HTML metin bileşeninde düzenleme yapıldı. `17dd7775a`
* \[Build] Başlatıcı proje ayarları güncellendi. `b765f6801`
* \[Add] Ziyaret edilen web bağlantısı önbelleği eklendi (HTML pencerelerinde tekrar tıklamaları hatırlamak için). `6b0bdcb46`
* \[Edit] Yazı tipi yükleyicisinde düzenleme yapıldı. `ce2967666`
{% endupdate %}

{% update date="2026-04-30" tags="Build,Fix,Add,Remove,Edit" %}
## 30 Nisan 2026

* \[Build] macOS ve ARM64 desteği eklendi, otomatik derleme hattı (GitHub Actions) düzenlendi. `6afc6d1f8`
* \[Fix] Derleme (dotnet restore) hatası düzeltildi. `c3a05243d`
* \[Fix] Derleme ayarlarında düzeltme yapıldı. `c1ba4a3ce`
* \[Build] .gitignore dosyası güncellendi. `94f2fe932`
* \[Build] Dağıtım (deploy) hattı güncellendi. `fc2e048f1`
* \[Add] Paylaşımlı ve güvenlik modülleri (ClassicUO.Shared, ClassicUO.Library) ana repoya eklendi. `82d26c3f2`
* \[Build] Dağıtım hattı tekrar güncellendi. `ad2db3df2`
* \[Remove] Oyun verisi klasörü .gitignore'dan çıkarıldı. `85a4dd121`
* \[Build] Dağıtım hattı üçüncü kez güncellendi. `148b12296`
* \[Build] Dağıtım hattı dördüncü kez güncellendi. `2d703bbde`
* \[Edit] Güncelleme sistemi kodunda düzenleme yapıldı. `e4b336b2f`
* \[Build] Dağıtım hattı beşinci kez güncellendi. `753ac77ae`
{% endupdate %}

{% update date="2026-04-27" tags="Add,Fix,Perf,Edit,Remove" %}
## 27 Nisan 2026

* \[Add] Harita render güncellemesinden sonra statik/mobil gölgeler geri getirildi. `86ca4507c`
* \[Fix] Bir yazım hatası (typo) düzeltildi. `be39ef9f7`
* \[Perf] Render performans altyapısında düzenlemeler yapıldı (liste yönetimi yeniden yapılandırıldı). `7bd68e0cb`
* \[Edit] Tekne hareket yönetiminde düzenleme yapıldı. `86a955962`
* \[Edit] Animasyonlu statik nesne yönetiminde düzenleme yapıldı. `b9a354143`
* \[Edit] Render listeleri altyapısı güncellendi. `eb97703c2`
* \[Add] Bellek dostu yeni bir liste yapısı (PooledList) eklendi. `bc5af7a6c`
* \[Remove] Eski liste yapısı (FastList) kaldırıldı. `e860aaa54`
* \[Edit] Metin çizim sisteminde düzenleme yapıldı. `f0336bf48`
* \[Edit] Oyun dosyası yönetiminde düzenleme yapıldı. `475e960f8`
* \[Edit] Yazı tipi yükleyicisinde düzenleme yapıldı. `f4907a159`
* \[Edit] Buton bileşeninde düzenleme yapıldı. `d580e17b8`
* \[Edit] Kırpılmış metin bileşeninde düzenleme yapıldı. `a58fc2cfd`
* \[Edit] Etiket bileşeninde düzenleme yapıldı. `38a11da03`
* \[Edit] Kitap penceresinde düzenleme yapıldı. `dc3f0fe6f`
{% endupdate %}

{% update date="2026-04-25" tags="Add,Build" %}
## 25 Nisan 2026

* \[Add] Nebula sunucusu (tamamlanarak) eklendi. `896e38da6`
* \[Build] Kurulum dosyası güncellendi. `ac1544030`
{% endupdate %}

{% update date="2026-04-13" tags="Security,Edit" %}
## 13 Nisan 2026

* 🔒 \[Security] Hile tespit eşik değeri artırıldı (hile önleme, detay paylaşılmıyor). `b89f22d13`
* \[Edit] Oyun kontrolcüsü, yakınlık sesli sohbet aktifse ona göre güncelleme yapacak şekilde düzenlendi. `079091fd0`
* \[Edit] Yakınlık bazlı sesli sohbet yöneticisinde düzenleme yapıldı. `af6bf52f0`
{% endupdate %}

{% update date="2026-04-12" tags="Fix,Edit" %}
## 12 Nisan 2026

* \[Fix] Onaltılık (hex) sayı ayrıştırmada boşluk temizleme düzeltmesi (ana projeden). `9faf653fb`
* \[Edit] Yakınlık bazlı sesli sohbette güncellemeler yapıldı. `1ad822baa`
{% endupdate %}

{% update date="2026-04-10" tags="i18n,Add,Remove,Edit" %}
## 10 Nisan 2026

* \[i18n] Yerelleştirme güncellendi. `ea4d9cdd9`
* \[Add] Günlük (Journal) penceresine tekrar eden mesajları filtreleme sistemi entegre edildi. `db68da979`
* \[Remove] İsim üstü gösterimin fare üzerine gelince hareket etmesi kapatıldı. `75a13c65c`
* \[Add] Yakınlık sohbeti tuş ayarları, ayarlar ve profil sistemine entegre edildi. `5d92e1792`
* \[Edit] Uygulama başlangıç kodunda düzenleme yapıldı. `e6135f4a1`
{% endupdate %}

{% update date="2026-04-09" tags="Edit" %}
## 9 Nisan 2026

* \[Edit] Yakınlık bazlı sesli sohbet yöneticisinde güncellemeler yapıldı. `e1adeb002`
{% endupdate %}

{% update date="2026-04-08" tags="Add,Fix" %}
## 8 Nisan 2026

* \[Add] Yeni bir sunucu (Nebula) eklendi. `9554168d2`
* \[Fix] Yakınlık bazlı sesli sohbet yöneticisindeki derleyici uyarıları giderildi. `b4ac88218`
* \[Fix] Ağ bağlantısı bileşenindeki derleyici uyarısı giderildi. `697676782`
{% endupdate %}

{% update date="2026-04-07" tags="Edit" %}
## 7 Nisan 2026

* \[Edit] Yakınlık bazlı sesli sohbette güncellemeler yapıldı. `c18af5052`
{% endupdate %}

{% update date="2026-04-06" tags="Add" %}
## 6 Nisan 2026

* \[Add] Sesli sohbet sunucusu (UOVoiceServer) dış kaynak olarak eklendi. `701cffc05`
* \[Add] Yakınlık bazlı sesli sohbet (ProximityVoice) özelliği eklendi. `ecfe2ddfe`
{% endupdate %}

{% update date="2026-04-04" tags="Build" %}
## 4 Nisan 2026

* \[Build] .gitignore dosyası güncellendi (proje bakımı). `7f90ffeea`
{% endupdate %}

{% update date="2026-04-03" tags="Add,Edit,Security,Refactor" %}
## 3 Nisan 2026

* \[Add] Yeni harita client komutları eklendi: -map, -worldmap, -overview. `034b4e139`
* \[Add] Açılır menü öğelerine sabit metin (clilocid dışında) desteği eklendi. `9b66c070a`
* \[Edit] Açılır menü penceresinde düzenleme yapıldı. `fd9662e13`
* \[Add] Web tabanlı harita servisine oda yönetimi ve odadaki oyuncuları gösterme özelliği eklendi. `b29edaf3a`
* 🔒 \[Security] Makro spam/flood koruması eklendi (detay paylaşılmıyor). `4ddfea011`
* \[Refactor] Yorum satırlarındaki bozuk karakterler temizlendi. `5b74f3fa6`
* \[Edit] Profil ayarlarında düzenleme yapıldı. `ff4396224`
{% endupdate %}

{% update date="2026-04-02" tags="Add" %}
## 2 Nisan 2026

* \[Add] Dünya haritasında zoom seviyesine göre etiket gösterme/gizleme ayarı eklendi. `3ad27f516`
{% endupdate %}

{% update date="2026-04-01" tags="Fix" %}
## 1 Nisan 2026

* \[Fix] En hızlı hareket modunda (SpeedMode 4) dünya senkron hatası ve animasyon hatası giderildi. `01283f0ba`
{% endupdate %}

{% update date="2026-03-31" tags="Add,Edit" %}
## 31 Mart 2026

* \[Add] "-info" komutuna pencere bilgisi de eklendi. `c24956dd7`
* \[Add] Geçerli profil için boş (null) kontrolü eklendi. `cb0ae0f8d`
* \[Add] Yeni "-quit" komutu eklendi; komutların komut listesinde görünüp görünmeyeceği ayarlanabilir hale getirildi. `86a258734`
* \[Add] Oyun içindeyken karakter değiştirmeyi sağlayan "-charlist" komutu ve penceresi eklendi. `836758a39`
* \[Add] "GOD Mode" eklendi: duvar ve zeminlerin üzerinden geçilebiliyor; "-godmode" client komutu ile. `81adb9e2c`
* \[Edit] Karakter listesi penceresinde zaten çevrimiçi olan karakterin seçilememesi sağlandı. `8bf42ced0`
* \[Add] Karakter ekranı için iki yeni profil ayarı eklendi. `fd5d0118b`
* \[Edit] Metin giriş penceresinde düzenleme yapıldı. `8777f5738`
* \[Add] Ayarlar penceresine arama ve filtreleme özelliği eklendi (önemli güncelleme). `0e228e464`
{% endupdate %}

{% update date="2026-03-26" tags="Edit,Add,Fix" %}
## 26 Mart 2026

* \[Edit] Sunucu-istemci veri paketi işleme kodunda düzenleme yapıldı. `258d6a168`
* \[Add] Bölge bayrağına göre renk ayarlamaları profil ayarlarına eklendi. `bf7ced332`
* \[Edit] Geliştirme ortamı ayarları güncellendi. `47652f0a5`
* \[Edit] Geliştirme ortamı ayarları güncellendi (istemci). `5ea90a804`
* \[Add] Büyü verisi (Spells.json) sistemi eklendi; büyücülük kitabı ve simgeleri güncellendi. `466ca1f57`
* \[Fix] Metin çiziminde hatalı kırpma sorunu düzeltildi. `e08be63ab`
{% endupdate %}

{% update date="2026-03-25" tags="Add,Edit" %}
## 25 Mart 2026

* \[Add] Küçük harita alanına merkez noktası (sarı nokta) eklendi. `fcef50d7e`
* \[Add] Ayar dosyası oluşturuldu. `26bc54390`
* \[Edit] Yerel ayar dosyası güncellendi. `70c57dbd8`
* \[Add] Ayar dosyası oluşturuldu. `ae2095b40`
{% endupdate %}

{% update date="2026-03-24" tags="Add" %}
## 24 Mart 2026

* \[Add] Harita alanı bileşeni TazUO'dan eklendi. `96460e355`
{% endupdate %}

{% update date="2026-03-23" tags="Add,Edit,Fix" %}
## 23 Mart 2026

* \[Add] Değer değişim olayları (ValueChanged) eklendi. `6253887be`
* \[Edit] Ayarlar penceresinde düzenleme yapıldı. `7be86c9ab`
* \[Fix] İsim üstü gösterimle tek tık mesajlarının iç içe girmesi sorunu düzeltildi. `179a56264`
* \[Edit] Konuşma balonu ve mesaj kutusu satır boyutları güncellendi. `b71909b31`
* \[Add] Açılır liste (combobox) bileşenine seçim olayı eklendi. `9fd1c07d9`
* \[Add] İsim üstü gösterime can çubuğuna ek olarak mana ve stamina çubuğu da eklendi. `49c64ed19`
* \[Add] Yazı parlaklığı (String Brightness) sistemi eklendi. `253d1ec26`
* \[Edit] Standart yetenekler penceresinde düzenleme yapıldı. `15e8035e3`
* \[Fix] Izgara yağma (GridLoot) penceresinde eşyaların renk göstermemesi sorunu giderildi. `6322d14f9`
* \[Edit] Arayüz tipi için varsayılan profil değeri ayarlandı. `151b1836a`
{% endupdate %}

{% update date="2026-03-22" tags="Edit" %}
## 22 Mart 2026

* \[Edit] Standart yetenekler penceresinde düzenleme yapıldı. `357d46881`
* \[Edit] Dünya haritası penceresinde düzenleme yapıldı. `077e0b79a`
{% endupdate %}

{% update date="2026-03-21" tags="Refactor,Fix" %}
## 21 Mart 2026

* \[Refactor] Kod sadeleştirmesi yapıldı (ana projeden). `597742d79`
* \[Fix] İsim üstü gösterim penceresi güncellendi ve düzeltmeler yapıldı. `32467675b`
* \[Refactor] Kullanılmayan tekrar eden bir kod satırı temizlendi. `8a74b469f`
{% endupdate %}

{% update date="2026-03-20" tags="Fix,Security,Edit,Perf" %}
## 20 Mart 2026

* \[Fix] Girdi/çıktı, yardımcı araçlar, ağ ve başlatıcı katmanlarında 14 doğrulanmış hata düzeltildi (ana projeden). `66be7872a`
* 🔒 \[Security] Güvenlik modülü proje ayarları güncellendi (detay paylaşılmıyor). `a4c836a72`
* \[Fix] HTML pencerelerinde siyaha yakın metinlerde oluşan siyah kenarlık hatası düzeltildi. `c1144cbda`
* \[Edit] Eksik dosyalar tamamlandı. `92675c61a`
* \[Perf] Metin çiziminde performans için paylaşımlı karakter atlası sistemine geçildi. `62ca1012a`
* \[Edit] Oyun sahnesi çizim sıralamasında düzenleme yapıldı. `93a659c81`
* \[Perf] Harita render sisteminde büyük bir performans güncellemesi yapıldı (chunk mesh yapısı). `a1aca2a4a`
* \[Fix] Şeffaflık dairesi gradyan modu ve yaprak/bitki soluklaşması düzeltildi. `73fc13ac5`
* \[Edit] Şeffaflık dairesi türü görünür yapıldı. `35a81620c`
* \[Fix] Küçük bir düzeltme entegre edildi. `8b252ded1`
{% endupdate %}

{% update date="2026-03-16" tags="Add,Fix" %}
## 16 Mart 2026

* \[Add] Yerel ayar dosyası oluşturuldu (geliştirme ortamı). `2aeef5c16`
* \[Fix] Ana projeden bir düzeltme entegre edildi. `8992d19f6`
* \[Add] Uyarlanabilir yürüme birleştirme ve hızlı dönüş seçeneği eklendi (ana projeden). `5ab04b97a`
* \[Add] Nesne etiketlerinde can çubuğu ve dostluk durumuna göre filtreleme eklendi (ana projeden). `27e996a17`
{% endupdate %}

{% update date="2026-03-10" tags="Edit" %}
## 10 Mart 2026

* \[Edit] Oda yönetim penceresinde düzenleme yapıldı. `e7eb04c3e`
* \[Edit] Durum çubuğunda düzenleme yapıldı. `fc9edddbf`
{% endupdate %}

{% update date="2026-03-04" tags="Edit,Add,Fix,Build,Remove" %}
## 4 Mart 2026

* \[Edit] Parlaklık kaydırıcısının maksimum değeri ayarlandı. `30530f8fd`
* \[Edit] Yetenek buton penceresinde düzenleme yapıldı. `46d2e1315`
* \[Add] Oda yönetim penceresi (RoomsManagerGump) oluşturuldu. `ad315bc57`
* \[Edit] Dünya haritası penceresinde düzenleme yapıldı. `15c06753b`
* \[Fix] Derleyici uyarıları ve null referans hataları giderildi. `7e0ed9d8a`
* \[Build] UOMapServer projesi için çözüm dosyası oluşturuldu. `e466b6243`
* \[Add] UOMapServer projesi eklendi. `2fe57ee9a`
* \[Edit] Dünya haritası koordinat etiketi düzenlendi. `9528fdbec`
* \[Edit] Oda yönetim penceresinde düzenleme yapıldı. `c8791a104`
* \[Fix] Şimşek (Lightning) efektindeki fazla beyazlık/parlaklık giderildi. `0a99d7558`
* \[Remove] Kullanılmayan loglar kaldırıldı. `77c763dd5`
* \[Add] Profil penceresine yazı karakter sınırlaması getirildi. `04c43fb13`
* \[Add] İlan panosuna (BBoard) yazı karakter sınırlaması getirildi. `ff1fc25d6`
* \[Fix] Varsayılan FPS ayarı 0'dan 60'a düzeltildi. `08b5a032b`
* \[Edit] Düşük FPS'lerde (12.5 ve altı) yürüme animasyon hızı ayarlandı. `16c38fa27`
* \[Add] Yok sayma listesine zaman bilgisi de eklendi. `3273b7c92`
* \[Fix] Ana projeden bir düzeltme entegre edildi. `f4f2f3dbc`
* \[Fix] Sayaç çubuğu boyutlarından kaynaklanan görsel kırpma hataları giderildi. `39f599e2c`
* \[Fix] Ana projeden bir düzeltme entegre edildi. `7aec84416`
* \[Fix] Ana projeden bir düzeltme entegre edildi. `b253da4ec`
{% endupdate %}

{% update date="2026-03-03" tags="Edit,Add,Fix,Remove" %}
## 3 Mart 2026

* \[Edit] Ayarlara yeni bir "Oyun" sekmesi eklenmeye başlandı. `90aea1998`
* \[Add] Yeni ayarlar eklendi. `c599357ee`
* \[Edit] Ayarlar penceresinde düzenleme yapıldı. `4c6ce143b`
* \[Edit] Yapılacaklar listesi (TODO) güncellendi. `ee0895a41`
* \[Add] Northern sunucusu eklendi. `fb4342482`
* \[Fix] Yorum satırlarındaki bozuk karakterler düzeltildi. `a7de3d7fb`
* \[Add] Parlaklık (brightness) desteği eklendi (önemli özellik). `30607b417`
* \[Edit] Ayarlar penceresinde düzenleme yapıldı. `df9f8685b`
* \[Edit] Sağ tık menüsü öğe renklerinin özelleştirilebilir olması sağlandı. `d87c8f25e`
* \[Remove] Gereksiz bir log kapatıldı. `cc445bd47`
* \[Add] Yok sayma listesine kişi eklemek için "-ignore" client komutu eklendi. `e594e07b0`
* \[Edit] Parlaklık özelliğinde düzenlemeler yapıldı. `deac13f9b`
* \[Fix] Parlaklık özelliğinde düzeltme yapıldı. `beb084837`
{% endupdate %}

{% update date="2026-03-02" tags="Edit,Security" %}
## 2 Mart 2026

* \[Edit] Buton bileşeninde düzenleme yapıldı. `55c23dd4d`
* \[Edit] Dünya haritası penceresinde düzenleme yapıldı. `f120c4eb4`
* \[Edit] Dükkan penceresinde düzenleme yapıldı. `83c1d9712`
* 🔒 \[Security] Hile tespit eşik değeri güncellendi (hile önleme, detay paylaşılmıyor). `011843e9e`
{% endupdate %}

{% update date="2026-03-01" tags="Fix,Edit" %}
## 1 Mart 2026

* \[Fix] Oyun yazı tipi ile ilgili bozukluklar giderildi. `010332270`
* \[Edit] Buton üzerine gelme olayı API'ye bağlandı. `db383128b`
* \[Edit] Görev oku penceresinde düzenleme yapıldı. `ae71de755`
* \[Fix] Dünya haritasında bölge bayrağına göre yazı renklendirme sorunu giderildi. `cc769e3f2`
* \[Fix] Ayarlarda iç içe giren oyun yazı tipi ve sohbet yazı tipi ayarları düzeltildi. `9a6490e47`
{% endupdate %}

{% update date="2026-02-28" tags="Edit" %}
## 28 Şubat 2026

* \[Edit] Sistem mesajı konumlandırma (SYSMESSAGELOC) ile ilgili güncellemeler yapıldı. `a0d67d906`
* \[Edit] Bazı özellikler API'ye bağlandı. `ab5fff45d`
{% endupdate %}

{% update date="2026-02-27" tags="Add,Edit,Remove,i18n,Fix" %}
## 27 Şubat 2026

* \[Add] Hata bildirme penceresi (BugReportGump) eklendi. `8daae5e67`
* \[Edit] Etki çubuğu (BuffBar) kullanımı API ayarına bağlandı. `3fc2ddbad`
* \[Add] Üst bilgi çubuğuna yeni butonlar eklendi. `cd516eddf`
* \[Remove] Karakter ekranında sürüme bağlı olarak günlük/görev butonlarının gizlenmesi kaldırıldı. `30097e13d`
* \[Add] Profil ayarına oyun yazı tipi (GameFont) eklendi. `d1ff4b7df`
* \[i18n] Kaynak yerelleştirmeleri güncellendi. `f967d4c87`
* \[Add] Yeni bir sunucu eklendi: northern. `e6ebbda01`
* \[Add] Ana dosyaya yeni sunucu tanımı eklendi. `b5369c5e4`
* \[Edit] Hata bildirimi (BugReport) gönderim paketi tamamlandı. `2d7fe16d2`
* \[Edit] Başlatıcı güncellemeleri yapıldı. `738ceb57d`
* \[Edit] Kitap penceresinde düzenleme yapıldı. `369405be0`
* \[Add] Konteyner adının gösterilmesi profil ayarı eklendi. `9fdb1daf7`
* \[Edit] Döşeli pencere görselinde emülatör uyumu için renk ayarı yapıldı. `f66c2b44e`
* \[i18n] Yeni yerelleştirme kaynakları eklendi. `5d892c6e8`
* \[Add] Ses filtreleme (SoundFilter) sistemi eklendi. `7873e8565`
* \[Edit] Yetenek (skill) penceresi orijinal OSI istemcisine benzetilmeye çalışıldı. `61672f83d`
* \[Edit] Modern renk seçici bileşeninde düzenleme yapıldı. `069916a03`
* \[Edit] "Hareketsizlik" hız modu (SpeedMode) ile ilgili düzenlemeler yapıldı. `e6f78a8f6`
* \[Fix] Kritik bir hareket hatası düzeltildi ("karakter uçuyordu"). `8d5be24e3`
* \[Edit] Runebook'tan gelen işaretler ayrıştırılıp XML dosyasına kaydedilecek şekilde ayarlandı. `0bab53da7`
* \[Edit] Runebook veri paketi güncellendi. `2b93f0365`
* \[Add] İşaret yönetim penceresine (MarkersManagerGump) anlık arama sonucu eklendi. `aa11996fe`
{% endupdate %}

{% update date="2026-02-23" tags="Add" %}
## 23 Şubat 2026

* \[Add] Client (kendi ekranındaki) seslerin sadece kendine duyulması seçeneği profil ayarlarına eklendi. `142c89d28`
* \[Add] İleri/geri gezinme butonları için yeni görsel kimlikler eklendi. `92e1d9c0a`
* \[Add] Yapay zeka asistanı için hariç tutma dosyası (.aiignore) oluşturuldu (proje bakımı). `6406d8cad`
{% endupdate %}

{% update date="2026-02-21" tags="Edit,Add,Build" %}
## 21 Şubat 2026

* \[Edit] Yaratık özellik (prop) gösteriminde düzenlemeler yapıldı. `6b3c31804`
* \[Edit] HTML metin bileşeninde düzenleme yapıldı. `df45fbefc`
* \[Add] Genel pencerelere ileri/geri gezinme butonları eklendi. `fb4de0d57`
* \[Edit] Parti üyeleri listesinde etiket yazı tipi ve rengi ayarlandı. `419246272`
* \[Add] Dünya haritasına bölge (region) adı gösterimi eklendi. `67038e326`
* \[Add] Görev okuna uzaklık, koordinat ve hedef adı bilgisi eklendi. `556cfe37e`
* \[Build] ARM64 işlemci mimarisi için derleme desteği eklendi. `a23fdff1d`
* \[Build] Proje derleme ayarları güncellendi. `5862febf6`
* \[Build] .NET 9 sürümüne geçiş uyarlamaları yapıldı; tek dosya (exe) derleme değişikliği. `63ede51c5`
* \[Add] ARM64 platform desteğine başlangıç yapıldı. `0a1ce736b`
* \[Add] Dünya haritasında bölge adı gösterme ayarı profil ayarlarına eklendi. `21172c852`
{% endupdate %}

{% update date="2026-02-20" tags="Add,Edit,Fix" %}
## 20 Şubat 2026

* \[Add] Yeni, gelişmiş bir dükkan penceresi (ShopGumpExtended) eklendi (deneysel, tamamlanmadı). `2a57b56b3`
* \[Add] İki yeni profil ayarı eklendi (modern dükkan penceresi ve konteyner stili). `0ad3d1707`
* \[Edit] Oyuncu karakteri kodunda düzenleme yapıldı. `da2e5990a`
* \[Add] Dükkan penceresi altyapısında eklenti yapıldı. `f299c538f`
* \[Add] Makrolara yeniden adlandırma butonu eklendi. `fd2fbe529`
* \[Fix] Makro isimlendirme ile ilgili bir sorun düzeltildi. `683e7433c`
* \[Add] Birden fazla yazı tipi dosyasının aynı anda kullanılabilmesi eklendi (deneysel). `f0f07e970`
* \[Add] Uygulama penceresine küçültme/büyütme, şeffaf arkaplan ve kapatma butonları eklendi. `71a3cbd03`
* \[Add] Makrolar için toplu isimlendirme özelliği eklendi. `d57e13e56`
{% endupdate %}

{% update date="2026-02-19" tags="Fix" %}
## 19 Şubat 2026

* \[Fix] Buton üzerindeki eşya görselinin pencere dışına taşması sorunu giderildi. `23aae99ed`
* \[Fix] Yeni hedefleme sisteminin üst/alt pencereleri yanlışlıkla boyaması düzeltildi. `5463470af`
* \[Fix] Yeni hedefleme sistemi seri numarası çift tıklamada da ayarlanacak şekilde düzeltildi. `426f769cd`
{% endupdate %}

{% update date="2026-02-17" tags="Edit,Security" %}
## 17 Şubat 2026

* \[Edit] İsim üstü gösterim penceresinde düzenleme yapıldı. `539cf19f1`
* \[Edit] Mini harita penceresinde düzenleme yapıldı. `bb52b8a87`
* \[Edit] Genel pencere altyapısında düzenleme yapıldı. `8f274bf0f`
* \[Edit] Sayaç çubuğu öğesinde düzenleme yapıldı. `7f343af17`
* \[Edit] Buton bileşeninde düzenleme yapıldı. `934905b17`
* \[Edit] Makro yönetim sisteminde düzenleme yapıldı. `c49cf8b6d`
* 🔒 \[Security] Güvenlik modülü (native) proje ayarlarında güncelleme yapıldı (detay paylaşılmıyor). `d1af089c8`
{% endupdate %}

{% update date="2026-02-13" tags="Remove" %}
## 13 Şubat 2026

* \[Remove] Profil dosyasına, "gelişmiş profili" kaldırabilen bir ayar (NOADV) eklendi. `d3c80047e`
{% endupdate %}

{% update date="2026-02-12" tags="Fix,Edit" %}
## 12 Şubat 2026

* \[Fix] Profil dosyasında (profiles.json) karşılığı olmayan ayarların hata vermesi düzeltildi. `754556a82`
* \[Edit] Büyücülük kitabı sayfa göstergesi güncellendi. `56e20fbd6`
* \[Edit] Bazı pencerelerin (spellicon gibi) asenkron açılıştan hariç tutulması sağlandı. `6eef75de2`
{% endupdate %}

{% update date="2026-02-11" tags="Add" %}
## 11 Şubat 2026

* \[Add] Runebook (işaret kitabı) verilerinin istemciye gönderilmesi eklendi. `d1ddacb2a`
* \[Add] Yardım penceresine konu yönlendirme (GotoTopic) eklendi. `d10c3198c`
* \[Add] Konteyner penceresine konteyner adının yazılması eklendi. `7359e29f7`
{% endupdate %}

{% update date="2026-02-08" tags="Edit" %}
## 8 Şubat 2026

* \[Edit] Karakter oluşturma ekranında Elf ve Gargoyle ırk seçenekleri sunucu özelliğine göre gösterilecek şekilde ayarlandı. `7fbe692ef`
{% endupdate %}

{% update date="2026-02-07" tags="Fix,Edit" %}
## 7 Şubat 2026

* \[Fix] Ayarlar menüsündeki makro listesi yukarı/aşağı butonları düzeltildi. `e32bfbdb0`
* \[Edit] Profil ayarları düzenlendi. `260eddc7e`
* \[Edit] Sohbet kontrolü çok satırlı yazmaya bağlandı. `d39647c6e`
{% endupdate %}

{% update date="2026-02-06" tags="Edit,Build" %}
## 6 Şubat 2026

* \[Edit] Hedefleme (target) ile ilgili sorunlar güncellendi. `0ab6df6ed`
* \[Edit] Durum çubuğunda ağırlık etiketi güncellendi. `c14367edc`
* \[Build] Kurulum dosyası güncellendi. `ab19500ed`
{% endupdate %}

{% update date="2026-02-05" tags="Fix,Remove,Edit" %}
## 5 Şubat 2026

* \[Fix] Şeffaflığın anlık güncellenmeme sorunu düzeltildi. `a62d078fd`
* \[Fix] Son hedef ve hedef bekleme durumunda hedefin elde kalması sorunu düzeltildi. `bd5042155`
* \[Fix] Karakter ekranındaki yazı renk sorunu düzeltildi. `4bd67df88`
* \[Fix] Haritada parti/lonca üyelerinin hareket güncellemesi düzeltildi. `7cb631531`
* \[Remove] Sayaç çubuğunda (CounterBar) düzenlemeler yapıldı; "Use" özelliği kapatıldı, sağ tık menüsüne temizleme eklendi. `360bbaeb2`
* \[Edit] Bazı makrolar API'ye bağlandı. `39685b2b6`
* \[Fix] En hızlı hareket modunda (SpeedMode 4) yürüyemezken animasyon eksikliği giderildi. `cce60edc5`
{% endupdate %}

{% update date="2026-02-04" tags="Add" %}
## 4 Şubat 2026

* \[Add] Çanta (backpack) düzenlerinin kaydedilip yüklenmesi sistemi eklendi. `3ed0a448e`
{% endupdate %}

{% update date="2026-02-01" tags="Edit,Fix,Perf" %}
## 1 Şubat 2026

* \[Edit] Başlatıcı (Bootstrapper) güncellendi. `7768fc78f`
* \[Edit] Sunucu-istemci veri paketi işleme kodunda düzenleme yapıldı. `4b1eae347`
* \[Edit] Oyun ekranı girdi işleyicisinde düzenleme yapıldı. `a843981eb`
* \[Edit] Hareket yönetim sisteminde (WalkerManager) düzenleme yapıldı. `8de1ffd76`
* \[Edit] Oyuncu karakteri kodunda düzenleme yapıldı. `e90aae8f0`
* \[Edit] Oyun verisi yükleyicisi ana projeden güncellendi. `8758d0e88`
* \[Edit] Oyun verisi yükleyicisindeki bir değişiklik geri alındı. `271115b60`
* \[Fix] Dünya metni üzerine arayüz çizim sırası düzeltildi. `cf35e768c`
* \[Perf] Performans bilgi penceresinde düzenleme yapıldı. `3c86ab6c7`
{% endupdate %}

{% update date="2026-01-29" tags="Perf,Edit" %}
## 29 Ocak 2026

* \[Perf] Performans bilgi penceresi (PerformanceInfoGump) eklendi. `64cb5f632`
* \[Edit] Sistem sohbet kontrolünde düzenleme yapıldı. `144f1e6a5`
{% endupdate %}

{% update date="2026-01-28" tags="Remove,Edit,Refactor,Fix" %}
## 28 Ocak 2026

* \[Remove] Eski başlatıcı paketi (zip) silindi (proje bakımı). `26ec90cbb`
* \[Edit] "Denywalk" durumunda ekran titremesi sorunu araştırıldı (kesin çözüm henüz uygulanmadı). `5d2cd9825`
* \[Edit] Oyuncu karakteri kodunda düzenleme yapıldı. `acc46559d`
* \[Refactor] Oyun verisi (tiledata) okuma mekanizması ana projeden entegre edilerek yeniden düzenlendi. `81198d691`
* \[Fix] Bir çökme (crash) hatası ana projeden entegre edilerek düzeltildi. `6b4669c57`
* \[Fix] Sohbet ve çok katmanlı (multi) derinlik sorunu ana projeden entegre edilerek düzeltildi. `4f04c34e1`
* \[Edit] Oyuncu karakteri kodunda düzenleme yapıldı. `db61eddcb`
{% endupdate %}

{% update date="2026-01-27" tags="Edit,Fix,Add,Refactor,Build" %}
## 27 Ocak 2026

* \[Edit] Ekran DPI ölçeği değiştiğinde pencere boyutunun buna göre güncellenmesi sağlandı. `7be1b1536`
* \[Fix] Sayaç çubuğunun (CounterBar) hücre boyutu değişimi düzgün çalışacak şekilde düzeltildi. `a1c1cf2db`
* \[Add] Yeni bir sunucu (wisdom) eklendi. `9df47aaa7`
* \[Refactor] Başlatıcıda kullanılmayan sınıflar temizlendi. `d804bdd60`
* \[Add] Yeni bir sunucu (wisdom) eklendi (tekrar/tamamlama). `ce9b018b8`
* \[Edit] Başlatıcı (Bootstrap) güncellemesi yapıldı. `70eec1821`
* \[Fix] Girişte API bağlantısındaki gecikme giderildi. `1484fcf4e`
* \[Build] Kurulum dosyası güncellendi. `1e851dc83`
* \[Build] Derleme/yükleme script'i güncellendi. `061ed607d`
* \[Edit] Türkçe hata mesajları kaynak dosyası güncellendi. `53ca08d86`
* \[Build] Kurulum dosyası güncellendi. `03a300a94`
* \[Build] Kurulum bağımlılıkları dosyası güncellendi. `99f978eb0`
* \[Build] Derleme/yükleme script'i güncellendi. `bf3241dfb`
* \[Build] Kurulum dosyası güncellendi. `dd1ff926d`
* \[Edit] Başlatıcı güncellemeleri yapıldı. `dbc521b0d`
{% endupdate %}

{% update date="2026-01-23" tags="Edit,Build,Add,Remove,Fix" %}
## 23 Ocak 2026

* \[Edit] Başlatıcı (Bootstrapper) güncellemeleri yapıldı. `5d1014735`
* \[Build] Script/derleme güncellemeleri yapıldı. `ede24b838`
* \[Edit] Durum çubuğunda düzenleme yapıldı. `10a8c1e29`
* \[Edit] Ayarlar penceresinde düzenleme yapıldı. `b42072fa6`
* \[Edit] Giriş penceresinde düzenleme yapıldı. `c3210d092`
* \[Edit] Onay/sözleşme penceresinde düzenleme yapıldı. `6c6b584c6`
* \[Edit] Yardım penceresinde düzenleme yapıldı. `a3ad6ec22`
* \[Edit] Karakter oluşturma/takas penceresinde düzenleme yapıldı. `fd6b9c5c8`
* \[Edit] Buton bileşeninde düzenleme yapıldı. `71a437e6a`
* \[Edit] Giriş ekranı kodunda düzenleme yapıldı. `a22ec0469`
* \[Edit] Profil ayarlarında düzenleme yapıldı. `2f413cf5e`
* \[Edit] Uygulama başlangıç kodunda düzenleme yapıldı. `54c5fd2cc`
* \[Edit] Geliştirici başlangıç ayarları güncellendi. `58ff7ee4c`
* \[Add] Yeniden boyutlanabilir görsele kısmi renk (hue) özelliği eklendi; isim üstü gösterimindeki sorun düzeldi. `663332d21`
* \[Edit] Giriş ekranı arkaplanı eski haline döndürüldü. `0f502caed`
* \[Remove] Bazı pencerelerde gereksiz görsel sorgusu kaldırıldı. `5bb46038b`
* \[Fix] Ayarlar menüsünün farklı yerde açılması sorunu giderildi. `15e4828c2`
* \[Edit] Karakter seçim ekranında, karakter ekranı verisi yoksa arkaplanın buna göre ayarlanması sağlandı. `054ae7959`
* \[Edit] Ayarlar penceresinde buton görselinde düzenleme yapıldı. `89c475f3a`
* \[Edit] Ayarlar penceresi son konumu hatırlayacak şekilde güncellendi. `c8cf3ee1d`
* \[Edit] Oyun içi aksiyonlar kodunda düzenleme yapıldı. `bc11270fc`
* \[Edit] Üst bilgi çubuğunda (TopBarGump) düzenleme yapıldı. `cc4a98391`
{% endupdate %}

{% update date="2026-01-22" tags="Add,Perf,Fix,Edit,Remove,Refactor" %}
## 22 Ocak 2026

* \[Add] Dünya haritasına parti ve lonca üyesi gösterimi eklendi. `de9ad5a8e`
* \[Perf] Pencere görsel sorgusu eklendi (performans). `5d9b403ea`
* \[Fix] Karakter ekranından büyücülük kitabı açılırken renk sorgusu eklendi; renksiz kitaplar düzeltildi. `099db4947`
* \[Edit] Dünya haritası penceresinde düzenleme yapıldı. `884237e4c`
* \[Edit] Karakter ekranında düzenleme yapıldı. `5243582b8`
* \[Edit] Konteyner (çanta/kutu) penceresinde düzenleme yapıldı. `b67720067`
* \[Remove] Butonlardaki üzerine gelme efekti geçici olarak kaldırıldı. `75c522b67`
* \[Add] Eşya aramaya renge göre filtreleme de eklendi. `7d200d9f0`
* \[Remove] Bazı loglar kaldırıldı. `01593773e`
* \[Refactor] Kullanılmayan sabit değerler temizlendi. `5ac9fe063`
* \[Edit] Varsayılan profil ayarları güncellendi. `cc324ce17`
* \[Edit] Eski Sphere (X1) sunucularında olup istemcide eksik olan efekt parametreleri için büyük düzenlemeler yapıldı. `3a3f826ff`
* \[Edit] Efekt sistemi güncellemeleri yapıldı. `9740a67d7`
* \[Fix] Türkçe karakterli bir mesajdaki hata düzeltildi. `5b6c9f788`
* \[Fix] Karakter ekranındaki binek (mount) slotu render sorunları düzeltildi. `c2bae2e96`
* \[Edit] Konteyner penceresinde tıklama alanı/tooltip konumu değiştirildi. `88d0d8c82`
* \[Fix] Küçük dosyaların geç yüklenmesi sorunu düzeltildi. `1ccd44f3c`
* \[Fix] Efektlerle ilgili çeşitli düzeltmeler yapıldı. `26b1072a0`
* \[Edit] Oyun verisi (TileData) yükleyicisinde düzenleme yapıldı. `7e9758d3f`
{% endupdate %}

{% update date="2026-01-21" tags="Add,Edit,Refactor,Fix,i18n,Build" %}
## 21 Ocak 2026

* \[Add] Dünya haritasına yürünen yolu kaydetme ve temizleme özelliği eklendi. `725e8e7b8`
* \[Edit] Ayarlar penceresinde düzenlemeler yapıldı. `7b0c85dfb`
* \[Edit] Başlatıcı uygulama ikonu güncellendi. `0ab619a59`
* \[Add] "Yürünen yolu göster" ayarı profil ayarlarına eklendi. `406ffcfa2`
* \[Edit] İstemci sürüm bilgisi veri gönderiminden hariç tutuldu. `264de8488`
* \[Edit] Sunucudan gelen hata mesajlarının gösterimi düzenlendi. `ff00a4d89`
* \[Refactor] Yorum satırlarındaki özel karakterler temizlendi (kod bakımı). `73b8f209d`
* \[Fix] Etki (buff) çubuğunda süre etiketinin hizası düzeltildi. `299eee32e`
* \[Edit] Can çubuğu (HealthBar) penceresinde düzenleme yapıldı. `a588ceafb`
* \[Add] Yeni sunucular eklendi, bağlantı adresleri güncellendi. `00ff13400`
* \[Edit] İkon uygulama yöntemleri değiştirildi. `ca63dd3b8`
* \[Add] Butonların üzerine gelme (hover) efekti sunucuya göre özelleştirilebilir hale getirildi. `b76b50b47`
* \[Add] Parti penceresine takip (follow) özelliği eklendi. `bab929151`
* \[Add] Yok sayma (Ignore) listesine, isim yanında karakter seri numarası da eklendi. `3b63541ab`
* \[Fix] Bazı yazı tiplerinde onay kutusu etiketinin dikey konum hatası düzeltildi. `0e6a1f176`
* \[i18n] Yerelleştirme güncellendi. `b9ba0bfd2`
* \[Edit] Yok sayma listesi yönetimi güncellendi. `8617e3fd7`
* \[Build] Derleme yapıldı. `56bfa4fda`
* \[Add] Parti üyesi bilgisine konum (X,Y, Harita) eklendi. `c82927fbf`
* \[Add] Makro hedefleme (MacroTarget) özelliği eklendi. `c7aa50dd2`
* \[Edit] Makro yönetim sisteminde düzenleme yapıldı. `ed3049784`
* \[Edit] Dünya haritası varlık yönetiminde düzenleme yapıldı. `ab41cad57`
* \[Edit] Komut yönetim sisteminde düzenleme yapıldı. `b0196f7ed`
* \[Edit] Oyuncu karakteri kodunda düzenleme yapıldı. `55252107d`
* \[Edit] Zemin görünümü kodunda düzenleme yapıldı. `06ecb38c4`
* \[Edit] Yol bulma (Pathfinder) sisteminde düzenleme yapıldı. `407def889`
* \[Edit] Oyun ekranı girdi işleyicisinde düzenleme yapıldı. `f97883b0e`
* \[Edit] Giriş ekranı kodunda düzenleme yapıldı. `daa7302a5`
* \[Edit] Makro kontrol penceresinde düzenleme yapıldı. `cd364e042`
* \[Edit] İnceleme (Inspector) penceresinde düzenleme yapıldı. `5063876ed`
* \[Edit] Onay/sözleşme penceresinde düzenleme yapıldı. `263d2dcbe`
* \[Edit] Giriş penceresinde düzenleme yapıldı. `eab36e21d`
* \[Edit] Görev oku (QuestArrow) penceresinde düzenleme yapıldı. `ada8efb9a`
* \[Edit] API güncellemesi yapıldı. `a72e4e768`
* \[Add] Düşme anında ses efekti eklendi (OSI istemcisine benzer şekilde). `3fe284a7e`
* \[Add] 3 boyutlu yüzeye duyarlı adım sesi özelliği eklendi. `b51d14639`
* \[Edit] (Geliştirici) test ortamı klasör ayarı değiştirildi. `36d834ad2`
* \[Add] Ayarlar penceresindeki makro alanına arkaplan eklendi. `f744ae6cc`
* \[Edit] Çeşitli küçük düzenlemeler yapıldı. `687be9642`
{% endupdate %}

{% update date="2026-01-19" tags="Add,Edit,Fix,i18n,Remove" %}
## 19 Ocak 2026

* \[Add] Büyücülük kitabında (Spellbook) fare tekerleğiyle sayfa değiştirme eklendi. `73cd5e9ac`
* \[Add] Genel pencerelerde fare tekerleğiyle sayfa değiştirme eklendi. `2d3c4915e`
* \[Edit] Durum çubuğunda düzenleme yapıldı. `3501e2a91`
* \[Fix] Şeffaflık kontrolündeki bir görsel sorun giderildi. `85ca5b6c7`
* \[i18n] Yerelleştirmeler güncellendi. `032d9136b`
* \[Remove] Eski "RazorMacro" özelliği kaldırıldı, son hedefe göre canlıya gitme özelliği kapatıldı. `478ad909e`
* \[Add] Yeni bir sunucu (uobattle) giriş listesine eklendi. `411caa26a`
* \[Fix] Şeffaflık dairesinin karaktere tam merkezlenmemesi sorunu düzeltildi. `5b756ce92`
* \[Edit] Kitap penceresinde düzenleme yapıldı. `a166202a7`
* \[Edit] Kitap penceresinde tekrar düzenleme yapıldı. `028db21f4`
* \[Edit] Kitap penceresinde üçüncü kez düzenleme yapıldı. `c09f6dff2`
{% endupdate %}

{% update date="2026-01-11" tags="Remove,Build" %}
## 11 Ocak 2026

* \[Remove] Derlenmiş .exe/.dll dosyaları git takibinden çıkarıldı (proje bakımı). `02a4d2e44`
* \[Build] Script'ler ve yapılandırma dosyaları güncellendi. `dbfe2cc87`
* \[Build] .gitignore dosyası güncellendi. `ae2dd3233`
* \[Build] Derleme komutları shell script'ten PowerShell'e taşındı (FTP ile yükleme yapılacak şekilde). `f6590446a`
* \[Build] Kurulum (installer) dosyası paylaşımlı klasöre taşındı. `84c527fac`
* \[Build] API bağlantıları AOT (Native derleme) ile uyumlu hale getirildi. `c730d9a3f`
{% endupdate %}

{% update date="2026-01-10" tags="Security,Build,Fix,Edit" %}
## 10 Ocak 2026

* 🔒 \[Security] Native güvenlik modülü (ClassicUO.Library) projeye eklendi (detay paylaşılmıyor). `1c4f128fb`
* 🔒 \[Security] Dahili bir yardımcı araç eklendi (detay paylaşılmıyor). `fd61d0576`
* 🔒 \[Security] Dosya yolu koruma aracı eklendi (detay paylaşılmıyor). `7f4905130`
* \[Build] Dış kaynaklar ve script'ler düzenlendi. `7dbbbd877`
* \[Fix] Ana projeden bir düzeltme entegre edildi. `97481f1e3`
* \[Edit] Yardımcı araçlar (Utility) modülü güncellendi. `b4e778c46`
* \[Edit] Paylaşımlı (Shared) modül güncellendi. `7bed26f46`
* \[Edit] Başlatıcı (Bootstrapper) modülü güncellendi. `4f24cc0ee`
* \[Edit] UOSoft'a özel istemci modülleri güncellendi. `162f4c567`
* \[Edit] İstemci (Client) modülünde büyük güncellemeler yapıldı. `e3e607960`
* \[Edit] Varlık (Assets) modülünde küçük güncellemeler yapıldı. `6e31ef401`
* \[Edit] Girdi/çıktı (IO) modülünde küçük güncellemeler yapıldı. `4acf162f1`
* \[Build] Proje derleme ayarları güncellendi. `504209d04`
* 🔒 \[Security] Ek güvenlik önlemleri eklendi (detay paylaşılmıyor). `070c22a2e`
{% endupdate %}

{% update date="2026-01-06" tags="Edit,Add,Remove" %}
## 6 Ocak 2026

* \[Edit] "Launcher" ismi "Bootstrap" olarak değiştirildi. `8f4801f93`
* \[Add] Yeni bir log türü (DEV) eklendi. `28c7a2f55`
* \[Add] Paylaşımlı (shared) bir proje eklendi. `7d3311948`
* \[Remove] Kullanılmayan "filepacker" projesi silindi. `6ddbf7986`
* \[Edit] Başlatıcı (Bootstrap) uygulamasında güncellemeler yapıldı. `4f2eb56fb`
{% endupdate %}

{% update date="2026-01-05" tags="Add,Security,Perf,i18n,Build" %}
## 5 Ocak 2026

* \[Add] Log sistemine milisaniye hassasiyeti eklendi. `a4187cd67`
* 🔒 \[Security] Hile önleme (anti-cheat) ve yetkisiz müdahale önleme (anti-hook) sistemleri baştan değiştirildi (detay paylaşılmıyor). `f9c720a16`
* \[Add] Paket kaydı (packetlog) client komutlarına eklendi. `e0809ac5e`
* \[Perf] Donanım bilgisi gönderimi performans için asenkron hale getirildi. `c166697b2`
* \[i18n] Yerelleştirme kaynakları güncellendi. `99a54c941`
* \[Build] Derleme/yükleme script'i güncellendi. `2a0b9199d`
* \[Add] Dosya güncelleme sistemine, dosyanın değiştirilme tarihini kontrol eden ek bir güvenlik kontrolü eklendi. `d55de340c`
* 🔒 \[Security] Hızlı/otomatik tıklama tespit sistemi güncellendi (hile önleme, detay paylaşılmıyor). `00dd42f3a`
{% endupdate %}

{% update date="2026-01-04" tags="Add,Build,Fix,Remove,Edit" %}
## 4 Ocak 2026

* \[Add] Binek (mount) yükseklik tanımları eklendi. `3f4daff31`
* \[Build] .gitignore dosyaları eklendi (proje bakımı). `673704b24`
* \[Fix] Evlerin sonradan (gecikmeli) görünmesi sorunu düzeltildi. `ecd46d77c`
* \[Fix] Log kaydında düzeltme yapıldı. `b3aa42430`
* \[Remove] "Following" (takip etme) özelliği geçici olarak kapatıldı. `549ee9baf`
* \[Edit] Dükkan penceresinde (ShopGump) para yetersizse fiyat etiketleri kırmızı gösterilecek şekilde ayarlandı. `63e706091`
* \[Edit] Sunucu veri paketleri daha detaylı ayrıştırılmaya başlandı. `16c3dfdce`
* \[Fix] Karakter ekranındaki (paperdoll) hatalar düzeltildi. `594932f04`
* \[Remove] Web tabanlı harita servisinden gereksiz bir sorgu kaldırıldı. `f0a9a7423`
* \[Add] Karakter ekranını yeniden açma altyapısı eklendi (henüz kullanılmıyor). `8342870a8`
* \[Edit] Ayarlar penceresinde düzenleme yapıldı. `0398ebc66`
* \[Edit] Profil ayarlarında düzenleme yapıldı. `e4f63d7ad`
{% endupdate %}

{% update date="2026-01-03" tags="Fix,Add,Edit" %}
## 3 Ocak 2026

* \[Fix] Ana ClassicUO projesinden bir düzeltme entegre edildi. `99d0e888b`
* \[Add] Ana projedeki hava durumu (Weather) özelliği entegre edildi (PR 1852). `ae73eb8ae`
* \[Fix] Karakter ayaklarının duvar arkasından görünmesi düzeltmesi sadece insan (human) karakterlerle sınırlandırıldı. `dd4c0f42a`
* \[Edit] Sunucu-istemci veri paketi işleme kodunda düzenleme yapıldı. `1682407fa`
* \[Edit] Büyük, kapsamlı bir güncelleme yapıldı. `bdebb6194`
{% endupdate %}

{% update date="2026-01-02" tags="Fix,Remove,i18n,Edit" %}
## 2 Ocak 2026

* \[Fix] Derleyici uyarısı giderildi. `b145c0a4b`
* \[Remove] Bir log kaydı kaldırıldı. `d5a3159aa`
* \[i18n] Yerelleştirme (dil) güncellemesi yapıldı. `419d8049f`
* \[Edit] Kaynak dosya dizini değiştirildi. `6b0dfba2e`
* \[Fix] Derleyici uyarısı giderildi. `c9fcb95e8`
* \[Remove] RazorACK paket gönderimi kaldırıldı. `7bcfe4efb`
* \[Edit] Genel bir güncelleme yapıldı. `fe3622f3d`
{% endupdate %}

{% update date="2026-01-01" tags="Edit,Fix,Add,Refactor,Perf,Build,i18n" %}
## 1 Ocak 2026

* \[Edit] TazUO'dan alınan Discord entegrasyonunda düzenlemeler yapıldı. `3859a4d45`
* \[Edit] Görsel kaynak (assets) dosyaları düzenlendi. `6184c8fd7`
* \[Fix] Derleyici uyarıları giderildi. `80dd776c3`
* \[Add] Görsel çizim motoruna (Renderer) FontStashSharp yazı tipi desteği eklendi. `8560a170d`
* \[Add] Varlık (Assets) sistemine FontStashSharp desteği eklendi. `2c99603d8`
* \[Edit] Şeffaflık bileşenine renk verme düzenlemesi yapıldı. `80eb5edfc`
* \[Add] Tıklanabilir web bağlantısı bileşeni eklendi (TazUO'dan). `c7c5b55cf`
* \[Edit] Yeniden boyutlanabilir günlük (Journal) penceresinin arkaplan rengi ayarlanabilir yapıldı. `928c987f2`
* \[Edit] Discord ayarlarında bir veri tipi değişikliği yapıldı. `98bb42ee1`
* \[Add] Profil ayarlarına yeni seçenekler eklendi. `af5e2ae55`
* \[Refactor] Komut yönetim sistemi yeniden düzenlendi. `c3f6be8bf`
* \[Edit] Yardım penceresinde düzenleme yapıldı. `578ab6fed`
* \[Perf] Pencere çerçeve çiziminde render performans düzenlemesi yapıldı. `d1d0fd53d`
* \[Perf] Yeniden boyutlanabilir statik görsellerde render performans düzenlemesi yapıldı. `02c960f73`
* \[Refactor] Metin giriş alanı yeniden düzenlendi. `346c82aea`
* \[Refactor] Metin kutusu yeniden düzenlendi (yazı renginin her zaman siyah görünmesi sorunu devam ediyor). `499aa69c4`
* \[Perf] Dış bağlantılı görselde render performans düzenlemesi yapıldı. `3a95e3ced`
* \[Edit] Genel kontrol bileşeninde düzenleme yapıldı. `b9298ebcd`
* \[Add] Pencere görseline (GumpPic) gömülü görsel desteği eklendi (TazUO'dan). `d700d325d`
* \[Edit] Kaydırılabilir alan bileşeninde düzenleme yapıldı. `b2087aa89`
* \[Edit] Genel pencere (Gump) altyapısında düzenleme yapıldı. `73169c417`
* \[Perf] Alan/bölge bileşeninde render performans düzenlemesi yapıldı. `c91c44af4`
* \[Edit] API bağlantı adresleri değiştirildi. `163875c0a`
* \[Edit] Sunucu-istemci veri paketi işleme kodunda düzenleme yapıldı. `9f1b2f579`
* \[Add] Desteklenen ekran yenileme hızı (refresh rate) tespiti eklendi. `ca14b7e60`
* \[Edit] Durum çubuğunda (StatusGump) düzenleme yapıldı. `a9c971c25`
* \[Edit] Ayarlar penceresinde düzenleme yapıldı. `3469131f9`
* \[Add] Olay yönetimi (EventSink) altyapısı eklendi (TazUO'dan). `f0b30cb0a`
* \[Edit] Dünya (World) yönetim kodunda düzenleme yapıldı. `f3ee89523`
* \[Edit] Oyun sahnesi (GameScene) kodunda düzenleme yapıldı. `4df483499`
* \[Edit] Mesaj tipi tanımlarında düzenleme yapıldı. `27a81e957`
* \[Edit] Oyun içi aksiyonlar kodunda düzenleme yapıldı. `3a19375c3`
* \[Add] Discord yönetim sistemi (DiscordManager) oluşturuldu. `e46a84a88`
* \[Add] Web tabanlı harita servisi yönetim sınıfı oluşturuldu. `6a5026efb`
* \[Add] Web tabanlı harita servisi oluşturuldu. `00a13bf6f`
* \[Edit] Harita (Map) kodunda düzenleme yapıldı. `bb3b999d7`
* \[Edit] Dünya haritası penceresinde düzenleme yapıldı. `5bd3de92a`
* \[Edit] Dünya görüntüleme penceresinde düzenleme yapıldı. `a8e0004e6`
* \[Build] İstemci proje ayarları güncellendi. `9894fef83`
* \[Build] Derleme çıktıları düzenlendi. `dbef28445`
* \[Build] Çözüm (solution) dosyası güncellendi. `6f71e600b`
* \[Add] Bilinen hatalar (BUGS.md) dosyası oluşturuldu. `4e5e469a2`
* \[i18n] Yerelleştirme (dil) dosyaları güncellendi. `f8d7c6b66`
{% endupdate %}

{% update date="2025-12-31" tags="Edit,Add,Refactor,Remove" %}
## 31 Aralık 2025

* \[Edit] API bağlantı adresleri değiştirildi. `468d542f4`
* \[Add] TazUO projesinden bazı eklentiler/bileşenler alınıp entegre edildi. `72a655548`
* \[Refactor] Kullanılmayan kodlar temizlendi. `1e17f2904`
* \[Refactor] UOLoop (ana oyun döngüsü) yeniden yazıldı. `8c7099a50`
* \[Edit] Log içerikleri düzenlendi. `84228dc1e`
* \[Edit] Arayüz (UI) tipiyle ilgili güncelleme yapıldı. `932216780`
* \[Edit] Tekne kontrol sisteminde düzenleme yapıldı. `6f5c234e5`
* \[Refactor] Komut yönetim sistemi (Command Manager) yeniden yazıldı ve komutlar penceresi (CommandsGump) eklendi. `4e8495370`
* \[Edit] Metin giriş penceresinde düzenleme yapıldı. `89edea7f8`
* \[Add] Yeni ekipman (paperdoll) slotları eklendi. `ad4c6d391`
* \[Edit] Metin kutusu bileşeninde düzenleme yapıldı. `7d28e934c`
* \[Edit] Kaydırma çubuğu (slider) bileşeninde düzenleme yapıldı. `236cb3ef8`
* \[Edit] Aynı pikselde hızlı tıklama sınırı gevşetildi (yanlışlıkla hile şüphesi oluşmasını azaltmak için). `35bf72e1e`
* \[Remove] Asistan üzerinden komut kaydı özelliği kapatıldı. `dd5c7c187`
* \[Edit] PNG yükleyici ile mevcut temanın ayarlanması sağlandı. `82a7b2192`
* \[Add] Yeni veri serileştirme (JSON) tanımları eklendi. `b1cd1bcb9`
* \[Edit] Oyun içi aksiyonlar (GameActions) dosyasında düzenleme yapıldı. `10dd9d1fc`
* \[Edit] Uygulama başlangıç kodunda düzenleme yapıldı. `31944fc85`
* \[Edit] Giriş ekranı (LoginScene) kodunda düzenleme yapıldı. `86c5e1b38`
* \[Add] Discord SDK dış kaynak olarak eklendi. `9c9535f11`
* \[Add] Yardımcı bir metin işleme (regex) aracı eklendi. `4f0d6b24b`
* \[Add] Web tabanlı harita servisi için veri serileştirme tanımları eklendi. `9fcbf5d08`
* \[Add] Sürüm geçmişi (VersionHistory) penceresi eklendi. `30f6b45c0`
* \[Add] Pencere konumlandırma yardımcı aracı eklendi. `baecfdfa5`
* \[Add] Yeni pencere çerçeve çizim bileşeni eklendi (TazUO'dan). `3dce0057f`
* \[Add] Kutu düzenleme (VBoxContainer) arayüz bileşeni eklendi (TazUO'dan). `9c81126e6`
* \[Add] Menü buton bileşeni eklendi (TazUO'dan). `efcaa9513`
* \[Add] Dış bağlantılı görsel (ExternalUrlImage) bileşeni eklendi (TazUO'dan). `9331db94e`
* \[Add] Alan/bölge (Area) arayüz bileşeni eklendi (TazUO'dan). `2f2dcb3fb`
* \[Add] FontStashSharp (yazı tipi) kütüphanesi projeye eklendi. `ae127c56f`
* \[Add] Yazı tipi ve varlık yükleyicileri eklendi (TazUO'dan). `0aa9d9b75`
* \[Add] Şeffaflık bileşenine renk (hue) desteği eklendi. `01788c1b3`
* \[Add] Discord arayüz bileşenleri eklendi (TazUO'dan). `cfa5bcde2`
* \[Add] Discord oyun içi pencereleri eklendi (TazUO'dan). `25678519e`
{% endupdate %}

{% update date="2025-12-30" tags="Add,Build" %}
## 30 Aralık 2025

* \[Add] Yardım indeksi (help index) penceresi eklendi. `f3bd93a0d`
* \[Add] Yardım içerik dosyası (Helpindx.json) oluşturuldu. `aa6764f3d`
* \[Add] Karakter kıyafet listesi dosyası oluşturuldu. `9eb3fd3ab`
* \[Build] Derleme yapıldı. `bf2c53769`
* \[Add] PNG yükleyici eklendi; pencere (gump) ve görsellerin özelleştirilmesi (override) sistemi getirildi. `4892f2ab6`
{% endupdate %}

{% update date="2025-12-29" tags="Edit,Build,Security" %}
## 29 Aralık 2025

* \[Edit] Başlatıcı (launcher/Bootstrap) uygulamasında güncelleme yapıldı. `d46a0cd07`
* \[Build] Derleme script'leri üzerinde düzenleme yapıldı. `ed607d5d9`
* 🔒 \[Security] Bcrypt (şifreleme) kullanımı kaldırıldı (güvenlik altyapı değişikliği). `017908993`
* \[Build] İstemci proje ayarları güncellendi. `dd2ce0542`
* \[Edit] Genel bir güncelleme yapıldı. `25180ce6d`
* \[Build] Script klasörü düzenlendi. `3f8c2dc8c`
* \[Edit] Başlatıcı güncellendi. `49ae8a771`
* \[Edit] Log içerikleri düzenlendi. `16a00d8d2`
* \[Edit] Karakter seçim ekranında düzenleme yapıldı. `f3968b796`
{% endupdate %}

{% update date="2025-12-28" tags="Build,Edit" %}
## 28 Aralık 2025

* \[Build] Yayınlama script'i güncellendi; dosyalar yayından önce sunucuya yükleniyor. `dfb630c4b`
* \[Build] İstemci derleme script'i güncellendi. `9f524135b`
* \[Edit] Başlatıcının (launcher) güncelleme mekanizması güncellendi. `b57a9d1a9`
{% endupdate %}

{% update date="2025-12-27" tags="Edit,Build,Add" %}
## 27 Aralık 2025

* \[Edit] Kritik, büyük bir güncelleme yapıldı. `735d90153`
* \[Edit] Ana ClassicUO projesindeki (upstream) güncellemeler UOSoft'a aktarıldı. `ffc418cd4`
* \[Edit] Genel ayarlar dosyasında düzenleme yapıldı. `a5c3b751a`
* \[Edit] Ekran yakınlaştırma (zoom) özelliği üzerinde çalışıldı. `925d2be11`
* \[Build] Derleme (build) script'leri eklendi. `b5d889a19`
* \[Edit] Genel bir güncelleme yapıldı. `f065ba2ea`
* \[Add] Discord entegrasyonuna (RPC/IPC) deneysel yeni yöntemler eklendi. `70d17a5d9`
{% endupdate %}

{% update date="2025-12-19" tags="Security,Edit,Add,Remove,Build,Fix" %}
## 19 Aralık 2025

* 🔒 \[Security] Dosya koruma sistemiyle ilgili ek bir çalışma yapıldı (detay paylaşılmıyor). `ed343ca39`
* \[Edit] Discord durum gösterimi (RPC) güncellendi. `e50127e52`
* \[Add] Eksik dosya kontrolü eklendi (güncelleme sistemi için). `d4ee85f14`
* \[Add] Hesap yönetimi (AccountManager) altyapısı eklendi. `4afa66443`
* \[Remove] Dünya haritasındaki karakter noktaları kaldırıldı. `5a8cb2383`
* \[Remove] Üst bilgi çubuğundaki (topbar) bilgi butonu kaldırıldı. `2ffd0893f`
* \[Edit] Çeşitli dosya ve ayar güncellemeleri yapıldı. `ad81a6d2e`
* \[Build] Test projesi ayarları güncellendi. `2e398375b`
* \[Fix] Bir derleyici uyarısı giderildi. `7d8b079bf`
* \[Edit] Başlatıcı (Bootstrapper) uygulamasında güncellemeler yapıldı. `e03af2200`
* \[Edit] Uygulama ortam ayarlarında düzenleme yapıldı. `78319861f`
* \[Add] Ekran renk tonu (screen hue) özelliği eklendi. `afd1c248d`
* \[Fix] Ekran renk tonu ve ağaç görünümü ile ilgili bir düzeltme eklendi. `20aa25f0a`
* \[Remove] Mevsim (season) sisteminde hatalı görünen eşyalar varsayılan listeden çıkarıldı. `247c1bd60`
* \[Fix] Karakter ayaklarının duvar arkasından görünmesi hatası için deneme amaçlı bir düzeltme yapıldı. `744369b54`
{% endupdate %}

{% update date="2025-12-16" tags="Security,Add,Edit" %}
## 16 Aralık 2025

* 🔒 \[Security] Dosya koruma sistemiyle ilgili bir modül eklendi (detay paylaşılmıyor). `ae2d37a49`
* \[Add] Projeye UOSoft'a özel klasör yapısı eklendi. `ef2e81b96`
* \[Edit] Başlatıcı (Bootstrap) uygulamasında güncelleme yapıldı. `0ce66634c`
* \[Edit] Log (kayıt tutma) sisteminde güncelleme yapıldı. `0b1900e35`
{% endupdate %}

{% update date="2025-12-13" tags="Fix,Edit" %}
## 13 Aralık 2025

* \[Fix] Bir derleyici uyarısı giderildi. `b653549b5`
* \[Edit] UOSoft fork'unun ilk büyük başlangıç commiti atıldı. `e3028ed30`
* \[Edit] Fork'un temel proje yapısı kuruldu. `ca591cb98`
* \[Edit] Deneme amaçlı bir commit. `f2468ffcc`
{% endupdate %}
{% endupdates %}
