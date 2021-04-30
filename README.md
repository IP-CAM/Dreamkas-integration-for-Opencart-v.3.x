# Dreamkas integration module for OpenCart 3.x

## Content Repository

- `. / SRC /` - Directory with source code modified by me
- `. / dreamkas-opencart-3.occmod.zip` - Modified module, ready for installation
- `./dreamkas-f opencart.ocmod.zip` - The initial module for OpenCart 2.3, on which this modification is based

## Description

Modification was tested on ** OpenCart 3.0.2.0 **.

The module is set, deleted, the settings are saved, read.

Fiscalization statuses are not immediately displayed on the main page of orders until you come to the order itself.

All major logic of the module is registered here: `upload / catalog / controller / extension / module / dreamkas.php`

## Short information about changes

Based on the module _ [Dreamkas-F OpenCart.ocmod.zip] (https://help.dreamkas.ru/hc/ru/article_attachments/115010763145/dreamkas-f_opencart.ocmod.zip) _ from the alt-team.ru team.

This archive is provided by Dreamkas employees. It is included in the repository for history.

## Important note regarding VAT

In this outdated module, there is still 18/180 VAT.

** It is important to know that from January 1, 2019 these rates were replaced with VAT 20/120! **

## Useful links

1. [History of the emergence of this modification] (http://blog.anthonyaxenov.ru/2018/05/09/module-integration-DReamkast-d.-OpenCart-3-0-2-0)
2. [Open documentation for Dreamkas API] (http://kabinet.docs.apiary.io)
3. [How to connect an online store to the checkout through the office?] (Https://help.dreamkas.ru/hc/ru/articles/115005007709)
4. [Connect the cashier to OpenCart] (https://help.dreamkas.ru/hc/ru/articles/115005504689-%D0%9F%D0%BE%D0%B4%D0%BA%D0%BB%D1% 8E% D1% 87% D0% B8% D1% 82% D1% 8C-% D0% BA% D0% B0% D1% 81% D1% 81% D1% 83-% D0% BA-OpenCart)
5. Group chat for developers in Telegram: [@apidreamkas] (https://t.me/apidreamkas)

## Support

** Please do not ask me help! **

I do not give any guarantees of its performance and I do not provide support.

Any manipulation with the module - for your fear and risk.

I do not have the opportunity to fully check how efficating this module works: for this you need real orders and purchases.
The project, in which I worked on this module, I no longer support.

I have no interest and need it. Many things about OpenCart, Dreamkas products and this module are already forgotten. Therefore, and since the project is initially not mine, personally, I will not definitely develop it.

Take and use. Does not work - Shtosh. If you have any refinement - Pull-Requests Are Welcome. But it is better to make the fork of this repository and develop the project on your own.

## License

[<img src = "http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png" Alt = "WTFPL" />] (License)

Argument:

1. Dreamkas distributes its modules without any license.
2. [The module code was written by the Alt-Team team, not Dreamkas (https://help.dreamkas.ru/hc/ru/articles/115005504689/comments/360000156078). In this case, the exclusive copyrights of Dreamkas on this code should be specified only within the framework of legal relations with the Alt-Team team.
3. This module is in public domain in the Dreamkas Support section. Neither [license agreement] (https://dreamkas.ru/content/kluch-oferta.pdf) nor [contract-offer] (https://dreamkas.ru/content/dogovor-oferta-clients.pdf), public Presented on Dreamkas:
   - do not contain conditions for use, changes and distribution by users of this module;
   - Not applicable for this case (see paragraph 2)
4. [Alt-Team update policy] (https://www.alt-team.ru/upgrade-policy.html) does not apply to the Dreamkas and OpenCart integration module, because This module is not for sale on their website;
5. In the source code of the module, it is not directly indicated by copywrites in accordance with Article 1271 of the Civil Code of the Russian Federation.

Based on this, I draw conclusions:

1. Dreamkas and the Alt-Team team in no way declare their rights to the module code, on the conditions for its use, distribution and change. Therefore, I have the right to do it yourself.
2. ** [License WTFPL V2] (License) ** How no other is suitable for this case.
3. The company Alt-Tim must be mentioned in the text of the license among other authors of the source code, because In the `dreamkas-f opencart.ocmod.zip / install.xml file, it is celebrated.

I am ready to discuss and change these conditions if you have something to say in essence.

----------

# Модуль интеграции Dreamkas для OpenCart 3.x

## Содержимое репозитория

- `./src/` - директория с исходным кодом модифицированного мной модуля
- `./dreamkas-opencart-3.ocmod.zip` - модифицированный модуль, готовый к установке
- `./dreamkas-f opencart.ocmod.zip` - исходный модуль для OpenCart 2.3, на котором основана данная модификация

## Описание

Модификация тестировалась на **OpenCart 3.0.2.0**.

Модуль устанавливается, удаляется, настройки сохраняются, читаются.

Статусы фискализации не сразу отображаются на главной странице заказов пока не зайдешь в сам заказ.

Вся основная логика модуля прописана здесь: `upload/catalog/controller/extension/module/dreamkas.php`

## Краткая информация об изменениях

Основано на модуле _[dreamkas-f opencart.ocmod.zip](https://help.dreamkas.ru/hc/ru/article_attachments/115010763145/dreamkas-f_opencart.ocmod.zip)_ от команды alt-team.ru.

Этот архив предоставляется самими сотрудниками Dreamkas. Он включен в репозиторий для истории.

## Важное замечание относительно НДС

В этом устаревшем модуле до сих пор существует НДС 18/180.

**Важно знать, что с 1 января 2019 эти ставки были заменены на НДС 20/120!**

## Полезные ссылки

1. [История появления этой модификации](http://blog.anthonyaxenov.ru/2018/05/09/модуль-интеграции-dreamkas-для-opencart-3-0-2-0)
2. [Открытая документация к Dreamkas API](http://kabinet.docs.apiary.io)
3. [Как подключить интернет-магазин к кассе через Кабинет?](https://help.dreamkas.ru/hc/ru/articles/115005007709)
4. [Подключить кассу к OpenCart](https://help.dreamkas.ru/hc/ru/articles/115005504689-%D0%9F%D0%BE%D0%B4%D0%BA%D0%BB%D1%8E%D1%87%D0%B8%D1%82%D1%8C-%D0%BA%D0%B0%D1%81%D1%81%D1%83-%D0%BA-OpenCart)
5. Групповой чат для разработчиков в Telegram: [@apidreamkas](https://t.me/apidreamkas)

## Поддержка

**ПОЖАЛУЙСТА, НЕ ПРОСИТЕ У МЕНЯ ПОМОЩИ!**

Я НЕ ДАЮ НИКАКИХ ГАРАНТИЙ ЕГО РАБОТОСПОСОБНОСТИ И НЕ ПРЕДОСТАВЛЯЮ ПОДДЕРЖКУ.

ЛЮБЫЕ МАНИПУЛЯЦИИ С МОДУЛЕМ — НА ВАШ СТРАХ И РИСК.

У меня нет возможности полноценно проверить насколько качественно работает этот модуль: для этого нужны реальные заказы и покупки.
Проект, в рамках которого я работал над этим модулем, я больше не поддерживаю.

У меня нет никакого интереса и необходимости в этом. Многие вещи об OpenCart, продуктах Dreamkas и этом модуле уже забыты. Поэтому, и поскольку проект изначально не мой, лично я развивать его точно не буду.

Берите и используйте. Не работает — штош. Если у вас есть какие-то доработки — pull-requests are welcome. Но лучше сделайте форк этого репозитория и развивайте проект дальше самостоятельно.

## Лицензия

[<img src="http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png" alt="WTFPL" />](LICENSE)

Аргументирую:

1. Компания Dreamkas распространяет свои модули без какой-либо лицензии.
2. [Код модуля был написан командой alt-team, а не компанией Dreamkas](https://help.dreamkas.ru/hc/ru/articles/115005504689/comments/360000156078). В этом случае исключительные авторские права Dreamkas на этот код должны быть оговорены только в рамках правовых отношений с командой alt-team.
3. Этот модуль находится в открытом доступе в разделе поддержки Dreamkas. Ни [лицензионное соглашение](https://dreamkas.ru/content/kluch-oferta.pdf), ни [договор-оферта](https://dreamkas.ru/content/dogovor-oferta-clients.pdf), публично представленные на сайте Dreamkas:
   - не содержат условий использования, изменения и распространения пользователями этого модуля;
   - неприменимы для этого случая (см. п. 2)
4. [Политика обновлений компании alt-team](https://www.alt-team.ru/upgrade-policy.html) не распространяется на модуль интеграции Dreamkas и Opencart, т.к. этот модуль не продаётся на их сайте;
5. В исходном коде модуля нигде прямо не указан копирайт в соответствии со статьёй 1271 ГК РФ.

Исходя из этого, делаю выводы:

1. Компания Dreamkas и команда alt-team никоим образом не заявляют о своих правах на код модуля, об условиях его использования, распространения и изменения. Поэтому я вправе сделать это самостоятельно.
2. **[Лицензия WTFPL v2](LICENSE)** как никакая другая лучше подходит для этого случая.
3. Компания Альт-тим должна быть упомянута в тексте лицензии среди прочих авторов исходного кода, т.к. в файле `dreamkas-f opencart.ocmod.zip/install.xml` встречается её упоминание.

Я готов обсудить и изменить эти условия, если вам есть что сказать по существу.
