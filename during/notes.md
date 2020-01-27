# Notes

1. Basecamp firmasını yakından takip ediyor
2. DHH, Rails
3. RubyMine, lisanslı IDE
4. Bolu  yaz kampı 15 gün sürüyor
5. David, Jason iki ortak ve kurucu
6. Ruby = mutlu programcı
7. Rails = gülümseyen programcı
8. CodeSchool sahipleri, Youtube videoları
9. ZSH, oh-my-zsh
10. `curl`'i iyi bil
11. [Ruby Style Guide](https://rubystyle.guide/)
12. version change log
13. git flow
14. Revolution OS (2001)
15. [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
16. git lfs
17. HTTP yaşam döngüsü
18. `puma.io` 
19. `artoo.io`
20. micro framework, php ve java'da da var
21. FrontController, Design Pattern
22. DSL (doman specific language)
22. Ruby = yakut, Gem = hazine sandığı
23. Gems'ler başka dil kodları da içerebilir
24. `rubygems.org`
25. yazılı iletişim yeteneği çok önemli
26. Müşteri ihtiyaçlarını bilen yazılımcı çok değerlidir
27. `bundler.io`, her şeyin çıkış noktası bu
28. Gemfile.lock dosyasını bilgisayar kullanıyor, insanlar Gemfile dosyası üzerinden çalışıyorlar. Bundler için kullanılıyor.
29. Gemfile bir kütüphane manifestosu
30. `config.ru` dosyası web server için gerekli dosya (rack-based server)
31. rack ile iletişime geçmek için kullanılan dosya `config.ru` dosyası. Bu dosya ile bir server ayaklandırılabiliyor, rack gem kullanılarak. 
32. [Rails Doctrine](https://rubyonrails.org/doctrine/)
33. [Ruby Toolbox](https://www.ruby-toolbox.com/), to examine Gems
34. Fazla Gems kullanımı, projede bağımlılıkları arttırarak sürdürebilirliği zorlaştırıyor. 
35. `nginx` çalışma mekanizmasını öğren!
36. Dosya isimlerinin tamamı küçük harfle ve alt çizgi ile ayrılıyor
37. JS, CSS, HTML, PDF içerisine embedded Ruby yerleştirilebiliyor
38. Rails'ın bütün controller'ı RESTful çalışıyor!
39. `rails routes` ile dönen sayfada, ilk sütundakiler Ruby helper
40. Rails'te controller'lar çoğuldur/çoğul tanımlanır
41. Model: Person, Controller: People, helper: person
42. Migration, db'de timetravel için yaratılmış bir araç sunuyor
43. `db/migrate/schema.rb` dosyasının içinde db ile ilgili her bilgi var, bu dosya değiştirilmemeli.
44. `rails console` , ruby gibi!
45. Anlatılacaklar: ORM (DAO), MVC, REST
46. Rails'te partials dosyaları _ ile başlıyor
47. Scaffolding
48. Rails Girls etkinlikleri
49. 4 temel etkinlik var TR'de:
    1.  Özgür Web Teknolojileri Günleri (bahara doğru, 2 günlük, haftasonu, konferans türü)
    2.  Özgür Yazılım günleri (kışa doğru)
    3.  Yaz kampı
    4.  Kış kampı
50. Rails'te: view: Action View / template, model: Active Record, controller: Action Pack
51. Front controller design pattern (Rails'te var, mutlaka bilinmeli, araştır)
52. ORM: MVC içinde database ile ilişki kısmı, datanın dildeki karşılığı: model (tablonun karşılığı = model)
53. SQL101 yaz kampına kadar öğrenilmeli
54. DB'de 2 kavram
    1.  data definition language: create, alter, log-table, change-table (Rails migration'da bu kısım etkin)
    2.  data query language: sorgula, update..vb (Rails'te active record kısmı)
55. Stimulus.js ve Turbolinks: 
    1.  Stimulus.js
        1. [Origin](https://stimulusjs.org/handbook/origin)
        2. Rails şart değil, başka sistemlerle de çalışıyor
        3. Event Driven Development bilgisini geliştirmen gerek JS kullanmak için
        4. [mutation observer](https://developer.mozilla.org/en-US/docs/Web/API/MutationObserver)
    2.  Turbolinks
        1.  [Video](https://www.youtube.com/watch?v=SWEts0rlezA)
        2.  Uygulamanın hızlı çalışmasını sağlamak işlevi
        3.  Çoğu şeyi arka planda hallediyor
        4.  Cross platform olduğu için mobil konusunda uzman birileri de gerekebilir
        5.  Rails'te zaten kurulu geliyor
        6.  pushState + ajax = pjax buradan çıkan bir fikir
56. Basecamp, proje takip ve yönetim sistemi, 3 adet proje ve 5 kişiye kadar ücretsiz, toplam 20 kullanıcı, 1GB veri alanı
    1.  Aktif olarak 5 yıldır BC kullanıyorlar
    2.  Rails konusunda bilgi ediniyorlar, nasıl kullanılıyor, yeni yaklaşımlar, Rails ekosistemi ve proje yönetimi hakkında fikir veriyor
    3.  Rails (Stimulus ve Turbolinks) ile yapılmış bir cross-platform uygulama
    4.  Basit ve kullanışlı bir ürün, monolithic uygulama, milyonlarda kullanıcısı var
57. Proje yap, Rails'i geliştir, iyi bir şeyler çıkarırsan bana ulaş, iş imkanı sağlarım, yurtdışında çok iş imkanı var
58. Proje yapacaksan Basecamp gibi düşünmelisin
59. Transaction konusunu araştır, database ile ilgili
60. Postgresql her anlamda güçlü bir dil, Rails ile çok uyumlu çalışıyor
61. Useful Gem: activeadmin
62. Controller zayıf/kısa, model büyük/şişman olmalı, controller'de fazla kod muhtemelen yanlıştır