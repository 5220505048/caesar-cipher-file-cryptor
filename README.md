# 🔐 Caesar Cipher File Cryptor

Bu proje, C dili kullanılarak geliştirilmiş, metin dosyaları üzerinde **Sezar Şifrelemesi (Caesar Cipher)** yöntemini kullanarak şifre çözme (decryption) işlemi gerçekleştiren bir araçtır.

## 🌟 Öne Çıkan Özellikler
- **Dosya Tabanlı İşlem:** Doğrudan `.txt` dosyalarından veri okur.
- **Dinamik Kaydırma:** Kullanıcının belirlediği anahtar (shift) miktarına göre metni çözer.
- **Karakter Koruma:** Büyük/küçük harf duyarlılığını korur ve alfabetik olmayan karakterleri (boşluk, nokta vb.) bozmaz.

## 📸 Uygulama Görüntüsü
![Uygulama Ekranı](image_f1b366.png)
*Girdi olarak verilen şifreli metnin, belirlenen anahtar ile çözülmüş hali.*

## 🛠 Teknik Detaylar
- **Dil:** C
- **Kütüphaneler:** `stdio.h`, `ctype.h`, `string.h`
- **Mantık:** $(x - n + 26) \pmod{26}$ formülü kullanılarak karakter kaydırma işlemi gerçekleştirilir.

## 💻 Nasıl Çalıştırılır?
1. `main.c` dosyasını derleyin: `gcc main.c -o cryptor`
2. Bir `input.txt` dosyası oluşturun ve içine şifreli metninizi yazın.
3. Programı çalıştırın: `./cryptor`

![image](https://github.com/5220505048/Algoritma-kisa-sinav-1.2/assets/127949378/f2a39bdf-622a-4695-94ca-36ca9cdc9b7e)
