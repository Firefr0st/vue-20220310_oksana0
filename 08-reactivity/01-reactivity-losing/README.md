# Потеря реактивности

👷🏻 _Задача нормальной сложности_\
📚 _Закрепление материала_

<!--start_statement-->

Реализовано небольшое приложение, которое отображает на странице данные множества датчиков.

При первом получении данных они успешно отображаются. Однако после получения новых данных, страница не обновляется.

Требуется найти причину потери реактивности и исправить её, изменяя только `SensorsDataView.vue`. Остальные модули
считаются _унаследованными библиотеками_.

Простое решение задачи не требует использования каких-либо дополнительных функций реактивности. Постарайтесь решить
задачу именно через реактивность, а не рендеринг.

<img src="https://i.imgur.com/nIWVWIE.gif" alt="Example" />
<!--end_statement-->

---

### Инструкция

📝 Для решения задачи отредактируйте файл: `components/SensorsDataView.vue`.

🚀 Команда запуска для ручного тестирования: `npm run serve`;\
приложение будет доступно на [http://localhost:8080/08-reactivity/01-reactivity-losing](http://localhost:8080/08-reactivity/01-reactivity-losing).

✅ Доступно автоматическое тестирование: `npm test ReactivityLosing`.