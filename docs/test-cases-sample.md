| ID | Role | Technique | Module | Scenario | Expected result | Status |
|----|------|-----------|--------|----------|-----------------|--------|
| SC-016 | Sekolah | EP | Form Tambah Realisasi Pekerjaan | Menyimpan nilai progres yang valid | Sistem menampilkan notif berhasil menyimpan data | Pass |
| SC-014 | Sekolah | BVA | Form Tambah Realisasi Pekerjaan | Menyimpan nilai progres yang tidak valid | Sistem menampilkan alert error dan tetap berada di halaman formulir | Pass |
| SC-019 | Sekolah | EP | Form Edit Realisasi Pekerjaan | Menyimpan nilai progress yang tidak valid | Sistem menampilkan alert error dan tetap berada di halaman formulir | Fail |
| SC-020 | Sekolah | EP | Form Edit Realisasi Pekerjaan | Menyimpan file bukti realisasi yang tidak valid | Sistem menampilkan alert error dan tetap berada di halaman formulir | Pass |
| SC-025 | Sekolah | Functional | Hapus Detail Realisasi Pekerjaan | Hapus detail realisasi pekerjaan | Sistem menampilkan notif berhasil menghapus data dan data pada tabel diperbarui | Fail |
| SC-043 | KCD | DT | Tambah Pekerjaan | Menambah pekerjaan dengan jenis pekerjaan tidak valid | Sistem hanya dapat memilih jenis pekerjaan yang merupakan wilayah wewenangnya | Fail |
| SC-046 | KCD | BVA | Tambah Pekerjaan | Menambah pekerjaan dengan batas atas dari total dan volume | Sistem menerima menyimpan data valid | Pass |
| SC-047 | KCD | EP| Tambah Pekerjaan | Menambah pekerjaan dengan inputan valid | Sistem menerima menyimpan data valid | Pass |
| SC-051 | KCD | EP & DT | Tambah Pekerjaan via Dashboard | Menambah pekerjaan dengan data tidak valid | Sistem hanya dapat memilih jenis pekerjaan yang merupakan wilayah wewenangnya & Sistem menolak data tidak valid | Fail |
| SC-064 | KCD | Functional | Form Edit Pekerjaan | Batal mengubah pekerjaan | Sistem tidak mengubah data | Pass |
| SC-136 | Bidang | Functional | Set Status Laporan Pekerjaan | Berhasil mengubah status laporan pekerjaan | Sistem menyimpan data baru | Pass |
| SC-137 | Bidang | Functional | Set Status Laporan Pekerjaan | Tutup form dengan perubahan data tanpa mengirim status laporan pekerjaan | Sistem tidak mengubah data | Fail |
| SC-143 | Bidang | DT | Realisasi Keuangan | Mengubah progres realisasi keuangan dengan nilai lebih kecil | Sistem menolak menyimpan data tidak valid | Fail |
| SC-144 | Bidang | EP & BVA | Realisasi Keuangan | Mengubah progres realisasi keuangan dengan nilai valid | Sistem menerima menyimpan data valid | Pass |
| SC-145 | Bidang | EP & BVA | Realisasi Keuangan | Mengubah progres realisasi keuangan dengan nilai tidak valid | Sistem menolak menyimpan data tidak valid | Fail |
| SC-188 | Disdik | EP | Reset Password Sekolah | Reset password dengan data valid | Sistem menampilkan notif berhasil mereset password sekolah | Fail |
| SC-189 | Disdik | EP | Reset Password Sekolah | Reset password dengan data tidak valid | Sistem menampilkan notif peringatan dan/atau menolak inputan tidak valid | Fail |
| SC-193 | Disdik | Functional | Logout | User berhasil logout | Logout Berhasil | Pass |
| SC-195 | Disdik | Security | Logout | User menekan tombol Back pada browser setelah logout | User tidak bisa mengakses sistem karena sesi sudah berakhir | Pass |
| SC-197 | Disdik | Functional | Export File | Ekspor data tabel menjadi file excel | Sistem mengunduh file excel | Pass |
