# Riskler ve Koruma Stratejisi

Ağımızda bulunan ofislerde neleri, neden ve nasıl koruyoruz?

*   **İstanbul Merkez:** Şirketin ana ERP, veritabanı ve Mail sunucuları buradadır.
    *   *Neden koruyoruz:* Şirketin kalbi olduğu için veri sızıntısı veya çökme büyük maddi kayba yol açar.
    *   *Nasıl koruyoruz:* Sunucular ayrı bir VLAN'a (30) alınmış ve dışarıdan gelen trafiğe karşı IPS (Saldırı Önleme Sistemi) aktif edilmiştir.
*   **Ankara Şube:** Satış ve saha operasyon verileri işlenir.
    *   *Neden koruyoruz:* Cihazlara fiziksel müdahale veya misafir cihazların ağa dahil olma riski vardır.
    *   *Nasıl koruyoruz:* Kullanılmayan switch portları kapatılmış ve MAC filtreleme yapılmıştır.
*   **İzmir Ar-Ge:** Şirketin tüm yazılım kaynak kodları buradadır.
    *   *Neden koruyoruz:* Fikri mülkiyetin çalınması (kod sızıntısı) en büyük risktir.
    *   *Nasıl koruyoruz:* Ar-Ge VLAN'ı (10) tamamen izole edilmiştir. Merkez ofisteki yönetim ekibi dahil kimse Ar-Ge ağına dışarıdan erişemez, veri çıkışı sıkı kurallara (DLP) tabidir.
