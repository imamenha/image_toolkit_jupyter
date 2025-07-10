# 🖼️ Image Toolkit in Jupyter Notebook

Proyek kecil ini dibuat untuk membantu melakukan **konversi** dan **kompresi gambar** secara mudah langsung dari **Jupyter Notebook**.

Cocok untuk kamu yang ingin:
- Mengelola gambar tanpa tool berat
- Belajar image processing dasar dengan Python
- Punya solusi ringan untuk convert/compress image (JPG/PNG/WEBP)

---

## ✨ Fitur

- ✅ Upload multiple image
- 💾 Save all images
- 🔁 Convert ke JPG / PNG / WEBP
- 🗜 Compress dengan pengaturan kualitas
- 📊 Menampilkan perbandingan ukuran before & after
- 📂 Output otomatis disimpan ke folder berdasarkan waktu

---

## 🚀 Cara Menjalankan

1. **Clone repo ini**
   ```bash
   git clone https://github.com/namakamu/image-toolkit-notebook.git
   cd image-toolkit-notebook
   ```

2. **Buat virtual environment (opsional tapi disarankan)**
   ```bash
   python -m venv venv
   source venv/bin/activate      # Windows: venv\Scripts\activate
   ```

3. **Install dependensi**
   ```bash
   pip install -r requirements.txt
   ```

4. **Jalankan Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Buka file `image_toolkit.ipynb`**  
   Upload gambar, dan mulai konversi atau kompresi dari interface interaktif.

---

## 📦 Dependencies

- `ipywidgets`
- `Pillow`
- `notebook`

Semua sudah dituliskan di `requirements.txt`.

---

## 📂 Struktur Output

Gambar hasil convert/compress akan disimpan otomatis ke:

```
output_images/
├── converted_YYYYMMDD_HHMMSS/
├── compressed_YYYYMMDD_HHMMSS/
```

---

## 🛡️ .gitignore (Disarankan)

Tambahkan file `.gitignore` dengan isi seperti ini:

```
venv/
__pycache__/
.ipynb_checkpoints/
input_images/
output_images/
*.pyc
.DS_Store
```

> Tujuannya supaya file hasil upload & output tidak ikut ke-push ke repo, dan environment lokal tidak tercampur.

---

## 🤝 Kontribusi

Kalau kamu punya ide fitur tambahan seperti:
- Resize / crop
- Watermark otomatis
- Integrasi dengan Telegram bot atau Gradio UI

Silakan open issue atau pull request ya! Senang bisa berkolaborasi 🙌

---

## 📫 Kontak

Bisa DM saya via [LinkedIn](https://www.linkedin.com/in/imamnurhadianto) atau email ke: `i.nurhadianto@gmail.com`

---

## 📃 Lisensi

MIT License – silakan digunakan dan dimodifikasi untuk kebutuhanmu ✅