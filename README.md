# Nesne Yönelimli Programlama
Bu repository, nesne yönelimli programlamaya (NYP) giriş yapmak isteyen yazılımcılar için hazırlanmış bir kaynaktır. Nesne yönelimli programlama, yazılım geliştirmede yaygın olarak kullanılan bir paradigmadır ve birçok programlama dilinde desteklenmektedir.



## Yazarlar

- [@halitozer](https://github.com/halitozerr)
- [@linkedin](https://www.linkedin.com/in/mustafa-halit-ozer/)



## Konular
 - [Nesne Yönelimli Programlama Nedir? ](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-nesne-y%C3%B6nelimli-programlama-nedir)
    - [Sınıf Hiyerarşileri Nedir?](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-s%C4%B1n%C4%B1f-hiyerar%C5%9Fileri-nedir-%E2%84%B9%EF%B8%8F)
    - [Nesne Yönelimli Programlama İlkeleri](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-nesne-y%C3%B6nelimli-programlama-i%CC%87lkeleri-%E2%84%B9%EF%B8%8F)
        - [Soyutlama (abstraction)](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-soyutlama-abstraction-%E2%84%B9%EF%B8%8F)
        - [Kapsülleme (encapsulation)](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-kaps%C3%BClleme-encapsulation-%E2%84%B9%EF%B8%8F)
        - [Miras (inheritance)](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-miras-inheritance-%E2%84%B9%EF%B8%8F)
        - [Polimorfizm (Polymorphism)](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-polimorfizm-polymorphism-%E2%84%B9%EF%B8%8F)
    - [Nesneler Arası İlişkiler](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-nesneler-aras%C4%B1-i%CC%87li%C5%9Fkiler-%E2%84%B9%EF%B8%8F)
        - [Inheritance (Kalıtım)](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-kal%C4%B1t%C4%B1m-inheritance)
        - [Implementation](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-association-ba%C4%9Flant%C4%B1)
        - [Association (Bağlantı)](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-dependency-ba%C4%9F%C4%B1ml%C4%B1l%C4%B1k)
        - [Dependency (Bağımlılık)](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-composition-bile%C5%9Fim)
        - [Composition (Bileşim)](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-composition-bile%C5%9Fim)
        - [Aggregation (İçerme)](https://github.com/halitozerr/NesneYonelimliProgramlama/blob/main/README.md#-aggregation-i%CC%87%C3%A7erme)




# ✨ Nesne Yönelimli Programlama Nedir? 


Nesne yönelimli programlama (NYP), yazılım geliştirme yaklaşımlarından biridir. Bu yaklaşım, programlamayı gerçek dünyadaki nesnelerin birleşimi olarak ele alır. NYP'de, bir programı oluşturan birbirleriyle ilişkili nesnelerin oluşturulması ve bu nesneler arasındaki etkileşimlerin tanımlanması önemlidir.

➕ **Nesne yönelimli programlama, bazı temel kavramlar üzerine kuruludur. Bunlar:**

1. 📦	**Sınıflar:** Sınıflar, nesnelerin taslaklarıdır. Her sınıf, belirli bir davranışı ve özellikleri tanımlar. Örneğin, "Araba" sınıfı, arabaların genel özelliklerini (renk, hız, model vb.) ve davranışlarını (ileri gitme, durma, dönme vb.) tanımlar.

2.	📦	**Nesneler:** Nesneler, sınıflardan türetilen somut örneklerdir. Her nesne, belirli bir sınıfa aittir ve sınıfın özelliklerini ve davranışlarını miras alır. Örneğin, "BMW" nesnesi, "Araba" sınıfına ait özellikleri ve davranışları içerir.

3.	📦	**Miras (kalıtım):** Miras, bir sınıfın başka bir sınıftan özelliklerini ve davranışlarını miras alabilmesini sağlar. Bu, kod tekrarını azaltır ve daha düzenli bir yapı sağlar. Örneğin, "BMW" sınıfı, "Araba" sınıfından türetilebilir ve "Araba" sınıfının özelliklerini ve davranışlarını miras alabilir.

4.	📦	**Nesne tabanlı programlama:** NYP, nesneler arasındaki etkileşimleri vurgulayan bir yaklaşımdır. Nesne tabanlı programlama, nesneler arasında veri ve işlevsellik taşıyan mesajlaşma ve yöntem çağrıları ile etkileşimi sağlar.

NYP, kodun daha anlaşılır, bakımı kolay ve tekrar kullanılabilir olmasını sağlar. Büyük ve karmaşık projelerde ölçeklenebilirlik sağlar ve yazılımı modüler hale getirir. Bu nedenle, birçok programlama dilinde Nesne Yönelimli Programlama kullanılmaktadır. Örnek olarak, Java, C++, Python gibi dillerin nesne yönelimli programlamaya odaklandığını söyleyebiliriz.





## ⚡ Sınıf Hiyerarşileri Nedir? ℹ️

Sınıf hiyerarşileri, nesne yönelimli programlamada sınıflar arasındaki ilişkileri ve miras (kalıtım) yapısını tanımlayan yapısal bir özelliktir. Bir sınıf hiyerarşisi, sınıflar arasındaki genelleme ve özelleştirme ilişkilerini yansıtır.

Bir sınıf hiyerarşisi, genel sınıf veya üst sınıf (base class veya superclass) olarak adlandırılan bir ana sınıfın altında yer alan bir veya daha fazla özel sınıf veya alt sınıf (derived class veya subclass) içerir. Alt sınıflar, üst sınıfın özelliklerini ve davranışlarını miras alır ve bunları genişletebilir veya değiştirebilir. Bu, kod tekrarını azaltır ve daha düzenli bir programlama yapısı sağlar.

Sınıf hiyerarşileri, "is-a" ilişkisini ifade eder. Bir alt sınıf, üst sınıfın bir türüdür. Örneğin, "Hayvan" sınıfı üst sınıf olarak düşünülebilir ve "Köpek" ve "Kedi" gibi alt sınıflar bu üst sınıfı genişletebilir. Bu durumda, "Köpek", "Hayvan" sınıfının bir türü olduğu için "Köpek, Hayvan'dır" şeklinde ifade edilebilir.

Sınıf hiyerarşileri, programlarda modülerlik ve ölçeklenebilirlik sağlar. Yeni sınıfların eklenmesi veya var olan sınıfların değiştirilmesi gerektiğinde, bu hiyerarşi sayesinde yapısal olarak düzenli bir şekilde yapılabilir. Ayrıca, kodun daha anlaşılır ve bakımı kolay hale gelir, çünkü bir üst sınıfta yapılan değişiklikler alt sınıflara otomatik olarak yansır.

Sınıf hiyerarşileri, nesne yönelimli programlamadaki birçok programlama dilinde desteklenir. Örneğin, Java'da sınıf hiyerarşileri "extends" anahtar kelimesiyle tanımlanırken, C++'da "inheritance" mekanizması kullanılır.




## ⚡ Nesne Yönelimli Programlama İlkeleri ℹ️

➕ **Nesne yönelimli programlama (NYP) ilke ve prensipleri şunlardır:**

1.	📦	**Soyutlama (Abstraction):** Soyutlama, bir nesnenin önemli özelliklerini vurgulayarak detaylardan soyutlama yapmaktır. Bu ilke, karmaşık bir sistemi daha anlaşılır hale getirir ve gereksiz karmaşıklığı önler. Soyutlamada, bir sınıfın yalnızca gerekli özelliklerini ve davranışlarını tanımlamak önemlidir.
2.	📦	**Kapsülleme (Encapsulation):** Kapsülleme, veri ve ilgili işlevlerin birlikte gruplandırılmasını sağlar. Bir sınıf, verileri (alanlar) ve bu verilere erişimi kontrol eden yöntemleri (metodlar) içerir. Kapsülleme, veri gizliliğini ve güvenliği sağlar, veriye doğrudan erişimi sınırlar ve sınıfın iç yapısını korur.
3.	📦	**Miras (Inheritance):** Miras, bir sınıfın diğer bir sınıftan özelliklerini ve davranışlarını miras alabilmesini sağlar. Alt sınıf (türetilmiş sınıf veya alt sınıf), üst sınıfın (temel sınıf veya üst sınıf) tüm özelliklerini ve davranışlarını miras alır ve bunları genişletebilir veya değiştirebilir. Miras, kod tekrarını azaltır, yeniden kullanılabilirliği artırır ve sınıf hiyerarşilerini oluşturur.
4.	📦	**Polimorfizm (Polymorphism):** Polimorfizm, aynı isimde farklı davranışlara sahip olabilme yeteneğidir. Farklı sınıflar aynı yöntem adını kullanabilir, ancak her sınıf kendi davranışını uygular. Polimorfizm, çok biçimlilik olarak da adlandırılır ve kodun daha esnek ve genel kullanılabilir olmasını sağlar.

➕ **Bu ilkelere ek olarak, nesne yönelimli programlama aşağıdaki prensipleri de destekler:**

1.	📦	**Tek Sorumluluk Prensibi (Single Responsibility Principle):** Her sınıfın yalnızca bir sorumluluğu olmalıdır. Bir sınıfın değişme nedeni yalnızca bir sorumluluğunun değişmesi olmalıdır. Bu prensip, sınıfların daha az bağımlı, daha okunaklı ve daha bakımı kolay olmasını sağlar.
2.	📦	**Açık/Kapalı Prensibi (Open/Closed Principle):** Bir sınıf, değişime kapalı (closed) olmalı, yani mevcut davranışını değiştirmemelidir. Ancak yeni davranışları eklemek için açık (open) olmalıdır. Kodun genişletilebilirliğini sağlar ve mevcut kodun değiştirilmesi gereğini azaltır.
3.	📦	**Liskov İskele İlkesi (Liskov Substitution Principle):** Alt sınıflar, üst sınıfların yerine geçebilmelidir. Yani, bir üst sınıfın nesnesi her zaman alt sınıfların nesnesi olarak kullanılabilmelidir. Bu prensip, programdaki hiyerarşik ilişkilerin sağlam ve tutarlı olmasını sağlar.
4.	📦	**Bağımlılıkların Tersine Çevrilmesi Prensibi (Dependency Inversion Principle):** Modüller arasındaki bağımlılıkların yüksek seviyeli modüllerden düşük seviyeli modüllere doğru değil, her ikisi de soyutlamalara bağımlı hale getirilmesi gerektiğini söyler. Bu prensip, esneklik, yeniden kullanılabilirlik ve kolay bakım sağlar.
Bu prensipler, yazılım tasarımının esnek, ölçeklenebilir, anlaşılır ve bakımı kolay olmasını sağlar. İyi bir nesne yönelimli programlama pratiği için bu prensipleri göz önünde bulundurmak önemlidir.




### ⚡ Soyutlama (abstraction) ℹ️

Soyutlama (abstraction) nesne yönelimli programlamadaki önemli bir ilkedir. Soyutlama, bir nesnenin önemli özelliklerini vurgulayarak detaylardan soyutlama yapmaktır. Yani, bir nesneyi temsil eden veri ve işlevlerin yalnızca gereken kısmını ortaya çıkarmaktır.

Soyutlama, karmaşık bir sistemin anlaşılır ve yönetilebilir olmasını sağlar. Bir sınıf veya nesne oluşturulurken, yalnızca o nesnenin önemli olan özelliklerine ve davranışlarına odaklanılır. Diğer detaylar gizlenir veya arka planda tutulur. Böylece, programcılar ve kullanıcılar yalnızca ilgili bilgilere odaklanabilir ve gereksiz karmaşıklıkla uğraşmak zorunda kalmazlar.

➕ **Soyutlama, iki temel bileşenden oluşur:**

1.	📦	**Veri Soyutlaması:** Bir nesnenin içerdiği verilerin önemli olanlarının belirlenmesidir. Veri soyutlaması, sınıfın alanlarını (properties) belirler. Örneğin, bir Araba sınıfında marka, model, renk gibi özellikler veri soyutlamasına örnek olabilir.

2.	📦	**İşlev Soyutlaması:** Bir nesnenin gerçekleştirdiği işlevlerin (metodlar) önemli olanlarının belirlenmesidir. İşlev soyutlaması, sınıfın metodlarını belirler. Örneğin, bir Araba sınıfında gaz ver, fren yap, direksiyonu çevir gibi işlevler işlev soyutlamasına örnek olabilir.

Soyutlama, sistemdeki farklı nesneler arasında bir arayüz oluşturur. Bu arayüz, nesnelerin nasıl kullanılacağını ve birbiriyle nasıl etkileşimde bulunacağını belirler. Diğer sınıflar veya modüller, sadece bu arayüzle etkileşime geçerek nesnelerle çalışabilirler. Bu, sistemde bağımlılıkların azaltılmasını sağlar ve bir nesnenin iç yapısının değiştirilse bile etkileşim kurulan diğer bileşenlerin bundan etkilenmemesini sağlar.

Soyutlama, programcılara daha yüksek düzeyde düşünme ve tasarlama olanağı sağlar. Karmaşık sistemlerin anlaşılması ve sürdürülmesi kolaylaşır. Ayrıca, kodun yeniden kullanılabilirliğini artırır çünkü soyutlanmış bileşenler, farklı projelerde veya farklı bağlamlarda tekrar kullanılabilir.


## ⌨️ Kullanım/Örnek 

```c#
using System;

public abstract class Hayvan
{
    public abstract void SesCikar();
}

public class Kedi : Hayvan
{
    public override void SesCikar()
    {
        Console.WriteLine("Miyav!");
    }
}

public class Kopek : Hayvan
{
    public override void SesCikar()
    {
        Console.WriteLine("Hav hav!");
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Hayvan kedi = new Kedi();
        Hayvan kopek = new Kopek();

        kedi.SesCikar(); // Kedinin miyav sesi çıkarır
        kopek.SesCikar(); // Köpeğin hav hav sesi çıkarır

        Console.ReadLine();
    }
}

```
Bu örnekte, "Hayvan" adında soyut bir sınıf (abstract class) tanımlanmıştır. Bu sınıf, "SesCikar" adında soyut bir metot içermektedir. Soyut metot, sadece bildirim olarak yer alır ve alt sınıflar tarafından uygulanmak zorundadır.

"Kedi" ve "Kopek" sınıfları, "Hayvan" sınıfından kalıtım alır ve "SesCikar" metotunu uygular. Her iki sınıf da kendi özel "SesCikar" davranışını tanımlamak zorundadır.

Main metodu, "Hayvan" sınıfından referanslarla "Kedi" ve "Kopek" sınıflarından nesneler oluşturur ve "SesCikar" metotlarını çağırır. Bu sayede, her nesne kendi özel "SesCikar" davranışını sergiler.

Sonuç olarak, "Kedi" nesnesi "Miyav!" sesini çıkarırken, "Kopek" nesnesi "Hav hav!" sesini çıkarır.

Bu örnek, soyutlama kavramını göstermektedir. Soyut sınıflar, soyut metotlar aracılığıyla alt sınıflara belirli bir davranışın uygulanmasını zorunlu kılar. Alt sınıflar, soyut metotları kendi ihtiyaçlarına göre gerçekleştirerek soyutlamayı tamamlar. Böylece, farklı alt sınıflar aynı soyutlama aracılığıyla farklı davranışları gerçekleştirebilir.

### ⚡ Kapsülleme (encapsulation) ℹ️

Kapsülleme (encapsulation), nesne yönelimli programlamadaki bir ilkedir ve veri ve ilgili işlevlerin birlikte gruplandırılmasını sağlar. Bir sınıf içinde veriler (alanlar) ve bu verilere erişimi kontrol eden yöntemler (metodlar) bulunur.

Kapsülleme, bir sınıfın iç yapısını gizlemek ve dış dünyaya sadece sınıfın belirli bir arayüzünü sunmak anlamına gelir. Bu, veri gizliliğini sağlar ve sınıfın iç işleyişini korur. Dış dünyadaki diğer kodun doğrudan sınıfın iç verilerine erişmesini veya bunları değiştirmesini engeller.

➕ **Kapsülleme, birçok fayda sağlar:**

1.	📦	**Veri gizliliği ve güvenlik:** Kapsülleme, verilerin sadece sınıfın içinden erişilebilmesini sağlar. Bu, verilerin doğrudan değiştirilmesini veya geçersiz değerler atanmasını engeller. Sınıf, verilere erişim için yöntemler (get/set metodları) sağlar ve bu yöntemler aracılığıyla veriye güvenli bir şekilde erişilebilir.

2.	📦	**Kodun kontrolü:** Kapsülleme, bir sınıfın iç yapısını koruyarak, sınıfın nasıl kullanılacağını kontrol etmeyi sağlar. Yalnızca belirli yöntemlere erişim sağlanarak, sınıfın doğru kullanılmasını sağlar ve hatalı kullanımı önler. Bu da kodun daha güvenilir ve hata ayıklamasının daha kolay olmasını sağlar.

3.	📦	**Kod tekrarının azaltılması:** Kapsülleme, benzer veri yapılarının ve işlevlerin bir araya getirilmesini sağlar. Bu da kodun tekrar kullanılabilirliğini artırır. Bir sınıfı başka bir projede veya farklı bir bağlamda kullanmak istediğinizde, sadece sınıfın arayüzüne (yani yöntemlerine) erişmeniz yeterlidir.

4.	📦	**Nesne yönelimli analiz ve tasarım:** Kapsülleme, nesne yönelimli analiz ve tasarım süreçlerinde önemli bir rol oynar. Sınıflar arasındaki ilişkileri ve etkileşimleri tanımlayarak sistemi daha iyi anlamanızı ve tasarlamanızı sağlar. Sınıfın iç yapısını değiştirmeden dışarıya açık bir arayüz sağlamak, sistemdeki bağımlılıkları azaltır ve modüler bir tasarımı teşvik eder.

Kapsülleme, nesne yönelimli programlamada veri ve işlevsellik arasındaki bağı güçlendirir ve kodun daha düzenli, anlaşılır ve bakımı kolay hale gelmesini sağlar.


## ⌨️ Kullanım/Örnek 

```c#
using System;

public class Calisan
{
    private string ad;
    private int yas;

    public string Ad
    {
        get { return ad; }
        set { ad = value; }
    }

    public int Yas
    {
        get { return yas; }
        set
        {
            if (value >= 18)
                yas = value;
            else
                Console.WriteLine("Çalışan yaş sınırını karşılamıyor!");
        }
    }

    public void BilgileriGoster()
    {
        Console.WriteLine("Ad: " + ad);
        Console.WriteLine("Yaş: " + yas);
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Calisan calisan = new Calisan();
        calisan.Ad = "Ahmet";
        calisan.Yas = 25;

        calisan.BilgileriGoster();

        Console.ReadLine();
    }
}

```
Bu örnekte, "Calisan" adında bir sınıf tanımlanmıştır. Bu sınıf, "ad" ve "yas" adında private (gizli) veri elemanlarına sahiptir. Bu veri elemanlarına erişimi kontrol etmek için public erişim belirleyicili "Ad" ve "Yas" özellikleri (properties) tanımlanmıştır.

"Ad" özelliği, "get" ve "set" erişimcileriyle birlikte tanımlanmıştır. Bu sayede, "Ad" özelliği okunabilir ve yazılabilir hale gelir.

"Yas" özelliği ise biraz daha karmaşık bir şekilde tanımlanmıştır. "set" erişimcisi içinde, veri doğrulama kontrolü yapılmıştır. Eğer atanan değer 18 veya daha büyükse, "yas" veri elemanı güncellenir. Aksi takdirde, bir uyarı mesajı ekrana yazdırılır.

"BilgileriGoster" metodu, "Calisan" sınıfının özelliklerini konsola yazdırır.

Main metodu, "Calisan" sınıfından bir nesne oluşturur ve "Ad" ve "Yas" özelliklerine değerler atar. Ardından "BilgileriGoster" metodu çağrılarak çalışanın bilgileri konsola yazdırılır.

Bu örnekte, "Calisan" sınıfındaki veri elemanları private olarak tanımlanmış ve erişimi kontrol altına alınmıştır. Özellikler aracılığıyla bu verilere erişim ve güncelleme sağlanırken, veri doğrulama gibi kontroller de yapılabilir. Bu sayede, sınıfın iç yapısı gizlenir ve daha güvenli ve tutarlı bir programlama deneyimi sunulur.

### ⚡ Miras (inheritance) ℹ️

Miras (inheritance), nesne yönelimli programlamadaki bir ilkedir ve bir sınıfın diğer bir sınıftan özelliklerini ve davranışlarını miras alabilmesini sağlar. Miras, sınıflar arasında hiyerarşik ilişkilerin kurulmasını ve kodun yeniden kullanılabilirliğini artırır.

Miras, bir üst sınıfın (ebeveyn sınıf veya temel sınıf) tüm özelliklerini ve metotlarını alt sınıflara (çocuk sınıflar veya türetilmiş sınıflar) aktarır. Bu sayede, alt sınıflar, üst sınıfların sahip olduğu özelliklere ve davranışlara erişebilir ve bunları kendi ihtiyaçlarına göre genişletebilir veya değiştirebilir.

➕ **Mirasın temel avantajları şunlardır:**

1.	📦	**Kodun tekrar kullanılabilirliği:** Miras, kod tekrarını önler ve var olan kodu yeniden kullanmayı sağlar. Bir üst sınıfta tanımlanan özellikler ve metotlar, alt sınıflarda yeniden yazılmadan kullanılabilir. Bu, kodun daha az yazılmasını, daha az hata yapılmasını ve daha az zamanda projelerin tamamlanmasını sağlar.

2.	📦	**Sınıf hiyerarşilerinin oluşturulması:** Miras, sınıflar arasında hiyerarşik ilişkilerin kurulmasını sağlar. Üst sınıf, genel bir kavramı temsil ederken, alt sınıflar daha spesifik özellikleri ve davranışları tanımlar. Bu şekilde, sistemdeki nesnelerin ilişkileri daha iyi anlaşılır ve yönetilebilir hale gelir.

3.	📦	**Polimorfizm:** Miras, polimorfizm ilkesini destekler. Polimorfizm, farklı nesnelerin aynı isimli metotları farklı şekillerde uygulayabilmesini sağlar. Bu sayede, alt sınıflar, üst sınıfın metotlarını kendilerine özgü şekilde uygulayabilir ve aynı isimli bir metot çağrıldığında farklı davranışlar sergileyebilirler.

4.	Kodun sürdürülebilirliği ve genişletilebilirliği:** Miras, kodun sürdürülmesini ve genişletilmesini kolaylaştırır. Bir üst sınıfın değişmesi durumunda, bu değişiklik otomatik olarak alt sınıflara yansır. Aynı şekilde, yeni özellikler eklemek veya davranışları değiştirmek istendiğinde, sadece ilgili alt sınıflara müdahale etmek yeterlidir.

➕ **Mirasın dikkat edilmesi gereken bazı noktalar da vardır:**

1.	📦	**Aşırı kullanımın önlenmesi:** Mirasın aşırı kullanımı, sınıflar arasında gereksiz bağımlılıklara ve karmaşıklığa yol açabilir. Sınıf hiyerarşisindeki her alt sınıfın gerçekten üst sınıfın özelliklerini ve davranışlarını miras alması gerektiğinden emin olmak önemlidir. Mantıksal bir ilişki varsa miras kullanılabilir, aksi takdirde başka bir yaklaşım daha uygun olabilir.

2.	📦	**Tek Sorumluluk Prensibi:** Sınıf hiyerarşisindeki sınıfların her birinin yalnızca bir sorumluluğu olması önemlidir. Miras kullanılırken, yeni bir alt sınıf oluşturulurken, yalnızca ilgili özellikler ve davranışlar eklenebilmelidir. Üst sınıftan miras alınan özelliklerin ve davranışların alt sınıflar tarafından anlamlı bir şekilde genişletilmesi ve değiştirilmesi gerekmektedir.

3.	📦	**Çoklu miras:** Bazı dillerde birden fazla üst sınıftan miras alma, yani çoklu miras, desteklenir. Ancak çoklu miras kullanımı karmaşık olabilir ve çakışmalara yol açabilir. Bu nedenle, doğru durumlarda ve dikkatli bir şekilde kullanılmalıdır.

4.	📦	**Alternatiflerin değerlendirilmesi:** Miras, her durumda en iyi çözüm olmayabilir. Bazen, bileşen tabanlı tasarım veya arayüzler kullanmak daha uygun olabilir. Bu nedenle, miras kullanmadan önce alternatif yaklaşımların değerlendirilmesi önemlidir.
Miras, nesne yönelimli programlamada sınıflar arasında ilişkilerin ve kodun yeniden kullanılabilirliğinin sağlanmasında önemli bir rol oynar. Ancak doğru kullanımı ve tasarımı gerektirir. İyi bir sınıf hiyerarşisi oluşturmak için dikkatli düşünmek ve gereksinimleri analiz etmek önemlidir.


## ⌨️ Kullanım/Örnek 

```c#
using System;

public class Arac
{
    protected string marka;
    protected string model;
    protected int yil;

    public Arac(string marka, string model, int yil)
    {
        this.marka = marka;
        this.model = model;
        this.yil = yil;
    }

    public void BilgileriGoster()
    {
        Console.WriteLine("Marka: " + marka);
        Console.WriteLine("Model: " + model);
        Console.WriteLine("Yıl: " + yil);
    }
}

public class Araba : Arac
{
    private int motorHacmi;

    public Araba(string marka, string model, int yil, int motorHacmi) : base(marka, model, yil)
    {
        this.motorHacmi = motorHacmi;
    }

    public void ArabaBilgileriniGoster()
    {
        BilgileriGoster();
        Console.WriteLine("Motor Hacmi: " + motorHacmi + " cc");
    }
}

public class Kamyon : Arac
{
    private int yukKapasitesi;

    public Kamyon(string marka, string model, int yil, int yukKapasitesi) : base(marka, model, yil)
    {
        this.yukKapasitesi = yukKapasitesi;
    }

    public void KamyonBilgileriniGoster()
    {
        BilgileriGoster();
        Console.WriteLine("Yük Kapasitesi: " + yukKapasitesi + " kg");
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Araba araba = new Araba("Ford", "Mustang", 2022, 5000);
        araba.ArabaBilgileriniGoster();

        Console.WriteLine();

        Kamyon kamyon = new Kamyon("Volvo", "FH16", 2021, 20000);
        kamyon.KamyonBilgileriniGoster();

        Console.ReadLine();
    }
}


```

Bu örnekte, "Arac" adında bir üst sınıf (base class) ve "Araba" ile "Kamyon" adında iki alt sınıf (derived class) bulunmaktadır. "Araba" ve "Kamyon" sınıfları, "Arac" sınıfından miras alır.

"Arac" sınıfı, "marka", "model" ve "yil" adında korunan (protected) veri elemanları ve "BilgileriGoster" adında bir metot içerir. Bu metot, araç bilgilerini konsola yazdırır.

"Araba" sınıfı, "Arac" sınıfından kalıtım alır ve ek olarak "motorHacmi" adında bir özel (private) veri elemanına sahiptir. "Araba" sınıfının yapıcı metodu (constructor), "Arac" sınıfının yapıcı metodunu çağırarak ortak özelliklerin ayarlanmasını sağlar. Ayrıca "ArabaBilgileriniGoster" adında bir metot da bulunur. Bu metot, "Arac" sınıfının "BilgileriGoster" metodunu çağırır ve araba özelindeki özellikleri konsola yazdırır.

"Kamyon" sınıfı da "Arac" sınıfından kalıtım alır ve "yukKapasitesi" adında bir özel veri elemanına sahiptir. Yapıcı metodu, "Arac" sınıfının yapıcı metodunu çağırır ve "KamyonBilgileriniGoster" adındaki metot, "Arac" sınıfının "BilgileriGoster" metodunu çağırır ve kamyon özelindeki özellikleri konsola yazdırır.

Main metodu, "Araba" ve "Kamyon" sınıflarından nesneler oluşturur ve ilgili metotları çağırarak araç bilgilerini konsola yazdırır.

Bu örnekte, "Arac" sınıfı ortak özellikleri ve davranışları içerirken, "Araba" ve "Kamyon" sınıfları bu ortak özellikleri miras alarak kendi özel davranışlarını ekleyebilir. Bu sayede kod tekrarından kaçınılır ve farklı araç türleri için özelleştirilmiş sınıflar oluşturulabilir.

### ⚡ Polimorfizm (Polymorphism) ℹ️

Polimorfizm (polymorphism), nesne yönelimli programlamadaki önemli bir ilkedir ve aynı isme sahip olan metotların farklı sınıflar tarafından farklı şekillerde uygulanabilmesini ifade eder. Yani, farklı nesneler aynı isme sahip bir metodu farklı şekillerde gerçekleştirebilir.

Polimorfizm, programlamanın esnekliğini ve genişletilebilirliğini artırır. Ayrıca, kodun daha anlaşılır ve sürdürülebilir olmasını sağlar. Polimorfizm, nesneler arasında bağımlılıkları azaltır ve daha genel ve soyutlanmış bir şekilde programlama yapmamızı sağlar.

➕ **Polimorfizm iki farklı şekilde gerçekleştirilebilir:**

1.	📦	**İstemci Odaklı Polimorfizm (Client-Side Polymorphism):** Bu tür polimorfizm, bir metot çağrıldığında hangi nesnenin metodu çalıştırılacağının çalışma zamanında belirlendiği durumu ifade eder. İstemci, farklı alt sınıfların metotlarını aynı şekilde çağırabilir ve bu metotlar farklı davranışlar sergileyebilir. Çalışma zamanında dinamik bağlama (dynamic binding) kullanılarak hangi metotun çalışacağı belirlenir.

    **Örneğin**, "Hayvan" adında bir üst sınıfımız olsun ve bu sınıftan "Köpek" ve "Kedi" adında iki alt sınıf türetelim. Her iki alt sınıf da "seseÇıkar()" adında bir metoda sahip olsun. İstemci kodunda ise farklı nesneler oluşturulup "seseÇıkar()" metodu çağrılsın. İstemci tarafından çağrılan metot, hangi nesneye bağlı olduğuna bağlı olarak farklı davranışlar sergileyebilir. Örneğin, köpek nesnesi "Hav!" sesi çıkarırken, kedi nesnesi "Miyav!" sesi çıkarabilir.

2.	📦	**Parametrik Polimorfizm (Parametric Polymorphism):** Bu tür polimorfizm, aynı metot ismini ve imzasını kullanarak farklı veri tipleri üzerinde çalışabilme yeteneğini ifade eder. Bu genellikle şablonlar (templates) veya jenerik tipler (generic types) gibi mekanizmalarla gerçekleştirilir. Bu sayede, aynı mantığı farklı veri tipleriyle kullanabiliriz ve kod tekrarını önleyebiliriz.

    **Örneğin**, bir dizi sıralama algoritması düşünelim. Bu algoritma, farklı veri tipleriyle (sayılar, karakterler, dizgeler vb.) çalışabilen ve sıralama işlemini gerçekleştiren bir metot içerebilir. Parametrik polimorfizm kullanarak, bu metotu farklı veri tipleri üzerinde kullanabiliriz. Bu sayede, aynı sıralama mantığını tekrar tekrar yazmak zorunda kalmadan, farklı veri tipleriyle çalışabilen bir algoritma oluşturabiliriz.

    **Örneğin**, bir "Sıralama" sınıfı oluşturalım ve bu sınıfın içinde "sirala" adında bir metot olsun. Bu metot, generic bir veri tipi kabul edecektir. Bu şekilde, bu metotu farklı veri tipleriyle kullanabiliriz. Örneğin, "Integer" tipindeki bir dizi için çağırabiliriz veya "String" tipindeki bir dizi için çağırabiliriz. İçerideki mantık aynı kalır, ancak farklı veri tiplerine uygun şekilde sıralama işlemi gerçekleştirilir.

➕ **Polimorfizm, nesne yönelimli programlamanın güçlü bir özelliğidir ve çeşitli avantajlar sunar:**

1.	📦	**Esneklik ve genişletilebilirlik:** Polimorfizm, programlamanın esnekliğini artırır ve değişikliklere daha kolay adapte olmayı sağlar. Yeni sınıflar eklendiğinde veya mevcut sınıflar değiştirildiğinde, mevcut kodu değiştirmeden farklı davranışlar elde etmek mümkündür.

2.	📦	**Kodun yeniden kullanılabilirliği:** Polimorfizm, kodun yeniden kullanılabilirliğini artırır. Bir metot veya işlev, farklı veri tipleriyle çalışabilen bir şekilde tasarlandığında, aynı kod parçası farklı senaryolarda kullanılabilir.

3.	📦	**Daha anlaşılır kod:** Polimorfizm, kodun daha anlaşılır olmasını sağlar. Aynı ismi taşıyan metotlar, farklı sınıflar tarafından farklı şekillerde gerçekleştirildiği için kodun amacı daha açık bir şekilde ortaya konabilir.

4.	📦	**Daha az bağımlılık:** Polimorfizm, bağımlılıkları azaltır. İstemci kodu, bir nesnenin hangi sınıfa ait olduğunu bilmek zorunda kalmadan, ortak bir arayüz üzerinden işlemlerini gerçekleştirebilir.

➕ **Polimorfizm, nesne yönelimli programlamada birçok fayda sağlar, bunlar arasında:**

1.	📦	**Esneklik ve genişletilebilirlik:** Polimorfizm, bir metodu farklı şekillerde uygulayabilme yeteneği sayesinde programlamanın esnekliğini artırır. Yeni sınıflar eklemek veya mevcut sınıfları değiştirmek, var olan kodu etkilemeden gerçekleştirilebilir.

2.	📦	**Kodun yeniden kullanılabilirliği:** Polimorfizm, farklı sınıflar arasında aynı arayüzü kullanarak kodun yeniden kullanılabilirliğini sağlar. Ortak bir arayüzü uygulayan sınıflar, aynı işlevselliği sağlar ve böylece kod tekrarını önler.

3.	📦	**Dinamik bağlama (Dynamic binding):** Polimorfizm, çalışma zamanında hangi sınıfa ait metotun çağrılacağını belirlemek için dinamik bağlama mekanizmasını kullanır. Bu, nesnelerin gerçek türlerine göre davranışlarının belirlenmesini sağlar. Çalışma zamanında gerçekleşen bu bağlama sayesinde, kodun daha esnek ve uyarlanabilir olmasını sağlar.

4.	📦	**Kodun anlaşılabilirliği:** Polimorfizm, kodun daha anlaşılır ve bakımı daha kolay hale gelmesini sağlar. Aynı ismi taşıyan metotların farklı sınıflar tarafından farklı şekillerde gerçekleştirildiği durumlarda, kodun amacı daha açık bir şekilde ortaya çıkar. İstemci kodu, yalnızca ortak bir arayüzle çalışırken, detaylara inmek zorunda kalmaz.

5.	📦	**Arayüzleri ve soyut sınıfları destekler:** Polimorfizm, arayüzleri ve soyut sınıfları kullanarak genel kodlama standartları oluşturmayı sağlar. Bu, birçok farklı sınıfın aynı arayüzü uygulayabileceği ve bu arayüz üzerinden birleşik bir şekilde kullanılabileceği anlamına gelir.

Polimorfizm, nesne yönelimli programlamanın güçlü bir ilkesidir ve kodun daha esnek, genişletilebilir ve anlaşılır olmasını sağlar. Doğru kullanıldığında, daha sürdürülebilir ve ölçeklenebilir bir kod tabanı oluşturmaya yardımcı olur.


## ⌨️ Kullanım/Örnek 

```c#
using System;

public class Sekil
{
    public virtual void Ciz()
    {
        Console.WriteLine("Bir şekil çiziliyor...");
    }
}

public class Dikdortgen : Sekil
{
    public override void Ciz()
    {
        Console.WriteLine("Dikdörtgen çiziliyor...");
    }
}

public class Ucgen : Sekil
{
    public override void Ciz()
    {
        Console.WriteLine("Üçgen çiziliyor...");
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Sekil sekil1 = new Sekil();
        Sekil sekil2 = new Dikdortgen();
        Sekil sekil3 = new Ucgen();

        sekil1.Ciz();
        sekil2.Ciz();
        sekil3.Ciz();

        Console.ReadLine();
    }
}



```

Bu örnekte, "Sekil" adında bir üst sınıf ve "Dikdortgen" ile "Ucgen" adında iki alt sınıf bulunmaktadır. "Sekil" sınıfının "Ciz" metodu sanal (virtual) olarak işaretlenmiştir.

"Dikdortgen" ve "Ucgen" sınıfları, "Sekil" sınıfından kalıtım alır ve "Ciz" metotunu override ederek kendi özel davranışlarını tanımlar.

Main metodu, "Sekil" sınıfının referanslarıyla "Sekil", "Dikdortgen" ve "Ucgen" sınıflarından nesneler oluşturur. Ardından "Ciz" metotlarını çağırır.

Polimorfizm özelliği sayesinde, her bir nesne kendi türe özgü "Ciz" metodu çalıştırılır. "sekil1.Ciz()" ifadesi, "Sekil" sınıfının "Ciz" metodu çalıştırır ve "Bir şekil çiziliyor..." çıktısını verir. "sekil2.Ciz()" ifadesi, "Dikdortgen" sınıfının override edilmiş "Ciz" metodu çalıştırır ve "Dikdörtgen çiziliyor..." çıktısını verir. Benzer şekilde, "sekil3.Ciz()" ifadesi, "Ucgen" sınıfının override edilmiş "Ciz" metodu çalıştırır ve "Üçgen çiziliyor..." çıktısını verir.

Bu örnekte polimorfizm, farklı nesnelerin aynı metodu farklı şekillerde uygulamasını gösterir. Üst sınıf referansı ile alt sınıflardan oluşturulan nesnelerin, ilgili metotları çağırırken kendi özel davranışlarını sergilemelerine olanak tanır.

## ⚡ Nesneler Arası İlişkiler ℹ️

"Nesneler Arası İlişkiler" kavramı, NYP'nin temel prensiplerinden biridir.

Nesne yönelimli programlama, gerçek dünyadaki nesneleri yazılım geliştirmeye uyarlamak için kullanılan bir yaklaşımdır. Bu yaklaşımda, yazılımı oluşturan birimler "nesne" olarak adlandırılır ve bu nesneler birbirleriyle etkileşim kurabilir.

"Nesneler Arası İlişkiler" dediğimiz şey, nesnelerin birbirleriyle nasıl etkileşimde bulunduğunu ve birbiriyle ilişkili olduğunu ifade eder. Bu ilişkiler, NYP'nin temelini oluşturan sınıf ve nesne kavramları üzerine inşa edilir.

➕ **Nesneler arasındaki ilişkiler, çeşitli şekillerde ifade edilebilir. En yaygın ilişki türleri şunlardır:**

### 📦 Kalıtım (inheritance):
 Nesne yönelimli programlamada önemli bir kavramdır. Kalıtım, bir sınıfın başka bir sınıftan özelliklerini ve davranışlarını miras almasını sağlayan bir ilişkiyi ifade eder. Bu, yazılım geliştirme sürecinde kodun tekrarını azaltır, kodun yeniden kullanılabilirliğini artırır ve daha düzenli bir yapı oluşturur.

Kalıtım, üst sınıf (baz sınıf, temel sınıf veya ana sınıf) ve alt sınıf (türetilmiş sınıf veya alt sınıf) arasında gerçekleşir. Üst sınıf, belirli özelliklere ve davranışlara sahip olan genel bir sınıftır. Alt sınıf ise üst sınıftan türetilmiş ve üst sınıfın özelliklerini ve davranışlarını miras almış olan bir alt kümeyi temsil eder.

Kalıtımın temel amacı, üst sınıfta tanımlanan özellikleri ve davranışları alt sınıflara aktarmaktır. Alt sınıflar, üst sınıftan miras aldıkları özelliklere ve davranışlara sahip olur ve bunları genişletebilir veya değiştirebilir. Bu şekilde, kalıtım hiyerarşisi oluşturulur ve sınıflar arasında bir ilişki kurulur.

➕ **Kalıtımın bazı avantajları şunlardır:**

1. **Kodun tekrarını azaltır:** Ortak özelliklere sahip sınıfları bir üst sınıfta tanımlamak, kodun tekrarını önler. Bu şekilde, kodun yeniden kullanılabilirliği artar ve yazılımın sürdürülebilirliği iyileşir.

2. **Kod organizasyonunu kolaylaştırır:** Kalıtım, kodun daha düzenli ve yapılandırılmış olmasını sağlar. İlgili sınıflar bir hiyerarşi içinde yer alır ve benzer özelliklere sahip sınıflar bir arada gruplanır.

3. **Polimorfizmi destekler:** Polimorfizm, nesnelerin aynı arayüz üzerinden farklı şekillerde davranabilmesini ifade eder. Kalıtım, polimorfizmi destekler ve farklı alt sınıfların aynı metotları farklı şekillerde uygulamasını sağlar. Bu sayede, aynı isme sahip bir metot farklı alt sınıflar için farklı davranışlar sergileyebilir.

Sınıflar arası ilişkileri modellemeyi kolaylaştırır: Kalıtım, sınıflar arasında bir ilişki kurarak daha anlamlı bir yapı oluşturur. Örneğin, "Hayvan" sınıfı üst sınıf olarak tanımlanabilir ve "Köpek" ve "Kedi" gibi alt sınıflar bu üst sınıftan türetilerek ilişkilendirilebilir. Bu şekilde, nesneler arasındaki gerçek dünya ilişkilerini modellemek daha kolay hale gelir.

Kalıtım, yazılım geliştirme sürecinde dikkatli bir şekilde kullanılmalıdır. Kalıtımın aşırı kullanımı, karmaşık ve kırılgan kod yapılarına yol açabilir. İyi bir kalıtım tasarımı için aşağıdaki prensiplere dikkat etmek önemlidir:

İyi bir sınıf hiyerarşisi oluşturmak için doğru seviyede soyutlama yapmak önemlidir. Üst sınıf, genel özelliklere ve davranışlara sahip olmalıdır.
"IS-A" ilişkisine uygunluğu sağlamak önemlidir. Yani, bir alt sınıfın üst sınıfıyla "bir tür" ilişkisi olmalıdır. Örneğin, "Köpek" bir "Hayvan" olduğu için kalıtım ilişkisi doğru olur.
Liskov İlkesi'ne dikkat etmek önemlidir. Bu ilke, alt sınıfların üst sınıfın yerine kullanılabileceği ve beklenen sonuçları üreteceği anlamına gelir.
Kalıtım, nesne yönelimli programlamanın önemli bir parçasıdır ve yazılım tasarımında büyük bir rol oynar. Doğru bir şekilde kullanıldığında, kodun yeniden kullanılabilirliğini artırır, kod organizasyonunu kolaylaştırır ve esnek bir yapı oluşturur.

## ⌨️ Kullanım/Örnek 

```c#
using System;

public class Sekil
{
    protected double alan;

    public void AlanHesapla()
    {
        Console.WriteLine("Alan hesaplanıyor...");
    }
}

public class Dikdortgen : Sekil
{
    private double uzunluk;
    private double genislik;

    public Dikdortgen(double uzunluk, double genislik)
    {
        this.uzunluk = uzunluk;
        this.genislik = genislik;
    }

    public double AlanGetir()
    {
        alan = uzunluk * genislik;
        return alan;
    }
}

public class Kare : Sekil
{
    private double kenarUzunlugu;

    public Kare(double kenarUzunlugu)
    {
        this.kenarUzunlugu = kenarUzunlugu;
    }

    public double AlanGetir()
    {
        alan = kenarUzunlugu * kenarUzunlugu;
        return alan;
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Dikdortgen dikdortgen = new Dikdortgen(5, 3);
        double dikdortgenAlan = dikdortgen.AlanGetir();
        Console.WriteLine("Dikdörtgen Alanı: " + dikdortgenAlan);

        Kare kare = new Kare(4);
        double kareAlan = kare.AlanGetir();
        Console.WriteLine("Kare Alanı: " + kareAlan);

        Console.ReadLine();
    }
}

```

Bu örnekte, "Sekil" adında bir üst sınıf ve "Dikdortgen" ile "Kare" adında iki alt sınıf bulunmaktadır. "Dikdortgen" ve "Kare" sınıfları "Sekil" sınıfından kalıtım alır.

Üst sınıf olan "Sekil" sınıfı, "alan" adında bir korunan bir değişken ve "AlanHesapla" adında bir metot içerir. Alt sınıflar olan "Dikdortgen" ve "Kare" sınıfları, "alan" değişkenini ve "AlanHesapla" metotunu miras alır.

"Dikdortgen" sınıfı, uzunluk ve genişlik parametrelerini alan bir yapıcı metot ve "AlanGetir" adında bir metot içerir. Bu metot, dikdörtgenin alanını hesaplar ve geri döndürür.

"Kare" sınıfı ise kenar uzunluğunu alan bir yapıcı metot ve "AlanGetir" adında bir metot içerir. Bu metot, karenin alanını hesaplar ve geri döndürür.

Main metodu, hem "Dikdortgen" hem de "Kare" sınıflarından nesneler oluşturur ve alanlarını hesaplar. Sonuçlar konsola yazdırılır.

Bu örnek, "Dikdortgen" ve "Kare" sınıflarının "Sekil" sınıfından özellikleri ve davranışları kalıtım yoluyla aldığını göstermektedir. Kalıtım sayesinde kod tekrarından kaçınılır ve ortak işlevler üst sınıfta tanımlanırken alt sınıflar özel işlevlerini yerine getirebilir.


### 📦 Implementation:

"Implementation" terimi, nesne yönelimli programlamada bir sınıfın veya arayüzün tanımlanan özelliklerini ve davranışlarını gerçekleştiren kodun yazılması anlamına gelir. Başka bir deyişle, bir sınıfın veya arayüzün tanımını uygulayan, işlevlerini yerine getiren ve özelliklerini kullanılabilir hale getiren kodun oluşturulmasıdır.

Bir sınıf veya arayüz tanımlandığında, bu tanımlama sadece bir şablondur ve doğrudan kullanılamaz. Bu şablondan nesneler oluşturmak veya arayüzleri uygulamak için gerçek bir uygulama yapılması gerekir. Bu uygulama, tanımlanan özelliklerin ve davranışların kod ile gerçekleştirilmesini içerir.

Implementation aşamasında, tanımlanan sınıf veya arayüzde yer alan metotların gövdeleri (implementasyonları) yazılır ve özelliklerin değer atamaları yapılır. Bu şekilde, sınıf veya arayüzün işlevsel hale gelmesi sağlanır.

Bir sınıfın implementation aşamasında, üyeler (değişkenler ve metotlar) tanımlanır ve işlevlerini yerine getirecek kod yazılır. Bu, sınıfın özelliklerini taşıyan değişkenlerin değerlerini depolamak, metotların belirli işlemleri gerçekleştirmek ve nesne üzerinde işlemler yapmak için kullanılır.

Bir arayüzün implementation aşamasında ise arayüzde tanımlanan metotların kodları yazılır ve belirli bir sınıf tarafından uygulanır. Arayüz, belirli bir davranışı veya yeteneği taşıyan metotların bir sözleşmesini tanımlar ve bir sınıf bu arayüzü uyguladığında, tanımlanan metotları gerçekleştirir.

Implementation aşaması, bir sınıfın veya arayüzün kullanılabilir hale gelmesini sağlar. Bu aşama, tanımlanan özelliklerin ve davranışların gerçek dünyadaki işlemleri yürüten kod ile ilişkilendirilmesini sağlar. Böylece, sınıf veya arayüzün işlevselliği kullanılarak nesneler oluşturulabilir ve arayüzler uygulanabilir hale gelir.

Implementation, yazılım geliştirme sürecinde önemli bir adımdır ve programın çalışması için gereklidir. Doğru bir implementation, tanımlanan sınıf veya arayüzün beklenen işlevselliği yerine getirmesini sağlar ve yazılımın doğru çalışmasını sağlar.

## ⌨️ Kullanım/Örnek 

```c#
using System;

public interface ISesCikarabilir
{
    void SesCikar();
}

public class Kedi : ISesCikarabilir
{
    public void SesCikar()
    {
        Console.WriteLine("Miyav!");
    }
}

public class Kopek : ISesCikarabilir
{
    public void SesCikar()
    {
        Console.WriteLine("Hav hav!");
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Kedi kedi = new Kedi();
        Kopek kopek = new Kopek();

        kedi.SesCikar(); // Kedinin miyav sesi çıkarır
        kopek.SesCikar(); // Köpeğin hav hav sesi çıkarır

        Console.ReadLine();
    }
}

```

Bu örnekte, "ISesCikarabilir" adında bir arayüz tanımlanmıştır. Bu arayüz, "SesCikar" adında bir metot bildirimini içermektedir.

"Kedi" ve "Kopek" sınıfları, "ISesCikarabilir" arayüzünü uygulayan sınıflardır. Her iki sınıf da "SesCikar" metotunu uygulamak zorundadır.

Main metodu, "Kedi" ve "Kopek" sınıflarından nesneler oluşturur ve "SesCikar" metotlarını çağırır. Bu sayede, her nesne kendi özel "SesCikar" davranışını sergiler.

Sonuç olarak, "Kedi" nesnesi "Miyav!" sesini çıkarırken, "Kopek" nesnesi "Hav hav!" sesini çıkarır.

Bu örnek, bir arayüzün nasıl uygulandığını ve her bir sınıfın kendi implementation'ını sağladığını göstermektedir. Arayüzler, bir sınıfın belirli bir davranışı uygulamasını garanti altına alır ve farklı sınıfların aynı arayüzü kullanarak farklı davranışlar sergilemesini sağlar.


### 📦 Association (Bağlantı):

Nesne Yönelimli Programlamada Association (Bağlantı), sınıflar arasında ilişki ve işbirliği kurmayı sağlayan bir kavramdır. İki veya daha fazla sınıf arasında bir ilişki kurulmasıyla, bu sınıflar arasında veri ve işlem paylaşımı gerçekleştirilebilir.

Association, sınıflar arasındaki bağı gösterir. Bu bağlantılar, bir sınıfın diğer sınıfı kullanmasını, içermesini veya ilişkili olmasını ifade edebilir. Association ilişkisi, bir sınıfın başka bir sınıfı referans etmesiyle oluşur.

Association örneği olarak, "Müşteri" ve "Sipariş" sınıflarını düşünelim. Her bir müşteri, bir veya daha fazla sipariş verebilir ve her bir sipariş belirli bir müşteriye ait olabilir. Bu durumda "Müşteri" ve "Sipariş" sınıfları arasında bir association ilişkisi vardır. Müşteri sınıfı, Sipariş sınıfına referans verebilir veya Sipariş sınıfını kullanabilir.

Association ilişkisi, bir sınıfın başka bir sınıfı kullanmasını gerektirebileceği gibi, çok yönlü de olabilir. Örneğin, "Okul" ve "Öğrenci" sınıfları arasında bir association ilişkisi olduğunu düşünelim. Bir okul, birçok öğrenciyi içerebilirken, bir öğrenci sadece bir okula ait olabilir. Bu durumda "Okul" ve "Öğrenci" sınıfları arasında bir birliktelik (aggregation) ilişkisi bulunur.

Association, sınıflar arasında veri ve işlem paylaşımını sağlar ve nesne yönelimli programlamada sınıflar arasındaki ilişkileri modellemek için kullanılır. Bu sayede daha karmaşık sistemlerin tasarımı ve uygulaması daha yapılandırılmış ve esnek bir şekilde gerçekleştirilebilir.

## ⌨️ Kullanım/Örnek 

```c#
using System;
using System.Collections.Generic;

public class Musteri
{
    public int MusteriId { get; set; }
    public string Ad { get; set; }
    public List<Siparis> Siparisler { get; set; }

    public Musteri()
    {
        Siparisler = new List<Siparis>();
    }

    public void SiparisVer(Siparis siparis)
    {
        Siparisler.Add(siparis);
        Console.WriteLine("Yeni sipariş verildi. Sipariş ID: " + siparis.SiparisId);
    }
}

public class Siparis
{
    public int SiparisId { get; set; }
    public string UrunAdi { get; set; }
    public double Fiyat { get; set; }
}

public class Program
{
    public static void Main(string[] args)
    {
        Musteri musteri = new Musteri();
        musteri.MusteriId = 1;
        musteri.Ad = "Ahmet Yılmaz";

        Siparis siparis1 = new Siparis();
        siparis1.SiparisId = 101;
        siparis1.UrunAdi = "Telefon";
        siparis1.Fiyat = 2500;

        Siparis siparis2 = new Siparis();
        siparis2.SiparisId = 102;
        siparis2.UrunAdi = "Bilgisayar";
        siparis2.Fiyat = 5000;

        musteri.SiparisVer(siparis1);
        musteri.SiparisVer(siparis2);

        Console.ReadLine();
    }
}


```

Bu örnekte, "Musteri" ve "Siparis" sınıfları arasında bir association ilişkisi vardır. "Musteri" sınıfı, "Siparis" sınıfına ait nesneleri içeren bir liste olan "Siparisler" özelliğine sahiptir. Ayrıca, "Musteri" sınıfının "SiparisVer" metodu, bir sipariş alır ve bu siparişi "Siparisler" listesine ekler.

Main metodu, bir müşteri ve iki sipariş oluşturur. Ardından, "musteri.SiparisVer" metoduyla her bir siparişi müşteriye ekler. Bu sayede, "Musteri" sınıfı ile "Siparis" sınıfı arasındaki association ilişkisi kullanılarak müşteriye ait siparişler yönetilebilir.

Bu örnek, association (bağlantı) ilişkisini göstermektedir. "Musteri" sınıfı, "Siparis" sınıfına referans verebilen bir özelliğe sahiptir ve bu sayede müşterinin siparişlerini yönetebilir.


### 📦 Dependency (Bağımlılık):

Nesne Yönelimli Programlamada Dependency (Bağımlılık), bir sınıfın başka bir sınıfa veya bileşene olan bağımlılığını ifade eder. Bir sınıfın içerisinde başka bir sınıfı kullanması veya bir bileşene erişmesi durumunda, bu sınıfın bağımlılığı söz konusudur.

Dependency (Bağımlılık), bir sınıfın başka bir sınıfı kullanması veya ona erişmesi gerektiği anlamına gelir. Örneğin, bir sınıfın bir veritabanı işlemi yapabilmesi için bir veritabanı bağlantısına ihtiyaç duyması durumunda, bu sınıf veritabanı bağlantısına bağımlıdır. Bu durumda, sınıfın çalışabilmesi için veritabanı bağlantısının sağlanması gerekmektedir.

Bağımlılık, bir sınıfın içerisinde başka bir sınıfın nesnesini oluşturma veya referansını alarak kullanma şeklinde gerçekleşebilir. Bağımlılığın olduğu durumlarda, bir sınıfın değişiklik yapılması veya geliştirilmesi gerektiğinde, bağımlı olduğu sınıfların da etkilenebileceği unutulmamalıdır. Bu nedenle, bağımlılıklar dikkatlice yönetilmeli ve sınıflar arasındaki bağımlılıklar minimuma indirilmelidir.

Dependency (Bağımlılık) yönetimi, nesne yönelimli programlamada önemli bir konudur. İyi bir bağımlılık yönetimi, kodun daha esnek, sürdürülebilir ve test edilebilir olmasını sağlar. Bağımlılıklar, genellikle arayüzler (interface) veya soyut sınıflar (abstract class) kullanılarak yönetilir. Bu sayede, sınıflar arasındaki bağımlılıklar azaltılır ve değişikliklerin etkileri kontrol altında tutulabilir.

## ⌨️ Kullanım/Örnek 

```c#
using System;

public interface ILogger
{
    void Log(string message);
}

public class FileLogger : ILogger
{
    public void Log(string message)
    {
        Console.WriteLine("File Logger: " + message);
    }
}

public class DatabaseLogger : ILogger
{
    public void Log(string message)
    {
        Console.WriteLine("Database Logger: " + message);
    }
}

public class UserManager
{
    private ILogger logger;

    public UserManager(ILogger logger)
    {
        this.logger = logger;
    }

    public void RegisterUser(string username)
    {
        // Kullanıcı kaydı işlemleri
        logger.Log("User registered: " + username);
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        ILogger logger = new FileLogger();
        UserManager userManager = new UserManager(logger);
        userManager.RegisterUser("JohnDoe");

        Console.ReadLine();
    }
}


```


Bu örnekte, bağımlılık (dependency) yönetimi için bir "ILogger" arayüzü (interface) tanımlanmıştır. "FileLogger" ve "DatabaseLogger" sınıfları, "ILogger" arayüzünü uygulayan farklı loglama mekanizmalarını temsil eder.

"UserManager" sınıfı, "ILogger" arayüzüne bağımlıdır. Yani, "UserManager" sınıfının bir loglama işlemi yapabilmesi için bir "ILogger" nesnesine ihtiyacı vardır. Bu nesne, sınıfın kurucusunda (constructor) enjekte edilir.

Main metodu, bir "FileLogger" nesnesi oluşturur ve bu nesneyi kullanarak bir "UserManager" nesnesini başlatır. "UserManager" nesnesi üzerinden "RegisterUser" metodu çağrıldığında, loglama işlemi gerçekleştirilir ve ilgili loglama mekanizması kullanılarak mesaj ekrana yazdırılır.

Bu örnek, bağımlılık yönetimini göstermektedir. "UserManager" sınıfı, "ILogger" arayüzüne bağımlıdır ve gerçekleştirilen loglama işlemi, enjekte edilen loglama mekanizması üzerinden gerçekleştirilir. Bu sayede, loglama mekanizması kolayca değiştirilebilir ve "UserManager" sınıfının kodunda herhangi bir değişiklik yapmadan farklı loglama mekanizmaları kullanılabilir.


### 📦 Composition (Bileşim):

Nesne Yönelimli Programlamada Composition (Bileşim), bir nesnenin başka nesneleri içermesi veya bunlardan oluşması durumunu ifade eder. Composition, daha karmaşık nesneleri oluşturmak için daha basit nesnelerin bir araya getirilmesini sağlar.

Composition ilişkisi, bir nesnenin diğer nesneleri içerdiği durumu ifade eder. Bu durumda, içerilen nesnelerin yaşam döngüsü, içerdikleri nesne ile birlikte olur. Yani, içeren nesne bir şekilde sonlandırıldığında, içerdikleri nesneler de etkilenir.

Composition, "bütün ve parça" ilişkisini ifade eder. Bir bütün, bir veya daha fazla parçadan oluşur ve parçalar bütünle birlikte anlam ifade eder. Örneğin, bir "Araba" sınıfı düşünelim. Araba, tekerlekler, motor, direksiyon gibi parçalardan oluşur. Araba nesnesi içerisinde bu parçaları içerir ve bu parçaların bir araya gelmesiyle bir araba oluşturulur.

Composition ilişkisi genellikle "has-a" ilişkisi olarak ifade edilir. Örneğin, "Araba" sınıfı "Motor" sınıfına sahip "has-a" ilişkisi vardır. Araba, Motor'u içerir veya Motor'a sahiptir.

Composition, nesneler arasındaki sıkı bağlantıyı ifade eder. İçerilen nesneler, içeren nesneyle doğrudan ilişkilidir ve birbirlerine erişebilirler. Bu sayede, içeren nesnenin davranışını ve özelliklerini etkileyebilirler.

Composition ilişkisi, nesne yönelimli programlamada karmaşık yapıları modellemek için yaygın olarak kullanılır. Bir sınıfın diğer sınıfları içermesi, daha esnek ve modüler bir tasarım sağlar. Bu sayede, kod tekrarını azaltır, sınıflar arasındaki bağımlılıkları kontrol eder ve daha kolay anlaşılabilir bir yapı oluşturur.


## ⌨️ Kullanım/Örnek 

```c#
using System;

public class Motor
{
    public void Calistir()
    {
        Console.WriteLine("Motor çalıştı.");
    }
}

public class Araba
{
    private Motor motor;

    public Araba()
    {
        motor = new Motor();
    }

    public void Calistir()
    {
        motor.Calistir();
        Console.WriteLine("Araba çalıştı.");
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Araba araba = new Araba();
        araba.Calistir();

        Console.ReadLine();
    }
}

```


Bu örnekte, "Araba" sınıfı "Motor" sınıfını içeren bir Composition ilişkisine sahiptir. "Araba" sınıfının içerisinde "Motor" nesnesi tanımlanır ve bu nesne "Araba" sınıfının bir parçası haline gelir.

"Motor" sınıfı, "Calistir" metoduyla temsil edilir ve Araba sınıfının içerisinde kullanılır. "Araba" sınıfı "Motor" sınıfını kullanarak "Calistir" metoduyla birlikte arabayı çalıştırır.

Main metodu, bir "Araba" nesnesi oluşturur ve bu nesne üzerinden "Calistir" metodu çağrılır. Bu sayede, "Araba" sınıfı içerisindeki "Motor" nesnesi kullanılarak arabayı çalıştırır.

Bu örnekte Composition (Bileşim) ilişkisi kullanılarak bir arabayı temsil ediyoruz. Araba, Motor'u içerir ve Motor'un çalıştırılması ile birlikte arabayı çalıştırır. Composition ilişkisi sayesinde arabayı oluşturmak ve çalıştırmak için farklı parçaları bir araya getirebiliriz.


### 📦 Aggregation (İçerme):

Nesne Yönelimli Programlamada Aggregation (İçerme), bir nesnenin başka bir nesneyi içerebileceği, ancak içeren nesnenin içerilen nesneye sahip olmasa bile yaşayabilmesi durumunu ifade eder. Aggregation, daha genel bir nesnenin daha spesifik bir nesneyi içermesini sağlar.

Aggregation ilişkisi, "has-a" ilişkisi gibi düşünülebilir, ancak içeren nesne sahip olmadan da var olabilir. İçeren nesne, içerilen nesneye bir referans tutabilir ve onunla işbirliği yapabilir, ancak içerilen nesnenin yaşam döngüsü içeren nesne bağlı olmadığından bağımsızdır.

Aggregation ilişkisi, bir bütün ve parça ilişkisini ifade eder, ancak parçaların bütünden bağımsız olarak var olabileceği durumu kapsar. Örneğin, bir "Üniversite" sınıfı düşünelim. Üniversite, farklı bölümleri temsil eden "Bölüm" nesnelerini içerebilir. Bu durumda, Üniversite ve Bölüm arasında bir Aggregation ilişkisi vardır. Üniversite, Bölüm'leri içerebilir, ancak Üniversite'nin var olması için Bölüm'lere sahip olması gerekmez.

Aggregation ilişkisi genellikle bir nesnenin bir koleksiyonu veya bir grup nesneyi içermesiyle gerçekleştirilir. İçerilen nesneler, içeren nesnenin ömrü boyunca farklı durumlarda eklenebilir veya kaldırılabilir.

Aggregation ilişkisi, nesneler arasında daha zayıf bir bağlantıyı ifade eder. İçeren nesne, içerilen nesneye sahip olmadan da var olabilir ve içerilen nesnenin yaşam döngüsü içeren nesnenin dışında kontrol edilebilir. Bu, daha esnek ve modüler bir tasarım sağlar ve nesnelerin yeniden kullanılabilirliğini artırır.

Aggregation ilişkisi, nesne yönelimli programlamada genellikle bir koleksiyonun veya gruplama yapısının kullanılmasıyla gerçekleştirilir. İçeren nesne, içerilen nesneleri tutmak için bir koleksiyon (List, Array, vb.) veya bir gruplama yapısı (Set, Dictionary, vb.) kullanabilir. Bu sayede, içeren nesne içerilen nesnelerle ilişkilendirilebilir ve onlarla işbirliği yapabilir.


## ⌨️ Kullanım/Örnek 

```c#
using System;
using System.Collections.Generic;

public class Ogrenci
{
    public string Ad { get; set; }
    public int Yas { get; set; }

    public Ogrenci(string ad, int yas)
    {
        Ad = ad;
        Yas = yas;
    }
}

public class Universite
{
    public string Ad { get; set; }
    public List<Ogrenci> Ogrenciler { get; set; }

    public Universite(string ad)
    {
        Ad = ad;
        Ogrenciler = new List<Ogrenci>();
    }

    public void OgrenciEkle(Ogrenci ogrenci)
    {
        Ogrenciler.Add(ogrenci);
    }

    public void OgrenciSil(Ogrenci ogrenci)
    {
        Ogrenciler.Remove(ogrenci);
    }

    public void OgrencileriListele()
    {
        Console.WriteLine("Üniversite Adı: " + Ad);
        Console.WriteLine("Öğrenciler:");
        foreach (var ogrenci in Ogrenciler)
        {
            Console.WriteLine("Ad: " + ogrenci.Ad + ", Yaş: " + ogrenci.Yas);
        }
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Universite universite = new Universite("ABC Üniversitesi");

        Ogrenci ogrenci1 = new Ogrenci("Ahmet", 20);
        Ogrenci ogrenci2 = new Ogrenci("Ayşe", 22);

        universite.OgrenciEkle(ogrenci1);
        universite.OgrenciEkle(ogrenci2);

        universite.OgrencileriListele();

        Console.ReadLine();
    }
}


```


Bu örnekte, "Universite" sınıfı "Ogrenci" sınıflarını içeren bir Aggregation ilişkisine sahiptir. "Universite" sınıfı, "Ad" adında bir özelliğe sahiptir ve aynı zamanda bir "Ogrenciler" listesi tutar.

"Ogrenci" sınıfı, "Ad" ve "Yas" adında özelliklere sahip basit bir sınıftır.

"Universite" sınıfının "OgrenciEkle" ve "OgrenciSil" metodları, "Ogrenciler" listesine öğrenci eklemek ve silmek için kullanılır.

Main metodu, bir "Universite" nesnesi oluşturur ve bu nesne üzerinden "OgrenciEkle" metodu kullanılarak iki öğrenci eklenir. Ardından "OgrencileriListele" metodu çağrılarak öğrencilerin listesi ekrana yazdırılır.

Bu örnekte Aggregation ilişkisi kullanılarak, "Universite" sınıfı "Ogrenci" nesnelerini içerir. "Universite" nesnesi, "Ogrenciler" listesini tutar ve içerilen nesnelerle işbirliği yapabilir. İçeren nesne olmadan da "Ogrenciler" listesi var olabilir ve içerilen nesnelerin yaşam döngüsü içeren nesneye bağlı değildir.
