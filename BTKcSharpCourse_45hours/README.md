# 💻 BTK Akademi: C# ile Nesne Yönelimli Programlama (45 Saat)

<div align="center">
  <img src="https://img.shields.io/badge/Focus-Object%20Oriented%20Programming-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Level-Beginner%20to%20Advanced-orange?style=for-the-badge" />
</div>

Bu bölüm, Engin Demiroğ eğitmenliğinde gerçekleştirilen 45 saatlik efsanevi C# kampının tüm kodlarını ve projelerini içerir. Kurs, "spagetti kod" yazmaktan kaçınıp, kurumsal standartlarda, sürdürülebilir ve test edilebilir yazılım geliştirme yetkinliği kazandırmayı amaçlar.

---

## 🗂️ Modül Detayları

Aşağıda, çözüm içerisindeki klasörlerin ve projelerin ne amaçla oluşturulduğu detaylandırılmıştır:

### 🟢 Başlangıç Seviyesi (Temeller)
*   **TypesAndVariables:** Value types (int, double, bool) ve Reference types farkları, bellek yönetimi (Stack vs Heap).
*   **Conditionals:** `if-else`, `switch-case` blokları ve `ternary operator` kullanımı.
*   **Loops:** `for`, `while`, `do-while` ve `foreach` döngüleri ile iterasyon mantığı.
*   **Arrays:** Tek boyutlu ve çok boyutlu dizilerle çalışma.
*   **Methods:** Parametreli metotlar, `ref` ve `out` keyword'leri, method overloading.

### 🟡 Orta Seviye (OOP Temelleri)
*   **Classes:** Sınıf yapısı, özellikler (properties), kapsülleme (encapsulation).
*   **Constructors:** Kurucu metotlar ve nesne başlatma süreçleri.
*   **Interfaces:** Arayüzler ile soyutlama, bağımlılıkları yönetme ve polimorfizm temelleri. **En kritik konulardan biridir.**
*   **Inheritance:** Kalıtım, `base` keyword'ü ve hiyerarşik yapı kurma.
*   **AbstractClasses:** Tamamlanmamış metotlar ve ortak operasyonların yönetimi.
*   **VirtualMethods:** Metot ezme (overriding) işlemleri.

### 🔴 İleri Seviye (Profesyonel Teknikler)
*   **InterfacesDemo & RecapDemo1:** Öğrenilenlerin gerçek hayat senaryosunda (örneğin bir müşteri yönetim sistemi) uygulanması. Interface'lerin neden "class"lardan daha kritik olduğunun kanıtı.
*   **Generics:** Tip güvenli (`Type-Safe`) kod yazma, `List<T>`, `Dictionary<TKey, TValue>` yapıları ve Generic Constraints (`where T : class, new()`).
*   **Attributes & Reflection:** Kodun kendisine çalışma zamanında erişme, meta veri ekleme. Validasyon kuralları oluşturmak için kullanıldı.
*   **Delegates & Events:** Metot referansları, kendi event'lerimizi oluşturma.
*   **Exceptions:** `try-catch-finally` blokları ve özel hata sınıfları (`Custom Exceptions`) oluşturma.

### 💾 Veri Erişimi ve Mimari
*   **AdoNetDemo:** Ham SQL sorguları ile veritabanına erişim (Eski ama temeli anlamak için gerekli).
*   **EntityFrameworkDemo:** Modern ORM aracı ile veritabanı işlemleri. CRUD operasyonları, LINQ sorguları.
*   **RecapDemo2:** Kursun final projesi niteliğinde. Katmanlı mimari benzeri bir yapı ile loglama, veritabanı erişimi ve iş kurallarının ayrıştırılması.

---

## 💡 Neler Öğrendim?

Bu modülü tamamlayarak şunları kazandım:
1.  **Interface Segregation:** Yazılımı lego parçaları gibi tasarlamayı.
2.  **Dependency Injection:** Bağımlılıkları new'lemek yerine dışarıdan enjekte etmeyi.
3.  **ORM Mantığı:** SQL yazmadan veritabanı ile nesne tabanlı konuşmayı.
4.  **Clean Code:** "Çalışıyorsa dokunma" değil, "Daha iyi nasıl yazılabilir?" felsefesini.

---
[🔙 Ana Sayfaya Dön](../README.md)
