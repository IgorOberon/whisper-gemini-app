# whisper-gemini-app
Эта программа транскрибирует audio с помощью whisper. Кроме того, по API она подключается к Gemini 2.5 Pro и согласно промпту, который можно редактировать и менять, анализирует содержимое расшифровки.

В архиве dist находится уже собранная программа, достаточно скачать папку, распаковать архив и просто запустить. Архив тут

https://github.com/IgorOberon/whisper-gemini-app/releases/tag/v1.0.0 

## Сборка программы из исходного кода

Сборку программы можно делать так (например, в Anaconda Powershell Prompt)

pyinstaller --noconsole --name "Whisper & Gemini Transcriber" t_app3.py 

Все необходимые библиотеки перечислены в файле requirements.txt. Установить их можно последовательно, а можно одной командой

pip install -r requirements.txt


После сборки нужно все файлы из папки bin в этом репозитории скопировать в ту же папку, в которой разместился файл Whisper & Gemini Transcriber.exe

## Использование API-ключей Gemini для анализа расшифровки

API-ключ для вызова Gemini внутри приложения взять можно отсюда

https://aistudio.google.com/apikey
