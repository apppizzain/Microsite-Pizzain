# Microsite Pizza!n

Microsite statis untuk halaman "Pilih Layanan" Pizza!n.

## Struktur

- `index.html` - struktur halaman dan daftar tombol.
- `styles.css` - layout poster, posisi tombol, responsif, dan animasi tombol terpencet.
- `script.js` - tempat mengganti link tombol.
- `assets/` - salinan aset dengan nama yang lebih rapi.

## Mengganti Link Tombol

Buka `script.js`, lalu ubah nilai pada objek `LINKS`.

```js
const LINKS = {
  menu: "#menu-link",
  delivery: "https://wa.me/6280000000000?text=Halo%20Pizza!n%2C%20saya%20mau%20pesan%20delivery",
  takeaway: "https://wa.me/6280000000000?text=Halo%20Pizza!n%2C%20saya%20mau%20pesan%20takeaway",
  feedback: "https://wa.me/6280000000000?text=Halo%20Pizza!n%2C%20saya%20mau%20memberi%20kritik%20dan%20saran",
};
```

Ganti `6280000000000` dengan nomor WhatsApp tujuan memakai format internasional tanpa tanda `+`.

## Cara Buka

Buka file `index.html` langsung di browser.
