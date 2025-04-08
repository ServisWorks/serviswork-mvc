# Инструкция для разработчиков

## Подключение к репозиторию ServisWork (GitHub)

### 1. Клонировать проект (SSH)
```bash
git clone git@github.com:ServisWorks/serviswork-mvc.git
```

### 2. Перейти в папку проекта
```bash
cd serviswork-mvc
```

### 3. Проверить подключение к GitHub через SSH
```bash
ssh -T git@github.com
```

### 4. Проверить текущие ветки
```bash
git branch
```

### 5. Создание новой ветки (по задаче)
```bash
git checkout -b feature/название_задачи
```

### 6. Работа с кодом и коммиты
```bash
git add .
git commit -m "Добавлено: описание задачи"
```

### 7. Отправка изменений на GitHub
```bash
git push -u origin feature/название_задачи
```

---

## Работа с GitHub CLI (если используется)

### Проверка авторизации
```bash
gh auth status
```

### Авторизация (если не выполнена)
```bash
gh auth login
```

---

## Основной адрес локального проекта:
```
http://localhost:5192/
```

## Путь к проекту на Mac:
```
/Users/gennadii/Desktop/serviswork_Core/ServisWork
```

---

Если возникнут вопросы по работе с Git, обращаться к Геннадию.


