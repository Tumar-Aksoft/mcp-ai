# mcp-ai — Барон Карл

**Beta!** MCP-сервис для уведомлений и напоминаний в Telegram.

Попроси ИИ отправить сообщение или создать напоминание — Барон Карл доставит его в Telegram, в том числе когда чат уже закрыт.

## Что доступно в основной Beta

- Привязка своего Telegram к учётной записи.
- Отправка уведомлений и проверка статуса доставки.
- Однократные и повторяющиеся напоминания с часовым поясом.
- Управление напоминаниями, тихими часами и отложенной доставкой.
- Подтверждение выполнения напоминаний и кнопки действий в Telegram.
- Приём подписанных внешних событий и каталог безопасных диагностических заданий.

Отправка сообщений и напоминаний проверена в личном пилоте через ChatGPT. Остальные функции и новые пользовательские сценарии проходят проверку.

**Обновление 14 октября 2026:** в отдельном ограниченном Calendar Staging-пилоте владельцем проверены Google Calendar только для чтения, фоновая синхронизация и Telegram-напоминания о событиях с заданным временем, включая автоматический перенос и отмену. Это не объявление выпуска календаря на основном endpoint. Объём проверки и ограничения описаны в [BETA.md](BETA.md).

## Как попробовать

Самостоятельная регистрация включена. Подключи MCP в совместимом клиенте, пройди вход или регистрацию Casdoor: при первом авторизованном вызове автоматически создаётся профиль Free. Затем привяжи Telegram по инструкции. Полный путь нового пользователя ещё проходит проверку; если столкнулся с проблемой, создай Issue без личных данных.

- [Инструкция подключения](CONNECTING.md)
- [Статус и ограничения Beta](BETA.md)
- [План развития сервиса](ROADMAP.md)
- [Сообщить об ошибке или предложить функцию](https://github.com/Tumar-Aksoft/mcp-ai/issues)

MCP endpoint: `https://mcp-ai.aksoft.kz/mcp` — доступ с авторизацией.
Telegram-бот: [@Karl_baron_bot](https://t.me/Karl_baron_bot).

## Исходники и установка

Публичный репозиторий предназначен для документации, обратной связи, готовых бинарных выпусков и примеров настроечных файлов без секретов. Исходный код остаётся приватным и здесь не публикуется. В конфигурационных примерах используются заглушки вместо паролей, токенов и других учётных данных.

Сейчас опубликована документация; готовых бинарников и проверенной инструкции самостоятельного развёртывания пока нет. Бинарные выпуски и примеры конфигурации будут размещаться по мере готовности и проверки.

## Обратная связь

Хочешь использовать MCP или предложить функцию? Присоединяйся к [Discussions](https://github.com/Tumar-Aksoft/mcp-ai/discussions). Об ошибке сообщи через [Issues](https://github.com/Tumar-Aksoft/mcp-ai/issues). Для обратной связи также можно написать на [tumar@aksoft.kz](mailto:tumar@aksoft.kz). Укажи, каким ИИ-клиентом пользуешься, что хотел сделать и что получилось. Не публикуй токены, коды привязки, личные сообщения или данные учётной записи.

## English

**Beta!** Baron Karl is a hosted MCP service for Telegram notifications and reminders. This public repository is intended for documentation, feedback, binary releases and configuration examples without secrets. Source code remains private. Self-registration is enabled and new authenticated users receive the Free plan; end-to-end onboarding for a new user is still being validated. ChatGPT delivery has been tested; Claude, Gemini and Chrome integrations are planned or experimental. An owner-tested, restricted Calendar Staging pilot now covers read-only Google Calendar sync and timed-event reminders; this is not a production calendar release. See [Beta status](BETA.md). No binaries are currently published.



