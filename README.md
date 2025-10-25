# 💖 Kişiye Özel İnteraktif Özür Mesajı

Bu proje, sevdiklerinizden özür dilemek için oluşturulmuş, animasyonlu ve interaktif bir web sayfasıdır.

## 🚀 Canlı Demo

Sayfanın canlı halini görmek için aşağıdaki linke tıklayabilirsiniz:

**[https://KULLANICI-ADINIZ.github.io/REPO-ADINIZ/](https://KULLANICI-ADINIZ.github.io/REPO-ADINIZ/)**

> **Not:** Yukarıdaki linki kendi GitHub kullanıcı adınız ve depo (repository) adınız ile güncellemeyi unutmayın!

## ✨ Özellikler

- **İnteraktif Başlangıç:** Kullanıcının tıklamasıyla başlayan bir deneyim.
- **Animasyonlu Mesajlar:** Ekranda beliren, dikkat çekici ve duygusal metinler.
- **Kaçan "Hayır" Butonu:** Özür dileme sürecine eğlenceli bir dokunuş.
- **Kalp ve Yıldız Yağmuru:** Romantik bir atmosfer yaratan arka plan animasyonları.
- **Kişiselleştirilebilir:** Mesajları, müziği ve son sahnedeki resmi kolayca değiştirebilirsiniz.

## 🔧 Nasıl Kişiselleştirilir?

`ozur.html` dosyasını bir metin düzenleyici ile açarak aşağıdaki değişiklikleri yapabilirsiniz:

1.  **Mesajı Değiştirmek İçin:**
    - JavaScript bölümünde (`<script>` etiketleri arasında) `const messageLines` ile başlayan satırı bulun.
    - `["Mesaj 1", "Mesaj 2", "Mesaj 3"]` şeklindeki metinleri kendi kişisel mesajlarınızla değiştirin.

2.  **Resmi Değiştirmek İçin:**
    - Kendi resminizi proje klasörüne koyun ve adını `indir.jpg` olarak değiştirin. Veya `ozur.html` dosyasındaki `<img src="indir.jpg">` satırında bulunan `indir.jpg`'yi kendi resminizin adıyla güncelleyin.

3.  **Müzik Eklemek İçin:**
    - `<audio>` etiketinin `src=""` özelliğine bir `.mp3` linki ekleyin.
    - Müziğin otomatik başlaması için JavaScript bölümündeki `backgroundMusic.play()` satırının başındaki `//` işaretini kaldırın.
