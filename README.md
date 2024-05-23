
## Хэш
В Git каждый коммит идентифицируется уникальным хэш-кодом (SHA-1). Этот хэш используется для отслеживания изменений и индентификации конкретных состояний репозитория. Хэш-код выглядит как длинная строка символов, например: `d670460b4b4aece5915caf5c68d12f560a9fe3e4`.

Пример команды для получения хэша из последнего коммита:
```sh
git log -1 --pretty=format:"%H"

## Лог
Команда `git log` позволяет просматривать историю коммитов в репозитории. Она выводит список коммитов с их хэшами, авторами, датами и сообщениями.

Пример использования команды `git log`:
```sh
git log 
Для вывода более компактной информации: 
git log --oneline
 
