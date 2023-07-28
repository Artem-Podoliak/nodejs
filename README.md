# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list
https://monosnap.com/file/Jnbi06vGUfjBAgB0qzwhyOeIJJxOQF

# Получаем контакт по id - выводим в консоль объект контакта или null, если контакта с таким id не существует.

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/19TSOZwRGlThUjxVH6aLs9SeFejHpu

# Добавляем контакт и выводим в консоль созданный контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/K4gWA5RYoHXXNzimveSEnxg2toTtnp

# Удаляем контакт и выводим в консоль удаленный контакт или null, если контакта с таким id не существует.

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH
https://monosnap.com/file/BeM5y5QfqPgAZGOqxdrb71BcdPJlAo
