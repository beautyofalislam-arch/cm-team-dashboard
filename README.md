# CM Team Dashboard

Prototipe dashboard Condition Monitoring untuk tim Reliability. Seluruh data merupakan simulasi; belum terhubung ke SAP.

## Cara membuka

1. Pada halaman repository, pilih **Code → Download ZIP**.
2. Ekstrak ZIP.
3. Buka **index.html** menggunakan Chrome, Edge, atau Firefox.

Tidak memerlukan instalasi, server, atau koneksi internet. Halaman file di GitHub menampilkan kode; dashboard dijalankan dengan membuka file HTML yang sudah diunduh. Repository ini belum dikonfigurasi sebagai website online.

## Fitur

- Overview: monitoring compliance, coverage, equipment condition, dan prioritas tindak lanjut.
- Findings & SAP: pencarian temuan, status pekerjaan, evidence eksekusi, dan verifikasi CM.
- Monitoring delivery: jadwal pengukuran, keterlambatan, dan kesiapan instrumen.
- Data & KPI rules: definisi KPI dan usulan pemetaan data SAP.
- Filter NGL-1 / NGL-3 / NGL-4 dan teknik Vibration / Oil analysis / Thermography.
- Klik equipment tag untuk melihat detail temuan.

## Batasan

Snapshot data demo: 17 September 2026. Dashboard read-only: belum menerima upload data atau menyimpan perubahan pengguna. Status SAP dan technical closure CM dipisahkan. Semua identitas equipment dan catatan bersifat sintetis. Definisi KPI dan pemetaan SAP merupakan usulan yang memerlukan peninjauan tim sebelum penggunaan operasional.

## Struktur

`index.html` berisi tampilan, style, JavaScript, dan data demo dalam satu file tanpa dependency eksternal.
