# kirpmaAlgoritmalari
Çizgi Kırpma Algoritmaları: Cohen-Sutherland ve Liang-Barsky
Proje Özeti
Bu proje, Cohen-Sutherland ve Liang-Barsky olmak üzere iki çizgi kırpma algoritmasının uygulanmasını göstermektedir. Proje, rastgele 2B çizgiler oluşturarak, bu çizgilerin bir kısmının veya tamamının belirli bir pencerenin dışında kalmasını sağlar ve bu çizgileri ayrı ayrı algoritmalarla kırpar. Amaç, her bir algoritmanın kırpma işlemini nasıl gerçekleştirdiğini görselleştirerek aralarındaki farkları anlamaktır.

Kullanılan Algoritmalar
Cohen-Sutherland Algoritması:

Bu algoritma, çizginin uç noktalarına birer bölge kodu atayarak çizginin tamamen içeride, tamamen dışarıda veya kısmen pencerenin içinde olup olmadığını belirler. Çizgilerin pencereyle kesiştiği durumlarda bit düzeyinde işlemler kullanarak kırpma yapar.
Liang-Barsky Algoritması:

Bu algoritma, parametre denklemlerini kullanarak bir çizginin pencerenin sınırlarıyla kesişip kesişmediğini ve nerede kesiştiğini belirler. Genellikle Cohen-Sutherland algoritmasına göre daha verimlidir çünkü kesişim noktalarını doğrudan hesaplar.
