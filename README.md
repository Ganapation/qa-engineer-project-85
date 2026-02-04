# Тестирование Codebattle

## О проекте
[Codebattle](https://codebattle.hexlet.io/) — платформа для соревновательного программирования от [Hexlet](https://ru.hexlet.io/), позволяющая участвовать в реальных-time баттлах против других разработчиков или ИИ.

## Содержание репозитория
- Документация процесса знакомства с Codebattle
- Пример решения задачи "cube_sum" (сумма кубов чисел)
- Заметки по использованию платформы

## Решенные задачи
### cube_sum
- **Описание:** Вычисление суммы кубов чисел от 1 до n
- **Язык:** Node.js
- **Решение:**
  ```javascript
  const solution = (num) => {
      return Math.pow(num * (num + 1) / 2, 2);
  };
  ```
- **Особенность:** Использование математической формулы вместо цикла для оптимальной производительности
- **Результат:** Победа над ботом AgentSmith

## Ключевые особенности Codebattle
- Соревновательное программирование в реальном времени
- Поддержка 20+ языков программирования
- Разные режимы: против ИИ, случайных соперников, друзей
- Рейтинговая система и турниры
- Задачи различной сложности

## Ссылки
- [Codebattle](https://codebattle.hexlet.io/)
- [Hexlet](https://ru.hexlet.io/)

---

### Hexlet tests and linter status:
[![Actions Status](https://github.com/Ganapation/qa-engineer-project-85/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/Ganapation/qa-engineer-project-85/actions)
