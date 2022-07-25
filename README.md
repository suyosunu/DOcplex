# DOcplex Nedir? #
İnternette __DOcplex nedir__ diye arattığınızda karşınıza hiç bir sonuç çıkmaz. Çünkü Docplex ile ilgili hiç Türkçe kaynak yoktur. <br>
DOcplex, IBM CPLEX'in gücünü python dilinin esnekliği ile birleştirebildiğimiz bir kütüphanedir. Peki IBM CPLEX nedir? IBM CPLEX iş kararlarınızı optimize etmek, optimizasyon modellerini hızla geliştirip devreye almak ve iş sonuçlarını önemli ölçüde iyileştirebilen gerçek dünya uygulamaları yaratmak için karar optimizasyonu teknolojisini kullanır. CPLEX'in kendi arayüzünde OPL (Optimization Programming Language) kullanarak model geliştirebilirsiniz. <br>

2012 yılında [Eray Çakıcı](https://github.com/ErayCakici/) ile tanıştığım IBM CPLEX serüveni 10 senedir devam ediyor. Yöneylem Araştırması ve Optimizasyon konusunda sayılı kişilerden olan Eray'ı burada anmadan geçmek olmazdı.  

Bu eğitim DOcplex'in kullanımının yaygınlaştırılması için hazırlanmıştır. Özellikle IBM'in hazırladığı kaynaklar kullanılarak detaylı anlatım yapılmaya çalışılmıştır. Gelip incelediğiniz için teşekkür ederim. 

### Eğitimde Neler Bulunmaktadır? ###
Eğitim X Notebook'tan oluşmaktadır. Basit modellerden başlayarak daha kompleks modellere doğru ilerleyeceğiz. Aşağıda her bir dersin içeriği ile ilgili notebookların açıklamaları bulunmaktadır. 

[DOcplex Chapter 00](https://github.com/suyosunu/DOcplex/blob/master/Chapter00/Docplex_C00.ipynb) : DOcplex'in ve eğitim içeriğinin anlatıldığı notebooktur. <br>
[DOcplex Chapter 01](https://github.com/suyosunu/DOcplex/blob/master/Chapter01/Docplex_C01.ipynb) : Optimizasyon, yöneylem araştırması ve matematiksel modelin ne olduğunun örneklerle anlatıldığı eğitimdir. Sektördeki gerçek hayat örneklerini, matematiksel modelin tanımını ve daha bir çok bilgiyi bu eğitimde bulabilirsiniz. <br>
[DOcplex Chapter 02](https://github.com/suyosunu/DOcplex/blob/master/Chapter02/Docplex_C02.ipynb) : DOcplex kütüphanelerinin yüklenmesi, basit bir matematiksel modelin DOcplex'de nasıl kurulduğunun detaylı anlatıldığı notebooktur. <br>
[DOcplex Chapter 03](https://github.com/suyosunu/DOcplex/blob/master/Chapter03/Docplex_C03.ipynb) : Doğrusal Programlamaya giriş eğitimidir. Bir örnek ile doğrusal programlama, grafik çözümü, DOcplex uygulaması, infeasiblity, hard ve soft constriantler anlatılmıştır. Relaxer ile infeasible bir modelin nasıl çözülebileceği anlatılmıştır<br>
[DOcplex Chapter 04](https://github.com/suyosunu/DOcplex/blob/master/Chapter04/Docplex_C04.ipynb) : IBM'in popüler örneklerinden biri olan Makarna Üretim PRoblemi'nin DOcplex ile çözümü anlatılmıştır. Karar değişkenlerinin ve kısıtların arraylerden kolaylıkla oluşturulmasını öğrenmek için güzel bir örnektir.<br>
[DOcplex Chapter 05](https://github.com/suyosunu/DOcplex/blob/master/Chapter05/Docplex_C05.ipynb) : Yine IBM'in popüler örneklerinden biri olan Süpermarket PRoblemi'nin DOcplex ile çözümü anlatılmıştır. Farklı kümelerdeki veriler kullanılarak kısıt yazma üzerine güzel bir örnektir.<br>
[DOcplex Chapter 06](https://github.com/suyosunu/DOcplex/blob/master/Chapter06/Docplex_C06.ipynb) : Bu dersimizde, Oil adlı IBM problemini DOcplex kullanarak Doğrusal Programala ile çözeceğiz. Pandas ve numpy kütüphanelerinin kullanımını, amaç fonksiyonu ve KPI'ların grafik gösterimlerini bu eğitimde bulabilirsiniz.<br>
[DOcplex Chapter 07](https://github.com/suyosunu/DOcplex/blob/master/Chapter07/Docplex_C07.ipynb) : Bu dersimizde, Pandas kütüphanesinin yardımı ile binary, integer ve sürekli değişkenlerin bir arada kullanıldığı bir doğrusal programlama probleminin çözümü bulunmaktadır. <br>
[DOcplex Chapter 08](https://github.com/suyosunu/DOcplex/blob/master/Chapter08/Docplex_C08.ipynb) : Bu eğitimde, akademik ya da kurumsal CPLEX kullanıcılarının DOcplex kütüphanesinde karşılaştıkları sınırlı kullanım hatasının nasıl giderileceği anlatılmıştır. <br>
[DOcplex Chapter 09](https://github.com/suyosunu/DOcplex/blob/master/Chapter09/Docplex_C09.ipynb) : Bu eğitimimizde, Listeners (Dinleyiciler) ile modellerimizi nasıl takip edebileceğimizi, limit vererek nasıl durdurabileceğimizi, tüm çözümleri nasıl inceleyebileceğimizi gibi özellikler anlatılmıştır <br>
[DOcplex Chapter 10](https://github.com/suyosunu/DOcplex/blob/master/Chapter10/Docplex_C10.ipynb) : CPLEX'in kendi dili olan OPL ile DOcplex arasındaki farkların bir örnek ile anlatıldığı notebooktur. <br>

### Faydalanılan Kaynaklar ###
CPLEX ücretli (yüksek ücretli) bir çözücü olduğu için kurumsal ve akademik alan dışında olmadığı için, internette kaynak sıkıntısı bulunmaktadır. Yine de IBM'in kendi oluşturduğu dokumanlar ve kaynaklar hem çok değerli hem de yeterlidir. 

Bu dokumanlar hazırlanırken aşağıdaki kaynaklardan faydalanılmıştır. <br> <br>
__Medium__ <br>
https://medium.com/@AlainChabrier/decision-optimization-education-a50cada93856 <br>
https://medium.com/@AlainChabrier/opl-vs-python-docplex-2d7b28814740 <br>

__Github__ <br>
https://github.com/IBMDecisionOptimization/docplex-examples <br>
https://github.com/IBMDecisionOptimization/docplex-doc <br>
https://github.com/IBMDecisionOptimization/docplex-mssql-sample <br>

__IBM__ <br>
http://ibmdecisionoptimization.github.io/docplex-doc/ <br>

### Komunite ###
Buna ek olarak, IBM'in tartışma platformu ve komunitesi takıldığınız yerler için çok faydalı olacaktır. Geliştiricilerin cevap verdiği bu platforma da kayıt olmanızı tavsiye ederim. <br>
https://community.ibm.com/community/user/datascience/communities/community-home/digestviewer?tab=digestviewer&CommunityKey=ab7de0fd-6f43-47a9-8261-33578a231bb7
