# 🎨 Portfolio 2026 - Красивое Портфолио с Анимациями

![Portfolio](https://img.shields.io/badge/Portfolio-2026-6c5ce7?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

Красивое современное портфолио с богатыми анимациями, градиентами и интерактивными элементами.

## ✨ Особенности

### 🎯 Разделы
- **Главная (Hero)** - Красивая главная страница с анимированным фоном
- **Обо мне** - Информация о вас со статистикой
- **Навыки** - Карточки навыков с прогресс-барами
- **Проекты** - Сетка проектов с красивым дизайном
- **Контакты** - Форма обратной связи и социальные ссылки

### 🎨 Дизайн
✅ Анимированные градиентные фоны  
✅ Glass-morphism эффект  
✅ Стилизованные буквы с тенями  
✅ Плавные переходы и масштабирование  
✅ Полная адаптивность (мобильные, планшеты, ПК)  
✅ Темные и светлые цветовые схемы  

### 🎭 Анимации (20+)
- Плавное появление элементов (`fadeInUp`)
- Пульсирующий заголовок (`titlePulse`)
- Анимированный фон (`gradient-shift`)
- Парящие иконки (`float`)
- Прогресс-бары (`progressBar`)
- Мерцающие звезды (`twinkle`)
- Масштабирование при наведении
- Параллакс эффект при скролле
- Свечение текста (`glow`)
- Рябь эффект при клике (`ripple`)

### ⚡ Интерактивность
- 🖱️ Кастомный светящийся курсор
- ⬆️ Кнопка "Вернуться вверх"
- 📝 Валидация формы контактов
- 🔍 Активные ссылки при скролле
- 📱 Адаптивное меню (мобильное)
- 🎬 Эффект печати текста
- 🌊 Волновой эффект при клике

## 🚀 Быстрый старт

### 1. Клонирование репозитория
```bash
git clone https://github.com/Roman355-max/portfolio.git
cd portfolio
```

### 2. Открытие локально
Просто откройте `index.html` в браузере!

### 3. Публикация на GitHub Pages
1. Перейдите в **Settings** репозитория
2. Выберите **Pages**
3. Под "Source" выберите **Deploy from a branch**
4. Выберите **main** branch
5. Сохраните

Ваш портфолио будет доступно по адресу:
```
https://Roman355-max.github.io/portfolio
```

## 📝 Персонализация

### Измените основной текст
Отредактируйте `index.html`:
```html
<h1 class="title">Ваше имя</h1>
<p class="subtitle">Ваша профессия | Ваши навыки</p>
```

### Обновите цвета
Отредактируйте переменные в `style.css`:
```css
:root {
    --primary: #6c5ce7;      /* Основной цвет */
    --secondary: #a29bfe;    /* Вторичный цвет */
    --accent: #00b894;       /* Цвет акцента */
    --dark: #2d3436;         /* Темный цвет */
    --light: #f5f6fa;        /* Светлый цвет */
}
```

### Добавьте свои проекты
```html
<div class="project-card">
    <div class="project-image" style="background: linear-gradient(135deg, #ваш-цвет-1, #ваш-цвет-2)"></div>
    <div class="project-content">
        <h3>Название проекта</h3>
        <p>Описание проекта</p>
        <div class="project-tags">
            <span class="tag">Технология 1</span>
            <span class="tag">Технология 2</span>
        </div>
        <a href="#" class="project-link">Просмотреть →</a>
    </div>
</div>
```

### Добавьте контакты
```html
<a href="mailto:your@email.com" class="contact-link">
    <span class="contact-icon">✉️</span>
    <span>Email</span>
</a>
```

## 🎨 Цветовые схемы

### Схема 1 (Фиолетовая)
```css
--primary: #6c5ce7;
--accent: #00b894;
```

### Схема 2 (Синяя)
```css
--primary: #0984e3;
--accent: #00cec9;
```

### Схема 3 (Розовая)
```css
--primary: #d63031;
--accent: #e17055;
```

## 📁 Структура файлов

```
portfolio/
├── index.html          # Основная HTML структура
├── style.css           # Все стили и анимации
├── script.js           # Интерактивность
└── README.md           # Документация
```

## 📊 Браузеры совместимости

| Браузер | Версия |
|---------|--------|
| Chrome  | 90+    |
| Firefox | 88+    |
| Safari  | 14+    |
| Edge    | 90+    |

## 🎓 Что использовано

### Технологии
- **HTML5** - Семантическая разметка
- **CSS3** - Flexbox, Grid, Animations, Gradients
- **JavaScript ES6+** - Интерактивность, DOM манипуляции
- **Intersection Observer API** - Анимации при скролле

### CSS Техники
- CSS Gradients (линейные и радиальные)
- CSS Animations и Transitions
- CSS Grid и Flexbox
- backdrop-filter (Glass morphism)
- text-shadow и box-shadow
- CSS Variables

### JavaScript Техники
- Event Listeners
- DOM Manipulation
- Intersection Observer
- requestAnimationFrame (косвенно)
- localStorage (опционально)

## 🌟 Примеры анимаций

### 1. Градиентный фон
```css
@keyframes gradient-shift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}
```

### 2. Пульсирующий текст
```css
@keyframes titlePulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.05); }
}
```

### 3. Прогресс-бар
```css
@keyframes progressBar {
    from { width: 0; }
    to { width: 100%; }
}
```

## 💡 Советы по улучшению

1. **Добавьте изображения проектов** - Замените цветные градиенты на реальные скриншоты
2. **Интегрируйте с backend** - Отправляйте формы на сервер
3. **Добавьте темный режим** - Используйт�� `prefers-color-scheme`
4. **SEO оптимизация** - Добавьте meta теги
5. **Производительность** - Сжимайте изображения и оптимизируйте JS

## 📱 Адаптивность

Портфолио полностью адаптивно и выглядит хорошо на:
- 📱 Мобильные телефоны (320px+)
- 📱 Планшеты (768px+)
- 💻 Ноутбуки (1024px+)
- 🖥️ Настольные ПК (1200px+)

## 🤝 Внести изменения

1. Форкните репозиторий
2. Создайте ветку (`git checkout -b feature/amazing-feature`)
3. Коммитьте изменения (`git commit -m 'Add amazing feature'`)
4. Пушьте ветку (`git push origin feature/amazing-feature`)
5. Откройте Pull Request

## 📄 Лицензия

Этот проект распространяется под лицензией MIT. Смотрите файл `LICENSE` для деталей.

## 📧 Контакты

- **Email**: your@email.com
- **GitHub**: [@Roman355-max](https://github.com/Roman355-max)
- **LinkedIn**: [Ваш профиль](https://linkedin.com)

---

**Создано с ❤️ для вашего успеха! 🚀**

Made with HTML5, CSS3, and JavaScript ✨
