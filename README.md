Питання до Кирила
Питання по АРІ для групового
1) В девайсах для кожного кольору є окремий обʼєкт, з книжками робити так само але для мови? --> окремий обʼєкт для кожної мови
2) як робити шляхи до зображень? --> поки скіпаю цей момент
3) В якому форматі зберігати дату публікації? В фігмі тільки рік, на порталах рік-місяць-день в форматі рррр - місяць - дд --> тільки рік
4) якщо немає знижкової ціни вигадую її сам? --> якщо снижки немає то "priceDiscount": null,
5) на якій мові мають бути збережені значення author, coverType, publication --> все англійською, пераграфи дескріпшена перекладаються на мову кнжки
6) в якому форматі зберігати значення illustrations? --> boolean

TODO:
1) зробити унікальні id UU-id
2) зробити слаг (slug -> namespaceId  + lang + book type e.g harry-potter-EN-e-book)
3) зробити namespaceId - namespaceId -> name property in kebab case e.g "Harry Potter" -> harry-potter (used in img urls)
4) description without title ['', '']
5) можливі значення coverType: "hardcover", "paperback", "ebook", "audiobook", "leather"
6) можливі значення мови - Код мови за стандартом ISO 639-1: "en", "uk"


поля які мають бути у нижок:
- langAvailable
- lang
- author
- coverType
- pageNumbers
- publicationYear
- publication (видавництво)
- format (140x210 mm)
- illustrations (true/false)
- category