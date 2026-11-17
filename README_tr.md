# CodeSnip | Yeni Nesil Kod ve Prompt Yöneticisi

<p align="center">
  <img src="https://img.shields.io/badge/Sürüm-26Q3.5-00ADB5?style=for-the-badge" alt="Sürüm 26Q3.5">
  <img src="https://img.shields.io/static/v1?label=Geli%C5%9Ftirme&message=Electron&color=47848F&style=for-the-badge" alt="Electron ile geliştirildi">
  <img src="https://img.shields.io/static/v1?label=Lisans&message=MIT&color=green&style=for-the-badge" alt="MIT Lisansı">
</p>

<p align="center">
  <a href="README_tr.md">
    <img src="https://img.shields.io/badge/Dil-Türkçe-red?style=for-the-badge" alt="Türkçe">
  </a>
  <a href="README.md">
    <img src="https://img.shields.io/badge/Language-English-blue?style=for-the-badge" alt="English">
  </a>
</p>

<p align="center">
  Kod parçacıklarını, terminal komutlarını ve yapay zekâ promptlarını yönetmek için geliştirilmiş modern, hızlı ve çevrimdışı öncelikli bir masaüstü uygulaması.
</p>

<p align="center">
  <img width="1920" alt="CodeSnip uygulama önizlemesi" src="https://github.com/user-attachments/assets/1e01968b-ef57-46bb-a8e7-743f0b2e65e5">
</p>

---

## Genel Bakış

**CodeSnip**, geliştiricilerin ve yapay zekâ meraklılarının kod parçacıklarını, terminal komutlarını ve promptlarını düzenlemesine ve yeniden kullanmasına yardımcı olmak için geliştirilmiş Electron tabanlı bir masaüstü uygulamasıdır.

Kategoriler oluşturun, koleksiyonunuzda arama yapın, kodları anında kopyalayın ve Base64 kodlamasıyla parçacıklarınızı paylaşın. CodeSnip, uygulama verilerini yerel olarak saklayarak kişisel koleksiyonunuzun cihazınızda kalmasını sağlar.

## Özellikler

- **Kod Parçacığı Yönetimi:** Yeniden kullanılabilir kod parçacıklarınızı düzenleyin ve yönetin.
- **Spotlight Araması:** Sezgisel arayüzü sayesinde içeriklerinizi hızlıca bulun.
- **Hızlı İşlemler:** Desteklenen kısayollar aracılığıyla doğrudan yeni parçacıklar ekleyin ve mevcut olanlara erişin.
- **Kod Parçacığı Paylaşımı:** Base64 kodlaması kullanarak parçacık verilerinizi paylaşın.
- **Çok Dilli Arayüz:** Türkçe, İngilizce ve İspanyolca dil desteği.
- **Kategori Yönetimi:** Kod parçacıklarınızı kategorilere ayırarak düzenli tutun.
- **Yerel Depolama:** Koleksiyonunuzu kendi cihazınızda saklayın.
- **Çevrimdışı Öncelikli Tasarım:** Temel işlevler internet bağlantısı olmadan çalışacak şekilde tasarlanmıştır.
- **Liquid Glass Arayüzü:** Sadelik ve kullanılabilirliğe odaklanan modern bir masaüstü arayüzü.

> [!NOTE]
> CodeSnip, yerel veri depolama ve çevrimdışı kullanım için tasarlanmıştır. Varsa harici kaynaklara bağlı özellikler internet bağlantısı gerektirebilir.

## Kurulum

### Gereksinimler

