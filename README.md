# 🏍️ Sembelit Rush

> Selit, pecut, jangan sampai terberak 💨

Game menyelit trafik dari pandangan atas, di jalan raya Malaysia (dan lebih jauh lagi!).
Main terus dalam browser, di phone atau laptop, tanpa install apa-apa.

### ▶️ **[Main sekarang](https://izprince99.github.io/Sembelit-Rush/)**

---

## 🎮 Kawalan

| | 💻 Laptop | 📱 Phone |
|---|---|---|
| Belok | `←` `→` atau `A` `D` | Tekan kiri / kanan skrin |
| Pecut ⚡ | `↑` atau `W` | Butang **⚡ PECUT** |
| Brek 🛑 | `↓` atau `S` | Butang **🛑 BREK** |
| Bunyi | `M` | Butang 🔊 |
| Mula / main semula | `Enter` | Butang **MAIN** |
| Pilih kenderaan | `1` `2` `3` | Tekan kad kenderaan |

## 🚘 Pilih kenderaan

| | Ciri |
|---|---|
| 🏍️ **Motor** | Rose gold, enjin 4 silinder, paling mudah menyelit |
| 🏎️ **Kereta Sport** | Deruman V8 garang dengan letupan ekzos, tapi lebih lebar (lebih susah menyelit) |
| 🐎 **Kuda** | Tapak kaki berlari, meringkik bila dipacu, tiada enjin dan tiada lampu |

## 📜 Peraturan

- ❤️ **5 nyawa**: gesel tepi kenderaan tolak 1 nyawa dan skor
- 🕳️ **Lubang** dan **duduk lama atas garisan** buat kenderaan hilang kawalan (dan tolak skor)
- 💥 **Game over**: langgar **belakang** kenderaan, atau langgar **haiwan / pejalan kaki**
- 🚑 **Ambulans** datang dari belakang. Bagi laluan, kalau tak kena tolak!
- 📢 Potong depan kenderaan tiba-tiba, dan pemandunya akan hon korang
- Makin lama main, makin laju dan makin sesak

## ⭐ Skor

| Cara | Mata |
|---|---|
| Setiap meter | +1 |
| **SELIT** celah antara dua kenderaan | +100 × combo (sampai ×5) |
| Selit antara kenderaan dan haiwan | +150 × combo |
| Siap 🎯 misi | +300, +400, +500… |
| Pindah 📍 lokasi baru | +500 |
| Hancurkan halangan (🛡️ / 🔫) | +30 |
| Bagi laluan ambulans | +100 |
| Gesel tepi / lubang / hilang imbangan | −50 / −30 / −40 |

Skor terbaik disimpan dalam browser korang.

## 🎯 Misi

Misi rawak muncul semasa main, contohnya *Selit 2 kali*, *Potong 8 kenderaan*, *Tempuh 300 m tanpa gesel*,
*Jangan brek 15 saat* dan *Tukar lorong 6 kali*. Siapkan misi untuk dapat markah bonus. Setiap misi seterusnya sedikit lebih susah.

## 📍 Lokasi

Bertahan **20 saat pada 160 km/j** untuk pindah ke lokasi seterusnya. Bila pindah, laju kembali perlahan.

| Lokasi | Kenderaan | Haiwan / halangan |
|---|---|---|
| 🇲🇾 **Lebuhraya Malaysia** | Kereta, lori, bas | Buaya, gajah, monyet, lembu, babi, lubang |
| 🌴 **Jalan Ladang Tanah Merah** | Pikap, motor cross, traktor, jentolak | Lembu, kambing, ayam, babi hutan, lopak lumpur |
| 🇹🇭 **Jalan Raya Thailand** | Kereta, tuk-tuk, songthaew, bas | Gajah, anjing, ayam, pejalan kaki, pelancong |

## ✨ Ciri-ciri lain

- 🛡️ **Perisai** (rempuh apa saja) dan 🔫 **Tembak** (hancurkan halangan di depan)
- 🌧️ Cuaca berubah: cerah → hujan → **ribut petir** ⛈️ dengan kilat dan guruh
- Kenderaan lain yang langgar haiwan akan **rosak dan berhenti** di lorong itu
- 🎸 Muzik rock semasa main, dan muzik sedih kelakar 🎺 bila game over

## 🛠️ Teknikal

Seluruh game berada dalam **satu fail `index.html`**: HTML, CSS dan JavaScript (Canvas 2D).
Semua grafik dilukis dengan kod dan emoji, dan semua bunyi serta muzik dijana dengan Web Audio API,
jadi game ni tak guna sebarang gambar atau fail bunyi luar.

Untuk main secara offline, muat turun `index.html` dan buka fail itu dalam browser.
