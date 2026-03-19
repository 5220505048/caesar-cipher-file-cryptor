# 🔐 Caesar Cipher File Cryptor

Bu proje, C dili kullanılarak geliştirilmiş, metin dosyaları üzerinde **Sezar Şifrelemesi (Caesar Cipher)** yöntemini kullanarak şifre çözme (decryption) işlemi gerçekleştiren bir araçtır.

## 🌟 Öne Çıkan Özellikler
- **Dosya Tabanlı İşlem:** Doğrudan `.txt` dosyalarından veri okur.
- **Dinamik Kaydırma:** Kullanıcının belirlediği anahtar (shift) miktarına göre metni çözer.
- **Karakter Koruma:** Büyük/küçük harf duyarlılığını korur ve alfabetik olmayan karakterleri (boşluk, nokta vb.) bozmaz.

## 📸 Uygulama Ekran Görüntüsü

![Caesar Cipher Demo](https://github.com/user-attachments/assets/58491735-5f03-4ff5-acd1-c6bb62be4592)

*Programın bir .txt dosyasını (örnekte `input.txt`) başarıyla okuduğu, kullanıcıdan kaydırma miktarını (`shift value`) aldığı ve şifreli mesajı (Caesar Cipher algoritması kullanarak) saniyeler içinde çözdüğü (`decrypted`) an.*

## 🛠 Teknik Detaylar
- **Dil:** C
- **Kütüphaneler:** `stdio.h`, `ctype.h`, `string.h`
- **Mantık:** $(x - n + 26) \pmod{26}$ formülü kullanılarak karakter kaydırma işlemi gerçekleştirilir.

## 💻 Nasıl Çalıştırılır?
1. `main.c` dosyasını derleyin: `gcc main.c -o cryptor`
2. Bir `input.txt` dosyası oluşturun ve içine şifreli metninizi yazın.
3. Programı çalıştırın: `./cryptor`
![image](https://github.com/user-attachments/assets/58491735-5f03-4ff5-acd1-c6bb62be4592)
