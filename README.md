# Spunkybot_Sysmyks

[SpunkyBot Repository](https://github.com/SpunkyBot/spunkybot)  
**Version: v1.13.0**

## New Features & Commands
- **Added Commands:** `!top`, `!topruns`, `!transl`, `!glist`, `!goto`, `!setgoto`, `!delgoto`, and more.
- Improved functionality and compatibility with **ioq3_sysmyks**.

## Requirements
- Required Python modules (install using `pip`).

- **Python 2.7** for SpunkyBot.
   unidecode
   wget
   sqlite3
   ConfigParser

- **Python 3** for the translation module.
   openai

## Configuration
1. Set up your **OpenAI API key** in `mod/translation.py` (line 7):
   ```python
   client = openai.Client(api_key="your-api-key-here")
   ```
2. Configure **conf/settings.cfg** according to your server setup.
3. Ensure you have a `mapcycle.txt` file for the bot to function properly.
4. Set the correct path to `mapcycle.txt` in **conf/settings.cfg**.
5. To add a new map, it must be listed in `mapcycle.txt`.
6. Execute the bot and enjoy!

---
🚀 **Optimized for a better Urban Terror server experience!**
