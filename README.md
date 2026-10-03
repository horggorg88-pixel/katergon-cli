# Katergon CLI

Публичные готовые сборки Katergon CLI для работников и пилотных пользователей.
Исходный код, серверная часть и пользовательские данные в этом репозитории не
публикуются.

## Скачать

- [Katergon CLI 0.9.2 для Windows x64](https://github.com/horggorg88-pixel/katergon-cli/releases/download/v0.9.2/Katergon-CLI-0.9.2-win-x64.zip)
- [SHA-256](https://github.com/horggorg88-pixel/katergon-cli/releases/download/v0.9.2/Katergon-CLI-0.9.2-win-x64.zip.sha256)
- [Подписанный манифест обновления](https://github.com/horggorg88-pixel/katergon-cli/releases/latest/download/katergon-cli-manifest.json)

## Установка

1. Скачайте ZIP и файл `.sha256`.
2. Проверьте контрольную сумму.
3. Распакуйте ZIP и запустите `Install.cmd`.
4. Откройте новый терминал и выполните `katergon version`.

В архив уже входит проверенный Node.js 20.20.2. Устанавливать Git, npm, Node.js
или скачивать репозиторий с исходниками не требуется. Установщик добавляет только
Katergon CLI и интеграционные hooks для уже установленного Codex; сам Codex он не
устанавливает. После установки CLI проверяет подписанный манифест и применяет
проверенное обновление автоматически; недоступность сети не блокирует текущую
версию.