- [Node.js](https://nodejs.org/) v18 veya üzeri
- npm
- Git

### 1. Depoyu klonlayın

```bash
git clone https://github.com/CodeSnip-DevTeam/CodeSnip.git
```

### 2. Proje dizinine girin

```bash
cd CodeSnip
```

### 3. Bağımlılıkları yükleyin

```bash
npm install
```

### 4. Uygulamayı derleyin

```bash
npm run dist
```

> [!TIP]
> Derleme komutu başarısız olursa `package.json` dosyasında tanımlanan scriptleri kontrol edin ve gerekli tüm bağımlılıkların yüklü olduğundan emin olun.

## Ekran Görüntüleri

<p align="center">
  <img width="1920" alt="CodeSnip ekran görüntüsü 1" src="https://github.com/user-attachments/assets/e31ec191-3f60-4b64-9a4b-7a8306fd653d">
  <br><br>
  <img width="1920" alt="CodeSnip ekran görüntüsü 2" src="https://github.com/user-attachments/assets/83036436-5c32-43c4-aa88-24eea23bbb24">
</p>

## Klavye Kısayolları

| Kısayol | Açıklama |
|---|---|
| `Ctrl + Shift + S` | CodeSnip'i ön plana getirir ve Spotlight aramasını açar. Uygulama arka plandayken de çalışır. |
| `Ctrl + Space` | Uygulama etkinken Spotlight aramasını açar veya kapatır. |
| `Esc` | Açık olan Spotlight arama panelini kapatır. |
| `Space` | Seçili arama sonucu için Quick Look önizlemesini açar. |
| `Yukarı / Aşağı Ok` | Spotlight arama sonuçları arasında gezinir. |
| `Enter` | Seçilen kodu ana arama çubuğuna aktarır veya desteklenen hızlı ekleme işlemini gerçekleştirir. |

> [!NOTE]
> Kısayolların kullanılabilirliği mevcut uygulama durumuna ve işletim sistemine bağlı olarak değişebilir.

## Kullanılan Teknolojiler

- [Electron](https://www.electronjs.org/)
- JavaScript
- HTML5
- CSS3
- [Node.js](https://nodejs.org/)

## Yol Haritası

- [x] **v1.0** — İlk sürüm
- [x] **v1.1** — Hata düzeltmeleri ve favoriler
- [x] **26Q2 (v2.0)** — Spotlight, kod parçacığı paylaşımı ve yeniden tasarlanan Liquid Glass arayüzü
  - [x] **26Q2.5** — JSON dışa aktarma/ içe aktarma, Spotlight iyileştirmeleri ve sürüm adlandırma güncellemesi
- [x] **26Q3** — Linux desteği, görünüm iyileştirmeleri, özelleştirme ve kategori yönetimi
  - [x] **26Q3.1** — Kritik hata düzeltmeleri
  - [x] **26Q3.5** — Önemli hata düzeltmeleri, İspanyolca dil desteği, açık tema iyileştirmeleri ve görsel yenileme
  - [ ] **26Q3.6** — Bakım güncellemeleri, hata düzeltmeleri ve kararlılık iyileştirmeleri
- [ ] **26Q4** — Uygulama optimizasyonu, kaynak yönetimi iyileştirmeleri ve Slackware ile Gentoo dahil olmak üzere genişletilmiş macOS/Linux desteği
- [ ] **27Q1** — Eklenti sistemi, kod önizleme, büyük performans iyileştirmeleri ve **BÜYÜK** bir sürpriz
- [ ] **27Q2** — Geliştirici ekosisteminin genişletilmesi, Eklenti Mağazası, manuel eklenti kurulumu, Geliştirici API'si ve gelişmiş kod parçacığı düzenleme
- [ ] **27Q3** — İsteğe bağlı bulut senkronizasyonu, cihazlar arası veri yönetimi, yerel öncelikli depolama, otomatik yedeklemeler ve senkronizasyon çakışmalarının çözümü
- [ ] **27Q4** — Yapay zekâ entegrasyonu, yerel yapay zekâ modeli desteği, harici yapay zekâ API entegrasyonları, akıllı kod kategorilendirme ve gelişmiş prompt yönetimi

> [!NOTE]
> Yol haritası mevcut geliştirme planlarını temsil eder ve öncelikler değiştikçe güncellenebilir. İlgili sürüm yayımlanana kadar hiçbir özellik tamamlanmış veya kullanıma sunulmuş sayılmaz. Bulut senkronizasyonu ve yapay zekâ entegrasyonları isteğe bağlı olarak sunulacak şekilde tasarlanmıştır.

## Katkıda Bulunma

Katkılarınızı, hata bildirimlerinizi ve önerilerinizi bekliyoruz.

### Hata Bildirme

1. Aynı hatanın daha önce bildirilmediğinden emin olmak için mevcut [Issues](https://github.com/CodeSnip-DevTeam/CodeSnip/issues) kayıtlarını kontrol edin.
2. Yeni bir issue oluşturun.
3. Sorunu ve yeniden oluşturmak için gereken adımları açıkça açıklayın.

### Kod Katkısı

1. Depoyu Fork edin.
2. Yeni bir özellik dalı oluşturun:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Değişikliklerinizi kaydedin:

   ```bash
   git add .
   git commit -m "Describe your changes"
   ```

4. Dalınızı GitHub'a gönderin:

   ```bash
   git push origin feature/your-feature
   ```

5. Bir Pull Request oluşturun.

## Lisans

CodeSnip, [MIT Lisansı](LICENSE) kapsamında dağıtılmaktadır.

## Geliştirici Ekibi

[CodeSnip Geliştirme Ekibi](https://github.com/CodeSnip-DevTeam)

---

<p align="center">
 CodeSnip | Kodlarını her zaman elinin altında tutmak isteyen geliştiriciler için geliştirildi.
</p>
