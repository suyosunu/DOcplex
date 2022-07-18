# DOcplex Nedir? #
İnternette __DOcplex nedir__ diye arattığınızda karşınıza hiç bir sonuç çıkmaz. Çünkü Docplex ile ilgili hiç Türkçe kaynak yoktur. <br>
__What is DOcplex__ yazdığınızda ise IBM sitesinde tanımı karşımıza çıkar  
IBM Decision Optimization CPLEX Modeling for Python, also known as DOcplex, is a library composed of two modules:

    Mathematical Programming Modeling for Python using docplex.mp (DOcplex.MP)
    Constraint Programming Modeling for Python using docplex.cp (DOcplex.CP)

DOcplex is a native Python modeling library for optimization.

It's compatible with the NumPy and pandas libraries and available from the PyPI or conda package managers.

Kaynak: https://www.ibm.com/docs/en/icos/12.9.0?topic=docplex-python-modeling-api
Özet olarak DOcplex, IBM CPLEX'in gücünü python dilinin esnekliği ile birleştirebildiğimiz bir kütüphanedir.
IBM CPLEX'in ne olduğunu bilmiyor olsanız zaten burada olmazdınız. Ama yine de IBM CPLEX'in ne olduğunu merak ediyorsanız şu linkten inceleyebilirsiniz. https://www.ibm.com/tr-tr/products/ilog-cplex-optimization-studio 
### DOcplex'i nasıl kullanabilirim? ##
DOcplex'i kullanmak için bilgisayarınızda CPLEX kurulu olması gerekir. Eğer ücretli sürüm bilgisayarınızda yüklü ise zaten sıkıntı yok. Fakat eğer yüklü değil ise iki altrnatifiniz var.

__1- Community Edition__ : https://www.ibm.com/tr-tr/products/ilog-cplex-optimization-studio adresine girdiğinizde __Ücretsiz Sürümü Deneyin__ linkine tıkladığınızda sizden bir formu doldurmanızı istenecektir. Bu formu doldurduğunuzda ücretsiz sürüme erişebilirsiniz. Ücretsiz sürümde bazı kısıtlamalar bulunmaktadır. (1000 karar değişkeni ve süre kısıtları vb.)

__2- Academic Edition__ : https://www.ibm.com/academic/topic/data-science adresine girdiğinizde sizden kayıt olmanız istenecektir. Kayıt olmak için, üniversite kimliğiniz (lisans, yüksek lisans, doktora ya da akademik kadro) ve edu uzantılı mail adresiniz istenecektir. Kayıt olduktan sonra hemen kullanıma açılmayabilir. Belirli bir kontrol mekanizmasından sonra edu uzantılı mail adresinize bir onay gelecektir ve bu onaydan sonra indirme linklerine ulaşabilirsiniz. Akademik versiyonun herhangi bir limiti yoktur. Fakat akademik versiyonu kurumsal çözümler için kullanamazsınız. Bunu engelleyen herhangi bir kontrol mekanizması olmasa da etik olarak yapmamanız gerekir.  
### Eğitimde Neler Bulunmaktadır? ###
Eğitim X Notebook'tan oluşmaktadır. Basit modellerden başlayarak daha kompleks modellere doğru ilerleyeceğiz. Aşağıda her bir dersin içeriği ile ilgili notebookların açıklamaları bulunmaktadır. 

DOcplex Chapter 00 : DOcplex'in ne olduğunun anlatıldığı ve eğitim içeriğinin anlatıldığı notebooktur. <br>
DOcplex Chapter 01 : DOcplex kütüphanelerinin yüklenmesi, matematiksel modelin DOcplex'de nasıl kurulduğunun detaylı anlatıldığı notebooktur. <br>

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
