# Prism Agent

Простой ИИ-агент для macOS: пять режимов, работа с файлами и документами,
понятный первый запуск и подтверждения перед действиями.

## Установка

### Homebrew (одна команда)

```bash
brew trust yumdaniil/prism-agent
brew install --cask yumdaniil/prism-agent/prism-agent
```

`brew trust` нужен один раз: Homebrew не доверяет сторонним тапам по умолчанию.
Обновление — `brew upgrade --cask prism-agent`, удаление — `brew uninstall --cask prism-agent`.

### Архив из Releases

1. Откройте раздел **Releases** и скачайте последнюю версию для macOS (Apple Silicon).
2. Распакуйте архив и перетащите приложение в «Программы».
3. При первом запуске откройте через правую кнопку → «Открыть».
4. Вставьте ключ провайдера в настройках.

## Требования

- macOS 14 или новее
- Apple Silicon
- ключ поддерживаемого провайдера

## Обратная связь

daniilprojects@yandex.ru

## Лицензии

Проект использует код Hermes Agent (Nous Research) по лицензии MIT.
Полный текст — в файле `LICENSE` и в приложении.
