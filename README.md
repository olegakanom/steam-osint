# Поиск по аккаунту Steam (OSINT 2025)
Актуальная подборка инструментов и ссылок для сбора информации по аккаунту Steam (ID, история ников, аватары, статистика, игры, взаимодействия и т.д.).      

Наш дискорд канал ( пробивы по фио, почтам , адресу , аккаунтам в соцсетях и т.д ) - https://discord.gg/zDNW39HKva       

Мануалы по подключениям к чужим IP-камерам тут ( слитые ) - https://t.me/+B-o_2HZOffxjYjFi      


## Основные инструменты
| №  | Сервис / Инструмент                                                                 | Что находит / Что делает                                                                 |
|----|-------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| 1  | [cipher387.github.io/quickcacheandarchivesearch](https://cipher387.github.io/quickcacheandarchivesearch/) | Покажет архивированную страницу, даст 20+ прямых ссылок на веб-архивы, поиск по ссылке на аккаунт |
| 2  | [socid_extractor (GitHub)](https://github.com/soxoj/socid_extractor)                | Найдёт Steam ID даже скрытого аккаунта                                                    |
| 3  | [steamid.uk](https://steamid.uk/)                                                   | Поиск по Steam ID, логину, Steam3, Community ID; история ников, дата создания, аватары, статистика друзей |
| 4  | [rep.tf](https://rep.tf/)                                                           | Агрегирует информацию об аккаунте из разных источников                                   |
| 5  | [steamidfinder.com/lookup](https://steamidfinder.com/lookup/)                       | Кешированная информация аккаунта                                                         |
| 6  | [steamid.io](https://steamid.io/)                                                   | Найдёт все ID, старый кастомный URL, имя и локацию                                       |
| 7  | [findsteamid.com](https://findsteamid.com/)                                         | Найдёт все ID, картинку аккаунта и дату создания                                         |
| 8  | [steamdb.info](https://steamdb.info/)                                               | Найдёт все ID, операционную систему и другое                                             |
| 9  | [Steam-OSINT-TOOL (GitHub)](https://github.com/matiash26/Steam-OSINT-TOOL)          | Покажет взаимодействия с другими аккаунтами Steam, список публичных комментариев         |
| 10 | [steamdb.info/calculator](http://steamdb.info/calculator/)                          | Посчитает сколько потратил пользователь на игры, даст статистику                         |
| 11 | [steamhistory.net](https://steamhistory.net/)                                       | История имени, аватаров, друзей, комментариев и прочее                                   |
| 12 | [logs.tf](https://logs.tf/)                                                          | История матчей в Team Fortress 2                                                         |
| 13 | [trends.tf](https://trends.tf/)                                                     | История имён в Team Fortress 2 и подробная статистика игрока                             |
| 14 | [rgl.gg](https://rgl.gg/)                                                           | Матчи в Team Fortress 2, может показать архивное имя и аватарку                          |
| 15 | [ugcleague.com/playersearch.cfm](https://www.ugcleague.com/playersearch.cfm)        | Найдёт страну пользователя (флаг возле имени) и прочее                                   |
| 16 | [cltf2.com/users](https://www.cltf2.com/users)                                      | История вступления в команды TF2, лиги и посты на форуме                                  |
| 17 | [csstats.gg](https://csstats.gg/)                                                   | Подробная статистика и история имён в Counter-Strike; перебирай матчи для доп. имён      |
| 18 | [faceittracker.net](https://faceittracker.net/)                                      | Подробная статистика на FACEIT, прошлые имена, карта активности, репорты                 |
| 19 | [faceitfinder.com](https://faceitfinder.com/)                                       | Краткая сводка об аккаунте на FACEIT, ссылка на профиль                                   |
| 20 | [opendota.com](https://opendota.com/)                                               | Архивная информация в Dota 2: карта активности, облако слов из чата, тепловая карта      |
| 21 | [stratz.com](https://stratz.com/)                                                   | Подробная статистика и история никнейма в Dota 2, карта активности, рейтинг порядочности |

## Поиск через URL
| №  | Ссылка                                                                              | Что покажет                                                                              |
|----|-------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| 1  | https://steamcommunity.com/id/USERNAME/videos                                       | Видео, скриншоты, коллекции пользователя и многое другое (замени USERNAME на ник)       |
| 2  | https://steamcommunity.com/id/12345678/recommended                                  | Обзоры пользователя (замени 12345678 на SteamID)                                         |
| 3  | https://steamcommunity.com/id/USERNAME/posthistory/                                 | Все сообщения пользователя (требуется авторизация, замени USERNAME)                      |
| 4  | https://steamcommunity.com/profiles/12345678/namehistory                            | История изменения имени (замени 12345678 на SteamID64)                                   |
