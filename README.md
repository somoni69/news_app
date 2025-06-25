# 🗞️ NewsApp v2 — Новости СНГ с категориями и поиском

Flutter-приложение, отображающее новости с использованием API [newsdata.io](https://newsdata.io/). Реализована навигация по категориям, поиск, обновление новостей и обработка ошибок изображений.

---

## 🚀 Основные функции:

- 🔍 Поиск новостей по ключевым словам
- 🗂️ Категории: Политика, Экономика, Шоу-бизнес, Спорт
- 📸 Отображение изображений и проверка ошибок загрузки
- 📅 Форматирование даты публикации (через `intl`)
- 🔁 Pull-to-refresh (обновление свайпом)
- ⚠️ Гибкая обработка ошибок при загрузке данных

---

## 🛠️ Используемые технологии:

- Flutter (Stateless/Stateful Widgets)
- Dart
- HTTP package (работа с REST API)
- Intl (дата/время)
- TabBar + TabBarView (для навигации)
- FutureBuilder (асинхронная загрузка контента)

---

## 📸 Скриншоты:
Добавь свои скриншоты в папку `screenshots/` и вставь сюда:
![image](https://github.com/user-attachments/assets/ad3c0b3a-fc63-4e7a-8c76-85a74c884376)
![image](https://github.com/user-attachments/assets/9a12c3f3-f569-4145-a595-da2375da1f74)
![image](https://github.com/user-attachments/assets/ed05f6f1-2c9e-412f-9cb4-e4d1cbff31aa)
![image](https://github.com/user-attachments/assets/3326c55e-87a8-40b1-bc25-6dd74530517d)
![image](https://github.com/user-attachments/assets/b98d62fa-9072-4c7a-ba41-8e989960890a)
![image](https://github.com/user-attachments/assets/b50beff5-d74c-47fa-b857-e92f2c48de8b)
![image](https://github.com/user-attachments/assets/2147c2cf-cafa-40ce-a57d-62baa83e2444)
![image](https://github.com/user-attachments/assets/fdbb301d-cfa1-4286-be4a-2ab2a6d6fe1d)
![image](https://github.com/user-attachments/assets/7e063227-b41d-4158-8e8c-5ab25b50705b)
```markdown

![image](https://github.com/user-attachments/assets/4c9e8e86-87f4-428e-9750-679d5807f1ce) ![Главный экран](screenshots/home_screen.png)

![image](https://github.com/user-attachments/assets/25e00295-7480-4381-a88c-5592a754a5d3) ![Поиск](screenshots/search.png)

![image](https://github.com/user-attachments/assets/0c28a8a5-cd22-4659-a523-5f34bebbd46b) ![Категория - Спорт](screenshots/sports.png)


flutter pub get
flutter run
