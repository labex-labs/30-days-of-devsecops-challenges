# 30 дней DevSecOps-челленджей

## Языки

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![30 дней DevSecOps-челленджей](https://course-cover.labex.io/30-days-of-devsecops-challenges.png?lang=ru)](https://labex.io/ru/courses/30-days-of-devsecops-challenges)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ru/courses/30-days-of-devsecops-challenges)

30-дневный маршрут DevSecOps-челленджей из Linux и Docker security labs: от аудита host exposure к permissions, secrets, service identity, container hardening, Compose isolation, image hygiene и incident cleanup.

![devops](https://img.shields.io/badge/devops-whitesmoke?style=for-the-badge&logo=devops)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## Упражнения

|   Индекс | Название                                                  | Сложность   | Практика                                                                                                                                                          |
|----------|-----------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 🎯 🆓 Аудит прослушиваемых сервисов                         | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-audit-listening-services-662167?course=30-days-of-devsecops-challenges'>Начать Испытание</a>              |
|       02 | 🎯 🆓 Удаление ненужного публичного порта                   | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-remove-unnecessary-public-port-662316?course=30-days-of-devsecops-challenges'>Начать Испытание</a>        |
|       03 | 🎯 🆓 Ограничение доступа к интерфейсу администратора че... | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-restrict-admin-interface-to-localhost-662317?course=30-days-of-devsecops-challenges'>Начать Испытание</a> |
|       04 | 🎯 🆓 Отключение листинга веб-каталогов                     | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-disable-web-directory-listing-662309?course=30-days-of-devsecops-challenges'>Начать Испытание</a>         |
|       05 | 🎯 🆓 Удаление открытого архива резервной копии             | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-remove-exposed-backup-archive-662313?course=30-days-of-devsecops-challenges'>Начать Испытание</a>         |
|       06 | 🎯 🆓 Исправление небезопасных прав доступа к файлу с се... | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-fix-unsafe-secret-file-permissions-662310?course=30-days-of-devsecops-challenges'>Начать Испытание</a>    |
|       07 | 🎯 🆓 Исправление прав доступа к веб-директории с доступ... | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-fix-world-writable-web-directory-662311?course=30-days-of-devsecops-challenges'>Начать Испытание</a>      |
|       08 | 🎯  Выделенный пользователь службы                         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/dedicated-service-user-662278?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                      |
|       09 | 🎯  Файл окружения службы                                  | Средний     | <a target='_blank' href='https://labex.io/ru/labs/service-env-file-662284?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                            |
|       10 | 🎯  Ограничение прав доступа к логам                       | Средний     | <a target='_blank' href='https://labex.io/ru/labs/log-write-boundary-662281?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                          |
|       11 | 🎯  Удаление жестко закодированных учетных данных          | Средний     | <a target='_blank' href='https://labex.io/ru/labs/linux-remove-hardcoded-credentials-662314?course=30-days-of-devsecops-challenges'>Начать Испытание</a>          |
|       12 | 🎯  Управление секретами в переменных окружения процес...  | Средний     | <a target='_blank' href='https://labex.io/ru/labs/process-env-secret-662282?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                          |
|       13 | 🎯  Удаление избыточных прав sudo                          | Средний     | <a target='_blank' href='https://labex.io/ru/labs/linux-remove-over-permissive-sudo-rule-662315?course=30-days-of-devsecops-challenges'>Начать Испытание</a>      |
|       14 | 🎯  Безопасный путь (PATH) для скрипта                     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/safe-script-path-662283?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                            |
|       15 | 🎯  Укрепление безопасности задания cron, выполняемого...  | Средний     | <a target='_blank' href='https://labex.io/ru/labs/linux-harden-root-run-cron-job-662312?course=30-days-of-devsecops-challenges'>Начать Испытание</a>              |
|       16 | 🎯  Аудит передачи стека Compose                           | Средний     | <a target='_blank' href='https://labex.io/ru/labs/compose-handoff-audit-662564?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                       |
|       17 | 🎯  Аудит портала поддержки                                | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/support-portal-audit-662472?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                        |
|       18 | 🎯  Раскрытие метрик через эндпоинт                        | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/metrics-endpoint-exposure-662477?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                   |
|       19 | 🎯  Локальная консоль отладки                              | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/local-debug-console-662476?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                         |
|       20 | 🎯  Доступ к внутренней базе данных                        | Средний     | <a target='_blank' href='https://labex.io/ru/labs/internal-database-access-662567?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                    |
|       21 | 🎯  Монтирование конфигурации в режиме «только для чте...  | Средний     | <a target='_blank' href='https://labex.io/ru/labs/read-only-config-mount-662479?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                      |
|       22 | 🎯  Рабочий процесс обработки изображений без прав roo...  | Средний     | <a target='_blank' href='https://labex.io/ru/labs/non-root-image-worker-662478?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                       |
|       23 | 🎯  Сборщик логов с минимальными привилегиями              | Средний     | <a target='_blank' href='https://labex.io/ru/labs/least-privilege-log-collector-662475?course=30-days-of-devsecops-challenges'>Начать Испытание</a>               |
|       24 | 🎯  Webhook Docker Socket                                  | Средний     | <a target='_blank' href='https://labex.io/ru/labs/webhook-docker-socket-662481?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                       |
|       25 | 🎯  Ограничение секретов в Compose                         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/scoped-compose-secret-662569?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                       |
|       26 | 🎯  Разделение сетей сервисов                              | Средний     | <a target='_blank' href='https://labex.io/ru/labs/split-service-networks-662571?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                      |
|       27 | 🎯  API-токен в переменных окружения                       | Средний     | <a target='_blank' href='https://labex.io/ru/labs/api-token-in-env-662473?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                            |
|       28 | 🎯  Устранение утечки токена при сборке                    | Средний     | <a target='_blank' href='https://labex.io/ru/labs/build-token-leak-662474?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                            |
|       29 | 🎯  Безопасный образ рабочего процесса                     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/safer-worker-image-662480?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                          |
|       30 | 🎯  Очистка после отладки инцидента                        | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/incident-debug-cleanup-662566?course=30-days-of-devsecops-challenges'>Начать Испытание</a>                      |

## О LabEx

[LabEx](https://labex.io) - это интерактивная практическая обучающая платформа, посвященная программированию и технологиям. Она объединяет лаборатории, ИИ-помощь и виртуальные машины для обеспечения практического обучения без видео. Со строгим подходом 'Учись делая', интерактивными онлайн-средами в браузере с автоматизированными пошаговыми проверками, структурированной организацией контента с системой на основе Дерева Навыков, и растущим учебным ресурсом из 30 Деревьев Навыков и более 6,000 Лабораторий, [LabEx](https://labex.io) предлагает всестороннее практическое образование. Платформа включает ассистента обучения Labby, построенного на последних моделях ИИ, обеспечивающего разговорный опыт обучения.

## Больше

- 🔗 [ Курсы программирования](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [ Проекты программирования](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [ Бесплатные туториалы](https://github.com/labex-labs/devops-free-tutorials)

