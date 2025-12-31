# 🎓 BTK Akademi: C# & Veri Yapıları Uzmanlık Yolculuğu

<div align="center">

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

</div>

<div align="center">
  <h3>👨‍💻 Bahattin Yunus Çetin</h3>
  <p>IT Architect | University Student</p>
  <a href="https://linkedin.com/in/bahattinyunus">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/bahattinyunus">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

---

## 📖 Proje Hakkında

Bu depo, **BTK Akademi** tarafından sunulan kapsamlı **C# Programlama** ve **Veri Yapıları & Algoritmalar** eğitimleri sırasında geliştirilen projeleri, teorik notları ve pratik uygulamaları içeren devasa bir arşivdir. 

Buradaki kodlar, basit "Hello World" örneklerinden başlayıp, kurumsal mimari prensiplerine (N-Tier Architecture, SOLID, AOP) uygun profesyonel projelere kadar uzanan bir öğrenme serüvenini temsil eder.

## 🚀 Kurs İçeriği ve Modüller

Bu repo iki ana disiplini kapsamaktadır:

### 1. [BTK C# ile Nesne Yönelimli Programlama (45 Saat)](./BTKcSharpCourse_45hours/)
C# dilinin derinlemesine incelendiği, .NET ekosistemine hakimiyet sağlayan ana modüldür. Sıfırdan başlayarak ileri seviye backend geliştirme tekniklerini içerir.

*   **🧱 Temeller:** Değişkenler, Döngüler, Koşullar, Metotlar.
*   **🏗️ OOP (Nesne Yönelimli Programlama):** 
    *   **Classes (Sınıflar):** Nesne modelleme.
    *   **Interfaces (Arayüzler):** Gevşek bağımlılık (Loose Coupling) ve sözleşmeler.
    *   **Inheritance (Kalıtım):** Kod tekrarını önleme ve hiyerarşi.
    *   **Abstract Classes:** Soyutlamalar.
*   **🛠️ İleri Seviye Konular:**
    *   **Generics & Collections:** Tip güvenli listeler ve sözlükler.
    *   **Delegates & Events:** Olay tabanlı programlama.
    *   **Reflection & Attributes:** Çalışma zamanı tip bilgisi ve meta veriler.
    *   **Exception Handling:** Profesyonel hata yönetimi.
*   **🗄️ Veri Erişimi (Data Access):** ADO.NET ve Entity Framework (ORM) ile veritabanı operasyonları.
*   **🏛️ Mimari Projeler:** `RecapDemo1` ve `RecapDemo2` gibi katmanlı mimari ve interface kullanımını pekiştiren gerçek hayat senaryoları.

### 2. [BTK Veri Yapıları ve Algoritmalar (19 Saat)](./dataStructsCourseBtk_19hours/)
Yazılım mühendisliğinin temeli olan veri yapıları ve algoritmaların C# ile implementasyonunu içerir. Algoritmik düşünme becerisini geliştirmeyi hedefler.

*   **Diziler (Arrays) & Listeler (Lists):** Veri saklamanın temelleri.
*   **Yığın (Stack) & Kuyruk (Queue):** LIFO ve FIFO prensipleri.
*   **Bağlı Listeler (Linked Lists):** Tek ve Çift Yönlü Bağlı Listeler.
*   **Ağaçlar (Trees):** Binary Search Trees (BST) ve gezinti algoritmaları.
*   **Sıralama Algoritmaları (Sorting):** Bubble Sort, Selection Sort, Insertion Sort.
*   **Arama Algoritmaları (Searching):** Linear Search, Binary Search.

---

## 🛠️ Teknik Yetkinlikler & Araçlar

Bu repodaki çalışmalar aşağıdaki teknolojiler ve araçlar kullanılarak geliştirilmiştir:

| Kategori | Teknoloji / Araç |
|----------|------------------|
| **Programlama Dili** | C# 10.0+ |
| **Framework** | .NET 6 / .NET 7 |
| **Veritabanı** | Microsoft SQL Server (LocalDB) |
| **ORM** | Entity Framework Core |
| **IDE** | Visual Studio 2022 |
| **Versiyon Kontrol** | Git & GitHub |

---

## 🏃‍♂️ Kurulum ve Çalıştırma

Projeleri yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1.  **Repoyu Klonlayın:**
    ```bash
    git clone https://github.com/bahattinyunus/btk-c-sharp-course.git
    cd btk-c-sharp-course
    ```

2.  **Visual Studio ile Açın:**
    *   İlgili klasöre gidin (örneğin `BTKcSharpCourse_45hours`).
    *   `CSharpCourse.sln` çözüm dosyasını Visual Studio 2022 ile açın.

3.  **Bağımlılıkları Yükleyin:**
    *   Solution Explorer'da çözüm üzerine sağ tıklayın ve "Restore NuGet Packages" seçeneğini seçin.

4.  **Veritabanını Hazırlayın (Gerekirse):**
    *   `Entity Framework` içeren projeler için `Package Manager Console` üzerinden `Update-Database` komutunu çalıştırarak veritabanını oluşturun (LocalDB kullanıyorsanız connection string'i kontrol edin).

5.  **Projeyi Çalıştırın:**
    *   Çalıştırmak istediğiniz projeyi "Set as Startup Project" olarak ayarlayın ve `F5`'e basın.

---

## 🌟 Öne Çıkan Özellikler

*   **Temiz Kod (Clean Code):** Değişken isimlendirmelerinden metod yapılarına kadar okunabilirlik ön planda tutulmuştur.
*   **SOLID Prensipleri:** Özellikle ileri seviye modüllerde SOLID prensiplerine uygun mimari yapılar kurulmuştur.
*   **Modüler Yapı:** Her konu kendi klasörü ve projesi altında izole edilmiştir, böylece konular birbirine karışmaz.

---

## 🤝 İletişim

Sorularınız, önerileriniz veya işbirliği için benimle iletişime geçmekten çekinmeyin:

Bahattin Yunus Çetin  
📧 [LinkedIn](https://linkedin.com/in/bahattinyunus)

---
*Bu proje, BTK Akademi eğitim serisinin bir parçası olarak geliştirilmiştir ve sürekli güncellenmeye devam edecektir.*
