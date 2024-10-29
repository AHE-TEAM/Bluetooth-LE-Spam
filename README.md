# Bluetooth LE Spam

Bu proje, Android akıllı telefonların yerleşik Bluetooth Düşük Enerji (BLE) işlevselliğini kullanarak hayali Bluetooth cihaz reklamları oluşturmayı amaçlıyor. Örneğin, Flipper Zero gibi cihazlarda bilinen bir yöntemdir. Diğer benzer uygulamalar mevcut olsa da, bu uygulamanın amacı kullanıcı dostu bir deneyim sunmaktır.

## Gereksinimler

- Android 8.0 (API seviyesi 26) veya üstü
- Bu uygulama IOS veya PC'de çalıştırılamaz (emülatör/VM ile bile)

## İşlevsellik

### Google Fast Pair (Android Cihazlar)
Bu uygulama, Google Fast Pair hizmetini taklit eden BLE reklamlarını taklit edebilir ve hedef cihaza gereksiz bildirimlerin gelmesine neden olur.

### Microsoft Swift Pair (Windows Cihazlar)
Bu uygulama, Microsoft Swift Pair hizmetini destekleyen cihazları taklit eden BLE reklamlarını gönderebilir. Eğer Swift Pair bildirimleri açıksa, yakınlardaki bir Windows 10 veya daha yeni bir cihaz sürekli bildirimler alır.

### Kolay Kurulum (Samsung)
Uygulama, özellikle Samsung cihazlarında açılır pencereleri tetikleyen BLE reklam setleri oluşturabilir.

### Apple Cihaz Bildirimleri (Apple cihazlar)
Bu uygulama, Bluetooth Düşük Enerji yoluyla çeşitli Apple cihazlarını taklit edebilir ve iOS cihazlarında istenmeyen açılır bildirimlerin gelmesine neden olabilir.

### Apple iOS 17 Çökmesi (Apple) YARI-ONARILDI
Gönderilen BLE paketinde bazı değişiklikler yaparak çeşitli iOS 17 cihazlarında yeniden başlatma tetiklenebilir. Bu, hedef iPhone’un geçici olarak donmasına ve ardından otomatik olarak yeniden başlatılmasına neden olur.

### Lovespouse (Yetişkin Oyuncakları)
Bu özellik, Lovespouse uygulamasını destekleyen çeşitli yetişkin oyuncaklarını etkinleştirip devre dışı bırakabilir. Daha fazla bilgiye [buradan](https://mandomat.github.io/2023-11-13-denial-of-pleasure/) ulaşabilirsiniz.

### Her Şeyi Bir Arada (Hepsi aynı anda)
Bu işlevsellik, uygulamanın diğer tüm özelliklerinden rastgele BLE reklam paketleri oluşturur. Bu, çevredeki en fazla sayıda cihazı etkiler.

## Yükleme

Proje deposunu klonlayıp Android Studio'da açarak uygulamayı kurabilirsiniz ya da [Sürüm Bölümünden](https://github.com/simondankelmann/Bluetooth-LE-Spam/releases) indirilebilir APK dosyalarını kullanabilirsiniz.

## Görseller

![Başlangıç ekranı](https://raw.githubusercontent.com/AHE-TEAM/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/Screenshot_20241029_145046_Bluetooth%20LE%20Spam.png)
![Reklam ekranı](https://raw.githubusercontent.com/AHE-TEAM/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/Screenshot_20241029_145109_Bluetooth%20LE%20Spam.png)
![Spam tespit ekranı 1](https://raw.githubusercontent.com/simondankelmann/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/detector1.jpeg)
![Spam tespit ekranı 2](https://raw.githubusercontent.com/simondankelmann/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/detector2.jpeg)
![Ayarlar ekranı](https://raw.githubusercontent.com/AHE-TEAM/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/Screenshot_20241029_145430_Bluetooth%20LE%20Spam.png)

## Sorumluluk Reddi

Bu depo, Bluetooth Düşük Enerji (BLE) protokolü hakkında eğitim ve araştırma amaçlıdır. Kullanıcılar, yasaların gerektirdiği şekilde tüm yasal düzenlemelere uymakla sorumludur.

Katkıda bulunmak isterseniz, projenin hedeflerine uygun olmasına dikkat ediniz. Daha fazla bilgi için [Discord sunucumuza](https://discord.gg/x4e4Gma585) katılabilirsiniz.
