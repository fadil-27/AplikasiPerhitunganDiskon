# Aplikasi Perhitungan Diskon  
Tugas 3 - Muhammad Fadilah (2210010500)

## Deskripsi Program  
Aplikasi ini adalah program desktop berbasis Java Swing untuk menghitung diskon.  
Pengguna dapat:  
- Memasukkan harga asli barang.  
- Memilih persentase diskon menggunakan **JComboBox** atau **JSlider**.  
- Memasukkan kode kupon untuk diskon tambahan.  
- Menampilkan hasil perhitungan berupa harga akhir dan penghematan.  
- Melihat riwayat perhitungan diskon sebelumnya.  

---

## Fitur Utama  
1. **Input Harga Asli**: Memasukkan harga asli barang.  
2. **Persentase Diskon**:  
   - Pilih melalui **JComboBox**.  
   - Gunakan **JSlider** sebagai alternatif.  
3. **Kode Kupon Diskon**: Tambahkan diskon tambahan dengan kode kupon.  
4. **Hasil Perhitungan**: Tampilkan harga akhir dan jumlah penghematan.  
5. **Riwayat Perhitungan**: Riwayat perhitungan ditampilkan di `JTextArea`.  

---

## Komponen GUI  
- **JFrame**: Membuat jendela utama aplikasi.  
- **JPanel**: Mengatur tata letak komponen GUI.  
- **JLabel**: Memberikan keterangan pada setiap input/output.  
- **JTextField**: Input harga asli dan output hasil perhitungan.  
- **JComboBox**: Memilih persentase diskon.  
- **JSlider**: Alternatif untuk memilih persentase diskon.  
- **JButton**: Tombol untuk melakukan perhitungan.  
- **JTextArea**: Menampilkan riwayat perhitungan diskon.  

---

## Cara Menjalankan Program  
1. **Persiapan**:  
   - Jalankan aplikasi menggunakan IDE (seperti IntelliJ IDEA atau NetBeans) atau file `.jar`.  
2. **Langkah Penggunaan**:  
   - Masukkan harga asli pada kolom **"Harga Asli"**.  
   - Pilih persentase diskon dari **JComboBox** atau gunakan **JSlider**.  
   - (Opsional) Masukkan kode kupon diskon.  
   - Tekan tombol **"Hitung"** untuk mendapatkan hasil.  
   - Lihat hasil di kolom **"Harga Akhir"** dan **"Penghematan"**.  
   - Riwayat perhitungan akan tercatat di `JTextArea`.  

---

## Format Perhitungan  
1. **Diskon**:  
   \[
   \text{Hemat} = \text{Harga Asli} \times \left(\frac{\text{Persentase Diskon}}{100}\right)
   \]  
   \[
   \text{Harga Akhir} = \text{Harga Asli} - \text{Hemat}
   \]  

2. **Kode Kupon Diskon**:  
   - Kode kupon **DISKON10** menambah diskon sebesar 10%.  
   - Diskon kupon diterapkan ke total harga.  

---

## Contoh Penggunaan  
1. Harga Asli: `Rp 100,000`.  
2. Persentase Diskon: `20%`.  
3. Harga Akhir: `Rp 80,000`.  
4. Penghematan: `Rp 20,000`.  

Dengan kode kupon **DISKON10**:  
- Diskon tambahan: `Rp 10,000`.  
- Harga Akhir: `Rp 70,000`.  
- Total Penghematan: `Rp 30,000`.  

---

## Kode Kupon yang Tersedia  
- **DISKON10**: Menambah diskon 10% dari harga asli.  

## Screenshot
![AplikasiPerhitunganDiskon](https://github.com/user-attachments/assets/7930b964-686a-48ad-9f04-c3c2aac8c6d9)


