# ModularBiz - Модульний бізнес-сайт

Повноцінний фронтенд для великого професійного бізнес-сайту, створений з використанням модульної архітектури та сучасних веб-технологій.

## 🚀 Особливості

### ✨ Дизайн та UI/UX
- **Сучасний дизайн** - Чистий, професійний інтерфейс
- **Адаптивність** - Ідеально працює на всіх пристроях
- **Анімації** - Плавні переходи та інтерактивні елементи
- **Доступність** - Відповідає стандартам веб-доступності

### 🧩 Модульна архітектура
- **Компонентний підхід** - Повторно використовувані компоненти
- **Масштабованість** - Легко додавати нові модулі
- **Підтримуваність** - Організована структура коду
- **Гнучкість** - Можливість швидкої кастомізації

### 🎨 Дизайн-система
- **Комплексна SCSS архітектура** - Variables, mixins, components
- **Утилітарні класи** - Швидка розробка інтерфейсів
- **Типографічна система** - Узгоджена типографіка
- **Колірна палітра** - Продумана колірна схема

## 🛠 Технології

- **React 18** - Сучасна бібліотека для UI
- **React Router** - Маршрутизація
- **SCSS** - Препроцесор CSS
- **Framer Motion** - Анімації
- **Webpack** - Збірка проекту
- **Font Awesome** - Іконки
- **Google Fonts** - Типографіка

## 📦 Структура проекту

```
ModularBusinessWebsite/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Layout/
│   │   │   ├── Header/
│   │   │   └── Footer/
│   │   └── Sections/
│   │       ├── HeroSection/
│   │       ├── FeaturesSection/
│   │       ├── ServicesSection/
│   │       ├── StatsSection/
│   │       ├── TestimonialsSection/
│   │       ├── PortfolioSection/
│   │       ├── TeamSection/
│   │       ├── BlogSection/
│   │       ├── CTASection/
│   │       └── ClientsSection/
│   ├── pages/
│   │   ├── Home/
│   │   ├── Services/
│   │   ├── About/
│   │   ├── Portfolio/
│   │   ├── Blog/
│   │   └── Contact/
│   ├── styles/
│   │   ├── abstracts/
│   │   │   ├── _variables.scss
│   │   │   └── _mixins.scss
│   │   ├── base/
│   │   │   ├── _reset.scss
│   │   │   ├── _typography.scss
│   │   │   └── _globals.scss
│   │   ├── components/
│   │   │   ├── _buttons.scss
│   │   │   ├── _cards.scss
│   │   │   ├── _forms.scss
│   │   │   └── _animations.scss
│   │   ├── utilities/
│   │   │   ├── _spacing.scss
│   │   │   └── _responsive.scss
│   │   └── main.scss
│   ├── App.jsx
│   └── index.js
├── package.json
├── webpack.config.js
└── README.md
```

## 🚀 Швидкий старт

### Установка
```bash
cd ModularBusinessWebsite
npm install
```

### Розробка
```bash
npm start
# або
npm run dev
```

Сайт буде доступний за адресою: `http://localhost:3000`

### Збірка для продакшену
```bash
npm run build
```

## 📱 Головні секції

### 🏠 Головна сторінка
- **Hero Section** - Вражаючий заголовок з анімаціями
- **Clients Section** - Логотипи клієнтів та партнерів
- **Features Section** - Основні переваги компанії
- **Services Section** - Каталог послуг з цінами
- **Stats Section** - Досягнення в цифрах
- **Portfolio Section** - Приклади робіт
- **Testimonials Section** - Відгуки клієнтів
- **Team Section** - Презентація команди
- **Blog Section** - Останні статті
- **CTA Section** - Заклик до дії

### 📋 Внутрішні сторінки
- **Послуги** - Детальний опис кожної послуги
- **Про нас** - Історія компанії та команда
- **Портфоліо** - Галерея проектів з кейсами
- **Блог** - Статті та новини
- **Контакти** - Форма зв'язку та контактна інформація

## 🎨 Стильова система

