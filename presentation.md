---
marp: true
paginate: false
---

# **Domain Driven Design 101**
Metin İrden
![bg contain opacity:50% blur:6px](assets/logo.jpg)

---

> Yazılımın kalbi, kullanıcısı için domain ile ilgili problemlemleri çözebilme yeteneğidir.
## **Eric Evans**

---

![bg contain](assets/big-blue-book.jpg)

---

Domain-Driver Design (**DDD**) kompleks domain problemlerine sahip yazılımları geliştirmek için bir dil ve domain merkezli bir yaklaşımdır. DDD terimi Eric Evans tarafından “**Domain-Driven Design: Tackling Complexity in the Heart of Software**” kitabında ortaya konmuştur.

DDD hem teknik hem de iş alanlarında karmaşıklığı sahip yazılımları üreten ekiplerin başarıya odaklanması için bazı pattern ve prensiplerden oluşur. 


![bg contain right:28%](assets/ec-ac.jpg)

---

Yazılımın sahip olduğu kompleksite, domain'den katılsal olarak gelen kompleksite ile teknik kompleksitenin birleşmesi sonucu ortaya çıkar.

![bg contain left:40%](assets/complex-domain-software-manage.jpg)

---

#### Kompleks Problemleri Domain Modelleri Kullanarak Çözün

Bir domain modeli gerçekliği değil, bir perspektifi ifade eder. Bu perspektif ise çözülmek istenen problemdir. Bu modelin çeşitli ifadeleri olan kod, diyagram, döküman ise aynı dil ile bağlıdır.

---

Kullanışlılığı, problemleri çözmek için karmaşık mantığı ve ilkelerini temsil etmesi becerisinden gelir.

Model, yalnızca yaratılan uygulama bağlamındaki sorunları çözmek için ilgili olan detayları içerir.

Yeni use case'ler domain'e dahil oldukça, geçerli kalabilmesi için sürekli olarak gelişmeye ihtiyacı vardır.

![bg contain right:55%](assets/complex-problem.jpg)

---

![bg contain left:60%](assets/domain-model.jpg)

- **İlk İyi Fikrinizde Durmayın.**
* **Her yeni problem ile birlikte modelinizi sorgulayın.**
* **Gerçek Hayatı Modellemeyin.**

---

> Yazılım projelerinin en karmaşık kısmı domain'in kendisini anlamaktır.
#### **Eric Evans**

---

#### Ubiquitous Language Kullanarak Model Dizayn Etmek

Yazılım çözümleri genellikle kötü iletişim ve domain ile teknik dil arasındaki terminoloji farklılıklarından dolayı başarısız sonuçlanır.

---

![bg contain](assets/use-of-ul.jpg)

---

Ubiquitous Language, teknik ve domain çeviri maliyetini en aza indirir ve tüm ifadeleri ''true model'' olarak da bilinen kod modeline bağlar. Paylaşılan bir dil, modelleme sırasında keşiflere de yardımcı olur ve bu, domain'e derinlemesine bir hakimiyet oluşturabilir.

---

![bg contain](assets/ubiquitious-language.jpg)

---

<!-- TODO: Öncesinde modeli implement edin? -->

#### Kodu Modeli Açıkça İfade Eden Şekilde Yazın

Ubiquitous Language modelin kod implementasyonu yapılırken class isimlerinde, property'lerde ve metod isimlendirmelerinde aynı şekilde kullanılmalıdır. DDD'nin sürekli gelişmesi modeli bu ortak dili kullanmaktan geçmektedir.

---

![bg contain left:55%](assets/domain-consept.jpg)

> Herhangi bir programcı, bilgisayarın anlayabileceği şekilde kod yazabilir. İyi programcılar ise insanların anlayabileceği kodlar yazar.
#### **Martin Fowler**

---

#### İşbirlikçi ve Sürekli Gelişen Modelleme

İşbirlikçi modellemenin en büyük yararlarından biri iş birimi tarafından sürekli olarak geri bildirim alıyor olmaktır. Sürekli geri bildirim alıyor olmak, development takımının modelde neyin önemli olup olmadığını fark etmesi için oldukça önemlidir.

---

![bg contain](assets/collaborative-modelling.png)

---

#### Karışık ve Büyük Modelleri Bounded Context'lere Ayırın

---

#### Bounded Contextleri Bir Araya Getirirek Uygulamaları Oluşturun

---

#### DDD'nin Göze Çarpan Noktaları

---

> # Teşekkürler :rocket: