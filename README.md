# Capstone-10-
# Analisis Strategi Disaster Recovery Center (DRC)

# Deskripsi
Proyek ini merupakan analisis strategi **Disaster Recovery Center (DRC)** untuk layanan **Dinas Kependudukan dan Pencatatan Sipil (Dukcapil) Kota Bogor**. Penelitian membandingkan implementasi **Cloud-Native (Microsoft Azure)**, **On-Premise**, dan **Hybrid** berdasarkan aspek teknis serta biaya untuk menentukan solusi yang paling efisien.

# Tujuan
- Mengidentifikasi layanan SPBE yang termasuk layanan kritis.
- Merancang arsitektur DRC berbasis Cloud dan On-Premise.
- Mengukur performa pemulihan menggunakan **Recovery Time Objective (RTO)** dan **Recovery Point Objective (RPO)**.
- Membandingkan **Total Cost of Ownership (TCO)** dari masing-masing skenario.
- Memberikan rekomendasi strategi DRC yang sesuai untuk Pemerintah Kota Bogor.

# Teknologi yang Digunakan
- VMware Workstation
- PostgreSQL Streaming Replication
- Cisco Packet Tracer
- Microsoft Azure Pricing Calculator
- Google Spreadsheet

# Hasil
- **Technical RTO:** 41 detik
- **Operational RTO:** 114 detik
- **RPO:** 0 transaksi (tidak ada kehilangan data)
- Solusi **On-Premise** lebih hemat dibandingkan Cloud penuh dengan penghematan sekitar **Rp2,43 miliar** dalam periode 5 tahun.
- Strategi yang direkomendasikan adalah **Hybrid DRC**, yaitu On-Premise sebagai sistem utama dan Azure Site Recovery sebagai cadangan saat terjadi bencana besar.

# Struktur Repository
```
├── laporan/
├── topologi/
├── simulasi/
├── analisis-biaya/
└── README.md
```
