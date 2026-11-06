# İzleme ve Yönetim (Monitoring)

Sistemimizin takibi iki koldan yapılmaktadır:

*   **Sistematik Kısım:** Tüm ofislerdeki FortiGate cihazları, loglarını İstanbul Merkez ofisteki FortiAnalyzer (SIEM) sunucusuna gönderir. CPU kullanımı %80'i aştığında, VPN tünelleri koptuğunda veya kritik bir IPS kuralı tetiklendiğinde sistem otomatik olarak e-posta alarmı üretir.
*   **İnsan Kısmı:** Mesai saatleri içinde (09:00 - 18:00) İstanbul Merkez ofisteki IT ve Güvenlik Ekibi NOC/SOC ekranlarından (Grafana vb.) anlık ağ trafiğini izler. Mesai dışı kritik alarmlar için nöbetçi IT personeline SMS bildirimi gider.
