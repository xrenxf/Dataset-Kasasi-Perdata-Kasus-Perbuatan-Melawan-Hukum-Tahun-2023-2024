## Sumber Data

Sumber utama pengumpulan data dalam dataset ini adalah **Direktori Putusan Mahkamah Agung Republik Indonesia**, yang dapat diakses melalui:

**Direktori Putusan Mahkamah Agung Republik Indonesia**  
[https://putusan3.mahkamahagung.go.id/]

Data perkara dikumpulkan berdasarkan dokumen putusan yang tersedia pada situs resmi tersebut, dengan fokus pada **perkara kasasi perdata dengan klasifikasi Perbuatan Melawan Hukum (PMH)** pada periode tahun 2023–2024.

Informasi yang terdapat dalam dataset CSV disusun berdasarkan informasi yang tercantum dalam dokumen putusan pengadilan. Dokumen putusan yang disertakan dalam repository digunakan sebagai **sumber dokumen utama untuk verifikasi dan penelusuran data**.

### Sumber Utama

- **Nama:** Direktori Putusan Mahkamah Agung Republik Indonesia
- **Institusi:** Mahkamah Agung Republik Indonesia
- **Situs:** Direktori Putusan Mahkamah Agung Republik Indonesia](https://putusan3.mahkamahagung.go.id/)
- **Periode Data:** 2023–2024
- **Jenis Perkara:** Perdata
- **Klasifikasi:** Perbuatan Melawan Hukum (PMH)
- **Tingkat Perkara:** Kasasi

---

## Tujuan Dataset

Dataset ini dikembangkan untuk:

- Menyediakan data terstruktur mengenai perkara kasasi Perbuatan Melawan Hukum.
- Mendukung penelitian hukum berbasis data (*data-driven legal research*).
- Mendukung analisis terhadap karakteristik perkara dan putusan pengadilan.
- Memudahkan peneliti dalam melakukan eksplorasi dan analisis data perkara.
- Menyediakan sumber data untuk penelitian terkait putusan pengadilan tingkat pertama, banding, dan kasasi.
- Mendukung penelitian di bidang *Legal Data*, *Legal Analytics*, *Natural Language Processing (NLP)*, dan *Legal Technology*.

---

## Atribut Dataset

Dataset CSV terdiri atas beberapa atribut yang menggambarkan informasi utama mengenai perkara dan putusan pengadilan.

| No. | Atribut | Keterangan |
|---:|---|---|
| 1 | **Nomor Perkara** | Nomor registrasi perkara kasasi. |
| 2 | **Tanggal Putusan** | Tanggal putusan kasasi dikeluarkan. |
| 3 | **Nama Hakim** | Nama hakim agung yang memeriksa dan memutus perkara kasasi. |
| 4 | **Penggugat/Pemohon** | Pihak yang mengajukan gugatan pada tingkat pertama atau mengajukan permohonan kasasi. |
| 5 | **Tergugat/Termohon** | Pihak yang digugat atau menjadi lawan dalam perkara, termasuk pihak yang menjadi termohon kasasi. |
| 6 | **Pertimbangan Hakim** | Alasan-alasan hukum (*ratio decidendi*) yang menjadi dasar bagi hakim dalam memeriksa, memutus perkara, dan merumuskan isi amar putusan. |
| 7 | **Amar Putusan** | Isi putusan kasasi yang memuat keputusan Mahkamah Agung. |
| 8 | **Hasil Kasasi** | Status hasil pemeriksaan kasasi, yaitu apakah permohonan kasasi dikabulkan atau ditolak oleh Mahkamah Agung. |
| 9 | **Nomor Putusan Pertama** | Nomor putusan yang dikeluarkan oleh pengadilan pada tingkat pertama. |
| 10 | **Amar Putusan Pertama** | Isi putusan pengadilan pada tingkat pertama. |
| 11 | **Nomor Putusan Banding** | Nomor putusan yang dikeluarkan oleh pengadilan pada tingkat banding. |
| 12 | **Amar Putusan Banding** | Isi putusan pengadilan tingkat banding yang menguatkan, mengubah, atau membatalkan putusan pengadilan tingkat pertama. |

---
