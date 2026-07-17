---
description: >-
  Bu sayfada, kurulum veya kullanım esnasında karşılaşabileceğiniz yaygın teknik
  durumlar ve çözümleri yer almaktadır.
---

# Hata & Uyarılar

#### Kütüphane Kaynaklı Sorunlar

Client, düzgün çalışabilmek için bazı resmi Windows kütüphanelerine ihtiyaç duyar. Bu kütüphaneler kurulumla birlikte otomatik yüklense de; internet kesintisi, VPN/Proxy kullanımı gibi nedenlerle eksik kalabilir.

* Belirti: Client'ın hiç açılmaması veya oyun içinde aniden kapanması (crash).
* Çözüm: Kurulumu yönetici olarak tekrar başlatın veya eksik kütüphaneleri (DirectX, .NET vb.) manuel olarak güncelleyin.

#### İşletim Sistemi Notları

UOSoft Client, en güncel Windows sürümlerinde en yüksek performansı verecek şekilde optimize edilmiştir.

* Windows 10 Pro / Windows 11 (64-Bit): En sorunsuz ve stabil çalıştığı sürümlerdir.
* Windows 10 Home: Bu sürüm bazı temel sistem bileşenlerini içermediği için kurulum esnasında daha fazla ek yapılandırma gerektirebilir.

#### Defender ve Güvenlik Uyarıları

UOSoft Client, topluluğuna karşı şeffaf ve tamamen temiz bir yazılımdır. Ancak bazı durumlarda Defender veya SmartScreen "False-Positive" uyarılar verebilir.

Neden Uyarı Alabilirsiniz?

1. Anti-Cheat Sistemleri: Hileyi engellemek için kullanılan gelişmiş yakalama yöntemleri.
2. Kod Karmaşıklaştırma: Yazılımın bütünlüğünü korumak ve tersine mühendisliği önlemek için kullanılan güvenlik kodları.
3. Özel Şifreleme: Veri güvenliğini sağlamak için kullanılan karmaşık algoritmalar.

{% hint style="info" %}
**Güvenlik Uyarıları ve Antivirüs Politikası Hakkında Resmi Bilgilendirme**

Yazılımlarımız, bazı üçüncü parti antivirüs programları tarafından hatalı şekilde (false-positive) tehdit olarak algılanabilmektedir. Piyasada çok sayıda antivirüs firması bulunması ve bazılarının bu hatalı bildirimleri kaldırmak için ücret talep etmesi nedeniyle, her bir program için ayrı ayrı doğrulama süreci yürütmek operasyonel çok fazla iş yükü oluşturmaktadır. Bu sebeple, uygulamalarımızın güvenilirlik değerlendirmesinde standart referans noktası olarak yalnızca _**Windows Defender dikkate alınmaktadır.**_ Olası güvenlik uyarılarında yalnızca bu platformun sonuçlarını dikkate almanızı rica ederiz.
{% endhint %}

> Bilgilendirme: Yazılımımızı düzenli olarak Microsoft'a analiz için göndersek de, Defender bazen güncel olmayan veritabanları nedeniyle bu güvenlik katmanlarını tehdit olarak algılayabilir.
>
> Önemli: Eğer bilgisayarınızda daha önceden var olan başka bir virüs varsa, bu zararlı yazılımlar client dosyalarımıza bulaşmaya çalışabilir. Bu durumda antivirüs programınız aslında bizim dosyamızı değil, ona bulaşmaya çalışan tehdidi algılıyor olabilir. Lütfen sisteminizi genel bir taramadan geçirdiğinizden emin olun.
