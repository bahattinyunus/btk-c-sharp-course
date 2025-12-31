# 📊 BTK Akademi: Yeni Başlayanlar İçin Veri Yapıları ve Algoritmalar

<div align="center">
  <img src="https://img.shields.io/badge/Algoritmalar-Kritik-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Veri%20Yap%C4%B1lar%C4%B1-Temel-blue?style=for-the-badge" />
</div>

Bu bölüm, yazılımın "mutfağı" olarak nitelendirilen **Veri Yapıları ve Algoritmalar** konusunu ele alır. 19 saatlik bu eğitim serisi boyunca, verinin bellekte nasıl tutulduğu, nasıl işlendiği ve performansın (Big O Notation) nasıl optimize edildiği C# dili ile uygulamalı olarak işlenmiştir.

---

## 🧠 İçerik Haritası

Projeler `Console Application` formatında geliştirilmiş olup, her biri belirli bir veri yapısını veya algoritmayı temsil eder.

### 1. Temel Veri Yapıları (Data Structures)
*   **Array & ArrayList:** Sabit ve dinamik boyutlu dizilerin farkları, bellek maliyetleri.
*   **Linked List (Bağlı Listeler):**
    *   *Singly Linked List:* Tek yönlü veri akışı.
    *   *Doubly Linked List:* Çift yönlü referanslar, ekleme/silme maliyetleri.
*   **Stack (Yığın):** LIFO (Last In First Out) prensibi. Tarayıcı geçmişi veya geri alma (undo) işlemleri mantığı.
*   **Queue (Kuyruk):** FIFO (First In First Out) prensibi. Yazıcı kuyrukları veya bilet sıraları.
*   **Tree (Ağaçlar):** Hiyerarşik veri yapıları.
    *   *Binary Search Tree (BST):* Arama işlemlerini logaritmik zamanda yapma `O(log n)`.

### 2. Algoritmalar (Algorithms)
*   **Sorting (Sıralama):** Veriyi belirli bir düzene sokma.
    *   *Bubble Sort:* En basit ama en maliyetli `O(n^2)`.
    *   *Selection Sort:* Seçerek sıralama.
    *   *Insertion Sort:* Araya ekleyerek sıralama.
    *   *Merge Sort & Quick Sort:* Böl ve yönet (Divide and Conquer) prensibi ile yüksek performans.
*   **Searching (Arama):**
    *   *Linear Search:* Tüm elemanları tek tek gezme.
    *   *Binary Search:* Sıralı dizide ortadan ikiye bölerek arama (Çok hızlı).

---

## 🔬 Neden Önemli?

Sadece kod yazmak değil, **doğru kodu yazmak** için bu kavramlar şarttır.
*   Hangi durumda `List` yerine `LinkedList` kullanılmalı?
*   Milyonlarca veriyi sıralarken neden `Bubble Sort` kullanılmaz?
*   Bir arama işlemi milisaniyeler sürerken diğeri neden saniyeler sürer?

Bu repodaki kodlar bu soruların cevabını pratik uygulamalarla vermektedir.

---
[🔙 Ana Sayfaya Dön](../README.md)
