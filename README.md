# Script instalasi azuracast (panel kontrol radio streaming)
Repositori ini berisi script instalasi azuracast, beserta cara instalasi azuracast untuk linux server.
Ini hanya untuk mempermudah saya dalam proses penginstalan azuracast, karena link download script yang asli nya sedikit panjang dan ribet untuk di hafal. Maka dari itu saya push ke GitHub saya ini.
## Instalasi
Untuk anda yang ingin menginstall azura cast di varian linux server, bisa mengikuti langkah-langkah berikut:
1. Arahkan ke direktori /var pada vps linux anda dengan perintah
```
cd /var
```
2. Lalu clone repositori ini dengan perintah
```
git clone https://github.com/fauzan-january/azuracast
```
3. Pindah ke direktori azuracast dengan perintah
```
cd azuracast
```
4. Berikan izin eksekusi file script dengan perintah
```
chmod +x docker.sh
```
5. Jalankan instalasi dengan perintah
```
./docker.sh install
```
6. Ikuti panduan instalasi yang muncul di layar hingga selesai
7. Terkait bahasa, port dan lainnya, biarkan saja default dengan langsung menekan enter
8. Setelah proses instalasi melalui terminal selesai, untuk setup selanjutnya melalui web interface (antarmuka web). Silahkan ikuti aja proses beserta panduannya.
Selesai
