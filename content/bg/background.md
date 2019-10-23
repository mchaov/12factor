Произход
==========

Хората създали и допълващи този документ са били преки участници в разработката и разгръщането на стотици приложения. Индиректно са били свидетели на разработката, експлоатацията, и разширяването на стотици хиляди приложения чрез работата си върху платформата <a href="http://www.heroku.com/" target="_blank">Heroku</a>.

Този документ синтезира целият ни опит и наблюдения на широка гама приложения от тип софтуер-като-услуга в "дивата природа". Той е триангулация на идеалните практики за разработката на приложения, отдавайки специално внимание на динамиката на органичният им разтеж във времето, както и динамиката на съвместната работа между разработчиците работещи върху кода, и <a href="http://blog.heroku.com/archives/2011/6/28/the_new_heroku_4_erosion_resistance_explicit_contracts/" target="_blank">избягването на софтуерната ерозия (статията е на Английски).</a>.

Нашата мотивация е да повишим информираността за някои системни проблеми, които видяхме в съвременната разработка на приложения, да предоставим споделен речник за обсъждане на тези проблеми и да предложим набор от широки концептуални решения на тези проблеми с придружаваща терминология. Форматът е вдъхновен от книгите на Мартин Фоулер: *<a href="https://books.google.com/books/about/Patterns_of_enterprise_application_archi.html?id=FyWZt5DdvFkC" target="_blank">Patterns of Enterprise Application Architecture</a>* and *<a href="https://books.google.com/books/about/Refactoring.html?id=1MsETFPD3I0C" target="_blank">Refactoring</a>*.

The contributors to this document have been directly involved in the development and deployment of hundreds of apps, and indirectly witnessed the development, operation, and scaling of hundreds of thousands of apps via our work on the <a href="http://www.heroku.com/" target="_blank">Heroku</a> platform.

This document synthesizes all of our experience and observations on a wide variety of software-as-a-service apps in the wild.  It is a triangulation on ideal practices for app development, paying particular attention to the dynamics of the organic growth of an app over time, the dynamics of collaboration between developers working on the app's codebase, and <a href="http://blog.heroku.com/archives/2011/6/28/the_new_heroku_4_erosion_resistance_explicit_contracts/" target="_blank">avoiding the cost of software erosion</a>.

Our motivation is to raise awareness of some systemic problems we've seen in modern application development, to provide a shared vocabulary for discussing those problems, and to offer a set of broad conceptual solutions to those problems with accompanying terminology.  The format is inspired by Martin Fowler's books *<a href="https://books.google.com/books/about/Patterns_of_enterprise_application_archi.html?id=FyWZt5DdvFkC" target="_blank">Patterns of Enterprise Application Architecture</a>* and *<a href="https://books.google.com/books/about/Refactoring.html?id=1MsETFPD3I0C" target="_blank">Refactoring</a>*.

