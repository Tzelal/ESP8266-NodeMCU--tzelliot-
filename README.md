### ESP8266-tzelliot-
**ESP8266 Başlarken/Kurulum (...NodeMCU...)**

![](GitHUB%20Resim/NODE-MCU.jpg)

Merhabalar kolay gelsin bu sayfada ilk kez ESP8266 modülü ile karşılaşmış ne yapması gerektiğini bilmeyenlere yardımcı olmaya çalışıcam.
Lafı fazla uzatmak istemiyorum son birkaç birşey ekleyip ESP8266 modülüne geçicem özellikle NodeMCU modülüne.Öncelikle burdaki amacım birşeyler yazarken öğrenmek ve yardımcı olmak o yüzden geri bildirimlerinizi bekliyorum şimdiden teşekkürler kolay gelsin.



**..............İLK ADIM..................**



Arduino uygulamasının güncel olduğuna dikkat et.Güncel olmayınca yeni uygulamalarda/projelerde hatalarla karşılaşabilirsin.
Arduno'yu (uygulamayı) daha önce hiç yüklemediysen [buraya](https://www.arduino.cc/en/Main/Software) tıklayarak uygulamayı indirebileceğin siteye ulaşabilirsin.

Arduino uygulamasını indirirken aşağıdaki resimde benim de yaptığım gibi Program Files değil de Users klasörüne indirmeni tavsiye ederim.Böylelikle ilerde yapacağın farklı projelerde izin konusunda program sana sıkıntı çıkarmaz.



![Arduino Setup](https://user-images.githubusercontent.com/36787074/54087997-13d79280-436a-11e9-94a0-47ca9f5296cf.PNG)



**.............İKİNCİ ADIM...............**



Şimdi...Arduino programını çalıştırınca yukarıda Files var orada Prefereneces'e tıklıyoruz.Aynen aşağıdaki olduğu gibi.


![Arduino Preferences](https://user-images.githubusercontent.com/36787074/54088602-c6125880-4370-11e9-8a86-674c3e73e82c.PNG)

Önümüze çıkan Preferences penceresinde aşağıda "Additional Boards Manager URLs" yazan yere aşağıda yazacağım URL'yi kopyalayıp yapıştır.

>http://arduino.esp8266.com/stable/package_esp8266com_index.json


![Arduino inside Preferences](https://user-images.githubusercontent.com/36787074/54088728-08886500-4372-11e9-918a-be1fa34461f2.PNG)


Yapman gereken işlem hemen üstteki resimde olduğu gibi.Üstteki URL'yi kopyala yapıştır yaptıktan sonra OK tıklaman yeterli.



**............ÜÇÜNCÜ ADIM..............**



Bu adımla birlikte Arduino uygulaması ESP8266 (NODEMCU) modülünü artık tanımaya başlıycak.Özetle modüle artık kod yükleyip çalıştırabilicez.Onun için ise önce aşağıdaki resimde olduğu gibi uygulamanın "Boards Manager" kısmına gitmemiz gerek.

![Boards Manager](https://user-images.githubusercontent.com/36787074/54089136-d4fc0980-4376-11e9-90c2-c309cdcdec8f.PNG)



Boards Manger penceresi açıldığında zaten önüne direkt çıkması gerekiyor.Çıkmaması durumunda yukarıdaki arama yerinden aşağıdaki resimde olan dosyayı arayıp indirmen gereken dosyaya ulaşabilirsin.Bu aşamanın da resmini aşağıya ekliyorum.


![ESP8266 Community](https://user-images.githubusercontent.com/36787074/54089038-8c901c00-4375-11e9-96ae-c57e2f03acce.png)

Bu işlemi de yaptıktan sonra esp8266'nın yüklenmesini beklemek kalıyor (biraz uzun sürüyor).Yükleme islemi bittikten sonra Boards'da ESP8266 ile ilgili tonlarca modül çıkıyor.Projen için kullanacağını seçebilirsin fakat ben burda genel olarak NodeMCU modülünü baz alarak anlattığım için onun nerede olduğunu resim olarak paylaşacağım.


![BMANAGER](https://user-images.githubusercontent.com/36787074/54089144-eb09ca00-4376-11e9-928c-75438869a217.PNG)

Dikkatini çekmiş olabilir.Orada iki tane NodeMCU seçeneği var.Genel olarak piyasada satılan 1.versiyon olduğu için onu seçtim.Elindeki versiyona göre diğerini de seçebilirsin.

İngilizce kaynak : [esp8266/Arduino](https://github.com/esp8266/Arduino/issues)

>### Okuduğun için teşekkür ediyorum.Umarım yardımcı olabilmişimdir.Her türlü geri bildirime açığım umarım katkılarını esirgemezsin.Projelerinde Kolay Gelsim :D ......

>**03/10/2019**



