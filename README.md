# Katergon CLI

Публичные готовые сборки Katergon CLI для учеников и пилотных пользователей.
Исходный код, серверная часть и пользовательские данные в этом репозитории не
публикуются.

## Скачать

- [Katergon CLI 0.7.1 для Windows x64](https://github.com/horggorg88-pixel/katergon-cli/releases/download/v0.7.1/Katergon-CLI-0.7.1-win-x64.zip)
- [SHA-256](https://github.com/horggorg88-pixel/katergon-cli/releases/download/v0.7.1/Katergon-CLI-0.7.1-win-x64.zip.sha256)

Контрольная сумма:

```text
5185242aaee788c16e86f60a88506c21e4ae5a1e99d0d42c8b84652a36256f9b
```

## Установка

1. Скачайте ZIP и файл `.sha256`.
2. Проверьте контрольную сумму.
3. Распакуйте ZIP и запустите `Install.cmd`.
4. Откройте новый терминал и выполните `katergon version`.

В архив уже входит проверенный Node.js 20.20.2. Устанавливать Git, npm, Node.js
или скачивать репозиторий с исходниками не требуется. Установщик добавляет только
Katergon CLI и интеграционные hooks для уже установленного Codex; сам Codex он не
устанавливает.
