Cara Menghubungkan Domain ke GitHub Pages:
Di GitHub:

Buka repositori Anda -> Settings -> Pages.

Di bagian Custom domain, masukkan yusuf-store25.web.id.

Klik Save. GitHub akan membuat file bernama CNAME di repositori Anda secara otomatis.

Di Panel Domain (Registrar):

Masuk ke akun tempat Anda membeli domain.

Cari pengaturan DNS Management.

Tambahkan CNAME Record: Host: www, Value: username-anda.github.io.

Tambahkan A Records (opsional tapi disarankan) untuk IP GitHub:

185.199.108.153

185.199.109.153

185.199.110.153

185.199.111.153

Tunggu Propagasi: Biasanya butuh waktu 1-24 jam hingga domain aktif sepenuhnya. Jangan lupa centang Enforce HTTPS di pengaturan GitHub Pages setelah domain terhubung.
