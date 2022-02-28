# :fontawesome-solid-poll: Oylamalar

Oylamalar modülü sayesinde çalışanlarınızın bir konu hakkındaki fikrini hızlıca alabilirsiniz.

Bir [oylama tanımladıktan](#oylama-tanimla) sonra ilgili oylama "Düzenle" butonu ile açılır ve [oylamaya soru eklenir](#yeni-soru-olustur).

## :fontawesome-solid-poll: Oylama Listesi
Oluşturulmuş oylamalar ve oylama raporları burada gösterilir, düzenlenir ya da silinir.

![](./images/oylamaListesi.png)

### Görüntüle

İlgili oylamaya ait sonuçların görüntülenebileceği ekrandır. Rapor, Excel ve PDF formatında indirilebilir ya da yazdırılabilir.

### Düzenle

İlgili oylamanın düzenlenebileceği ekrandır. Sayfadaki özellikler için bkz: [Oylama Tanımla](#oylama-tanimla)

### Sil

İlgili oylamanın silinmesini sağlar. Tıklanması halinde onay penceresi görünür.

## Yeni Oylama Oluştur

### <a name="oylama-tanimla"></a>Oylama Tanımla

Tüm kullanıcıların katılabileceği yeni bir oylama oluşturmak için kullanılır.

| Özellik                  | Açıklama                                                     |
| ------------------------ | ------------------------------------------------------------ |
| Bildirim Gönderme Durumu | Açık olması halinde; oylama yayınlandığı anda firmanızdaki tüm kişilere bildirim gönderilir. |
| Başlık                   | Oylama başlığı.                                              |
| Aktifleştirme Durumu     | Aktif olması durumunda oylama görünür, Pasif olması durumunda görünmez. |
| Liste Görseli            | Oylama listesinde gösterilecek görseldir.                    |
| Galeri Görseli           | Oylama açıldığında gösterilecek görseldir.                   |
| Oylama Başlangıç Tarihi  | Oylama, seçilen tarihten sonra görünür olur. Yayınlanma tarihi geldiğinde -aktifleştirildiyse- kullanıcılara bildirim gider. |
| Oylama Bitiş Tarihi      | Oylama, seçilen tarihten sonra kapanır. Yayınlanma tarihi geldiğinde -aktifleştirildiyse- kullanıcılara bildirim gider. |

!!! note "Not"

    Mobil Yaka uygulaması üzerinden oylamayı tamamlamış kullanıcı, oylamayı tamamladığını aynı penceredeki listeden görür.
    
    Kullanıcı oylamaya katılmadı ise oylama bitiş tarihi geldiğinde bu oylamayı bir daha göremez.
    
    Aktifleştirme durumu "Pasif" seçilirse oylama kullanıcılara tamamen görünmez hâle gelir.
    
    Herhangi bir sebeple oylamayı kaçıran kullanıcılarınız için tekrar aynı oylamayı oluşturmak yerine, oylama bitiş tarihini uzatabilirsiniz. Bu durumda oylamayı tamamlamış kullanıcılar için oylama tekrar açılmayacaktır.

## Oylama Düzenle

### <a name="yeni-soru-olustur"></a>Yeni Soru Oluştur

Bir oylamaya birden fazla soru eklenebilir.

![](./images/yeniSoruOlustur.png)

| Özellik              | Açıklama                                                     |
| -------------------- | ------------------------------------------------------------ |
| Açıklama             | Soru metnidir.                                               |
| Aktifleştirme Durumu | Aktif olması durumunda soru, oylama içerisinde görünür. Pasif olması durumunda görünmez. |
| Oylama Tipi Seçiniz  | Emoji, Rakam, Yıldız olarak oylama puanlanabilir.            |
| Cevap Metinleri      | Puanlama için 1-5 arası değerlerin metnidir.                 |

<figure markdown>   ![Oylama Tipleri](./images/oylamaTipleri.jpg)  <figcaption>Oylama Tipleri</figcaption> </figure>

#### Listele

İlgili oylama sorusuna ait sonuçların görüntülenebileceği ekrandır. Rapor, Excel ve PDF formatında indirilebilir ya da yazdırılabilir.

#### Düzenle

İlgili sorunun düzenlenebileceği ekrandır. Sayfadaki özellikler için bkz: [Yeni Soru Oluştur](#yeni-soru-olustur)

!!! warning "Uyarı"

    Oylamayı tamamlamış en az 1 kullanıcı olması hâlinde;
    
    - Sorularda düzenleme yapılamaz.
    
    - Soru eklenebilir ancak oylamayı tamamlamış olanlar bu yeni soruları yanıtlayamazlar.

#### Sil

İlgili sorunun silinmesini sağlar. Tıklanması halinde onay penceresi görünür.

## Uygulama İçi Görünümü

??? info "Oylama Listesi"

    <iframe width="300" height="533" src="https://xd.adobe.com/embed/a51929be-b754-4dc0-ad0d-97be0156061d-f04a/screen/bb0dbead-7b0a-48a7-93af-152fab2afe54" frameborder="0" ></iframe>