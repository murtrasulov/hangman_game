# README

This README would normally document whatever steps are necessary to get the
application up and running.

Виселица
Описание:

Консольная версия данной игры https://ru.wikipedia.org/wiki/Виселица_(игра)

При запуске компьютер загадывает слово, необходимо его угадать, вводя буквы.

Возможно сделать 7 ошибок, после чего игра заканчивается проигрышем.
Настройка игры:

Слова для игры можно добавить/удалить в файле

/data/words.txt

Шаблоны для отображения виселицы находятся в

/data/figures/

Слова записаны в верхнем регистре. Во время игры буквы Ё-Е, Й-И равнозначны.
Запуск игры:

1    Склонировать репозиторий

2    Перейти в директорию с игрой

3    Установить гемы

   bundle install

5    Запустить игру

  bundle exec ruby main.rb
