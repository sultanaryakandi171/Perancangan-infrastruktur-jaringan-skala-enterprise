# Perancangan Infrastruktur Jaringan Skala Enterprise & IoT Portfolio

Repositori ini berisi dokumentasi lengkap dan file simulasi Cisco Packet Tracer untuk dua skenario implementasi arsitektur jaringan tingkat lanjut. Proyek ini mengintegrasikan kompetensi inti dari kurikulum Cisco CCNAv7 (ITN, SRWE, dan ENSA).

## 📂 Struktur dan Isi Repositori

### 1. Publikasi Ilmiah Tugas Akhir (IoT & WSN)
* **`Tautan Jurnal Resmi`**: [Evaluasi Kinerja Sistem WSN Berbasis ESP32 dengan Topologi Star dan Mesh Multi-Hop (Jurnal Litek)](https://ejournal.pnl.ac.id/index.php/litek/article/view/121).
* **Teknologi Utama:**
  * **Wireless Sensor Network (WSN)** menggunakan 6 unit node ESP32.
  * **Topologi Star & Mesh Multi-Hop** dengan pengujian protokol ESP-NOW dan PainlessMesh (Self-healing).
  * **Analisis Performa** berbasis parameter Packet Delivery Ratio (PDR), Latensi, dan RSSI.

### 2. Lab Jaringan Kantor (VLAN, HSRP, VoIP)
* **`Jaringan_Kantor_VLAN_HSRP_VoIP.pkt`**: File mentah simulasi Cisco Packet Tracer.
* **`Dokumentasi_Jaringan_Lab_Kantor.pdf`**: Laporan teknis yang mendokumentasikan konfigurasi redundansi gateway dan layanan IP Phone.
* **Teknologi Utama:**
  * **VLAN & Inter-VLAN Routing** untuk segmentasi departemen kerja.
  * **HSRP (Hot Standby Router Protocol)** untuk menyediakan redundansi default gateway tinggi (High Availability).
  * **VoIP (Voice over IP)** untuk implementasi layanan telepon digital berbasis IP pada infrastruktur router Cisco.

### 3. Lab Jaringan Warnet (Multilayer, ACL, NAT, DHCP)
* **`Warnet_Multilayer_Network_ACL_NAT_DHCP.pkt`**: File mentah simulasi Cisco Packet Tracer.
* **`Dokumentasi_Jaringan_Lab_Warnet.pdf`**: Laporan teknis perancangan jaringan distribusi bisnis internet cafe.
* **Teknologi Utama:**
  * **Multilayer Switch (Layer 3)** untuk proses routing lokal berkecepatan tinggi antar segmen.
  * **DHCP Server** untuk distribusi pengalamatan IP dinamis dan otomatis ke perangkat *client*.
  * **NAT (Network Address Translation)** untuk mentranslasikan IP privat lokal ke internet menggunakan konfigurasi PAT (Port Address Translation).
  * **Access Control Lists (ACL)** sebagai fitur pengamanan lalu lintas data dan pembatasan hak akses jaringan.

---
*Dibuat oleh Sultan Arya Kandi sebagai bukti keahlian teknis implementasi routing, switching, keamanan jaringan berbasis perangkat Cisco, serta pengembangan infrastruktur IoT.*
