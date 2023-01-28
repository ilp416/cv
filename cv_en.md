EN | [RU](cv_ru.md)

[Resume](README.md)

# CV
Levaneuski-Peravozchykau Ilya 05 Sep 1986 Brest, Belarus

# 2020-Now [belodezhda.ru] Brest, Belarus (part.remote)
Belodezhda.ru - shop of women's clothing. There is a lot of garment factories in Brest. Presli aggregate production of these factories(about 100 brands) and sells in Ukraine/Belarus/Russia.

*I worked with:*
  * Integration with delivery services like NovaPoshta/CDEK/RussianPost
  * Integration and creating andpoints for marketing tools like RetailRocket/Unisender/Esputnik
  * Development different schemes to work with dealers and sellers
  * Profiling and fixing performance issues
  * System of promo codes and discounts
  * Landing pages

# 2020-2022 [myDog.show] Own little project
mydog.show - service of registration on dog shows. More complex tasks for dog clubs is formation event catalog, because it has complex rules, and most of clubs made it manually. But more people book dogs on event at last moment, so it was a problem to made a catalog after last dog is registered and be on time to print in printing house before event starts. With my service it performed in few minutes and service cover a lot of other club tasks.

*features*
  * Generation *.docx catalogs
  * Generation printable diploms and description cards
  * Data parsing from google forms to DB
  * Online catalogs with fast search on the page

*Tech stack:* Rails 6, postresql, react, Ubuntu-server at Amazon, Gitlab, Rspec, Sidekiq  

# From March 2019 [GuruWalk] Valencia, Spain (remote)
GuruWalk — free walking tours service which works in 78 countries. It based on ShareTribe, and like as MotionTribe project was forked and grows up separately. My work is implementation of new features and test coverage of new and old code.

*Task examples:*
  * Modification tours sorting algorithm, by availability, booked seats count and rating. The task required build index as different table.
  * Move endpoints from contrllers to APIs.
  * Creating ViewModels/Serializers.
  * Services for support list on localities(resolving uniqueness problem, removing orphans)
  * Admin's page to resolving problems with wrong data from GoogleGeocoding)
  * Autotranslations for fields filled in at only language.
  * Export gurus to Intercom system
  * Seats limits for non-premium tours
  * Catching and fixing random occured fails on CI builds

# 2018-2019 [MotionTribe] Brussels (remote)
Service of renting photo-video cameras and accessories in Brussels and London. I worked as only fulltime developer (Backend Ruby), teamlead worked one day per week. The works was a challenge: The project was forked from (Sharetribe)[https://github.com/sharetribe/sharetribe] platform and was modified to not-updatable state, spec was abandoned. Even at current time you can see, Sharetribe was devoped by many persons which has different mind, and have used different ways to dev.
As consequence you can find a call of sophisticated service , based on gracefull design pattern, and raw SQL-query in same fat controller. The first thing I did was updating Rails, enabling and fixing specs, setup CI/CD.

The main my responsibility was feature development (Backend + state to work in browser, FrontEnd and Desing are executed by teamlead)
*Tasks examples:*
  * Calculation service, work with renting AND selling in same time(sharetribe can't)
  * Stripe by charge/transfer
  * Omnyauth through Google and Facebook
  * Discounts through coupons(from owner/from project)
  * Convertation `communities` to `cities`(remove constraints of working inside single community)
  * Invoices generator
  * Sort listings by owner response time 
  * SMS-notifications (OVH)
  * IDs verification (VeriffMe)
  * Change URL format(cities, locale, remove subdomains)

*Tech stack:* Rails 3, migrated to Rails 4, Mysql, Ubuntu-server at Amazon, CircleCi, Sentry, Github, Rspec, Sphinx, Delayed Jobs, Memcached, HAML, SASS, jQuery

We have successfully finished feature-plan, but project didn't have financial success and was made decision about terminating.

# 2016-2018 [RENTMANIA](http://rentmania.com) Moscow(remote)
The first and most popular C2C renting service in Moscow and Saint Petersburg, start working in Los Angeles. After apply I was second developer, in few month our command contained 3 Backend, 2 Frontend, teamlead and 1 QA. I've got PM resposibilities on vacation time. We had work by Agile/Scrum. We developed project as Service-oriented app. We had a lot of external API like as SMS/Email notifications, payment systems, google analitics, verification, etc.

*Tasks examples:*
* Design of Order, Invoice models
* Transactions for order states
* Up payments systems(Yandex.Money, Payu, Stripe)
* Dev API(Grape + Swagger)
* SEO-optimization(by incoming tasks)
* Analitics, stats by orders, users and lots
* I18n, prepate to start service in new cities
* Dev of admin workspace

*Tech stack:* Rails 3, migrated to Rails 4, Mysql, Sidekiq + Redis, CI/CD Codeship, Github, Honeybadger, Elastic Search, TDD, Amazon.

The work in startup gives uniq skills instead regular company: Skill of finding most cheepest/faster/simplest decision of task, give a value of task from business position and take responsibility to do or not to do some task(convice the team about true decision).

# 2015 Freelancer
* http://www.osfk.org/ - developed virtual club cards.
* Few projects of PixelPerfect layout.
* Small backend tasks like DataMapping for charts.

# 2008-2015 "Vash Vybor plus", Brest
Fullstack web-dev at "Vash vybor plus" — the biggest factory of plastic doors/windows in Brest state.
Website created for internal usage for dealers and employees to create orders, schedulling offline works. By few yeard project was growed up to large ERP-system which includes bookkeeping, manufacture-software(Wintecs), production order processing software(FoxPro) and Webapp(my child)

The first version was trivial by tech stack (LAMP), but take impressive funcionality:
* Auth of all imployees and dealiers, messaging, section of Docs and Software downloads
* Schedulling all works from first visit to product mounting. System counting busyness of masters, holidays, dinner time, approximate shipping time by locations. Marks of finished works, lateness. 
* Creating orders, order names generation, storing order-files, contract generation
* Push orders in production
* Show financial stats
* Show manufacture online information about order states, planned and real order finish prof time and shipping
* Claim service, repair service
* Stats, analitics and reports

Factory and administration was located in different cities. Company used 2 self-owned servers under Linux system (Setup and installation is my work, file-store sync, DB-replication).


The second version started to develop in 2013. I had a teamlead and RoR FullStack role. This project became evolution of design and cover all functions of first version, but provide comfortable environment to deliver new features

# In 2013 graduated Brest State Technical University.
Faculty of Invormation Technoligies, spec automated system of data processing.
Graduate project: "Information system Online consult". System was intended as part of ERP-system described above. This was a not regular online chat. It performed requests to DB and can to answer for simple queries about orders from clients independently without managers. 

# About
I think I am a perfectionist with all consequences: I have some troubles when I must to finish task as is without some refactoring and some dressing.
I consider myself as a creative person. As my hobby I have restoration car 1979 y.d. project, and take part in the kart racing championship of Belarus.
