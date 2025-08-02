# whisper-gemini-app
Эта программа транскрибирует audio с помощью whisper. Кроме того, по API она подключается к Gemini 2.5 Pro и согласно промту, который можно редактировать и менять, анализирует содержимое расшифровки.

## Сборка программмы

Сборку программы можно делать так (например, в Anaconda Powershell Prompt)

pyinstaller --noconsole --name "Whisper & Gemini Transcriber" t_app3.py 

После сборки нужно все файлы из папки bin в этом репозитории скопировать в ту же папку, в которой разместился файл Whisper & Gemini Transcriber.exe

## Использование API-ключей Gemini для анализа расшифровки

API-ключ для вызова Gemini внутри приложения взять можно отсюда

https://aistudio.google.com/apikey

В архиве dist находится уже собранная программа, достаточно скачать папку, распаковать архив и просто запустить. Архив тут

https://github.com/IgorOberon/whisper-gemini-app/releases/tag/v1.0.0 
