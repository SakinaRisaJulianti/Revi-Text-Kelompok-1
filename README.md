# Revi Text

Editor teks ringan berbasis terminal untuk Windows, dibuat menggunakan C++ dan Win32 Console API.

---

## Fitur

- Tampilan mulus tanpa flicker
- Undo / Redo (Ctrl+Z / Ctrl+Y)
- Navigasi dengan tombol panah, Home, End
- Edit multi-baris
- Status bar (baris & kolom)

---

## Cara Build

```bash
g++ -std=c++17 src/main.cpp -o revi.exe -static
```

## Cara Pakai

Jalankan file `revi.exe`, tekan **ESC** untuk keluar.

### Pintasan Keyboard

| Tombol       | Aksi               |
|--------------|--------------------|
| Tombol panah | Gerakkan kursor    |
| Home / End   | Awal / akhir baris |
| Enter        | Baris baru         |
| Backspace    | Hapus karakter     |
| Ctrl + Z     | Undo               |
| Ctrl + Y     | Redo               |
| ESC          | Keluar             |
