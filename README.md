# UML-Handbook-

📩
CRM.V2
CRM Projesi(Customer Relationship Management-Müşteri İlişkileri Yönetimi)
Genel
Gunumuzde bir cok kurulus verilerini yonetme ve saklama gibi opsiyonlari kismende olsa ucretsiz destekledigi icin Google drive ve bilesenlerini kullanmaktadir. Cesitli organizasyonlar IT alaninda calismak isteyen multeci kokenli kisiler icin mentor gorusmesi ve istenilen sartlari saglayanlar icin projelendirme ve mulakat asamalari dahil olmak uzere bir dizi islem yapmakta ve bu islemleri google drive uzerinde gerceklestirmektedir. Adaylarin takip edilmesi icin drive uzerinde surekli oturumun acik olmasi , excel metinlerin karisikligi ,istenilen verilere kisa yoldan ulasabilme vs gibi zorluklar nedeni ile isleri daha kolay hale getirebilecek kullanici dostu bir uygulama tasarlamak amaciyla asagidaki proje tasarlanmistir.

Kullanici Arayuzu Detaylari
Giris Penceresi

1-Kullanici Adi ve Sifre

google drive ana gmail-hesabi kullanicisi tarafindan kaydedilmis kullanici adi-sifre sahibi kisilerin erisimine izin verilmeli . Bu bilgiler Kullanicilar dosyasında yer almaktadır. Eğer kullanıcının giriş yetkisi Admin’se Tercihler - Admin menüsüne yönlendirmeli, eğer giriş yetkisi User’sa Tercihler menüsüne yönlendirmeli.

Uygulamaya özelleştirilmiş bir giriş sayfası oluşturulmalı ve bu sayfa asagidaki ozellikleri içermelidir.

Kullanici adi ve sifre icin iki ayrı input ögesi.

Bu iki bilgiye reaksiyon verecek ve sonraki bir giris butonu.

Butonun tiklandiginda basarili olup olmadigini bildirecek bir uyari yazisi.

Istege gore uygulamayi kapatacak baska bir buton ekleyip pencere goruntusu kaldırılabilir.

Tutarli ardalan renkleri, kutu kenar sekilleri, buton ozellikleri (hover, pressed, yuvarlak kenar), yazilar icin farkli fontlar ve renkler kullanarak ozellesmis ve giris penceresi oluşturulmalıdır.

Ipucu: Once bir frame yerlestirip ogeleri ustune yerlestirerek, hem frame i hem de uzerine yerlestirdiginiz ogeleri layout,spacer kullanarak dinamik boyut olusturabilirsiniz.

Tercihler

A-)Tercihler Admin

1- Basvurular

Basvurular butonu admini ilk basvuru penceresine yönlendirmeli

2- Mentor gorusmesi

Mentor gorusmesi butonu admini mentor penceresine yonlendirmeli

3- Mulakatlar

Mulakatlar butonu admini mulakatlar penceresine yonlendirmeli

4- Admin Menü

Admin butonu admini Admin penceresine yönlendirmeli.

B-)Tercihler

1- Basvurular

basvurular butonu kullaniciyi ilk basvuru penceresine yonlendirmeli

2- Mentor gorusmesi

mentor gorusmesi butonu kullaniciyi mentor penceresine yonlendirmeli

3- Mulakatlar

mulakatlar butonu kullaniciyi mulakatlar penceresine yonlendirmeli

Basvurular

1-Ara

text satirina girilen karakterler ile isim soyisimler icinde arama yapabilen bir buton islevi kazandirilmali

(orn: 'As' girisinde drive da kayitli as ile baslayan tum isimleri getirebilmeli)

2-Tum Basvurular

Tum basvurular butonu tiklandiginda driveda bulunan başvurular dosyasındaki kayitli bulunan tum basvurular ekrana getirilmeli

3-Mentor Gorusmesi Tanimlananlar (Basvurular Dosyasındaki ilgili sutun)

Mentor gorusmesi tanimlananlar butonu tiklandiginda, basvuru yaptiktan sonra kendisine mentor gorusmesi tanimlanmis kisiler ekrana getirilmeli

4-Mentor Gorusmesi Tanimlanmayanlar

Mentor gorusmesi tanimlanmayanlar butonu tiklandiginda, basvuru yaptiktan sonra kendisine halen mentor atanmamis olan kisiler ekrana getirilmeli

5- Basvurular Mükerrer Kayıt Butonu

Mükerrer Kayıt Butonu tıklandığında driveda bulunan Basvurular dosyasındaki aynı isim ve mail adresiyle kayıt olan kişiler (sadece tekrar eden adaylar) ekrana getirilmeli.

6- Önceki VIT Kontrol Butonu

Onceki VIT butonu tıklandığında Drive’da kayıtlı olan VIT1, VIT2 ve Başvurular Dosyalarının birinde veya ikisinde ortak olan tüm adayları ekrana getirmeli. (Buradaki amaç da bir adayın birden fazla VIT’e başvurup başvurmadığını görmek).

7- Farklı Kayıt Butonu

