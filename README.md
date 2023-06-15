# Bagaimana cara setup di *repository* lokal?
1. Buat branch baru untuk repository ini, lalu clone branch tersebut ke komputer lokal.
2. Jalankan command berikut pada terminal (pastikan *path*-nya tertuju pada *repository* lokal) untuk menginstall dependency yang diperlukan:
```console
pip install -r requirements.txt
```
3. Jalankan script di `belajardatsci/venv/activate.bat` untuk menyalakan virtual environment
4. Tulis command berikut untuk menyalakan website di komputer lokal
```console
python -m mkdocs serve
```
5. Buka URL yang diberikan oleh console di browser untuk melihat websitenya.

# Bagaimana cara berkontribusi ke projek ini?
1. Jika ingin menambahkan page, pilih salah satu section yang berkaitan (contoh: section `Fundamental`) lalu buat file baru di dalam folder tersebut dengan format `<nama artikel>.md`.
2. Setelah selesai menulis artikel, jangan lupa untuk menambahkan nama page tersebut di dalam bagian `nav` pada `mkdocs.yml` agar artikel tersebut dapat diakses dari website ini.
3. Ajukan *pull request* untuk di-*review* oleh anggota kami.
