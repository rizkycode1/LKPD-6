# LKPD-6
Misi 1
Pertanyaan: Apa yang dimaksud dengan Merge Conflict dalam Git?
Merge Conflict adalah kondisi ketika Git menemukan perubahan yang berbeda pada bagian atau baris kode yang sama dari dua branch yang akan digabungkan, sehingga Git tidak dapat menentukan perubahan mana yang harus dipakai secara otomatis.
Jawaban Studi Kasus
Kasus 1
Pertanyaan: Budi ingin membatalkan proses merge yang bermasalah. Apa perintahnya?
Jawaban:
git merge --abort

Perintah tersebut digunakan untuk membatalkan proses merge yang sedang berlangsung dan kembali ke kondisi sebelum merge.
Kasus 2
Apakah merge conflict selalu berarti ada anggota tim yang melakukan kesalahan?
Jawaban:
Tidak. Merge conflict tidak selalu berarti ada anggota tim yang melakukan kesalahan. Conflict dapat terjadi secara normal ketika dua developer mengubah bagian atau baris kode yang sama pada branch yang berbeda. Git tidak dapat menentukan perubahan mana yang harus dipertahankan secara otomatis, sehingga anggota tim perlu berdiskusi dan menentukan hasil yang disepakati.
