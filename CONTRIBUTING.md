# 🤝 Внесок у проект

Дякуємо за інтерес до проекту! Ми раді будь-якому внеску від розробників.

## 📋 Як внести свій внесок

### 1. Форк репозиторію
1. Перейдіть на [GitHub репозиторій](https://github.com/Alex-Green-Oleksiy/Alex-Green-Oleksiy)
2. Натисніть кнопку "Fork" у правому верхньому куті
3. Клонуйте ваш форк локально:
   ```bash
   git clone https://github.com/your-username/Alex-Green-Oleksiy.git
   cd Alex-Green-Oleksiy
   ```

### 2. Створення гілки
Створіть нову гілку для ваших змін:
```bash
git checkout -b feature/your-feature-name
# або
git checkout -b fix/your-fix-name
```

### 3. Внесення змін
1. Внесіть необхідні зміни
2. Перевірте код за допомогою ESLint:
   ```bash
   npm run lint
   npm run lint:fix
   ```
3. Протестуйте ваші зміни:
   ```bash
   npm run dev
   npm run build
   ```

### 4. Коміт змін
Використовуйте зрозумілі повідомлення комітів:
```bash
git add .
git commit -m "feat: add new component for user profile"
git commit -m "fix: resolve navigation issue on mobile"
git commit -m "docs: update README with new features"
```

### 5. Push та Pull Request
```bash
git push origin feature/your-feature-name
```
Потім створіть Pull Request на GitHub.

## 📝 Правила комітів
Використовуйте [Conventional Commits](https://www.conventionalcommits.org/):
- `feat:` - нова функція
- `fix:` - виправлення помилки
- `docs:` - зміни в документації
- `style:` - зміни в стилях
- `refactor:` - рефакторинг коду
- `test:` - додавання тестів
- `chore:` - зміни в конфігурації

## 🎨 Стандарти коду

### JavaScript/React
- Використовуйте функціональні компоненти з хуками
- Надавайте перевагу arrow functions
- Використовуйте деструктуризацію
- Додавайте PropTypes або TypeScript типи

```jsx
import React from 'react';
import PropTypes from 'prop-types';

const MyComponent = ({ title, children }) => {
    return (
        <div className="my-component">
            <h2>{title}</h2>
            {children}
        </div>
    );
};

MyComponent.propTypes = {
    title: PropTypes.string.isRequired,
    children: PropTypes.node
};

export default MyComponent;
```

### CSS
- Використовуйте camelCase для класів
- Групуйте пов'язані стилі
- Додавайте коментарі для складних стилів

```css
.myComponent {
    display: flex;
    align-items: center;
    padding: 1rem;
}

.myComponentTitle {
    font-size: 1.5rem;
    font-weight: bold;
    color: #333;
}
```

## 🐛 Повідомлення про помилки
При повідомленні про помилку включіть:
1. **Опис проблеми** - що сталося?
2. **Кроки для відтворення** - як це повторити?
3. **Очікувана поведінка** - що має статися?
4. **Фактична поведінка** - що сталося замість цього?
5. **Скріншоти** - якщо це UI проблема
6. **Версія браузера/ОС** - якщо це релевантно

## 💡 Запропонувати нову функцію
При запропонуванні нової функції опишіть:
1. **Проблему** - що ви намагаєтесь вирішити?
2. **Рішення** - як це можна реалізувати?
3. **Альтернативи** - які ще є варіанти?
4. **Додатковий контекст** - скріншоти, приклади

## 📞 Зв'язок
- **Issues:** [GitHub Issues](https://github.com/Alex-Green-Oleksiy/Alex-Green-Oleksiy/issues)
- **Discussions:** [GitHub Discussions](https://github.com/Alex-Green-Oleksiy/Alex-Green-Oleksiy/discussions)
- **Email:** your.email@example.com

## 🙏 Подяка
Дякуємо всім контриб'юторам за їх внесок у проект!

---
**🎯 Разом ми створюємо якісні рішення!** 