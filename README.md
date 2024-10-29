  Bluetooth LE Spam /\* Genel sayfa stili \*/ body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f9; color: #333; } h1 { text-align: center; margin-top: 20px; } /\* Dil seçme menüsü stili \*/ .language-selector { position: relative; display: inline-block; text-align: center; margin: 10px; } .language-selector button { background-color: #008cba; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; } .language-selector-content { display: none; position: absolute; background-color: #f4f4f9; min-width: 160px; box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2); z-index: 1; border-radius: 5px; } .language-selector-content a { color: #333; padding: 10px 20px; text-decoration: none; display: block; border-bottom: 1px solid #ddd; } .language-selector-content a:hover { background-color: #ddd; } /\* İçerik stili \*/ .content { max-width: 800px; margin: 20px auto; padding: 20px; background-color: white; border-radius: 5px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); } img { max-width: 100%; height: auto; margin: 10px 0; } function setLanguage(lang) { const elements = document.querySelectorAll('\[data-lang\]'); elements.forEach(el => { el.style.display = el.getAttribute('data-lang') === lang ? 'block' : 'none'; }); } function toggleLanguageMenu() { const menu = document.getElementById("languageMenu"); menu.style.display = menu.style.display === "block" ? "none" : "block"; } window.onclick = function(event) { const menu = document.getElementById("languageMenu"); if (!event.target.matches('.lang-button')) { if (menu.style.display === "block") { menu.style.display = "none"; } } }

Bluetooth LE Spam
=================

Language

[Türkçe](#) [Русский](#)

Bu proje, Android akıllı telefonların yerleşik Bluetooth Düşük Enerji (BLE) işlevselliğini kullanarak hayali Bluetooth cihaz reklamları oluşturmayı amaçlıyor. Örneğin, Flipper Zero gibi cihazlarda bilinen bir yöntemdir. Diğer benzer uygulamalar mevcut olsa da, bu uygulamanın amacı kullanıcı dostu bir deneyim sunmaktır.

Gereksinimler
-------------

*   Android 8.0 (API seviyesi 26) veya üstü
*   Bu uygulama IOS veya PC'de çalıştırılamaz (emülatör/VM ile bile)

İşlevsellik
-----------

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

Yükleme
-------

Proje deposunu klonlayıp Android Studio'da açarak uygulamayı kurabilirsiniz ya da [Sürüm Bölümünden](https://github.com/simondankelmann/Bluetooth-LE-Spam/releases) indirilebilir APK dosyalarını kullanabilirsiniz.

Görseller
---------

*   ![Başlangıç ekranı](https://raw.githubusercontent.com/AHE-TEAM/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/Screenshot_20241029_145046_Bluetooth%20LE%20Spam.png)
*   ![Reklam ekranı](https://raw.githubusercontent.com/AHE-TEAM/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/Screenshot_20241029_145109_Bluetooth%20LE%20Spam.png)
*   ![Spam tespit ekranı 1](https://raw.githubusercontent.com/simondankelmann/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/detector1.jpeg)
*   ![Spam tespit ekranı 2](https://raw.githubusercontent.com/simondankelmann/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/detector2.jpeg)
*   ![Ayarlar ekranı](https://raw.githubusercontent.com/AHE-TEAM/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/Screenshot_20241029_145430_Bluetooth%20LE%20Spam.png)

Sorumluluk Reddi
----------------

Bu depo, Bluetooth Düşük Enerji (BLE) protokolü hakkında eğitim ve araştırma amaçlıdır. Kullanıcılar, yasaların gerektirdiği şekilde tüm yasal düzenlemelere uymakla sorumludur.

Katkıda bulunmak isterseniz, projenin hedeflerine uygun olmasına dikkat ediniz. Daha fazla bilgi için [Discord sunucumuza](https://discord.gg/x4e4Gma585) katılabilirsiniz.

Этот проект направлен на создание фиктивных рекламных объявлений для Bluetooth-устройств, используя встроенные функции Bluetooth Low Energy (BLE) на Android-смартфонах. Например, метод, известный на таких устройствах, как Flipper Zero. Хотя существуют другие аналогичные приложения, цель этого приложения — предложить удобный интерфейс.

Требования
----------

*   Android 8.0 (API уровень 26) или выше
*   Это приложение не может работать на iOS или ПК (даже с эмулятором/виртуальной машиной)

Функциональность
----------------

### Google Fast Pair (Android устройства)

Это приложение может имитировать рекламу BLE, имитирующую службу Google Fast Pair, вызывая на целевом устройстве ненужные уведомления.

### Microsoft Swift Pair (устройства Windows)

Это приложение может отправлять рекламу BLE, имитируя устройства с поддержкой Microsoft Swift Pair. Если уведомления Swift Pair включены, близлежащие устройства с Windows 10 или новее будут получать постоянные уведомления.

### Легкая настройка (Samsung)

Приложение может создавать наборы рекламы BLE, вызывающие всплывающие окна на устройствах Samsung.

### Уведомления для устройств Apple (Apple устройства)

Это приложение может имитировать различные устройства Apple с помощью Bluetooth Low Energy, вызывая нежелательные всплывающие уведомления на iOS-устройствах.

### Краш iOS 17 (Apple) ЧАСТИЧНО ИСПРАВЛЕН

Внося некоторые изменения в отправляемый пакет BLE, можно вызвать перезагрузку на некоторых устройствах iOS 17, заставляя целевой iPhone временно зависать, а затем автоматически перезагружаться.

### Lovespouse (взрослые игрушки)

Эта функция позволяет включать и отключать различные взрослые игрушки, поддерживающие приложение Lovespouse. Больше информации можно найти [здесь](https://mandomat.github.io/2023-11-13-denial-of-pleasure/).

### Все вместе (все функции одновременно)

Эта функция создает случайные рекламные пакеты BLE с использованием всех функций приложения, чтобы затронуть максимальное количество устройств вокруг.

Установка
---------

Вы можете клонировать репозиторий проекта и открыть приложение в Android Studio, или использовать загружаемые APK-файлы в [Разделе выпусков](https://github.com/simondankelmann/Bluetooth-LE-Spam/releases).

Изображения
-----------

*   ![Başlangıç ekranı](https://raw.githubusercontent.com/AHE-TEAM/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/Screenshot_20241029_145046_Bluetooth%20LE%20Spam.png)
*   ![Reklam ekranı](https://raw.githubusercontent.com/AHE-TEAM/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/Screenshot_20241029_145109_Bluetooth%20LE%20Spam.png)
*   ![Spam tespit ekranı 1](https://raw.githubusercontent.com/simondankelmann/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/detector1.jpeg)
*   ![Spam tespit ekranı 2](https://raw.githubusercontent.com/simondankelmann/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/detector2.jpeg)
*   ![Ayarlar ekranı](https://raw.githubusercontent.com/AHE-TEAM/Bluetooth-LE-Spam/refs/heads/main/Assets/Screenshots/1.0.8/Screenshot_20241029_145430_Bluetooth%20LE%20Spam.png)

Отказ от ответственности
------------------------

Этот репозиторий предназначен для обучения и исследования протокола Bluetooth Low Energy (BLE). Пользователи несут ответственность за соблюдение всех применимых законодательных норм.

Если вы хотите внести свой вклад, убедитесь, что он соответствует целям проекта. Для получения дополнительной информации присоединяйтесь к нашему [серверу Discord](https://discord.gg/x4e4Gma585).