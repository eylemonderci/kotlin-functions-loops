
---


### 📄 **README.md**
```markdown
# Kotlin Functions & Loops

Bu proje, **Kotlin dilinde döngü yapıları** (`for`, `while`) ve **fonksiyon tanımlama biçimlerini** içermektedir.  
Fonksiyonların parametre alması, değer döndürmesi, varsayılan parametreler ve döngülerin farklı kullanımları örneklerle anlatılmıştır.

---

##  İçerik Özeti

- `for`, `while`, `downTo` ve `until` döngüleri
- Parametreli & parametresiz fonksiyonlar
- Geriye değer döndüren fonksiyonlar
- Varsayılan parametre (default parameter)
- Kullanıcıdan alınan aralıkta koşullu sayıları bulma
- Basit kullanıcı doğrulama fonksiyonu (`islem_login`)
- Matematiksel işlemler fonksiyonu (`mat_islemler`)

---

##  Amaç

Bu proje, **fonksiyon yapısını ve döngü mantığını** kavratmayı hedefler.  
Öğrencilerin, Kotlin'de modüler kod yazma pratiği kazanması amaçlanmıştır.

---

##  Kullanılan Teknolojiler

- Kotlin (JVM)
- IntelliJ IDEA / Android Studio

---

##  Dosya Bilgisi

- **Dosya Adı:** `Kod1.kt`  
- **Paket:** `com.example.ybshafta3`

---

##  Örnek Fonksiyon

```kotlin
fun mat_islemler(sayi1: Int, sayi2: Int, sayi_islem: Int) {
    when (sayi_islem) {
        1 -> println("$sayi1 + $sayi2 = ${sayi1 + sayi2}")
        2 -> println("$sayi1 - $sayi2 = ${sayi1 - sayi2}")
        3 -> println("$sayi1 * $sayi2 = ${sayi1 * sayi2}")
        4 -> println("$sayi1 / $sayi2 = ${sayi1 / sayi2}")
        else -> println("Hatalı değer girdiniz!")
    }
}
