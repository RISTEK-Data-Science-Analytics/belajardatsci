# Bagaimana cara berkontribusi?
1. Buat branch baru untuk repository ini, lalu clone branch tersebut ke komputer lokal.
2. Jalankan command berikut pada terminal (pastikan *path*-nya tertuju pada *repository* lokal) untuk menginstall dependency yang diperlukan:
```console
pip install -r requirements.txt
```
3. Jika ingin menambahkan page, pilih salah satu section yang berkaitan (contoh: section `Fundamental`) lalu buat file baru di dalam folder tersebut dengan format `<nama artikel>.md`.
4. Setelah selesai menulis artikel, jangan lupa untuk menambahkan nama page tersebut di dalam bagian `nav` pada `mkdocs.yml` agar artikel tersebut dapat diakses dari website ini.
5. Ajukan *pull request* untuk di-*review* oleh anggota kami.
