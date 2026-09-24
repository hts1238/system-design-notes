
# [System Design Interview - An Insider's Guide (Vol 1 and 2)](https://bytebytego.com/courses/system-design-interview)
Эти заметки основаны на книгах System Design Interview — [тома 1 и 2, 2-е издание](https://www.goodreads.com/book/show/54109255-system-design-interview-an-insider-s-guide) 

Заметки доступны здесь: https://pagefy.io/system-design/system-design-interview-by-alex-xu

**Примечание:** работа над этими заметками продолжается. 


 * [Глава 1 — Масштабирование от нуля до миллионов пользователей](./01.%20Scaling/)
 * [Глава 2 — Оценки на салфетке](./02.%20Back%20Of%20the%20Envelope%20Estimation/)
 * [Глава 3 — Структура собеседования по проектированию систем](./03.%20System%20Design%20Framework/)
 * [Глава 4 — Проектирование ограничителя частоты запросов](./04.%20Rate%20Limiter//)
 * [Глава 5 — Проектирование согласованного хеширования](./05.%20Consistent%20Hashing/)
 * [Глава 6 — Проектирование хранилища ключ-значение](./06.%20Key-Value%20Store/)
 * [Глава 7 — Проектирование генератора уникальных идентификаторов в распределённых системах](./07.%20Unique-Id%20Generator/)
 * [Глава 8 — Проектирование сокращателя URL](./08.%20URL%20Shortener/)
 * [Глава 9 — Проектирование веб-краулера](./09.%20Web%20Crawler/)
 * [Глава 10 — Проектирование системы уведомлений](./10.%20Notification%20System/)
 * [Глава 11 — Проектирование системы новостной ленты](./11.%20News%20Feed%20System/)
 * [Глава 12 — Проектирование системы чата](./12.%20Chat%20System/)
 * [Глава 13 — Проектирование системы автодополнения поиска](./13.%20Search%20Autocomplete/)
 * [Глава 14 — Проектирование YouTube](./14.%20Youtube/)
 * [Глава 15 — Проектирование Google Drive](./15.%20Google%20Drive/)
 * [Глава 16 — Сервис поиска объектов поблизости](./16.%20Proximity%20Service/)
 * [Глава 17 — Поиск друзей поблизости](./17.%20Nearby%20Friends/)
 * [Глава 18 — Проектирование Google Maps](./18.%20Google%20Maps/)
 * [Глава 19 — Распределённая очередь сообщений](./19.%20Distributed%20Message%20Queue/)
 * [Глава 20 — Система сбора метрик, мониторинга и оповещений](./20.%20Metrics%20Monitoring%20and%20Alerting%20System/)
 * [Глава 21 — Агрегация событий кликов по рекламе](./21.%20Ad%20Click%20Event%20Aggregation/)
 * [Глава 22 — Система бронирования отелей](./22.%20Hotel%20Reservation%20System/)
 * [Глава 23 — Распределённый почтовый сервис](./23.%20Distributed%20Email%20Service/)
 * [Глава 24 — Объектное хранилище типа S3](./24.%20S3-like%20Object%20Storage/)
 * [Глава 25 — Таблица лидеров в многопользовательской игре в реальном времени](./25.%20Real-time%20Gaming%20Leaderboard/)
 * [Глава 26 — Платёжная система](./26.%20Payment%20System/)
 * [Глава 27 — Цифровой кошелёк](./27.%20%20Digital%20Wallet/)
 * [Глава 28 — Фондовая биржа](./28.%20Stock%20Exchange/)


# Дополнительные материалы

### Ограничение частоты запросов
- [Алгоритм автоматического выключателя](https://martinfowler.com/bliki/CircuitBreaker.html)
- [Ограничитель частоты запросов Uber](https://github.com/uber-go/ratelimit/blob/master/ratelimit.go)


### Согласованное хеширование
- [Согласованное хеширование](https://tom-e-white.com/2007/11/consistent-hashing.html)
- [CS168: Введение и согласованное хеширование:]( http://theory.stanford.edu/~tim/s16/l/l1.pdf)
- [Apache Cassandra](http://www.cs.cornell.edu/Projects/ladis2009/papers/Lakshman-ladis2009.PDF)
- [Масштабирование Discord](https://blog.discord.com/scaling-elixir-f9b8e1e7c29b)
- [Google Maglev](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44824.pdf)


### Хранилища ключ-значение
- [Amazon Dynamo](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
- [Архитектура Cassandra](https://docs.datastax.com/en/archived/cassandra/3.0/cassandra/architecture/archIntro.html)
- [Архитектура Google BigTable](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
- [Внутреннее устройство Amazon Dynamo DB](https://www.allthingsdistributed.com/2007/10/amazons_dynamo.html)
- [Шаблоны проектирования в Amazon Dynamo DB](https://www.youtube.com/watch?v=HaEPXoXVf2k)
- [Внутреннее устройство Amazon Dynamo DB](https://www.youtube.com/watch?v=yvBR71D0nAQ)


### Генератор уникальных идентификаторов
- [Серверы билетов: недорогие распределённые уникальные первичные ключи](https://code.flickr.net/2010/02/08/ticket-servers-distributed-unique-primary-keys-on-the-cheap)
- [Snowflake](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake.html)


### Веб-краулер
- [Обход веб-страниц](http://infolab.stanford.edu/~olston/publications/crawling_survey.pdf)
- [Динамический рендеринг Google](https://developers.google.com/search/docs/guides/dynamic-rendering)



### Системы чатов
- [Как Discord хранит миллиарды сообщений](https://discord.com/blog/how-discord-stores-billions-of-messages)
- [Flannel: периферийный кэш на уровне приложения для масштабирования Slack](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale/)


### Автодополнение поиска
- [Как мы создали Prefixy](https://medium.com/@prefixyteam/how-we-built-prefixy-a-scalable-prefix-search-service-for-powering-autocomplete-c20f98e2eff1)
- [Префиксное хеш-дерево](https://people.eecs.berkeley.edu/~sylvia/papers/pht.pdf)


### YouTube
- [Архитектура YouTube](http://highscalability.com/youtube-architecture)
- [Масштабирование YouTube, 2012](https://www.youtube.com/watch?v=w5WVu624fY8)
- [Транскодирование видео в больших масштабах](https://www.egnyte.com/blog/2018/12/transcoding-how-we-serve-videos-at-scale/)
- [Трансляция видео в Facebook](https://engineering.fb.com/ios/under-the-hood-broadcasting-live-video-to-millions/)
- [Масштабируемое кодирование видео в Netflix](https://netflixtechblog.com/high-quality-video-encoding-at-scale-d159db052746)
- [Кодирование на основе сцен в Netflix](https://netflixtechblog.com/optimized-shot-based-encodes-now-streaming-4b9464204830)


### Google Drive
- [Дифференциальная синхронизация](https://neil.fraser.name/writing/sync/)
- [Видео о дифференциальной синхронизации](https://www.youtube.com/watch?v=S2Hp_1jqpY8)
- [Как мы масштабировали Dropbox](https://www.youtube.com/watch?v=PE4gwstWhmc&feature=youtu.be)
