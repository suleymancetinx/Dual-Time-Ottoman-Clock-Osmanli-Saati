<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Orbitron&weight=700&size=35&center=true&vCenter=true&width=600&height=80&color=1572B6&lines=Osmanlı+Zaman+Pusulası;Dual-Time+Ottoman+Clock;Inspired+by+Johann+Meyer" alt="Typing Greeting">
</div>

<div align="center">
  <a href="https://suleymancetinx.github.io/osmanli-zaman-pusulasi/" target="_blank">
    <img alt="Live Demo" src="https://img.shields.io/badge/Canli_Deneyim-Goster-1572B6?style=for-the-badge&logo=google-chrome&logoColor=white">
  </a>
</div>

---

# 🕰️ Osmanlı Zaman Pusulası (Dual-Time Ottoman Clock)

Bu proje, geç Osmanlı döneminin estetik anlayışını modern web teknolojileriyle harmanlayarak, kullanıcıya aynı anda hem **Alafranga (Avrupa/Zevalî)** hem de **Alaturka (Ezanî/Gurubî)** zamanı gösteren interaktif bir dijital saat arayüzüdür.

## 📖 Bir İmtiyazın Hikayesi: Johann Meyer'in İzinde

Bu projenin temeli, 19. yüzyılın en büyük mühendislik meydan okumalarından birine dayanmaktadır. 

Sultan II. Abdülhamid Han'ın hizmetinde sarayda görevli Alman saat ustası **Johann Meyer**, Avrupa'daki saat fabrikalarının "imkansız" dediği bir sorunu çözmek için 8 yılını feda etti: *Güneşin batışına göre kendini her gün otomatik olarak ayarlayan bir saat geliştirmek.*

1886 yılında Meyer, bu devrim niteliğindeki "Ezanî Saat" mekanizmasını tamamlayarak Sultan'a takdim etti. Meyer, saati sunarken şu tarihi sözleri not düşmüştür:
> "Avrupa'daki saat fabrikatörleri zamanı alaturka olarak göstermek için kendi kendine ayar edilir bir saat imalinin olanaksız olduğunu beyan etmişler iken, bendeniz sekiz sene bu husus hakkında düşünüp uğraştıktan sonra... her gün güneşin batışına bağlı olarak kendi kendine ayar edilir bir saat imaline muvaffak oldum."

Bu dijital uygulama, Meyer'in meşakkatle vücuda getirdiği o mekanik dehanın, 21. yüzyıl yazılım dünyasındaki bir yansımasıdır.

## ✨ Özellikler

- **Çift Zamanlı Gösterim:** Aynı ekranda modern ve geleneksel saati eşzamanlı takip edebilme.
- **Dinamik Alaturka Zamanı:** Namaz vakitleri API'si kullanılarak o günün Akşam Ezanı (güneş batışı) vakti otomatik çekilir ve Alaturka saat tam o an `12:00` olacak şekilde matematiksel olarak hizalanır.
- **Tarihi Estetik:** Rumi desenler, İznik çinisi motifleri ve altın varak görünümlü CSS tasarımları.
- **Osmanlıca Kadran:** Alaturka saat yüzünde döneme uygun olarak Osmanlıca rakamlar (١, ٢, ٣...) kullanılmıştır.
- **Responsive Tasarım:** Masaüstü ekranlarda yan yana ihtişamlı bir görünüm sunarken, mobil cihazlarda dikey (alt alta) düzene geçerek kusursuz bir kullanıcı deneyimi (UX) sağlar.

## 🚀 Kullanılan Teknolojiler

- **HTML5** (Semantik yapı ve erişilebilirlik)
- **CSS3** (Flexbox/Grid, Pseudo-elementler ve UI tasarımı)
- **Vanilla JavaScript (ES6+)** (Zaman hesaplamaları ve DOM manipülasyonu)
- **RESTful API** ([Aladhan API](https://aladhan.com/prayer-times-api) - Güneş batış vakitleri için)

## ⚙️ Kurulum

Bu proje saf (vanilla) web teknolojileri ile inşa edilmiştir.

1. Projeyi bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/suleymancetinx/osmanli-zaman-pusulasi.git](https://github.com/suleymancetinx/osmanli-zaman-pusulasi.git)

2. index.html dosyasını tarayıcınızda açın.

   Geliştirici İmzası
Plaintext
_____       _                                
       / ____|     | |                               
      | (___  _   _| | ___ _   _ _ __ ___   __ _ _ __  
       \___ \| | | | |/ _ \ | | | '_ ` _ \ / _` | '_ \ 
       ____) | |_| | |  __/ |_| | | | | | | (_| | | | |
      |_____/ \__,_|_|\___|\__, |_| |_| |_|\__,_|_| |_|
                            __/ |                      
                           |___/                   
Suleyman Cetin tarafından titizlikle tasarlanmıştır.