Farklı Kayıt Butonu tıklandığında Driveda kayıtlı olan VIT1 ve VIT2 de ortak olmayan adaylar ekrana getirilmeli

8- Basvuru Filtreleme Butonu

Basvuru Filtreleme Butonu tıklandığında Basvurular dosyasında bulunan mükerrer kayıtları almadan, filtreleyerek ekrana getirmeli.(Yani bir isim birden fazla kez kayıt edilmişse, bu kayıt sadece 1 kere ekrana getirilmeli)

(Eğer isterseniz, – 5/6/7/8 – bu seçenekleri QComboBox’la da yapabilirsiniz ayrı ayrı buton koymak yerine.)

9-Tercihler Ekranina Geri Don

Tercihler Ekranina Geri Don butonu tiklandiginda kullanici Tercihler ekranina geri donmeli

Mentor

1-Ara

text satirina girilen karakterler ile isim soyisimler icinde arama yapabilen bir buton islevi kazandirilmali (orn: 'As' girisinde drive da kayitli as ile baslayan tum isimleri getirebilmeli)

2-Tum Gorusmeler

Tum gorusmeler butonu tiklandiginda Mentor dosyasında kayitli tum gorusmeler ekrana getirilmeli

3-Coklu sekme

Bu sekmede secilen tercihe uygun kayitlar ekrana getirilmelidir.

4-Tercihler Ekranina Geri Don

Tercihler Ekranina Geri Don butonu tiklandiginda kullanici Tercihler ekranina geri dönmelidir.

Mulakatlar

1-Ara

text satirina girilen karakterler ile isim soyisimler icinde arama yapabilen bir buton islevi kazandirilmali (orn: 'As' girisinde drive da kayitli as ile baslayan tum isimleri getirebilmeli)

2-Proje Gonderilmis Olanlar (Mulakatlar Dosyasındaki ilgili sutun)

Proje gonderilmis olanlar butonu tiklandiginda Mulakatlar dosyasında kayitli projesi gonderilmis adaylar ekrana getirilmeli

3- Projesi Gelmis Olanlar (Mulakatlar Dosyasındaki ilgili sutun)

Projesi gelmis olanlar butonu tiklandiginda Mulakatlar dosyasında kayitli projesi gelmis adaylar ekrana getirilmeli

4-Tercihler Ekranina Geri Don

Tercihler Ekranina Geri Don butonu tiklandiginda kullanici Tercihler ekranina geri dönmeli

Admin Menü


1- Etkinlik Kaydı Butonu

Bu kayıt Google Drive’da bulunan etkinlikleri ekrana getirmelidir

2- Mail Butonu

Bu Buton takvimdeki etkinlikler çekildikten sonra etkinlikte kayıtlı e-mail adreslerine otomatik mail göndermeyi sağlamalıdır.

3- Tablo

Google Takvimde çekilen kayıtların gözükeceği bir tablo.

4-Tercihler-Admin Ekranina Geri Don Butonu

Tercihler-Admin Ekranina Geri Don butonu tiklandiginda admin Tercihler-Admin ekranina geri dönmeli

Proje sureci ile ilgili genel bilgiler 
Her takimin 2 mentoru olacaktir.

Proje gorev yonetimini "Trello Board" uzerinden takip edecegiz.

Mentorleriniz takim calismalarinizi ve gorevlerinizi Trellodan takip edecekler

Takim mentorlerinizi de Trelloya eklemelisiniz

Takim uyeleriniz ile her gun min 30 dk gunluk toplanti yapmalisiniz (daily meeting)

Gunluk toplantilarinizda ;

Takim uyeleri neleri bitirdiklerini

Proje ile ilgili genel degerlendirmeler

Bir sonraki gun icin neler yapilmasi planlaniyor gorusulmelidir

Trello'da  belirli tarihlerin adına bir listeler olacaktir. Ayrıntılar, görevler ve toplantıda yapılacaklar Trello'da günlük olarak bu listede tutulacaktır.

Projeyi zamaninda tamamlamak icin bu adimlari takip edebilmek onemlidir.

Takim mentorleri ile asagida belirtilen tarihlerde toplantilar yapilacaktir.

O toplantıya kadar her adımdaki kısım tamamlanacak ve yeni adıma geçilecektir. Takımdaki her öğrenci o adımda yaptığı rolü toplantıda mentora sunacaktır.

Her toplantıdan sonra mentorlar her ekip üyesinin ilerleyip ilerlemediğine ilişkin bir değerlendirme yapacaktır.

Proje tamamlandıktan sonra mentorlerinize  online olarak proje sunumu yapılacaktır.

Projenin Bitmis Olmasi Icin
Mentorleriniz ile koordineli bir sekilde calisabilmek

UML diagramlari yapmis olmak

Programin .exe halinde calismasini saglamak

Projeyi gununde sunuma hazirlamis olmak

Github icerisinde Readme dosyasi ile saklamak

Medium icin makale haline getirmis olmaniz beklenmektedir (opsiyonel)

Program icin kullanilacak araclar
VS code

