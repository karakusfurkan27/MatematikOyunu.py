# 4 İşlem Matematik Oyunu

Bu Python programı, Tkinter kütüphanesini kullanarak geliştirilmiş basit bir 4 işlem matematik oyunudur. Oyuncu, rastgele üretilen matematiksel sorulara doğru cevap vermeye çalışır. Sorular toplama, çıkarma, çarpma ve bölme işlemlerinden oluşur. Kullanıcı, her doğru cevap için "Doğru!" mesajı alırken, yanlış cevap verdiğinde "Yanlış, tekrar dene!" mesajı alır.

## Özellikler
- Rastgele dört işlem soruları (toplama, çıkarma, çarpma, bölme)
- Bölme işlemi için yalnızca tam bölünebilir sayılar kullanılır
- Kullanıcı doğru cevabı girdiğinde "Doğru!" mesajı, yanlış cevap verdiğinde "Yanlış, tekrar dene!" mesajı görüntülenir
- Hatalı girişlerde (örn. sayı yerine metin girilmesi) kullanıcıyı uyarır

## Gereksinimler
- Python 3.x
- Tkinter (Python ile birlikte gelir)

## Kullanım
1. Python yüklü bir ortamda bu dosyayı çalıştırın.
2. Oyuncuya bir soru gösterilecektir.
3. Kullanıcı, cevabını girip "Cevabı Kontrol Et" butonuna tıklayarak cevabını kontrol edebilir.
4. Doğru cevap verildiğinde yeni bir soru otomatik olarak verilecektir.
5. Yanlış cevap verildiğinde kullanıcıya hata mesajı gösterilecek ve yeni bir soru sunulacaktır.

## Kurulum
Tkinter, Python ile birlikte geldiği için ekstra bir kurulum yapmanıza gerek yoktur.

## Kodun Açıklaması
- **Tkinter**: Kullanıcı arayüzünü oluşturmak için kullanılır.
- **random**: Rastgele sayılar ve işlemler oluşturmak için kullanılır.
- `new_question()` fonksiyonu, rastgele bir soru oluşturur ve ekrana yansıtır.
- `check_answer()` fonksiyonu, kullanıcının cevabını kontrol eder ve sonucu ekrana yazdırır.
- Kullanıcı her cevaptan sonra yeni bir soru ile karşılaşır.

## Ekran Görüntüsü
Oyunun arayüzünde, kullanıcıya bir soru ve cevabı girip kontrol etmesi için bir metin kutusu, bir etiket ve bir buton yer alır.

## Lisans
Bu proje MIT lisansı altında lisanslanmıştır.
