# 🥟 Demo Sistem Pemesanan Dimsum (E-Menu & Delivery Prototype)

Prototype ini dibuat untuk mensimulasikan alur pemesanan makanan take away multi-cabang dengan sistem pembayaran QRIS otomatis dan notifikasi WhatsApp tanpa biaya bulanan (Rp 0).

## 🚀 Cara Menjalankan Demo:
1. Anda cukup membuka file [index.html](file:///C:/Users/ACER/.gemini/antigravity/scratch/dimsum-order-demo/index.html) langsung di browser Anda (Google Chrome, Edge, Safari, dll).
2. Atau jalankan perintah berikut di terminal:
   ```powershell
   Start-Process "C:\Users\ACER\.gemini\antigravity\scratch\dimsum-order-demo\index.html"
   ```

## 🛠️ Fitur yang Disimulasikan:
1. **Multi-Outlet Switcher:** Pemilihan cabang outlet tujuan (karena klien belum dine-in dan punya beberapa cabang).
2. **Katalog & Keranjang Belanja:** Pemilihan varian dimsum, pengaturan porsi, dan subtotal dinamis.
3. **Pilihan Metode Pemenuhan:**
   - **Delivery (Ojol):** Simulasi pemilihan alamat rumah dengan penghitungan jarak dan ongkir otomatis.
   - **Ambil Sendiri (Self-Pickup):** Pemilihan jadwal tanggal dan jam pengambilan makanan.
4. **Checkout & QRIS Dinamis:** Rincian invoice dan simulasi pembayaran lunas instan.
5. **Notifikasi WhatsApp 0 Biaya (`wa.me`):** Tiket order rapi yang siap dikirim langsung ke WhatsApp kasir tanpa biaya vendor/API berbayar.
6. **Layar Kasir / Outlet (Kitchen View):** Tab khusus untuk melihat simulasi tablet kasir toko saat ada pesanan baru masuk secara real-time.