Json (data saklamak icin)

UML diyagramlar

Github

OOP

Pyqt6 ve Qt designer

Meeting Schedule

Online Kick-off Meeting - 20/10/2024 

GOREV DAGILIMI YAPMAK ve PROJE TAKIBI OLUSTURMAK AKABINDE ISE UML DIAGRAMI YAPMAK VE LOGİN BAGLANTISINI KONTROL EDEREK TERCIH MENU VE ADMIN TERCIH MENUYE ERISIM SAGLAMAK AYRICA TERCIH MENU'DEN BASVURULAR, MENTOR, MULAKATLAR ve ADMIN MENU'ye ERISIM SAGLAYABILMEK

Online Mentor Meeting -22/10/2024 

GOOGLE DRIVE'DAKI MULAKATLAR SAYFASI ve MENTOR SAYFASINDAKİ VERILERIN KODLARININ OLUSTURULARAK EKRANDA YAZDIRILMASI

Online Mentor Meeting - 25/10/2024

GOOGLE TAKVIM'DEN ETKINLIK KAYDI VERILERININ CEKILEREK, BU VERILERIN ADMIN MENU'DE YAZDIRILMASI ve ETKINLIKTE KAYITLI KISILERE MAIL GONDERILMESI (ADMIN MENU ISLEMLERI) 

Online Mentor Meeting - 28/10/2024

BASVURULAR MENU'DEKI KODLARIN OLUSTURULMASI VE EKRANDA YAZDIRILMASI 

 Online Mentor Meeting - 29/10/2024

PROJENIN MAKALE HALINE GETIRILMESI (OPSIYONEL) ILE GITHUB HESAPLARINIZDA OZEL PROJE OLUSTURULMASI, README, REQUIREMENTS.TXT ve PROJE DOSYALARININ GITHUB'A YUKLENMESI. AYRICA PROJE SUNUMUNA HAZIRLIK

 Final Presentation  Online- 30/10/2024

Proje Adimlari

1. ADIM: 

GOREV DAGILIMI YAPMA

PROJE TAKIBI OLUSTURMA (TRELLO)

PROJE SAYFALARI ICIN ARAYUZ TASARIMLARI

UML TASARIMI OLUSTURMA (PLAN YAPMA) VE CIZIMI

OZELE: GOREV DAGILIMI YAPMA, UML CIZIM, ARAYUZ TASARIMLARI, KULLANIM SENARYOSU OLUSTURMA.

TAVSIYELER:

 BU ADIM GRUP UYELERI TARAFINDAN PAYLASILABILIR.

 PROJE SAYFALARI (RESIMDEKI ARAYUZLER FIKIR VERMESI ACISINDAN TASARLANDI, KENDINIZ RENK SECIMI, FARKLI TASARIM VE BUTON GOLGELEMELERI EKLEYEBILECEGINIZ GIBI AYRICA FARKLI ILAVE GORSELLIK VE EKLEMELER DE YAPABILIRSINIZ.)

UML CIZIMI ICIN: https://lucid.app veya https://app.diagrams.net/ sitelerini kullanabilirsiniz.

PROJE TAKIBI ICIN: https://trello.com/

ADIM

PROGRAM KULLANILDIGINDA GOOGLE DRIVE ve GOOGLE TAKVIMDE BULUNAN ILGILI VERILERIN SORUNSUZ CEKILEBILMESI.

ADMIN MENU'DE ISTENILEN BILGILERIN TAMAMLANMASI.

TAVSIYELER:

2. - 3. ADIMLAR: BU ADIMLAR DA KEZA GRUP UYELERI TARAFINDAN PAYLASILABILIR.

GOOGLE TAKVIM VERILERINI CEKMEK ICIN TAKVIME BIR IKI ETKINLIK EKLEMENIZ VE BU ETKINLIKLERE ZAMAN VE MAIL ADRESI GIRMENIZ GEREKMEKTEDIR.

DOKUMAN VERILERI GSPREAD ILE CEKILEBILIR. TAKVIM VERILERI ISE GOOGLEAPI, GOOGLECALENDARAPI veya GOOGLE oauth2client servisleriyle çekilebilir. Faydalanmak için kullanabileceğiniz web siteleri: https://console.cloud.google.com, https://developers.google.com/calendar/overview

REQUIREMENTS Dosyası için: pip freeze > requirements.txt (https://learn.microsoft.com/tr-tr/visualstudio/python/managing-required-packages-with-requirements-txt?view=vs-2022)

ADIM

PENCERE TANIMLARINDA ISTENILEN GEREKSINIMLERIN TAMAMLANMASI.

SORUNSUZ CALISMASINA YONELIK TESTLERININ YAPILMASI.

REQUIREMENTS ve README DOSYALARININ OLUSTURULMASI

KULLANIM SENARYOSUNUN OLUSTURULMASI (MAKALE HALINE GETIRILMESI)

PROJENIN TUM DOSYALARININ GITBOOK HESAPLARINA YUKLENMESI. 

ADIM - FINAL

SUNUM YAPILMASI
