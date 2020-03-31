# [Hangman](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))

## [Hangman](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0)) - это консольная игра, которая написана на языке `Ruby`


### Коротко об игре:

Есть скрытое слово `Слово: __ __ __ __ __ __`, которое Вам нужно отгадать.

Вы вводите букву. Если она есть в слове, тогда буква откроется `Слово: __ __ __ __ __ А`.

Если нет - Вы будете на шаг ближе к проигрышу.

Допускается максимум 7 ошибок!

### Для запуска программы, Вам нужно:

  1. Зайти в командной строке в директорию где находится файл с игрой.

  2. Набрать в консоли такую команду:

     `ruby main.rb`


### Добавление новых слов:

Файл с загаданными словами находится `hangman/data/words.txt`.

Просто на новой строке допишите слово в верхнем регистре и сохраните файл.

*Так-как программа написана на языке программирования `Ruby`, проверьте установлен ли он на вашем устройстве.*
