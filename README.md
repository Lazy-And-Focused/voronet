# Воронет — система связанных чатов для стримов

![Логотип Воронет](https://example.com/path-to-logo.png)

**Воронет** — система объединённых чатов для стримеров, позволяющая синхронизировать общение со зрителями с разных платформ в едином интерфейсе

## О проекте

Воронет решает ключевую проблему мультистриминга — разрозненность чатов. Вместо мониторинга нескольких окон (Twitch, YouTube, VK Play Live и др.) вы получаете **единое пространство для общения** со зрителями

Основные возможности:

- Объединение чатов с разных платформ в один интерфейс
- Поддержка API для кастомной интеграции

## Использование API

Бэкенд используется в качестве выдачи данных для авторизации (см. [PlantUML](https://editor.plantuml.com/uml/bP5DJaGX48JtdA9MhiOBc616NStMdmDqe7N8UmyIQ3HpUtc4HGT_ajasNrMgYcCHobAtrHXhySm-P7OIuWUiDUPf3Hm5j_Tu9BTmzBZ32L_KRf90LSufXy9clExWGpk-SFuCZXiy34BvHQJ98MniS2GXnQRLOLpt6Ng5zTIljEmCnUaHBddkFIRl7p5FMia7d3apBgdcVeSdeIck6cGoBzKvBkMzhjgdHT4pZM6kKhUgCst__YHTo1yWj32so_yvUb7SuArmDiT6r6tz1W00))

В качетсве получения информации мы будем использовать вебхуки или вебсокеты

- [Twitch](https://dev.twitch.tv/docs/chat/send-receive-messages)
