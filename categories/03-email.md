# 📧 Email-адреса

Поиск информации по электронной почте: владелец, связанные аккаунты, утечки паролей.

## Обратный поиск email

| Сервис | Описание |
|--------|----------|
| [Hunter](https://hunter.io/) | Поиск email по имени и компании |
| [reversegenie.com](http://www.reversegenie.com/email.php) | Платный отчёт по email |
| [email2phonenumber](https://github.com/martinvigo/email2phonenumber) | Получение телефона по email |

## Проверка на утечки

| Сервис | Описание |
|--------|----------|
| [Have I Been Pwned](https://haveibeenpwned.com/) | Наличие адреса в утечках, список затронутых баз |
| [Hacked Emails](https://hacked-emails.com/) | Проверка email на публичные дампы |
| [LeakCheck](https://leakcheck.net) | Платный поиск по утечкам |
| [Snusbase](https://snusbase.com) | Платный сервис поиска по дампам |
| [Firefox Monitor](https://monitor.firefox.com/breaches) | Свежие утечки с уведомлениями |
| [WeLeakInfo](http://weleakinfo.com) | Поиск по скомпрометированным базам |
| [GhostProject](https://ghostproject.fr/) | Проверка паролей из утечек |

## Инструменты

- [LeakLooker](https://github.com/woj-ciech/LeakLooker) — поиск открытых баз через Shodan (нужен API-ключ).
- `email2phonenumber` — связка email → телефон, из которой строится дальнейший пробив.

## Методы

- Простой поиск email в кавычках в Google/Yandex часто выдаёт профили на разных площадках.
- Проверяйте один адрес в нескольких базах утечек — покрытие у сервисов разное.
- Обратите внимание на плюс-теги (`user+tag@gmail.com`) — они указывают, где был зарегистрирован аккаунт.

## Смежные категории

- Утечки и базы → [12-utechi.md](12-utechi.md)
- Никнеймы → [04-niki.md](04-niki.md)
