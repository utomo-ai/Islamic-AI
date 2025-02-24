# Islamic-AI
Utomo Muhammad Isa © 2025
Islamic A.I a full desktop Application integrated LLM and Local LLM with TTS. A.I assistant using SQL with Al-Qur'an and Hadith Search capabilities. A.I Summary on Web search.

RUN APP:
(Put LLAMAFILE in the same folder)

Islamic A.I.bat 	(Windows OS 64Bit)
32BIT.bat 		(Windows OS 32Bit)

NET-SQL.exe
----------------
This app is to convert all [NET] Web Search Results into a Database.
Click to create a new net.db in files/net/net.db

INSTALL FONT:
lvnm.ttf

ADD API KEYS:
GEMINI_API_KEY=<REGISTER_GOOGLE_GEMINI>
WA_APPID=<REGISTER_WolfRamAlpha>
YOUTUBE_API_KEY=<REGISTER_GOOGLE_CUSTOM_API_YOUTUBE>
GOOGLE_CSE_API_KEY=<REGISTER_GOOGLE_CUSTOM_API_SEARCH>
GOOGLE_CSE_CX=17ccb55a057d549a5
NEWS_API_KEY=<REGISTER_https://newsapi.org/>

PRAYER TIME
------------------
Methods = Muslim World League
1. SETTINGS (page)
2. SETTINGS.INI (SETTINGS32.INI)
    [BASIC]
    latitude = <latitude>
    longitude = <longitude>

A.I MODEL
-------------
LOCAL Model :
You need to install ollama (OLLAMA SETUP.txt)
llamafile :
Create a folder (eg. C:\llama)
Use LLM_FILE.bat to open llamafile
("C:\llama\qwen.llamafile.exe")

Browser Settings:
Ollama 		= http://localhost:11434
Lllamafile 	= http://localhost:8080

ONLINE Model:
Get API key from :https://aistudio.google.com/app/apikey

Slow Computer/Laptop :
TURN OFF TTS

Troubleshooting APP freeze:
- Temporary (Not Responding), because A.I generate response in a streaming with a long text. Responses with EMOJIS and XML/HTML formats. (You could tell A.I : No Emojis and HTML formats) 
- No Quota or Online Server Busy 


Text To Speech OPTIONS
----------------------
1. SETTINGS (page)
2. SETTINGS.INI (SETTINGS32.INI)
   [TTS SETTINGS]
   language = <YOUR LANGUAGE>
   lang_label = <LANGUAGE LABEL>

Google TTS support languages:
https://gtts.readthedocs.io/en/latest/module.html#languages-gtts-lang

English (Australia)
English (United Kingdom)
English (United States)
English (Canada)
English (India)
English (Ireland)
English (South Africa)
English (Nigeria)
French (Canada)
French (France)
Mandarin (China Mainland)
Mandarin (Taiwan)
Portuguese (Brazil)
Portuguese (Portugal)
Spanish (Mexico)
Spanish (Spain)
Spanish (United States)
