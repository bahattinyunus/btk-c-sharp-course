# 🎓 BTK Akademi: C# & Veri Yapıları Uzmanlık Yolculuğu ve Mimari Manifesto

<div align="center">

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Architecture](https://img.shields.io/badge/Software-Architecture-orange?style=for-the-badge&logo=codeigniter&logoColor=white)
![Data Structures](https://img.shields.io/badge/Data-Structures-blue?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

</div>

<div align="center">
  <h3>👨‍💻 Bahattin Yunus Çetin</h3>
  <p>IT Architect | University Student | Software Craftsman</p>
  <p><em>"Kod yazmak sadece bilgisayara emir vermek değildir; karmaşık problemleri zarif, sürdürülebilir ve ölçeklenebilir yapılara dönüştürme sanatıdır."</em></p>
  <a href="https://linkedin.com/in/bahattinyunus">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/bahattinyunus">
    <img src="https://img.shields.io/badge/GitHub-Follow-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

---

## 📖 Projenin Felsefesi ve Vizyonu

Bu depo, sıradan bir kod arşivi olmanın çok ötesindedir. **BTK Akademi** bünyesinde, sektörün duayenlerinden Engin Demiroğ rehberliğinde gerçekleştirilen, toplamda 60 saati aşan **C# Programlama** ve **Veri Yapıları & Algoritmalar** eğitimlerinin, yaşayan bir yazılım mimarisine dönüşmüş halidir. 

Buradaki her bir satır kod, sadece "çalışsın yeter" mantığıyla değil, **"Clean Code" (Temiz Kod)** felsefesi, **SOLID** prensipleri ve kurumsal yazılım geliştirme standartları gözetilerek inşa edilmiştir. Basit bir konsol uygulamasından,Dependency Injection konteynerini simüle eden karmaşık yapılara kadar uzanan bu serüven, bir yazılımcının "Junior" seviyesinden "Architect" bakış açısına evrilme sürecini belgeler. Projeler, spagetti kodun kaosundan uzaklaşıp, modülerliğin ve sürdürülebilirliğin düzenine doğru atılan kararlı adımları temsil eder.

## 🚀 Derinlemesine Modül Analizi

Repo, yazılım mühendisliğinin iki temel ayağı üzerine kurulmuş devasa bir kütüphanedir: Mimari Tasarım ve Algoritmik Yetkinlik.

### 1. [BTK C# ile Nesne Yönelimli Programlama ve Mimari Tasarım (45 Saat)](./BTKcSharpCourse_45hours/)
Bu modül, C# dilini sadece bir araç olarak değil, bir düşünce sistemi olarak ele alır. .NET ekosisteminin derinliklerine inilerek, kurumsal düzeyde backend sistemlerin nasıl kurgulanması gerektiği incelenir.

*   **🧱 Temellerin Ötesi (Beyond Basics):** Değişkenler ve döngüler sadece syntatic sugar olarak değil, bellek yönetimi (Stack vs Heap) ve performans (Boxing/Unboxing) perspektifinden ele alınmıştır.
*   **🏗️ OOP Felsefesi (The Philosophy of OOP):** 
    *   **Classes & Encapsulation:** Veriyi koruma sanatı. Bir sınıfın neden sadece tek bir sorumluluğu olmalı (SRP)?
    *   **Interfaces & Polymorphism:** Gevşek bağımlılık (Loose Coupling) neden hayati önem taşır? Interface'ler ile sistemin "plug-and-play" hale getirilmesi.
    *   **Inheritance vs Composition:** Kalıtımın doğru ve yanlış kullanımları. "Is-a" ve "Has-a" ilişkilerinin derin analizi.
*   **🛠️ İleri Seviye Mühendislik (Advanced Engineering):**
    *   **Generics & Type Safety:** Tip güvenliğinin çalışma zamanı hatalarını (Runtime Errors) derleme zamanına (Compile Time) çekmekteki rolü.
    *   **Delegates & Events:** Observer tasarım deseninin (Design Pattern) C# dilindeki doğal implementasyonu. Sistemin asenkron ve olay tabanlı (Event-Driven) tepkiler vermesini sağlamak.
    *   **Reflection & Attributes:** Kodun çalışma zamanında kendini analiz etmesi. Aspect Oriented Programming (AOP) için zemin hazırlama (Örn: Validation, Logging, Caching aspect'leri).
*   **🏛️ Mimari Projeler (Architectural Projects):** `RecapDemo` serisi, katmanlı mimarinin (N-Tier Architecture), Business-Data Access ayrımının ve Entity Framework ile modern veritabanı yönetiminin canlı kanıtıdır.

### 2. [BTK Veri Yapıları ve Algoritmik Düşünce (19 Saat)](./dataStructsCourseBtk_19hours/)
İyi bir mimar, aynı zamanda sistemin kaynaklarını en verimli kullanan kişidir. Bu modül, kodun "Time Complexity" (Zaman Karmaşıklığı) ve "Space Complexity" (Alan Karmaşıklığı) analizlerini içerir.

*   **Veri Yapıları Simülasyonu:** Hazır kütüphaneleri kullanmak yerine, `LinkedList`, `Stack`, `Queue` ve `Binary Search Tree` yapıları sıfırdan pointer mantığıyla (referanslar üzerinden) inşa edilmiştir. Bu, "arka planda neler dönüyor?" sorusunun cevabıdır.
*   **Algoritmik Verimlilik:** Milyonlarca verinin olduğu bir senaryoda `Linear Search` kullanmanın felaketini ve `Binary Search` veya `Hash Table` kullanmanın mucizesini matematiksel olarak kanıtlar (Big O Notation).
*   **Sıralama Stratejileri:** Quick Sort ve Merge Sort gibi "Divide and Conquer" (Böl ve Yönet) algoritmalarının rekürsif (öz-yinelemeli) yapısı ile bellek üzerindeki dansı.

---

## 🛠️ Teknoloji Yığını ve Araç Seti

Bu proje, modern yazılım geliştirme süreçlerinde standart kabul edilen, endüstriyel güce sahip araçlarla geliştirilmiştir:

| Alan | Araç / Teknoloji | Açıklama |
|------|------------------|----------|
| **Core Language** | **C# 10.0+** | Modern sentaks, pattern matching ve record tipleri ile güçlendirilmiş yapı. |
| **Framework** | **.NET 6 / .NET 7** | Cross-platform çalışma yeteneği ve yüksek performanslı runtime (CLR). |
| **Database** | **MSSQL (LocalDB)** | İlişkisel veritabanı yönetim sistemlerinin (RDBMS) endüstri standardı. |
| **Data Access** | **Entity Framework Core** | Code-First yaklaşımı ile veritabanı şemasını koddan türetme gücü. |
| **Environment** | **Visual Studio 2022** | Gelişmiş debugger, intellisense ve refactoring araçları. |
| **Version Control** | **Git** | Dağıtık versiyon kontrolü ve kod tarihçesi yönetimi. |

---

## 🏃‍♂️ Profesyonel Geliştirme Ortamı Kurulumu

Bu repoyu sadece indirmekle kalmayın, onu bir laboratuvar ortamı gibi kurarak deneyimleyin:

1.  **Repository Klonlama:**
    ```bash
    git clone https://github.com/bahattinyunus/btk-c-sharp-course.git
    cd btk-c-sharp-course
    ```

2.  **Solution Analizi:**
    *   Visual Studio 2022 ile `CSharpCourse.sln` dosyasını açın.
    *   **Solution Explorer** penceresinde projelerin modüler yapısını inceleyin. Her bir proje referansının mimari bir amaca hizmet ettiğini göreceksiniz.

3.  **Bağımlılık Yönetimi:**
    *   Projedeki dış kütüphaneler (NuGet paketleri) otomatik olarak restore edilmelidir. Eğer edilmezse terminalden `dotnet restore` komutunu çalıştırarak tüm eksik paketleri tamamlayın.

4.  **Veritabanı Migrasyonları:**
    *   `EntityFrameworkDemo` projesi Code-First yaklaşımını kullanır. `Package Manager Console` üzerinden `Update-Database` komutunu vererek veritabanının sıfırdan, model sınıflarına uygun şekilde oluşturulmasını izleyin.

---

## 🌟 Neden Bu Repo? (Kazanımlar)

Bu repo, "Youtube tutorial" seviyesindeki yüzeysel bilgi yığınından sıyrılıp, gerçek mühendislik pratiklerine odaklanır:
*   **Spagetti Koddan Arınma:** `new` anahtar kelimesini kullanmaktan neden kaçınmalıyız? (Dependency Injection'a giriş).
*   **Sürdürülebilirlik:** Bir kodu 6 ay sonra okuduğunuzda (veya başkası okuduğunda) hala anlaşılabilir olması için gereken isimlendirme standartları.
*   **Test Edilebilirlik:** Kodun birim testlere (Unit Tests) uygun yazılması için gereken soyutlama seviyesi.

---

## 🤝 İletişim ve İşbirliği

Yazılım, paylaşarak büyüyen bir ekosistemdir. Bu mimari yolculuk hakkındaki fikirleriniz, eleştirileriniz veya katkılarınız benim için değerlidir.

**Bahattin Yunus Çetin**  
*Mimar, Öğrenci, Kaşif*  
📧 [LinkedIn Profilim](https://linkedin.com/in/bahattinyunus) üzerinden profesyonel ağımıza katılın.

---
> *"Mükemmellik, eklenecek bir şey kalmadığında değil, çıkarılacak bir şey kalmadığında elde edilir." - Antoine de Saint-Exupery*
