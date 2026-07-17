# Plugins & Assistants

ClassicUO'nun (ve dolayısıyla UOSoft istemcisinin) alt yapısında, **Razor**, **RazorEnhanced** veya **ClassicAssist** gibi 3. parti eklentileri (`.dll` / `.exe` / `.so` / `.dylib`) yükleyebilen bir eklenti sistemi bulunur.

UOSoft sunucularında 3. parti asistanlar kısıtlıdır. UOSoft istemcisi; hile önleme (**anti-cheat**) ve yetkisiz müdahale önleme (**anti-tamper**) sistemleriyle korunmaktadır (bkz. [Changelog](giris/guncellemeler/)). Bu nedenle Razor/RazorEnhanced/ClassicAssist gibi otomasyon sağlayan 3. parti asistanların kullanımı **kısıtlıdır veya yasaktır**. Eski sürümlerde bulunan "asistan üzerinden komut kaydı" gibi bazı özellikler bu yüzden bilinçli olarak kapatılmıştır.

**Bağlandığın sunucunun kurallarını kontrol etmeden 3. parti bir asistan kurma** — tespit edilmesi hesap/karakter yaptırımına yol açabilir. Hangi araçların serbest olduğu sunucudan sunucuya değişebilir; kesin bilgiyi her zaman bağlandığın UOSoft sunucusunun kendi kurallarından/Discord'undan teyit et.

## Genel bilgi: eklenti nasıl kurulur (izin verilen durumlarda)

Eğer bağlandığın sunucu belirli bir asistanın kullanımına izin veriyorsa, kurulum genel olarak şöyle işler:

1. Sunucunun izin verdiği eklentiyi indir (genelde bir `.zip` dosyası olarak gelir).
2. `.zip` dosyasını istemci klasöründeki `Data/Plugins/` altına çıkar (klasör yoksa oluştur).
3. Client otomatik olarak eklentiyi tanır ve çalışmaya başlar.

## Neden dikkatli olmalısın?

* Anti-tamper sistemleri, istemci belleğine veya dosyalarına dışarıdan müdahale eden araçları tespit etmek üzere tasarlanmıştır.
* Sunucu tarafından izin verilmeyen bir eklenti kullanmak, otomasyon (bot) kullanımıyla karıştırılabilir ve hesabının incelemeye alınmasına neden olabilir.
* Bir eklentinin "vanilla ClassicUO'da çalışıyor olması", UOSoft istemcisinde de sorunsuz/izinli çalışacağı anlamına gelmez.

**Özetle:** İstemcinin teknik olarak eklenti yükleyebilme kapasitesi var, ama bunu kullanmadan önce bağlandığın sunucunun kurallarını kontrol et.
