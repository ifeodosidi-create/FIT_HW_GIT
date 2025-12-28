# Инструкция по работе с Git - казалось просто, но не тут то было...

## 1. Инициализация репозитория
```bash
git init
```
## Команды Git
```powershell
git add README.md
git commit -m "Создан README.md с описанием git init"
```
## 2. Проверка состояния репозитория
```bash
git status
```
## 3. Добавление файлов к коммиту
```bash
git add README.md
git add .
```
## 4. Создание коммита
```bash
git commit -m "Сообщение"
```
## 5. Просмотр истории коммитов
```bash
git log
git log --oneline
```
## 6. Просмотр различий между версиями
```bash
git diff
```
## 7. Работа с ветками
```bash
git branch
git branch <имя_ветки>
git checkout <имя_ветки>
```
## 8. Слияние веток
```bash
git merge <имя_ветки>
```
## 9. Удаление ветки
```bash
git branch -d <имя_ветки>
```
## 10. Клонирование репозитория
```bash
git clone <url>
```