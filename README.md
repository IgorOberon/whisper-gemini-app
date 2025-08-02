# whisper-gemini-app
Эта программа транскрибирует audio с помощью whisper. Кроме того, по API она подключается к Gemini 2.5 Pro и согласно промту, который можно редактировать и менять, анализирует содержимое расшифровки.
Сборку программы можно делать так 

pyinstaller --noconsole --name "Whisper & Gemini Transcriber" t_app3.py (например, в Anaconda Powershell Prompt)

API-ключ для вызова Gemini внутри приложения взять можно отсюда

https://aistudio.google.com/apikey

В архиве dist находится уже собранная программа, достаточно скачать папку, распаковать архив и просто запустить.
