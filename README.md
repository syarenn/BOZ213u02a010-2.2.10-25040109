# BOZ213u02a010-2.2.10-25040109
# Python Operatörler ve İfadeler – İç İçe Kesirler

## 1. Proje Ne Yapar?

Bu çalışma, Nesne Tabanlı Programlama dersi kapsamında tüm öğrencilere verilen ortak bir Python laboratuvar uygulamasıdır.

Program, kullanıcıdan alınan bir sayı üzerinden iç içe geçmiş kesirli bir matematiksel ifadeyi hesaplar.

Hesaplanan sonuç `y` değişkenine atanır ve konsol ekranında görüntülenir.

## 2. Proje Neden Faydalıdır?

Bu laboratuvar çalışması, Python programlama dilinde aritmetik operatörlerin ve işlem önceliğinin öğrenilmesini amaçlamaktadır.

Çalışma sayesinde:

- Matematiksel ifadelerin Python koduna dönüştürülmesi,
- İç içe parantezlerin kullanılması,
- Bölme ve toplama operatörlerinin uygulanması,
- İşlem önceliğinin anlaşılması,
- `float()` fonksiyonuyla veri tipi dönüşümü yapılması,
- `input()` ve `print()` fonksiyonlarının kullanılması

becerileri pekiştirilmektedir.

## 3. Kullanıcılar Projeyi Nasıl Çalıştırabilir?

### Kullanılan Teknolojiler

- Python 3
- Python IDLE

### Programın Çalıştırılması

1. Python IDLE açılır.
2. `main.py` dosyası açılır.
3. F5 tuşuna basılarak program çalıştırılır.
4. Kullanıcıdan bir x değeri istenir.
5. Girilen değer matematiksel ifadede kullanılır.
6. Hesaplanan sonuç ekrana yazdırılır.

### Kullanılan Matematiksel İfade

**y = 1 / (x + 1 / (x + 1 / (x + 1 / x)))**

### Örnek Girdiler ve Beklenen Çıktılar

| Girdi (x) | Çıktı (y) |
|---|---|
| 1 | 0.6000000000000001 |
| 10 | 0.09901951266867294 |
| 100 | 0.009999000199950014 |
| -5 | -0.19258202567760344 |

### Kullanılan Python Yapıları

| Python Yapısı | Görevi |
|---|---|
| `input()` | Kullanıcıdan veri alır. |
| `float()` | Girilen değeri ondalıklı sayıya dönüştürür. |
| `/` | Bölme işlemini gerçekleştirir. |
| `+` | Toplama işlemini gerçekleştirir. |
| `()` | İşlem önceliğini belirler. |
| `print()` | Hesaplanan sonucu ekrana yazdırır. |

### Dikkat Edilmesi Gerekenler

Matematiksel ifadenin doğru hesaplanabilmesi için parantezlerin doğru yerleştirilmesi gerekmektedir.

Sıfıra bölme hatasını önlemek için x değeri 0 olmamalıdır.

## 4. Kullanıcılar Nereden Yardım Alabilir?

Programla ilgili sorular ve hata bildirimleri GitHub Issues bölümü üzerinden paylaşılabilir.

Python'un resmî dokümantasyonundan da yararlanılabilir.

## 5. Projeyi Kim Geliştirir ve Sürdürür?

Bu laboratuvar çalışması, Nesne Tabanlı Programlama dersi kapsamında tüm öğrencilere verilen ortak bir uygulamadır.

Başlangıç kodu ve matematiksel ifade ders materyali olarak sunulmuştur. Eksik kod bölümü laboratuvar yönergeleri doğrultusunda bireysel olarak tamamlanmıştır.

Çalışmanın GitHub ortamına aktarılması ve belgelendirilmesi depo sahibi tarafından gerçekleştirilmiştir.

## Kaynakça

Python Software Foundation. (t.y.). *The Python Tutorial*. Python Documentation.

https://docs.python.org/3/tutorial/

Van Rossum, G., Warsaw, B. ve Coghlan, A. (2001). *PEP 8 – Style Guide for Python Code*. Python Enhancement Proposals.

https://peps.python.org/pep-0008/

## Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Ayrıntılı bilgi için `LICENSE` dosyasına bakılabilir.
