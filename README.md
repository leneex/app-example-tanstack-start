# TanStack Start

Пример приложения [TanStack Start](https://tanstack.com/start), которое можно развернуть без настройки.

## Параметры деплоя

Приложение разворачивается как frontend: при сборке страницы пререндерятся в HTML (`prerender` в `vite.config.ts`).

| Параметр          | Значение         |
| ----------------- | ---------------- |
| Фреймворк         | TanStack Start   |
| Команда сборки    | `npm run build`  |
| Директория сборки | `dist/client`    |

Пример с серверным рендерингом — `app-example-tanstack-start-ssr`.

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
npm install

# запуск в дев режиме с отслеживанием изменений
npm run dev

# сборка для продакшн с минификацией
npm run build

# локальный просмотр собранной сборки
npm run preview
```
