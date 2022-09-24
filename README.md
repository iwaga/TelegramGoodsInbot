# TGGoodsInbot
A store with the functionality of multi-cities.
Бот - Магазин в телеграм с функциональностями мульти-города и местонаходением покупателя.

**Функции для пользователя**
- каталог двух уровней, категория - товар.
- поддержка (контакты) - Кнопка с выводом контактов администратора
- FAQ - информативное, изменяемое сообщение с заготовленным синтаксисом и HTML разметкой
- подробная Статистика бота: кол-во поступлений, покупок, пользователей, позиций, категорий, чистой прибыли
- определение местонахождения пользователя

**Удобности(плюшки)**
- отдельный файл с настройками бота. Вам не придётся лезть в код бота (settings.ini)
- небольшая дизайнерская часть (кнопки, текста, смайлики)

**Для внедрения:**
- автоматическое создание и настройка БД (Базы Данных) при запуске бота

**Для админа:**
- отправка бота на технические работы (бот становится доступен только админам)
- при запуске бота, происходит автоматическая проверка обновления
- возможность включения/выключения покупок и пополнений
- добавление неограниченного количества администраторов
- роль админа магазина, управляющего своими товарами в каталоге
- добавление неограниченного количества администраторов магазинов
- удобная и многофункциональная админ панель
- определение и хранение города нахождения товара

**Платежная система**
- Если при пополнении баланса пользователем QIWI кошелёк не будет работать, администраторам придёт уведомление
- При добавление/изменение QIWI кошелька, бот автоматически проверяет их на работоспособность
- При выводе ошибок со стороны QIWI, бот расшифровывает код ошибки в текст
- Доступен выбор способов пополнения (по форме, по нику, по номеру)
- Изменение QIWI кошелька через админ-панель бота
- Проверка работоспособности QIWI кошелька
- Просмотр баланса QIWI кошелька

**Каталог и товары**
- Удобные страницы для прокручивания категорий и позиций
- Возможность прикреплять изображения к позициям
- Удаление сразу всех товаров, позиций и категорий
- Выгрузка всех товаров с определённой позиции
- Массовая и одиночная загрузка товаров

**Общие функции**
- Поиск информации о пополнениях и покупках по чекам
- Полная Информация о пользователе при его поиске
- Просмотр последних 10-ти покупок пользователя
- Рассылка сообщения всем пользователям бота
- Поиск профиля пользователя по ID и юзернейму
- Изменение и выдача баланса пользователю

**Защита**
- Админ-фильтры на все хендлеры, гарантирующие приватность админ функционала
- Защита от оплаты в тенге при пополнении баланса
- Защита от неправильного HTML синтаксиса
- Защита от повторной выдачи баланса
- Защита от спама в боте (Middlewares)

**Настройка**
1. Скопируйте папку бота. 
2. Заполните файл settings.ini.
3. Стартовать бот. 
4. Заполнить информационные поля. 
5. Наполнить каталог товарами.
6. Привлекать пользователей в каталог.

**Процесс покупки для покупателя**
1. Выбор товара. 
2. Пополнение счета. 
3. Ожидание звонка продавца и уточнение параметров домтааки. 
4. Получение товара. 
5. Подтверждение получения.
6. Отправка отзыва о покупателей.
 
**Процесс продажи для продавца**
1. Получение сообщения о заказе. 
2. Звонок покупателю. 
3. Отправка товара покупателю.
4. Получение отзыва о покупателей.

PRO версия:
- поддержка мультипродавцов; 
- 192 города России в справочнике, который можно расширить. 

TODO:
- карточка магазина.

Работающий экземпляр пока только по России в 192 городах; https://t.me/Goodsinbot
Чтобы добавлять свои товары, отправьте запрос на продавца из бота, нажав "Я продавец".
По вопросам пишите пожалуйста в телеграм: **@raclear**
