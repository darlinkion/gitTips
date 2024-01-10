git add
Команда git add добавляет содержимое рабочего каталога в индекс для последующего коммита
git status показывает состояния файлов в рабочем каталоге и индексе: какие файлы изменены,
но не добавлены в индекс; какие ожидают коммита в индексе. Вдобавок к этому выводятся подсказки о том, как изменить состояние файлов.
git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, 
а затем сдвигает указатель текущей ветки на этот слепок.
«Разгитить» папку, если что-то пошло не так, — rm -rf .git
Если ввести git commit без флага -m, откроется редактор Vim. Чтобы выйти из него, нажмите клавишу Esc, наберите последовательность символов :q! и нажмите Enter.