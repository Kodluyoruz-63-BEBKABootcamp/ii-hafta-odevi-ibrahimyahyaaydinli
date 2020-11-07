# Yeni bir Gitthub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?

## GNU General Public License

#### GPLv3 en kısıtlayıcı lisanslardan biridir.Yazılımın sahibi için yüksek koruma sunar.

* Yazılım her dağıtıldığında halka açık hale getirilmelidir.
* Yazılımda gerçekleştirilen değişiklikler aynı lisans altında yayınlanmalıdır.
* Kaynak kod için yapılmış değişiklikler belgelenmiş olmalıdır.
* Oluşturulan yazılımda patentli materyal kullanılmışsa,kullanıcıların kullanması için onlara hak verir.
Eğer ki kullanıcı patentli materyal kullanımı nedeniyle dava açarsa, onlar yazılımı kullanma hakkını kaybederler.


## Apache License 2.0

#### Apache Licence 2.0 kulanıcılara daha fazla esneklik sağlar.

* Yazılımın bir dağıtımı yapıldığında kaynak kodun halka açık olmasına gerek yoktur.
* Yazılımda yapılan değişiklikler her lisans altında yayınlanabilir.
* Kaynak kod için yapılmış değişiklikler belgelenmiş olmalıdır.
* GPLv3 ile aynı patent kullanım korumasını sunar.
* Projede bulunan ticari markaların isimlerinin kullanılmasını açıkça yasaklar.

## Berkeley Software Distribution (BSD)

#### BSD, 2 ve 3 maddeli olmak üzere iki ana versiyona sahiptir.Her ikisi de Apache Lisans'ından daha fazla esneklik sağlar.

* Yazılımın bir dağıtımı yapıldığında kaynak kodun halka açık olmasına gerek yoktur.
* Yazılımda yapılan değişiklikler her lisans altında yayınlanabilir.
* Kaynak kod için yapılmış değişiklikler belgelenmeyebilir.
* Patent kullanımı hakkında açıkça bir durum belirtmez.
* Lisans ve telif hakkı, kaynak kodun derlenmiş versiyonunun belgelerine dahil edilmesi zoruludur.
* BSD 3 maddeli versiyonunun 3. maddesi, yazılımdan türetilen ürünlerin tanıtılmasında yazarın ve katkıda bulunanların isimlerinin izin olmadan kullanılamayacağını belirtir.

## MIT License

#### MIT lisansı en fazla serbestlik sağlayan lisanstır ve aynı zamanda en popüler olandır.Yazılımın sahibine daha düşük koruma sunar.

* Yazılımın bir dağıtımı yapıldığında kaynak kodun halka açık olmasına gerek yoktur.
* Yazılımda yapılan değişiklikler her lisans altında yayınlanabilir.
* Kaynak kod için yapılmış değişiklikler belgelenmeyebilir.
* Patent kullanımı hakkında açıkça bir durum belirtmez.

# Merge - Squash-Rebase arasındaki farklar nelerdir?

## Merge pull request 
  Github'da bir "pull request"de __Merge pull request__ i seçtiğinizde tüm commitler bir __branch__ tan temel __branch__ a birleştirme kaydı yolu üzerinden eklenir.
  
