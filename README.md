# Tutorial Testnet Namada Ceremony

<p style="font-size:14px" align="right">
<a href="https://t.me/bangpateng_airdrop" target="_blank">Join Telegram Bang Pateng<img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
</p>

<p align="center">
  <img height="150" width="200" src="https://user-images.githubusercontent.com/38981255/202869174-007d02a5-8b51-450d-9fcd-406c94e817a5.JPG">
</p>

## Referensi

[Dokumen resmi](https://github.com/anoma/namada-trusted-setup)

[Dasboard Website Testnet](https://ceremony.namada.net/)

# Install Via Source Code

### Pertama, Anda perlu menginstal beberapa dependensi. Pada sistem berbasis debian Anda dapat menggunakan:
```
sudo apt update && sudo apt install -y curl git build-essential pkg-config libssl-dev
```
### Setelah itu, Anda harus menginstal Rust dengan memasukkan perintah berikut:
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```
source "$HOME/.cargo/env"
```
### Jika Anda sudah menginstal Rust, pastikan itu adalah versi terbaru:
```
rustup update
```
### Setelah semuanya terinstal, tiru repositori Namada Trusted Setup Ceremony GitHub dan ubah direktori menjadi namada-trusted-setup:
```
git clone https://github.com/anoma/namada-trusted-setup.git
cd namada-trusted-setup && git checkout v1.1.0
```
### Membangun biner:
```
cargo build --release --bin namada-ts --features cli
```
### Pindahkan biner $PATH (mungkin memerlukan sudo):
```
mv target/release/namada-ts /usr/local/bin 
```
### Mulai kontribusi Anda:
```
namada-ts contribute default https://contribute.namada.net 'ISI-TOKEN-YANG-KALIAN-DAPAT-DI-EMAIL'
```
Isi dan Masukan Uniqe Code Kalian Tanda Titik jangan di Hapus Tetap di Gunakan

*Note : Masih Ada Lanjutan Ane Kepilih Masuk di Ceremony #2 Mulai Besok Jam Your cohort round is 2 and will start at 2022-11-20 09:00:00 UTC and finish at 2022-11-21 09:00:00 UTC*
