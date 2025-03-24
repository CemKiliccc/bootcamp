Metro Ağı Rota Bulucu

Bu proje, bir metro ağı üzerinde en az aktarmalı ve en hızlı rotaları bulmayı sağlayan bir Python uygulamasıdır. Kullanıcı, iki istasyon arasında en uygun rotayı öğrenebilir.

Kullanılan Teknolojiler ve Kütüphaneler

Python 3: Projenin temel programlama dili.

collections.defaultdict: Hatları ve istasyonları organize etmek için kullanıldı.

collections.deque: En az aktarmalı rotayı bulmak için kullanılan BFS algoritması için kuyruk yapısı sağladı.

heapq: En hızlı rotayı bulmak için kullanılan Dijkstra algoritmasının öncelikli kuyruk yapısını sağladı.

typing: Veri tiplerini daha net tanımlamak için kullanıldı.

Algoritmaların Çalışma Mantığı

BFS (En Az Aktarmalı Rota)

Breadth-First Search (BFS) algoritması kullanılarak iki istasyon arasındaki en az aktarmalı rota bulunur.

Mantık: BFS, en kısa yolu bulmak için katman katman ilerleyen bir algoritmadır. Bu sayede, en az durak değiştirerek hedefe ulaşmanın yolu belirlenebilir.

Kullanım Amacı: Aktarma sayısını minimize ederek en pratik güzergahı belirlemek.

Dijkstra (En Hızlı Rota)

En hızlı rotayı bulmak için Dijkstra Algoritması kullanılmıştır.

Mantık: Öncelikli kuyruk (heapq) ile en düşük sürede ulaşılan istasyonlar önceliklendirerek en hızlı rota bulunur.

Kullanım Amacı: Kullanıcının toplam süre açısından en verimli yolculuk güzergahını belirlemek.

Örnek Kullanım ve Test Sonuçları

Örnek Metro Ağı

Kırmızı Hat: Kızılay, Ulus, Demetevler, OSB

Mavi Hat: AŞTİ, Kızılay, Sıhhiye, Gar

Turuncu Hat: Batıkent, Demetevler, Gar, Keçiören
