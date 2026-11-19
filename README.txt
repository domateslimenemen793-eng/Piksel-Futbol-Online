PİKSEL FUTBOL — ÇEVRİMİÇİ SUNUCU
1) Node 18+ kurulu bir sunucuda bu klasörü çalıştır:   node server.js
   (PORT=8080 varsayılan; kayıtlar DATA_DIR=./data içinde kalıcıdır)
2) Tarayıcıdan http://SUNUCU:8080 adresini aç. Herkes aynı adresten girer; hesaplar, klanlar, odalar ve maçlar ortaktır.
3) İnternete açmak için Render / Railway / Fly.io / VPS gibi Node çalıştıran bir servise yükle (başlatma komutu: node server.js).
   HTTPS gerekiyorsa servisin kendi sertifikası yeterlidir; istemci otomatik wss:// kullanır.
   Kalıcı disk bağla (DATA_DIR) yoksa yeniden başlatmada hesaplar silinir.
4) Sağlık/istatistik: /health
Ana Admin kodu ve Mavi hediye kodu mağazadaki Hediye Kodu kutusundan kullanılır.
