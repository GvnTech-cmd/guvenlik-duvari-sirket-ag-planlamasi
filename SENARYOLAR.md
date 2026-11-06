# Senaryolar ve Olay Müdahalesi

Ağımızda yaşanabilecek muhtemel olaylar ve sistemin vereceği tepkiler:

1. **Senaryo 1 (Zararlı Yazılım):** Bir personel oltalama (phishing) e-postasına tıklayıp zararlı dosya indirirse, Firewall üzerindeki Antivirüs profili devreye girer ve indirmeyi durdurur.
2. **Senaryo 2 (İzinsiz Erişim):** Misafir ağındaki (VLAN 99) biri şirket sunucularına girmeye çalışırsa, aradaki "Default Deny" kuralı gereği paket anında düşürülür (drop) ve IT ekibine log düşer.
3. **Senaryo 3 (Cihaz Arızası):** İstanbul Merkez'deki ana FortiGate cihazı (Primary) arızalanırsa, High Availability (HA) yapısı sayesinde yedek cihaz (Secondary) saniyeler içinde devreye girer ve ağ kesintisi yaşanmaz.
