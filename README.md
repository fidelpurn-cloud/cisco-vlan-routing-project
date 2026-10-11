# Network Engineering Project: VLAN & Inter-VLAN Routing

## 📌 Deskripsi Proyek
Repositori ini mendokumentasikan perancangan, konfigurasi, dan pengujian **Virtual Local Area Network (VLAN)** serta **Inter-VLAN Routing (Router-on-a-Stick)** menggunakan aplikasi **Cisco Packet Tracer**. Proyek ini berfokus pada segmentasi jaringan enterprise secara logis untuk meningkatkan efisiensi *broadcast domain*, keamanan data, serta manajemen lalu lintas antar-subnet yang terpusat melalui *router*.

---

## 🛠️ Alat dan Teknologi yang Digunakan
- **Perangkat Simulasi:** Cisco Packet Tracer (`.pkt`)
- **Teknologi Utama:** VLAN (IEEE 802.1Q Trunking), Access Port, dan Router-on-a-Stick (Sub-interface Routing)
- **Skema Alokasi Jaringan (IP Addressing):**
  - **VLAN 10 (Management):** Network `10.10.10.0/24` | Gateway: `10.10.10.1`
  - **VLAN 20 (Operational):** Network `172.16.20.0/24` | Gateway: `172.16.20.1`
  - **VLAN 30 (IT):** Network `192.168.30.0/24` | Gateway: `192.168.30.1`

---

## ⚠️ Catatan Ralat Visual Dokumentasi
Pada rekaman video demonstrasi proyek ini, terdapat sedikit kekeliruan visual pada pelabelan teks di *canvas* Cisco Packet Tracer, di mana posisi label **VLAN 20** dan **VLAN 30** sempat tertukar dengan posisi penempatan perangkat PC di bawahnya. Seluruh standar implementasi teknis dan hasil pengujian dalam repositori ini sepenuhnya merujuk pada standar alokasi IP di atas sebagai acuan yang valid.

---

## 📈 Hasil dan Pencapaian Pengujian
- **Komunikasi Intra-VLAN:** Perangkat di dalam segmen VLAN yang sama berhasil terhubung dan bertukar data secara langsung tanpa kendala.
- **Komunikasi Inter-VLAN:** Komunikasi lintas subnet berhasil diteruskan secara stabil oleh *router* melalui pemanfaatan *sub-interface* dan enkapsulasi `dot1Q`.
- Berhasil menyusun dokumentasi proyek jaringan secara komprehensif beserta file simulasinya.

---

## 📂 Cara Menggunakan Repositori
1. Unduh file simulasi berformat `.pkt` yang tersedia di dalam repositori ini.
2. Buka file tersebut menggunakan aplikasi **Cisco Packet Tracer** untuk melihat detail topologi jaringan secara utuh.

---

## 🎥 Bukti Video Demonstrasi
Rekaman video demonstrasi dan penjelasan implementasi proyek ini dapat dilihat melalui tautan berikut:
- 🔗 **[Tautan Video Dokumentasi Proyek VLAN (Google Drive)](https://drive.google.com/drive/folders/1PzMIu0bDagsLjIL5mU8Q8YUPLosiIU1P?usp=sharing)**

---
## 👨‍💻 Penulis
**Mochamad Rizky Fidel Purnama**  
*SMK Informatika Al-Irsyad Al-Islamiyyah Cirebon (Teknik Jaringan Komputer dan Telekomunikasi)*
