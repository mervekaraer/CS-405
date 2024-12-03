# CS405 Project 2: Texture + Illumination

## Proje Açıklaması
Bu proje, 3D modelleme ve görselleştirme için temel yapı taşlarını içerir. Amaç, texture kullanımı ve aydınlatma gibi grafiksel işlemleri gerçekleştirmektir. Proje toplamda 4 görev içerir. İlk üçü zorunlu, dördüncüsü isteğe bağlıdır.

## Dosya Yapısı
- **project2.html**: Proje ana sayfası, 3D modeli görüntülemek için kullanılır. Bu dosya değiştirilmemelidir.
- **project2.js**: Ana uygulama dosyası. Tüm görevler bu dosyada gerçekleştirilmelidir.
- **obj.js**: Mesh verilerini işlemek için kullanılan destek dosyası.

## Görevler

### Görev 1: Texture Desteği (30 puan)
- **Durum**: Tamamlandı.
- **Açıklama**: Texture boyutlarının sadece 2'nin katı olma gerekliliği kaldırıldı. Artık her boyutta texture kullanılabilir.
- **Test**: `resources/leaves.jpg` dosyası başarıyla test edilmiştir.

### Görev 2: Aydınlatma Eklenmesi (40 puan)
- **Durum**: Tamamlandı.
- **Açıklama**: Ambient ve diffuse ışık eklendi. Aydınlatma yoğunluğu slider ile kontrol edilebiliyor. Ok tuşları ışık kaynağını hareket ettiriyor.
- **Test**: Görsel testler başarılı.

### Görev 3: Specular Aydınlatma (30 puan)
- **Durum**: Kod yazıldı, ancak test sırasında çalışmadı.
- **Açıklama**: Specular ışık efektleri eklendi ve "Specular Light Intensity" slider ile kontrol edilebilir şekilde tasarlandı.
- **Gerekli Düzenlemeler**:
  - **Specular ışık hesaplamaları** yeniden kontrol edilmeli.
  - **Fragment shader (meshFS)** incelenmeli

### Görev 4: Çoklu Texture Desteği (Bonus 30 puan)
- **Durum**: Denendi ama başarısız oldu. Diğer taskleri bozduğu için bazı geliştirmeler silindi
- **Açıklama**: Birden fazla texture'nin birleştirilmesi ve arayüzde toggle seçeneği eklenmesi planlanıyordu.

## Kullanım
1. **project2.html** dosyasını bir tarayıcıda açın.
2. 3D model ve texture dosyalarını yükleyin.
3. Aydınlatma ve diğer ayarları slider ve ok tuşları ile düzenleyin.

## Bilinen Sorunlar
- Görev 4te iki tane texture eklenemedi