### Кольори
```scss
// Основні кольори
$primary-color: #2563eb;
$secondary-color: #f59e0b;
$success-color: #10b981;
$warning-color: #f59e0b;
$error-color: #ef4444;

// Нейтральні кольори
$white: #ffffff;
$gray-50: #f9fafb;
$gray-900: #111827;
$black: #000000;
```

### Типографіка
```scss
// Шрифти
$font-primary: 'Inter', sans-serif;

// Розміри
$font-size-xs: 0.75rem;    // 12px
$font-size-sm: 0.875rem;   // 14px
$font-size-base: 1rem;     // 16px
$font-size-lg: 1.125rem;   // 18px
$font-size-xl: 1.25rem;    // 20px
$font-size-2xl: 1.5rem;    // 24px
$font-size-3xl: 1.875rem;  // 30px
$font-size-4xl: 2.25rem;   // 36px
$font-size-5xl: 3rem;      // 48px
```

### Відступи
```scss
$spacing-1: 0.25rem;   // 4px
$spacing-2: 0.5rem;    // 8px
$spacing-4: 1rem;      // 16px
$spacing-6: 1.5rem;    // 24px
$spacing-8: 2rem;      // 32px
$spacing-12: 3rem;     // 48px
$spacing-16: 4rem;     // 64px
$spacing-20: 5rem;     // 80px
```

## 🧩 Компоненти

### Кнопки
```jsx
<button className="btn btn-primary">Основна кнопка</button>
<button className="btn btn-secondary">Вторинна кнопка</button>
<button className="btn btn-ghost">Прозора кнопка</button>
```

### Картки
```jsx
<div className="card">
  <div className="card-header">
    <h3 className="card-title">Заголовок</h3>
  </div>
  <div className="card-body">
    <p className="card-text">Контент картки</p>
  </div>
</div>
```

### Форми
```jsx
<div className="form-group">
  <label className="form-label">Назва поля</label>
  <input type="text" className="form-input" placeholder="Введіть текст" />
</div>
```

## 📱 Адаптивність

Сайт повністю адаптивний та оптимізований для:
- 📱 **Мобільні пристрої** (320px+)
- 📱 **Планшети** (768px+)
- 💻 **Десктопи** (1024px+)
- 🖥 **Великі екрани** (1280px+)

## ⚡ Оптимізація

### Продуктивність
- **Lazy loading** - Відкладене завантаження компонентів
- **Оптимізація зображень** - Стиснені та адаптивні зображення
- **Мінімізація коду** - Стиснені CSS та JS файли
- **Tree shaking** - Видалення невикористаного коду

### SEO
- **Семантична розмітка** - Правильні HTML теги
- **Meta теги** - Оптимізовані заголовки та описи
- **Структуровані дані** - Schema.org розмітка
- **Sitemap** - Карта сайту для пошукових систем

## 🔧 Налаштування

### Кастомізація кольорів
Змініть змінні в файлі `src/styles/abstracts/_variables.scss`:

```scss
$primary-color: #ваш-колір;
$secondary-color: #ваш-колір;
```

### Додавання нових компонентів
1. Створіть папку в `src/components/`
2. Додайте файли `.jsx` та `.scss`
3. Імпортуйте компонент в потрібному місці

### Додавання нових сторінок
1. Створіть папку в `src/pages/`
2. Додайте компонент та стилі
3. Додайте маршрут в `App.jsx`

## 🌟 Особливості реалізації

### Модульність
- Кожен компонент самодостатній
- Можливість повторного використання
- Легка кастомізація та розширення

### Сучасні технології
- React Hooks для стану компонентів
- CSS Grid та Flexbox для розкладки
- CSS Custom Properties для динамічних стилів

### Анімації
- Framer Motion для складних анімацій
- CSS transitions для простих ефектів
- Intersection Observer для анімацій при скролі

## 📞 Підтримка

Для питань та пропозицій:
- 📧 Email: info@modularbiz.ua
- 📱 Телефон: +38 (012) 345-67-89
- 🌐 Сайт: https://modularbiz.ua

## 📄 Ліцензія

MIT License - використовуйте код як завгодно!

---

**Створено з ❤️ для успішного бізнесу в цифровому світі**
