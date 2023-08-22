# Git / GitHub - памятка #
[На главную](../../README.md)
___

## Содержание
- GitHub - удаление ветки
___

## GitHub - клонирование репозитория
- [статья](https://ploshadka.net/github-remove-branch/)
___
## Git - команды
### Репозитории
- `git clone` - создать локальный клон удалённого репозитория.
    - `git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY`

### Ветки
- `git fetch` - обновить удаленные ветки у себя в репозитории.
- `git branch` - вывести список локальных веток. 
- `git branch -r` - показать удаленные (remote) ветки. 
- `git branch -a` - вывести список всех веток (локальных и удаленных).
####  Удаление веток
- `git branch -d branch_name` - удаляет локальную ветку, если уже сделан её пуш и мердж.
- `git branch -D branch_name` - принудительно (force) удаляет локальную ветку, несмотря ни на что.
- `git push origin --delete stage` - теперь удалим такую же ветку из самого репозитория.