![Merge](https://docs.github.com/assets/images/help/pull_requests/standard-merge-commit-diagram.png)
 
## Squash and merge
 Github'da bir "pull request"de __Squash and merge__ i seçtiğinizde bir __Pull request__ in commitleri tek bir commit olarak sıkıştırılır.Katkıda bulunanın tüm kişisel commitlerini görmek yerine, commitler tek bir bir committe kombinlenerek __default branch__ ta merge edilir.
 ![Squash](https://docs.github.com/assets/images/help/pull_requests/commit-squashing-diagram.png)
 
## Rebase and merge
Rebase komutu ile merge ettiğimizde branchdaki commitler ana branchda gerçekleşmiş gibi sayar ve tarihçe olarak arkada iz bırakmadan sanki değişiklikler ana branchda gerçekleşmiş gibi varsayılır.

# Agile-Scrum-Kanban

## Agile Nedir?
Agile (Çeviklik), bir organizasyonun yeni koşullara uyum sağlayabilme ve yeni iş fırsatları yaratmak için yönünü değiştirebilme yeteneğidir.
Agile Manifesto ve Çevik Yazılımın 12 Prensibi (Twelve Principles of Agile Software) 1990’larda yaşanan endüstri hüsranının sonucu olarak ortaya çıkmıştır.
17 kişiden oluşan bir grup, “düşünce liderleri” fikir birliğine vararak Agile Manifesto’yu ve Çevik Yazılım’ın 12 Prensibini yazıya geçirdiler.
Agile’ın amacı sürekli değişim, artan karmaşıklık ve belirsizliğe rağmen müşteri odaklı olarak kesintisiz değer üretmektir. Müşteri takımlara daima doğrudan ya da dolaylı olarak rehberlik eder. Uçtan uca değer üretebilen takımlar son kullanıcı için yarattıkları etkiyi deneyimledikçe bu yenilikçi çalışma biçimi daha da anlam kazanır ve işte mucizeler tam da bu noktada ortaya çıkmaya başlar.

### Scrum ve Kanban

#### Scrum
Scrum, işleyiş olarak çok iyi tanımlanmış kurallar bütününe sahip bir Agile framework’dür. Öncelikle ekibin öğrenmesi ve uygulaması gereken çeşitli süreçler mevcut. Bu süreçler de daha önce Agile prensipler ile çalışmamış bir ekip için çok hızlı ve kolayca implemente edilebilecek bir süreç değil. Scrum’a geçmek isteyen bir ekibin, Sprint’ler halinde çalışmayı öğrenmesi, self organized ve cross-functional bir geliştirici ekip kurabilmesi, Scrum seremonileri adı verilen çeşitli etkinlikleri organize etmesi ve katılması ilk sayılabilecek örnekler arasındadır. İlk adımların atılmasının ardından da ekibin kendini sürekli geliştirip, kod kalitesini arttırması ve daha çok sorumluluk alması beklenecektir. Son cümleyi aslında hem bir zorunluluk hem de Scrum uygulanmasının ardından gelecek doğal bir sonuç olarak da düşünebiliriz.

#### Kanban
Kanban, Scrum kadar yapılandırılmış bir framework değildir. Zaten süreç anlamında kurallara sahip de değil. Kanban, waterfall dahil tüm yazılım geliştirme metodolojileri ile birlikte kullanılabilir. Kanban’ın asıl mantığı, bir board üzerinde, ilgili ürünün geliştirilme aşamasında, başından sonuna kadar tüm adımları görebiliyor olmak. Board üzerinde, her bir işin anlık olarak alabileceği durumu işaret eden kolonlar yer alır. Bu kolonlar soldan sağa doğru yeni işlerin yer aldığı en soldaki kolondan, tamamlanan işlerin yer aldığı en sağdaki kolona doğru devam eder. Bu kolonlar şirket ihtiyacına göre şekillendirilebileceği gibi varsayılan olarak New, In Progress, Testing, Ready For Release, Released kolonlarını düşünebiliriz.

Kanban’ın şart koştuğu tek kuralı WIP limitleme olarak düşünebiliriz. Board’umuzda bulunan kolonlar için bir maksimum iş limiti koymalıyız. Örneğin In Progress kolonunda maksimum 5 iş olabilir kuralı konulması halinde, geliştirici ekibin aynı anda 6 ve üstü işle uğraşmaması gerektiği belirlenmiş oluyor. Bu sayede yeni işe başlamak isteyen bir geliştiricinin, önce üstten gelen işleri tamamlaması gerekiyor. Aynı şekilde Testing kolonunda maksimum 10 iş olabilir kuralı ile test ekibine destek olunması gerektiği belirlenebiliyor.

## Gang of Four
Yaklaşık 25 yıl önce Gang of Four (GoF) olarak bilinen Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides, Design Patterns — Elements of Reusable Object-Oriented Software adında kitap yayınladılar ve ilk kez yazılım alanında tasarım kalıpları kavramını ortaya attılar.
#### Tasarım Kalıpları
Tasarım kalıpları, yazılım tasarımında sürekli karşılaşılan genel sorunlara esnek, yeniden kullanılabilir, başarılı çözümler getiren hazır kalıplardır.

# Interface ve Abstract sınıflar arasındaki farklar nelerdir?

## Abstract Class
Abstract sınıflar sınıf hiyerarşisinde genellikle base class (temel sınıf) tanımlamak için kullanılan ve soyutlama yeteneği kazandıran sınıflardır. Bir sınıfı abstract yapmak için abstract keywordünü kullanırız. Abstract sınıflar en az bir tane abstract metod bulundurması bir best practice’tir.

* Abstract sınıfları genel olarak inheritance (kalıtım) uygularken kullanırız.
* new anahtar sözcüğü ile nesneleri oluşturulamaz.
* İçerisinde değişken ve metod bulundurabilir.
* Abstract sınıflardan türetilen sınıfların abstract metodları implement etmesi zorunludur. Diğer metodları override etmeden de kullanabilir.
* Constructors (yapıcı metodlar) ve destructors (yıkıcı metodlar) bulundurabilirler.
* Static tanımlanamazlar.
* Bir sınıf yalnızca bir abstract sınıfı inheritance yoluyla implement edebilir. Çoklu kalıtım (multiple inheritance) desteklenmez.
* Abstract olmayan metodları da bulundurabilir.
## Interface 
Interface, içerisinde sadece kendisinden türeyecek olan sınıfların içini dolduracağı metod tanımlarının bulunduğu ve soyutlama yapmamıza olanak sağlayan bir yapıdır. 
Interface’leri tanımlarken interface keywordünü kullanırız. 
Tanımladığımız yapının interface olduğunu belirtmek için isminin önüne I harfini getirmek bir best-practice olacaktır. 
Böylece kodlama yaparken inherit aldığımız yapının bir class mı yoksa interface mi olduğunu kolaylıkla ayırt edebiliriz.



