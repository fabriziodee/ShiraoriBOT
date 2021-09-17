<p align="center">
	<img src="https://media.giphy.com/media/Xr2km20NNBNqSN6iwu/giphy.gif" width="200" style="margin-left: auto;margin-right: auto;display: block;">
</p>
<h1 align="center">SHIRAORI BOT</h1>

# notes!!

```
* sebelum kalian clone hapus dulu file [session.data.json](https://github.com/Hidayatilman/ShiraoriBOT/blob/main/session.data.json)
* before you clone first delete the file [session.data.json](https://github.com/Hidayatilman/ShiraoriBOT/blob/main/session.data.json)
```

## error fix it yourself 

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Hidayatilman/ShiraoriBOT)

[![Grup WhatsApp](https://img.shields.io/badge/GroupWhatsapp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/GVwpKf83s42D1CnIfDW19G)

[![My Bot](https://img.shields.io/badge/MyBot-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](http://wa.me/48459069720?text=.menu)

## UNTUK PENGGUNA WINDOWS/VPS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/Hidayatilman/ShiraoriBOT
npm install
npm update
npm index
```

---------

## UNTUK PENGGUNA TERMUX
```bash
git clone https://github.com/Hidayatilman/ShiraoriBOT --branch termux
cd ShiraoriBOT
npm i
npm update
node .
```

## UNTUK PENGGUNA HEROKU

### Instal Buildpack
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/DuckyTeam/heroku-buildpack-imagemagick.git

---------

## Arguments `node . [--options] [<session name>]`

#### Contoh: `node . --self --restrict --autoread`

### `--self`

Aktifkan mode self (Mengabaikan yang lain)

### `--prefix <prefixes>`

* `prefixes` dipisahkan oleh masing-masing karakter
Setel awalan

### `--server`

Digunakan untuk [heroku](https://heroku.com/) atau pindai melalui situs web

### `--db <json-server-url>`

Gunakan db eksternal alih-alih db lokal, 
Contoh Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

Server harus memiliki spesifikasi seperti ini

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--restrict`

Mengaktifkan plugin terbatas (yang dapat menyebabkan nomor Anda **diblokir** jika digunakan terlalu sering)

* Administrasi Grup `add, kick, promote, demote`

### `--img`

Aktifkan pemeriksa gambar melalui terminal

### `--autoread`

Jika diaktifkan, semua pesan masuk akan ditandai sebagai telah dibaca

### `--nyimak`

Tidak ada bot, cukup cetak pesan yang diterima dan tambahkan pengguna ke database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

 [![Nurutomo](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) | [![Ariffb](https://github.com/ariffb25.png?size=100)](https://github.com/ariffb25)
----|----
[Nurutomo](https://github.com/Nurutomo) | [Ariffb](https://github.com/ariffb25)
 Penulis / Pencipta | Penulis ulang
 
## Thanks To

* [`Nurutomo`](https://github.com/Nurutomo) 
* [`ariffb25`](https://github.com/ariffb25) 
* [`ilman`](https://github.com/Hidayatilman) 
* [`botstylee`](https://github.com/botstylee)

### Donated

[`Saweria`](https://saweria.co/manilman)
