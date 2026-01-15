# CommandLogicStudio

Minecraft için geliştirilen **datapack’ler**, **sunucu içi yönetim araçları** ve  
**deneysel framework projeleri**nin toplandığı organizasyon.

Bu organizasyon; bakım, modülerlik ve sürüm uyumluluğu odaklı çalışmalar içerir.  
Genel kullanımdan çok, **geliştirici ve test amaçlı** projeler barındırır.

---

## 📦 İçerik Türleri

- ⚙️ Sunucu yönetim datapack’leri  
- 🧩 GUI / menü sistemleri  
- 🧠 Global tick & handler framework’leri  
- 🛠️ Deneysel ve dahili araçlar  

---

## 🧪 Geliştirme Yaklaşımı

- Modüler yapı
- Tick-safe sistemler
- Okunabilir mcfunction mimarisi
- Geriye dönük uyumluluk önceliği

---

## 🔒 Kullanım Notu

Bu organizasyondaki projelerin bir kısmı:
- Deneyseldir
- Dahili kullanım içindir
- Genel dağıtıma uygun olmayabilir

Her repo kendi README’sinde kullanım durumunu belirtir.

---

## 👤 Organizasyon Yapısı

- Ana hesap: proje yönetimi ve ana geliştirme
- Yan hesap(lar): test, otomasyon ve deneysel çalışmalar

---

> GulcePacks — düzenli, kontrollü ve sürdürülebilir Minecraft datapack geliştirme alanı.

<details>
<summary><strong>⚠️ Log Uyarıları ve Hata Bilgilendirmesi</strong></summary>

Bu bölüm, log dosyasında görünen hata ve uyarıların **datapack kaynaklı olmadığını** açıklamak amacıyla eklenmiştir.

---

### ❌ Datapack Kaynaklı Hata Bulunmamaktadır

Log kayıtlarında;
- Datapack dizinlerine ait (`data/.../function(s)`)
- `.mcfunction` dosyalarına referans
- Stacktrace veya çökme raporu
- Komut sözdizimi (syntax) hatası

**yer almamaktadır.**  
Bu durum datapack’in sorunsuz çalıştığını göstermektedir.

---

### ⚠️ Teknik Uyarılar (Datapack Dışı)

**Bilinmeyen oyuncu için bilgi güncellemesi yok sayıldı**  
- İstemci ve sunucu arasındaki senkronizasyon farklarından kaynaklanır  
- Oyun içi sistemleri veya datapack işleyişini etkilemez

**Profil anahtarı alınamadı / doğrulama yanıtı alınamadı**  
- Ağ bağlantısı veya kimlik doğrulama süreci ile ilgilidir  
- Datapack tarafından kontrol edilemez

---

### ℹ️ Oyuncu Kaynaklı Mesajlar

**Bilinmeyen veya eksik komut**  
**Tanımsız puan tablosu görevi**  
- Yanlış veya eksik komut kullanımından kaynaklanır  
- Datapack hatası değildir

**Yetki yok / işlem izni bulunmuyor**  
- Yetkilendirme sisteminin düzgün çalıştığını gösterir  
- Hata olarak değerlendirilmez

---

### ✅ Sonuç

Log dosyasında görünen tüm uyarılar;
- İstemci davranışları
- Bağlantı ve senkronizasyon süreçleri
- Oyuncu kaynaklı hatalar

nedeniyle oluşmuştur.

**Datapack tarafında işlevsel veya teknik bir hata tespit edilmemiştir.**

</details>
