---
marp: true
title: DDD-101
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

* **İlk İyi Fikrinizde Durmayın.**
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

Ubiquitous Language, teknik ve domain çeviri maliyetini en aza indirir ve tüm ifadeleri "true model" olarak da bilinen kod modeline bağlar. Paylaşılan bir dil, modelleme sırasında keşiflere de yardımcı olur ve bu, domain'e derinlemesine bir hakimiyet oluşturabilir.

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

To build effective and maintainable software for complex domains you need a dedicated team of software experts working in a iterative development cycle. But as Eric Evans observed in his book Domain-Driven Design, technical practice and expertise will only get you so far. Without a focus on the most important parts of the problem domain, an environment where you can collaborate with domain experts, an obsession with a ubiquitous language and the understanding that concepts need to be understood in context, you may end up with a ball of mud when juggling technical and domain complexity.

---

#### FOCUS EFFORT WHERE IT MATTERS

Not all of a system will be well designed and often, it isn’t cost effective to strive for this. Instead identify the core domain and the core complexity and focus effort there. The core domain is the reason you are writing the software in the first place. DDD is expensive and time consuming so use it where it matters. Sometimes it’s better just to get on and code, rather than looking for complexity where there is none. Not all projects will have suitable complexity that warrants the effort of DDD. If you have an appreciation for the problem space and an empathy for your business you will be in a better position to judge the opportunity cost as you align effort.

---

#### DESIGN A MODEL WITHIN A BOUNDED CONTEXT

When creating a model for a large domain it can lose explicitness if there are multiple teams involved, where different language is used or where concepts mean different things in different contexts. Therefore, just as you distill the problem domain to reveal multiple sub domains, you must also decompose the solution space and develop models within explicit boundaries. Context is everything; context and isolation ensure the integrity of your code. It reduces cognitive load and enables multiple teams to work autonomously.

---

#### BIND EXPRESSIONS OF THE MODEL USING A UBIQUITOUS LANGUAGE

Software projects fail due to poor communication coupled with the overhead of translation between domain and technical terminology. A Ubiquitous Language enables software experts to bind the code model to other expressions of the domain model, such as conversations and diagrams with domain experts, making for more effective communication. Better communication gives you an increased chance to reveal deeper insights in the model. This is why it is vital that the code model is expressed explicitly using the Ubiquitous Language and why it’s important to obsess over language. And remember, a language should be specific to a bounded context.

---

#### COLLABORATE IN LEARNING AND MODELLING

Don’t underestimate the power of collaborative modelling and learning between domain experts and software experts. Knowledge crunching is an ongoing process; collaboration and engagement with the business should not be constrained to the start of a project. Deep insights and breakthroughs only happen after living with the problem through many development iterations. Facilitation patterns to help crunch domain knowledge are extremely important - get good at mining for information and engaging with the business! DDD is the process of learning, refining, experimenting, and exploring in the quest to produce an effective model. It is often said that working software is simply an artifact of learning.

---

> # Teşekkürler :zap: