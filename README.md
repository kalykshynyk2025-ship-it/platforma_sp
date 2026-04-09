# Platforma SP — Demo Landing (MVP)

Одностраничный демонстрационный сайт (landing page) для концепции платформы, где:

- крупные компании публикуют бизнес-задачи;
- малый бизнес и специалисты предлагают решения;
- финальное решение выбирает и утверждает крупная компания.

Сделано на **vanilla HTML/CSS/JS** без бэкенда.

## Что внутри

- современный адаптивный дизайн (desktop + mobile);
- структура: Hero, «Как это работает», «Для кого платформа», пример задачи, преимущества, CTA, footer;
- простые анимации: hover и fade-in;
- SVG-иконки;
- фиктивная обработка формы email на фронтенде (MVP-демо).

## Быстрый запуск локально

### Вариант 1: открыть напрямую

Просто откройте файл `index.html` в браузере.

### Вариант 2: через локальный сервер (рекомендуется)

```bash
python3 -m http.server 8080
```

После запуска откройте: <http://localhost:8080>

---

## Публикация на GitHub (GitHub Pages)

### 1) Создайте репозиторий

Например: `platforma_sp`

### 2) Инициализируйте git и отправьте код

```bash
git init
git add .
git commit -m "feat: add one-page MVP landing"
git branch -M main
git remote add origin https://github.com/<your-username>/platforma_sp.git
git push -u origin main
```

### 3) Включите GitHub Pages

1. Откройте репозиторий на GitHub.
2. Перейдите в **Settings → Pages**.
3. В блоке **Build and deployment** выберите:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `/ (root)`
4. Нажмите **Save**.

Через 1–3 минуты сайт будет доступен по адресу:

`https://<your-username>.github.io/platforma_sp/`

---

## Публикация на GitVerse

> Ниже — универсальный сценарий для GitVerse-репозитория со статическим сайтом.

### 1) Создайте репозиторий в GitVerse

Создайте пустой репозиторий, например `platforma_sp`.

### 2) Подключите remote GitVerse и отправьте код

```bash
git remote add gitverse https://gitverse.ru/<your-username>/platforma_sp.git
# если remote уже есть:
# git remote set-url gitverse https://gitverse.ru/<your-username>/platforma_sp.git

git push -u gitverse main
```

### 3) Включите публикацию статического сайта

В интерфейсе GitVerse откройте настройки репозитория и включите раздел Pages/Static Hosting (если доступен в вашем тарифе/пространстве), указав ветку `main` и корень проекта.

После деплоя получите публичный URL из настроек проекта.

---

## Структура проекта

```text
.
├── index.html
└── README.md
```

## Лицензия

Демо-проект для презентации концепции.
