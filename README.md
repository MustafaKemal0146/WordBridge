# İngilizce-Türkçe Kelime Quiz Uygulaması

Bu terminal tabanlı uygulama, İngilizce-Türkçe kelime bilginizi test etmenize olanak sağlar. Farklı dil seviyelerinde (A1'den C2'ye) kelime pratikleri yapabilirsiniz.

## ⚠️ Önemli Not

Bu uygulama şu an için yalnızca Linux işletim sistemlerinde ve Termux üzerinde sorunsuz çalışmaktadır. Windows kullanıcıları için uyumlu hale getirme çalışmaları devam etmektedir. Anlayışınız için teşekkür ederiz.

## Özellikler

- İngilizce → Türkçe veya Türkçe → İngilizce yönünde çalışma imkanı
- 6 farklı dil seviyesi (A1, A2, B1, B2, C1, C2)
- Her seviye için özel kelime havuzu
- 1-20 arası soru sayısı seçimi
- Çoktan seçmeli sorular (4 seçenek)
- Anlık geri bildirim (doğru/yanlış)
- Quiz sonunda detaylı başarı raporu

## Gereksinimler

- Python 3.x
- Linux işletim sistemi
- curses kütüphanesi (Linux'ta varsayılan olarak yüklüdür)

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/MustafaKemal0146/WordBridge/
cd WordBridge
```

2. Uygulamayı çalıştırın:
```bash
python main.py
```

## Kullanım

1. Önce çalışmak istediğiniz dil yönünü seçin:
   - İngilizce → Türkçe
   - Türkçe → İngilizce

2. Seviyenizi seçin:
   - A1 (Başlangıç)
   - A2 (Temel)
   - B1 (Orta)
   - B2 (Orta Üstü)
   - C1 (İleri)
   - C2 (Üst)

3. Çözmek istediğiniz soru sayısını belirleyin (1-20 arası)

4. Her soru için 4 seçenek arasından doğru cevabı seçin

5. Quiz sonunda başarı raporunuzu görüntüleyin

## Program Yapısı

- `select_language()`: Dil yönü seçimi
- `select_level()`: Seviye seçimi
- `select_question_count()`: Soru sayısı belirleme
- `ask_questions()`: Soru sorma ve cevap alma
- `show_results()`: Sonuçları gösterme
- `main()`: Ana program döngüsü

## Gelecek Güncellemeler

- Windows işletim sistemi desteği
- MacOS desteği
- Grafiksel kullanıcı arayüzü

## Katkıda Bulunma

1. Bu depoyu fork edin
2. Yeni bir dal oluşturun (`git checkout -b yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Dalınıza push yapın (`git push origin yeni-ozellik`)
5. Bir Pull Request oluşturun

## Lisans

Bu proje [GNU 3.0 lisansı](LICENSE) altında lisanslanmıştır.

## İletişim

İletişim için: [E-posta Adresim](mailto:ismustafakemal0146@gmail.com)

## Teşekkürler

Bu projeye katkıda bulunan herkese teşekkürler!
