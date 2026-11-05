![SvelteKit Logo](https://st.timeweb.com/cloud-static/apps-logo/svelte.svg)

# SvelteKit на Deno

Пример приложения [SvelteKit](https://svelte.dev/docs/kit) на [Deno](https://deno.com/) с серверным рендерингом (SSR), которое можно развернуть в **Timeweb Cloud Apps**.

:tada: [Демо]

:rocket: [Создать свой Apps](https://timeweb.cloud/my/apps/create)

:books: [Документация Timeweb Cloud Apps](https://timeweb.cloud/docs/apps)

## Параметры деплоя

Выберите рантайм **Deno**, фреймворк **SvelteKit** и тип приложения **backend**. Приложение запускается как сервер.

| Параметр | Значение |
| --- | --- |
| Фреймворк | SvelteKit |
| Версия Deno | 2.7.14 |
| Тип приложения | `backend` |
| Команда сборки | `deno task build` |
| Команда запуска | `deno task start` |

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
deno install --allow-scripts

# сборка для продакшн
deno task build

# запуск собранного серверного приложения
deno task start
```
