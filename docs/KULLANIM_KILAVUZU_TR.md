# Markit Ayrıntılı Kullanım Kılavuzu

Bu kılavuz, Markit Android uygulamasını ilk kez kullanmaya başlayanlar için hazırlanmıştır. Markit; internette okurken karşılaştığınız kelime ve ifadeleri kaydetmenizi, bunları kişisel listelerde düzenlemenizi ve aralıklı tekrar sistemiyle çalışmanızı sağlar.

> Uygulamanın arayüzü İngilizcedir. Bu kılavuzda düğme ve menü adları, ekranda göreceğiniz İngilizce halleriyle yazılmıştır.

## İçindekiler

1. [Markit nasıl çalışır?](#1-markit-nasıl-çalışır)
2. [İlk kullanım](#2-ilk-kullanım)
3. [Liste oluşturma ve düzenleme](#3-liste-oluşturma-ve-düzenleme)
4. [Kayıt ekleme ve yönetme](#4-kayıt-ekleme-ve-yönetme)
5. [Öğrenme seviyeleri](#5-öğrenme-seviyeleri)
6. [Learn modu](#6-learn-modu)
7. [Review Words modu](#7-review-words-modu)
8. [Game modu](#8-game-modu)
9. [Çalışma aşamaları](#9-çalışma-aşamaları)
10. [Review bildirimleri](#10-review-bildirimleri)
11. [Progress ekranı](#11-progress-ekranı)
12. [Miray Browser](#12-miray-browser)
13. [Web sayfasından kelime kaydetme](#13-web-sayfasından-kelime-kaydetme)
14. [Page Reader ile sesli okuma](#14-page-reader-ile-sesli-okuma)
15. [Sekmeler, Recent tabs ve Bookmarks](#15-sekmeler-recent-tabs-ve-bookmarks)
16. [Yedekleme, geri yükleme ve liste aktarımı](#16-yedekleme-geri-yükleme-ve-liste-aktarımı)
17. [Free ve Premium](#17-free-ve-premium)
18. [Cihaz değiştirme ve uygulamayı yeniden yükleme](#18-cihaz-değiştirme-ve-uygulamayı-yeniden-yükleme)
19. [Sık karşılaşılan durumlar](#19-sık-karşılaşılan-durumlar)
20. [Verimli kullanım önerileri](#20-verimli-kullanım-önerileri)

---

## 1. Markit nasıl çalışır?

Markit’in temel çalışma düzeni dört adımdan oluşur:

1. Öğrenmek istediğiniz dil için bir liste oluşturursunuz.
2. Kelime veya ifadeleri elle ya da Miray Browser üzerinden kaydedersiniz.
3. Yeni kayıtları **Learn** modunda çalışırsınız.
4. Tekrar zamanı gelen kayıtları **Review Words** modunda yeniden çalışırsınız.

Markit, kelimeleri yalnızca alfabetik bir listede tutmaz. Her kaydın öğrenme seviyesini ve bir sonraki tekrar zamanını ayrı ayrı takip eder. Başarılı çalışmaların ardından kayıt seviyesi yükselir ve bir sonraki tekrar daha ileri bir tarihe planlanır.

Kelime listeleri, öğrenme ilerlemesi, ayarlar, Browser yer imleri ve yakın geçmiş cihazdaki yerel SQLite veritabanında tutulur. Normal liste ve çalışma kullanımı için Markit hesabı gerekmez.

## 2. İlk kullanım

Uygulamayı ilk açtığınızda ana ekranda **My Lists** alanını görürsünüz.

Önerilen ilk kurulum:

1. Sağ alttaki mavi **+** düğmesine dokunun.
2. Listeye kolay tanınan bir ad verin. Örnek: `English News`.
3. Bir liste rengi seçin.
4. **Select language** alanından öğrenilen dili seçin.
5. İsterseniz **Voice** alanından o liste için kullanılacak sesi belirleyin.
6. **Save** düğmesine dokunun.

Dil seçimi zorunludur. Dil seçmeden kaydetmeye çalışırsanız Markit ilgili alanı vurgular.

## 3. Liste oluşturma ve düzenleme

### Ana liste oluşturma

Ana ekrandaki mavi **+** düğmesi yeni bir üst düzey liste oluşturur. Farklı diller veya çalışma alanları için ayrı listeler kullanabilirsiniz.

Örnek yapı:

```text
English
├── BBC News
├── Technology
└── Daily expressions
```

### Alt liste oluşturma

Bir listenin içinde alt liste oluşturarak içerikleri konu, kitap, ünite veya kaynak bazında ayırabilirsiniz. Üst listenin kayıt sayısı gösterilirken alt listelerdeki kayıtlar da toplam hesaplamaya dâhil edilir.

### Liste rengi

Hazır renklerden birini seçebilir veya özel renk seçiciyi kullanabilirsiniz. Özel renk alanında renk tonu, parlaklık ve RGB/hex değeri üzerinden daha hassas seçim yapılabilir.

Liste rengi:

- Ana ekranda listenin görsel kimliğini oluşturur.
- Miray Browser’da o listeye kaydedilen kelimelerin vurgu rengini belirler.
- Liste rengi sonradan değiştirildiğinde Browser’a yeniden girildiğinde kayıtlar güncel renkle gösterilir.

### Listeyi düzenleme

Liste içindeki kalem simgesine dokunarak liste adını, rengini, dilini veya sesini değiştirebilirsiniz. Yenileme simgesi liste verilerini yeniden yükler. **My lists** düğmesi bulunduğunuz listenin içinden ana liste ekranına döner.

### Liste arama

Ana ekrandaki **Filter** alanına kaydın bir bölümünü yazın. Eşleşen listeler ve ilgili liste ağacı gösterilir. Arama kayıt, çeviri ve cümle içinde yapılarak bulunan sonuçlar gösterilir.

### Birden fazla listeyi yönetme

Liste seçim kutularını kullanarak birden fazla liste seçebilirsiniz. Açılan işlem menüsünden seçili listeleri taşıyabilir, kopyalayabilir veya silebilirsiniz. Silme işleminden önce seçilen liste ve kayıtları dikkatle kontrol edin.

## 4. Kayıt ekleme ve yönetme

### Elle kayıt ekleme

Bir listeyi açın ve sağ alttaki mavi **+** düğmesine dokunun.

Bir kayıt şu alanlardan oluşur:

- Öğrenilecek kelime veya ifade
- Çeviri
- Kelimenin geçtiği örnek cümle

Çeviri ve cümle zorunlu olmayabilir; ancak kelimeyi bağlam içinde hatırlamayı kolaylaştırdığı için örnek cümle eklenmesi önerilir.

### Kaydı düzenleme

Bir kayıt kartına dokunduğunuzda **Edit record** penceresi açılır. Buradan kelimeyi, çeviriyi ve örnek cümleyi değiştirebilir veya kaydı silebilirsiniz.

### Sesli dinleme

Kayıt kartındaki hoparlör simgesi, kelime veya ifadeyi listenin seçilmiş dil ve sesiyle okur.

### Seviye rozeti

Hoparlör simgesinin altında `L0` ile `L5` arasında renkli bir seviye rozeti bulunur. `L5 ✓`, kaydın ustalık seviyesine ulaştığını gösterir. Bu rozet yalnızca bilgi amaçlıdır; dokunulduğunda ayrı bir işlem başlatmaz.

### Toplu kayıt işlemleri

Kayıtların seçim kutularını kullanarak birden fazla kayıt seçebilirsiniz:

- **Select all:** Geçerli filtrede görünen tüm kayıtları seçer.
- **Copy:** Seçili kayıtların kopyasını başka listeye ekler.
- **Move:** Seçili kayıtları başka listeye taşır.
- **Delete:** Seçili kayıtları topluca siler.

Taşıma ve kopyalama sırasında kayıtların öğrenme seviyesi ve review bilgileri korunur.

### Son eklenen kayıtlar

Ana ekranın alt bölümündeki **The 20 most recently added records**, en son eklenen 20 kaydı gösterir. Birden fazla kayıt seçerek bu alandan toplu silme işlemi yapabilirsiniz.

## 5. Öğrenme seviyeleri

Yeni kayıtlar `Level 0` seviyesinde başlar. Seviyeler `L0`–`L5` arasında ilerler.

| Seviye | Genel anlamı | Sonraki tekrar aralığı |
|---|---|---:|
| L0–L1 | Yeni veya çok erken öğrenme | 4 saat |
| L2 | Temel öğrenme sürüyor | 24 saat |
| L3 | Orta düzey hatırlama | 3 gün |
| L4 | Güçlü hatırlama | 7 gün |
| L5 | Ustalık seviyesi | Önce 30 gün |

Level 5 son durak değildir. Başarılı ustalık tekrarları yaklaşık 60, 90, 180 ve 360 günlük daha geniş aralıklarla devam eder.

Bir çalışma oturumunun tamamlanmasının ardından:

- Başarılı kayıtlar seviye atlayabilir.
- Başarısız kalan kayıtlar aynı seviyede kalır.
- Yeni seviye ve tekrar tarihi liste ekranına dönüldüğünde güncel olarak görünür.

## 6. Learn modu

**Learn**, ağırlıklı olarak Level 0, Level 1 ve Level 2 kayıtlar içindir.

1. Bir listeye dokunun.
2. Açılan çalışma menüsünde **Learn** seçeneğine dokunun.
3. Gösterilen çalışma aşamalarını tamamlayın.
4. Oturum sonunda sonuç özetini inceleyin.

Markit düşük seviyeli kayıtları önceliklendirir ve kayıtları küçük, karışık gruplar halinde sunar. Böylece sürekli aynı sabit sırayı ezberlemek yerine kelimenin kendisini öğrenmeniz amaçlanır.

Bir kayıt Learn içinde çalışıldıktan sonra review süresi başlar. Süresi geldiğinde kayıt, seviyesi henüz L0–L2 olsa bile **Review Words** bölümünde de görünebilir. Başarılı biçimde Level 3’e yükselen kayıt Learn kapsamından çıkar.

## 7. Review Words modu

**Review Words**, planlanan tekrar zamanı gelmiş kayıtları içerir.

Çalışma menüsündeki sayı, o liste ve ilgili alt listelerde review zamanı gelmiş kayıtların miktarını gösterir. Kayıt yoksa seçenek pasif olabilir.

Review oturumu tamamlandığında görsel sonuç ekranında:

- Çalışılan toplam kayıt sayısı
- Seviye atlayan kayıt sayısı
- Aynı seviyede kalan kayıt sayısı
- Her kayıt için önceki ve yeni seviye (`L2 → L3` gibi)

gösterilir. Seviye atlayanlar yeşil, aynı kalanlar gri, Level 5’e ulaşanlar altın tonuyla vurgulanır.

## 8. Game modu

**Game**, listedeki kayıtları farklı alıştırmalarla tekrar etmenizi sağlar. Game, düzenli Learn ve Review çalışmalarını destekleyen pratik alanıdır; planlanan Review oturumlarının yerine geçmesi amaçlanmaz.

Free sürümde belirli sayıda tamamlanan Game oturumundan sonra reklam teklifi gösterilebilir. Premium sürümde reklamlar kaldırılır.

## 9. Çalışma aşamaları

Learn ve Review oturumlarında aşağıdaki aşamalar kullanılabilir:

1. **Flashcards:** Kelimeyi, çeviriyi ve bağlamı tanıma.
2. **Guess:** Gösterilen ipucundan doğru kaydı tahmin etme.
3. **Match:** Kelime ve karşılığını eşleştirme.
4. **Write:** Cevabı klavyeyle yazma.

### Write modunda cevap kontrolü

Kontrol, listenin seçilmiş diline duyarlıdır. Büyük/küçük harf, boşluk, noktalama ve farklı apostrof biçimleri gibi ortak yazım farklılıkları güvenli şekilde normalleştirilir.

Ayrıca desteklenen diller için dile özgü kolaylıklar bulunur. Örneğin Türkçe klavye biçimleri, İngilizce kısaltmalar, Almanca `ä/ae`, `ö/oe`, `ü/ue`, `ß/ss`, Fransızca bağlama biçimleri ve diğer desteklenen dillerin karakter özellikleri dikkate alınır. Uzun cevaplarda anlamı bozmayacak sınırlı bir yazım hatası kabul edilebilir; Çince, Japonca ve Korecede anlam değişmesi riski nedeniyle genel karakter mesafesi uygulanmaz.

## 10. Review bildirimleri

Review zamanı gelen kayıtlar için günlük hatırlatıcı kurabilirsiniz.

1. Ana ekranda sağ üstteki profil simgesine dokunun.
2. **Review reminder** satırındaki anahtarı açın.
3. Android 13 veya üzerindeyseniz bildirim iznine onay verin.
4. Satırın sol bölümüne dokunun.
5. İstediğiniz saati seçip **Save time** düğmesine dokunun.

Seçilen saat satırın altında `Every day at 10:00` biçiminde görünür. Anahtarı kapattığınızda hatırlatıcı durur ancak seçilmiş saat saklanır.

Hatırlatıcı davranışı:

- Markit seçilen saatte yalnızca review zamanı gelmiş kayıt varsa bildirim gösterir.
- Aynı listeye ait kayıtlar tek bildirimde gruplanır.
- Birden fazla liste varsa toplam liste ve kayıt sayısı özetlenir.
- Genişletilen bildirimde liste adları ve bazı örnek kelimeler görünür.
- Telefon yeniden başlatıldığında etkin hatırlatıcı yeniden planlanır.
- Android’in pil optimizasyonu nedeniyle bildirim seçilen saatten birkaç dakika sonra gelebilir.

Bildirim iznini reddederseniz hatırlatıcı kapalı kalır. İzni daha sonra Android’in Markit uygulama ayarlarından açabilirsiniz.

## 11. Progress ekranı

Profil menüsünden **Progress** seçeneğini açın.

Bu ekranda genel olarak şunları inceleyebilirsiniz:

- Günlük çalışma süresi
- Çalışılan ve eklenen kayıtlar
- Doğru ve yanlış cevaplar
- Seviye atlamaları
- Learn, Review ve diğer çalışma etkinlikleri
- Liste bazında ilerleme
- Level 0–5 dağılımı
- Son 7 ve son 30 günlük sütun grafikleri

Liste çalışma menüsündeki küçük seviye grafiği de seçili liste ve alt listelerindeki L0–L5 dağılımını hızlıca gösterir.

## 12. Miray Browser

Miray Browser’ı ana ekrandaki renkli **Read & Learn with Miray Browser** kartından veya profil menüsünden açabilirsiniz.

### Üst araç çubuğu

- **Home:** Aktif okumayı duraklatır ve Browser başlangıç ekranını açar.
- **Refresh:** Geçerli web sayfasını yeniler.
- **Address field:** Web adresi veya arama ifadesi girmenizi sağlar.
- **Bookmark:** Geçerli sayfayı Bookmarks bölümüne ekler veya kaldırır.
- **Three-dot menu:** Sekmeler, sayfada bulma, kayıt listesi değiştirme ve diğer işlemleri açar.
- **My lists:** Açık Browser sekmelerini kapatmadan Markit liste ekranına döner.

### Arama yapma

Adres alanına tam bir web adresi veya arama ifadesi yazabilirsiniz. Web adresi değilse arama olarak açılır. Yazarken geçmiş sitelerden öneriler gösterilebilir.

### Kayıt listesini değiştirme

Her Browser sekmesinin kendi hedef kayıt listesi olabilir. Durum satırında aşağıdakine benzer bir bilgi görünür:

```text
Markit saves to: English › BBC News
```

Three-dot menüdeki **Change saving list** işlemiyle o sekmenin hedef listesini değiştirebilirsiniz. Değişiklikten sonra eklenen kayıtlar seçili listenin renginde vurgulanır.

## 13. Web sayfasından kelime kaydetme

1. Web sayfasında bir kelime veya ifadeyi basılı tutarak seçin.
2. Seçim menüsünden **Add to Markit** seçeneğine dokunun.
3. Gerekirse hedef listeyi seçin veya **New list** ile yeni liste oluşturun.
4. Seçilen metni, çeviriyi ve yakalanan örnek cümleyi kontrol edin.
5. **Save** düğmesine dokunun.

Kaydedilen kelime veya çok kelimeli ifade sayfada hedef listenin rengiyle vurgulanır. Bir kayıt başka bir kelimenin içinde geçiyorsa eşleşen bölüm de vurgulanabilir; örneğin `drive` kaydı `driver` içindeki `drive` bölümünde görülebilir.

Sayfa yenilendiğinde veya daha sonra yeniden açıldığında kayıtlar yerel veritabanından okunarak tekrar vurgulanır. Farklı listelerdeki kayıtlar, ait oldukları listenin güncel rengiyle gösterilir.

Vurgulanmış bir kayda dokunarak çevirisini görebilir ve **Edit** işlemini açabilirsiniz. Bir kaydı düzenlemek veya silmek diğer vurguları kaldırmaz.

## 14. Page Reader ile sesli okuma

Web sayfasının sağındaki hareketli hoparlör düğmesine dokunarak Page Reader kontrollerini açın. Hoparlör düğmesini sürükleyerek uygun bir konuma taşıyabilirsiniz.

### Kontroller

- **Play / Pause:** Okumayı başlatır veya duraklatır.
- **Stop:** Okuma oturumunu durdurur.
- **Previous / Next:** Önceki veya sonraki cümleye geçer.
- **Repeat:** Geçerli cümleyi tekrarlar. Tekrar dokunulduğunda kapanır.
- **Tap sentence to start:** Simgeye dokunduktan sonra sayfada okumaya başlanacak cümleyi seçmenizi sağlar. Simgeye tekrar dokunursanız seçim modu kapanır.
- **Volume:** Ses seviyesini ayarlar.
- **Speed:** Okuma hızını `0.25×` ile `3.00×` arasında değiştirir.
- **Settings:** Reader dilini ve sesini seçmenizi sağlar.

Okunan bölüm paragraf paragraf bulunur ancak konuşma ve yeşil takip vurgusu cümle cümle ilerler. Böylece ekrandaki vurgu konuşulan cümleyle daha yakın eşleşir.

### Kaldığınız yere dönme

Sekmeyi kapatmadan Browser’dan ayrılırsanız Markit mevcut paragrafı ve okuma konumunu saklar. Sayfaya döndüğünüzde ilgili paragraf bulunur ve ilk uygun cümle hazırlanır. Okuma otomatik başlamaz; devam etmek için **Play** düğmesine dokunun.

Başka sekmeye geçtiğinizde, aynı sekmede yeni sayfa açtığınızda, Android Back ile önceki sayfaya döndüğünüzde veya uygulamayı arka plana aldığınızda aktif ses durur. Böylece görünmeyen eski bir sayfanın sesi devam etmez.

### Sayfa içeriğinin seçilmesi

Reader; başlık, paragraf, liste öğesi ve alıntı gibi içerikleri önceliklendirir. Menü, form, çerez bildirimi, reklam ve footer gibi alanları mümkün olduğunca dışarıda bırakır. Web sitelerinin yapıları farklı olduğu için bazı sayfalarda fazladan metin okunabilir.

## 15. Sekmeler, Recent tabs ve Bookmarks

### Tabs

Three-dot menüden **Tabs** ekranını açın.

- Bir sekme kartına dokunarak o sayfaya geçin.
- Kartın köşesindeki **×** ile yalnızca o sekmeyi kapatın.
- **+ New tab** ile yeni sekme açın.
- **Close all tabs** ile bütün açık sekmeleri kapatın.

Açık sekmeler uygulamadan ayrıldığınızda korunur. Bir sekmeyi kapatmanız, o sayfadaki çalışma oturumunun tamamlandığı anlamına gelir; sayfa daha sonra Bookmarks veya Recent tabs üzerinden açılırsa normal olarak sayfanın başından açılır.

### Recent tabs

Browser başlangıç sayfasındaki **Recent tabs**, yakın zamanda ziyaret edilen sayfaları önizlemeleriyle gösterir.

- Karta dokunarak sayfayı yeniden açabilirsiniz.
- **×** ile yalnızca ilgili geçmiş öğesini kaldırabilirsiniz.
- **Clear all** bütün yakın geçmişi temizler.

Recent tabs öğesini silmek açık sekmeyi kapatmaz ve Bookmark kaydını silmez.

### Bookmarks

Adres çubuğunun yanındaki sarı bookmark simgesi geçerli sayfayı kaydeder. Başlangıç ekranındaki **Bookmarks** alanından sayfayı yeniden açabilirsiniz.

- Bookmark kartına dokunmak sayfayı açar.
- Karttaki **×** bookmark kaydını kaldırır.
- Geçerli sayfada sarı simgeye tekrar dokunmak da bookmark kaydını kaldırır.

Bookmarks ve Recent tabs birbirinden bağımsızdır.

## 16. Yedekleme, geri yükleme ve liste aktarımı

Bu işlemlere profil menüsünden ulaşılır.

### Backup

**Backup**, aşağıdaki verileri tek bir Markit yedek dosyasına kaydeder:

- Listeler ve alt listeler
- Kelime ve ifade kayıtları
- Çeviriler ve örnek cümleler
- Öğrenme seviyeleri ve review tarihleri
- İlerleme ve uygulama ayarları
- Miray Browser Bookmarks
- Miray Browser Recent tabs

Android dosya seçicisi açılır. Dosyayı cihaz hafızasına veya dosya seçicide görünen Google Drive gibi bir bulut sağlayıcısına kaydedebilirsiniz.

### Restore

**Restore** ile daha önce oluşturulmuş tam Markit yedeğini seçebilirsiniz. Mevcut verilerin üzerine geri yükleme yapılabileceği için doğru dosyayı seçtiğinizden emin olun.

Güncel yedekler Bookmarks ve Recent tabs bilgilerini de geri getirir. Eski sürüm yedeklerinde Browser verisi yoksa cihazdaki mevcut Bookmarks ve Recent tabs korunur.

### Export list

Yalnızca belirli bir listeyi başka cihaza veya kullanıcıya aktarmak için **Export list** kullanın. Liste ağacından dışa aktarılacak listeyi seçin.

### Import list

**Import list** ile Markit liste dosyası içe aktarılır. Dosyada öğrenme seviyeleri ve review planları varsa Markit bunları da aktarmak isteyip istemediğinizi sorar:

- **Import progress:** Öğrenme seviyelerini ve review tarihlerini de getirir.
- **Start fresh:** Kelimeleri getirir ancak öğrenme sürecini yeniden başlatır.

### Bulut kullanımı hakkında

Markit yedekleri otomatik olarak kendi sunucusuna yüklemez. Buluta kaydetmek istiyorsanız Android dosya seçicisinde kendi bulut sağlayıcınızı seçmeniz gerekir. Başka cihazda aynı sağlayıcı üzerinden dosyayı seçerek Restore veya Import işlemi yapabilirsiniz.

## 17. Free ve Premium

Free sürüm, temel öğrenme düzenini kullanmanıza izin verir. Liste oluşturma, Learn, Review, Game, Progress, Restore ve Import özelliklerinin temel kullanımı devam eder.

Free sürümde liste/kayıt sayısı, toplu seçim, yedekleme, dışa aktarma, gelişmiş Reader işlemleri ve reklam aralıkları için sınırlar bulunabilir. Bu değerler uygulama güncellemesi gerektirmeden Remote Config üzerinden değiştirilebilir.

Premium genel olarak:

- Reklamları kaldırır.
- Liste ve kayıt sınırlarını kaldırır.
- Toplu işlemleri sınırsız hale getirir.
- Gelişmiş Reader kullanımını açar.
- Backup ve Export sınırlarını kaldırır.

### Aylık ve yıllık plan

Premium ekranında **Monthly** ve **Yearly** seçenekleri bulunur. Her ikisi de aynı Premium özelliklerini açar. Yıllık plan, 12 aylık toplam maliyete göre tasarruf sağlıyorsa oran ekranda gösterilir.

Aktif aylık abonelikten yıllığa veya yıllıktan aylığa geçiş seçebilirsiniz. Plan değişikliği Google Play’e ertelenmiş değişiklik olarak gönderilir; mevcut ödenmiş dönem sonuna kadar geçerli plan devam eder, yeni plan bir sonraki yenilemede başlar. Ekrandaki:

- **Current:** Şu anda aktif olan planı,
- **Scheduled:** Mevcut dönem bittikten sonra başlayacak planı

gösterir.

Abonelik iptali ve ödeme yönetimi Google Play Store’un **Payments & subscriptions › Subscriptions** bölümünden yapılır. Abonelik yenilenmez ve ücretli dönem sona ererse uygulama Free sürüme döner. Aynı Google hesabıyla yeniden yükleme yapıldığında aktif satın alma Google Play üzerinden tekrar tanınabilir; yerel kelime verileri için ayrıca yedek almanız gerekir.

## 18. Cihaz değiştirme ve uygulamayı yeniden yükleme

Markit’in öğrenme verileri cihazda yerel olarak tutulduğu için uygulamayı silmeden veya cihaz değiştirmeden önce mutlaka **Backup** oluşturun.

Önerilen cihaz değiştirme sırası:

1. Eski cihazda profil menüsünü açın.
2. **Backup** seçeneğine dokunun.
3. Yedeği erişebildiğiniz güvenilir bir bulut klasörüne kaydedin.
4. Yeni cihazda Markit’i yükleyin.
5. Profil menüsünden **Restore** seçeneğini açın.
6. Aynı yedek dosyasını seçin.
7. Listeleri, seviyeleri, Bookmarks ve Recent tabs alanlarını kontrol edin.
8. Premium aboneliğiniz varsa yeni cihazda aynı Google Play hesabını kullandığınızdan emin olun.

Açık Browser sekme oturumları tam yedeğe dâhil değildir. Bookmarks ve Recent tabs geri gelir; canlı sekmeleri gerektiğinde bunlardan yeniden açabilirsiniz.

## 19. Sık karşılaşılan durumlar

### Liste kaydedilmiyor

Liste adı ve özellikle **Select language** alanını kontrol edin. Dil seçimi zorunludur.

### Browser’da seçilen metin kaydoluyor ama görünmüyor

Sayfanın yüklenmesini tamamlamasını bekleyin. Hedef kayıt listesinin doğru olduğunu kontrol edin. Bazı web siteleri metni sık sık yeniden oluşturduğu için sayfayı yenilemek gerekebilir.

### Vurgu rengi beklediğim gibi değil

Kaydın bulunduğu listenin rengini kontrol edin. Liste rengini değiştirdiyseniz Browser’a yeniden girin veya sayfayı yenileyin.

### Review Words içinde kayıt görünmüyor

Kayıt için planlanan tekrar zamanı henüz gelmemiş olabilir. Level rozeti tek başına kaydın review için hazır olduğu anlamına gelmez.

### Review bildirimi gelmiyor

Şunları kontrol edin:

- Profil menüsündeki **Review reminder** anahtarı açık mı?
- Seçilen saat doğru mu?
- Android bildirim izni açık mı?
- Review zamanı gelmiş en az bir kayıt var mı?
- Android pil tasarrufu bildirimi geciktirmiş olabilir mi?

### Reader sesi başka sayfaya geçince devam ediyor

Güncel davranışta sekme değişimi, yeni sayfa yükleme, Android Back veya uygulamanın arka plana alınması sesi durdurur. Uygulamayı güncel sürümle kullandığınızdan emin olun.

### Abonelik Play Store’da görünmüyor

Satın alımda kullanılan Google hesabının Play Store’da etkin hesap olduğundan emin olun. Test abonelikleri yalnızca ilgili lisans test hesabında ve test koşulları altında görünebilir.

### Uygulamayı silersem kayıtlarım korunur mu?

Yerel uygulama verileri silinebilir. Uygulamayı kaldırmadan önce Backup oluşturun. Premium satın alma Google Play hesabıyla tekrar tanınabilir ancak bu işlem yerel kelime verilerini geri getirmez.

## 20. Verimli kullanım önerileri

- Tek kelimelerin yanında günlük ifadeleri ve kalıpları da kaydedin.
- Örnek cümleyi mümkün olduğunca koruyun; bağlam hatırlamayı kolaylaştırır.
- Listeleri dil, kaynak veya konu bazında düzenleyin.
- Browser’da uzun süre kayıt yapmadan önce **Markit saves to** satırındaki hedef listeyi kontrol edin.
- Yeni kayıtları küçük Learn oturumlarıyla çalışın.
- Review zamanı gelen kayıtları biriktirmeden düzenli tamamlayın.
- Size uygun bir günlük Review reminder saati seçin.
- Uzun yazıları Bookmarks’a ekleyin.
- Okumaya aynı yerden devam etmek istediğiniz sayfaların sekmesini kapatmayın.
- Cihaz değişikliği ve uygulama kaldırma öncesinde güncel Backup alın.
- Yedek dosyasını yalnızca cihazda bırakmak yerine güvenilir ikinci bir konumda saklayın.

---

## Gizlilik ve destek

Markit’in veri işleme açıklaması için [Privacy Policy](https://ozoyegin.github.io/markit-privacy/privacy-policy.html) sayfasına bakabilirsiniz.

Gizlilik ve destek iletişimi: [ozguryegin@gmail.com](mailto:ozguryegin@gmail.com)

Geliştirici: **ozofamily**
