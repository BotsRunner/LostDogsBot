## Функционал  
| Функционал                                              | Поддерживается |
|---------------------------------------------------------|:--------------:|
| Многопоточность                                         |       ✅        |
| Поддержка .session                                      |       ✅        |
| Поддержка прокси                                        |       ✅        |
| Авторегистрация в боте                                  |       ✅        |
| Авто выполнение заданий                                 |       ✅        |
| Авто выбор карты                                        |       ✅        |
| Сбор ежедневных наград                                  |       ✅        |
| Бот для управления вашими сессиями                                  |       ✅        |
| Поддержка 4х языков (Испанский, Русский, Английский, Немецкий) |       ✅        |


## [Настройки бота](https://github.com/GravelFire/LostDogsBot/blob/master/.env-example/)
| Настройка               |                                Описание                                 |
|-------------------------|:-----------------------------------------------------------------------:|
| **API_ID / API_HASH**   | Данные платформы, с которой запускать сессию Telegram (сток - Android)  | 
| **BOT_TOKEN**           | Токен бота, который вы можете взять у https://t.me/BotFather  | 
| **ADMIN_UID**           | Ваш уникальный идентификатор (Можно получить в https://t.me/myidbot), чтобы только вы могли им пользоваться (ботом в телеграмме)     | 
| **LANGUAGE_CODE**       | Язык, на котором будет работать наш бот, на данным момент доступны en-Английский, **de**-Немецкий, **es**-Испанский, **ru**-Русский. (Обратите внимание как их нужно записывать, рядом с названием языка написано сокращение, другое написание не подойдёт) _(дефолт. **ru**)_ |
| **AUTO_TASK**           |               Автовыполнение задач в игре  _(True / False)_                        |
| **RANDOM_CARD**         |      Авто-выбор случайной карты  _(True / False)_                                  |
| **REF_ID**		      |		Ваша реферальный ссылка после startapp=                                        |
| **SLEEP_TIME**          |          Время сна между циклами _(напр. [3000, 3600])_          |
| **USE_RANDOM_DELAY_IN_RUN**  | Использовать ли рандомную задержку при запуске _(True / False)_                               |
| **RANDOM_DELAY_IN_RUN**      | Рандомная задержка при запуске _(напр. [0, 15])
_                                               |
| **USE_RANDOM_DELAY_IN_RUN**  | Использовать ли фейковый юзер-агент _(True / False)_                               |
| **USE_PROXY_FROM_FILE** | Использовать-ли прокси из файла `proxies.txt`  _(True / False) |

## Команды бота
| Команда               |                                Описание                                 |
|-------------------------|:-----------------------------------------------------------------------:|
| /start                 | Запуск бота          |

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/) **Только версия 3.11**

## Получение API ключей
1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/GravelFire/LostDogsBot) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/GravelFire/LostDogsBot
cd LostDogsBot
```
## Запуск
Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Для быстрого запуска вы можете использовать аргументы, например:

```shell
~/LostDogsBot >>> python main.py --action (1/2)
# Или
~/LostDogsBot >>> python main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```

