# ЭкоШаг — веб-интерфейс

Статическая страница чата с локальной моделью через Ollama.
Браузер обращается напрямую к `http://localhost:11434` на компьютере пользователя; сайт данные не получает.

Запуск Ollama с разрешением для домена:

```bash
launchctl setenv OLLAMA_ORIGINS "https://ecoshag.ru,https://www.ecoshag.ru"
ollama pull qwen3:4b
```
