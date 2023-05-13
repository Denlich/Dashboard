# Dashboard

Це веб застосунок для відслідковування завдання з розподілом на предмети. Тут можна фільтрувати та сортувати як завдання, так і предмети за різними критеріями, такими як: тип робіт, можливі бали, дедлайн тощо. Використовуємо Typescript з React для клієнтської частини, та Java з Spring для серверної. Вони взаємодіятимуть через RestAPI.

Для шифрування данних таких як пароль будемо використовувати spring security bcrypt, що буде його шифрувати. Для гарантії, що тільки авторизовані користувачі можуть отримати доступ до своїх завдань і змінювати їх будемо використовувати json web token.
