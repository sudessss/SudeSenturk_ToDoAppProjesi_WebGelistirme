# 🚀 SudeSenturk_WebGelistirmeProjesi_ToDoApp

🔗 **Canlı Uygulama Linki:** [SudeSenturk To-Do App (GitHub Pages)](https://sudessss.github.io/SudeSenturk_ToDoAppProjesi_WebGelistirme/)

### 📋 To-Do App Staj Projesi Hakkında
Bu uygulama, kullanıcıların günlük görevlerini **CRUD** (Create, Read, Update, Delete) prensiplerine uygun olarak yönetebilmesini sağlayan dinamik bir görev yönetim platformudur.

---

### 🖥️ Geliştirme Süreci
* **Yerel Geliştirme:** Kod yazımı, hata ayıklama ve arayüz tasarımı aşamalarını kendi yerel ortamımda yürüttüm.
* **Test ve Kalite:** Uygulamanın farklı senaryolarda (görev ekleme, tamamlama, silme) doğru çalışıp çalışmadığını manuel test süreçleriyle deneyimledim.
* **Modern Araçlar:** Vite ve React gibi modern geliştirme araçlarını kullanarak, gerçek dünya projelerinde kullanılan iş akışlarını bizzat uygulama ve pekiştirme fırsatı buldum.

---

### 🛠️ Kullanılan Teknolojiler & Özellikler
* **Frontend:** React + Tailwind CSS
* **Versiyon Kontrol:** Git & GitHub
* **Veri Saklama:** LocalStorage ile veri persist etme (sayfa yenilense bile görevler kaybolmuyor)
* **Yeni Kullanıcı Ekleme:** Form üzerinden kullanıcı/görev ekleme ✅
* **Kullanıcı Silme:** İstenmeyen görevleri kaldırma ✅

---

### 📁 Proje Klasör Yapısı (Folder Structure)
Uygulama, sürdürülebilirlik ve kodun okunabilirliğini artırmak amacıyla modüler bir mimari ile inşa edilmiştir:

```text
todo-app/
├── src/
│   ├── components/           # Tekrar kullanılabilir arayüz bileşenleri
│   │   ├── ProgressCircle.jsx# Görev tamamlanma oranını gösteren grafik
│   │   ├── TaskCard.jsx      # Her bir görevin görsel kart yapısı
│   │   └── EditModal.jsx     # Görev düzenleme için açılır pencere
│   ├── pages/                # Sayfa bazlı ana bileşenler
│   │   └── Dashboard.jsx     # Uygulamanın ana yönetim ekranı
│   ├── hooks/                # Özel React Hook'ları
│   │   └── useLocalStorage.js# Verilerin tarayıcıda saklanmasını sağlayan mantık
│   ├── interfaces/           # Veri tipleri ve modellemeler
│   │   └── Task.js           # Görev (Task) objesinin veri yapısı
│   ├── styles/               # Tasarım ve stil dosyaları
│   │   ├── global.css        # Genel uygulama stilleri
│   │   └── index.css         # Tailwind veya standart CSS tanımları
│   ├── utils/                # Yardımcı fonksiyonlar (Helpers)
│   │   ├── api.ts            # API entegrasyonu (Fetch/Axios)
│   │   └── storage.ts        # LocalStorage yönetim yardımcıları
│   ├── App.jsx               # Ana uygulama bileşeni ve yönlendirme
│   └── main.jsx              # React giriş noktası (Entry Point)
├── public/                   # Statik varlıklar (Favicon, resimler vb.)
├── vite.config.js            # Vite konfigürasyonu ve Build ayarları
└── package.json              # Proje bağımlılıkları ve scriptleri

🔄 Kurulum ve Yayına Alma Süreci
Projeyi yerel ortamda çalıştırmak ve GitHub Pages üzerinde canlıya almak için takip ettiğim teknik iş akışı şu şekildedir:

1. Proje Dizinine Giriş
Terminal üzerinden proje klasörüne erişim sağladım:

Bash
cd todo-app
2. Bağımlılıkların Yüklenmesi
Projenin ihtiyaç duyduğu tüm paketleri (React, Tailwind, dnd-kit vb.) yerel ortama kurdum:

Bash
npm install
3. Yerel Geliştirme Sunucusunu Başlatma
Geliştirme sürecinde anlık önizleme yapmak için Vite sunucusunu kullandım:

Bash
npm run dev
4. Canlıya Alma (Production Deploy)
Uygulamayı derleyip GitHub Pages üzerinde yayınlamak için hazırladığım deploy script'ini çalıştırdım:

Bash
npm run deploy
Bu komut arka planda önce projeyi optimize ederek derler (npm run build), ardından oluşan dist klasörünü gh-pages branch'ine aktararak yayını tamamlar.


👨‍💻 Proje Künyesi
Geliştirici: Sude Şentürk
Proje Adı: SudeSenturk_WebGelistirmeProjesi_ToDoApp
Durum: Production Ready (Canlıda)
Canlı Link: [SudeSenturk To-Do App (GitHub Pages)](https://sudessss.github.io/SudeSenturk_ToDoAppProjesi_WebGelistirme/)

ℹ️ Hakkında (About)
Bu proje, modern web geliştirme standartlarını öğrenmek amacıyla geliştirilmiş, React ve Vite ekosistemine dayalı bir görev yönetim uygulamasıdır. Başlangıç aşamasında eğitim materyallerinden faydalanılmış olsa da; projenin deployment (yayına alma) süreçleri, terminal üzerinden Netlify CLI yönetimi ve klasör yapısı optimizasyonları tamamen şahsım tarafından yürütülmüştür.

---


### 📸 Uygulama Görselleri

| Dashboard Görünümü | Veri Düzenleme | Görev Yönetimi |
|:---:|:---:|:---:|
| ![Dashboard](https://raw.githubusercontent.com/sudessss/SudeSenturk_ToDoAppProjesi_WebGelistirme/main/assests/ToDoApp_IlkGosterim.png) | ![Düzenleme](https://raw.githubusercontent.com/sudessss/SudeSenturk_ToDoAppProjesi_WebGelistirme/main/assests/ToDoApp_VeriDuzenleme.png) | ![Yönetim](https://raw.githubusercontent.com/sudessss/SudeSenturk_ToDoAppProjesi_WebGelistirme/main/assests/ToDoApp_eklenengoreviduzenlemevecopeatma.png) |
| **Genel Özet** | **Tüm Gosterimler** | **Video Rehber** |
| ![Özet](https://raw.githubusercontent.com/sudessss/SudeSenturk_ToDoAppProjesi_WebGelistirme/main/assests/ToDoApp_IkıncıGosterim_VeriEklenilmis.png) | ![Hepsi](https://raw.githubusercontent.com/sudessss/SudeSenturk_ToDoAppProjesi_WebGelistirme/main/assests/ToDoApp_HepsiSayfasında_TumGosterimler.png) | [▶️ Videoyu İzle](https://github.com/sudessss/SudeSenturk_ToDoAppProjesi_WebGelistirme/blob/main/assests/ToDoApp_KullanimVideosu.mov) |
