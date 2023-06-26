# Первые шаги

Создаем репозиторий командой git clone ...
Выводим состояние файлов командой git status(git status -s ничего не возвращает после клонирования)

# В файле .gitignore в папке terraform задали игнорирование

Игнорируем:
- файлы в любых директориях .terraform
- файлы состояний terraform с расширением  .tfstate 
- файлы креш-логов  начинающиеся на crash. и заканчивающиеся на .log 
- файлы override.tf, override.tf.json или заканчивающиеся на _override.tf или заканчивающиеся на _override.tf.json
- файлы CLI конфигурации с названиями .terraformrc и .terraform.rc
- файлы секретной/приватной информации с расширениями .tfvars и .tfvars.json