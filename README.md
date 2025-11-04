# 🏙️ rp_bangclaw_green

### 🌎 Основан на: [`rp_bangclaw_yellow`][github_rp_bangclaw]

**rp_bangclaw_green** — это расширенное и переосмысленное видение оригинальной карты **rp_bangclaw**  
Мы решили разграничить и аккуратно реализовать все свои идеи, чтобы сделать карту именно такой, какой по нашему мнению она должна была быть изначально

> [!NOTE]
> **Проект находится в активной разработке**  
> Когда карта будет готова, мы опубликуем:
> - 📦 **Скомпилированную BSP-версию**
> - 🛠️ Версию в **Steam Workshop**

### 🐞 Сообщить об ошибке

Нашли ошибку или хотите предложить улучшение?  
[Создайте issue][github_new_issue] или сообщите в **Discord**: `yaroslavtarka`

### 🔧 Для разработчиков

1. **Скачайте или клонируйте репозиторий**  
Репозиторий содержит все исходные VMF-файлы и дополнительный контент  
*Распакуйте архив, если вы скачали репозиторий в виде ZIP-файла 🗜️*
2. **Переместите папку `content` в директорию:**
	```
	..\steamapps\common\GarrysMod\garrysmod\addons
	```
*Вы также можете хранить репозиторий в другом месте, указав путь к нему в `mount.cfg`  
Недостаток этого метода в том, что игра не видит папку `scripts`  
Из-за этого невозможно наблюдать изменения в `soundscape_bangclaw.txt` в реальном времени*

### ⚙️ Параметры компиляции

📄 В файл `GarrysMod/garrysmod/lights.rad` добавьте следующие строки:

```
forcetextureshadow props/de_inferno/tree_small.mdl
forcetextureshadow props/de_inferno/tree_large.mdl
forcetextureshadow props_c17/fence01a.mdl
forcetextureshadow props_c17/fence01b.mdl
forcetextureshadow props_c17/fence03a.mdl
forcetextureshadow metal/metalfence001a
```

| Этап        | Параметры                                                           |
|-------------|---------------------------------------------------------------------|
| **VBSP**    | _без параметров_                                                    |
| **VVIS++**    | _без параметров_                                                  |
| **VRAD**    | `-StaticPropPolys -TextureShadows -StaticPropLighting -LDR -Final`  |

Мы используем [**модифицированный компилятор видимости VVIS++**][vvis++_ficool2]  
*Подробнее о **VVIS++** вы можете ознакомиться на [**Valve Developer Community**][vvis++_VDC]*

### 🛠️ Разработчики

- [**YaroslavTarka**][steam_tarka] — Основатель проекта
- [**Web_Artur**][steam_webartur] (*boxden*) — Маппер 🔨

### 🔗 Полезные ссылки

- 🟨 [**Репозиторий карты rp_bangclaw_yellow**][github_rp_bangclaw]
- ⚙️ [**Улучшенный компилятор VVIS++**][vvis++_ficool2] | [*Подробнее о VVIS++*][vvis++_VDC]

<!-- Links -->
[steam_webartur]: https://steamcommunity.com/profiles/76561198115550963
[steam_tarka]: https://steamcommunity.com/profiles/76561198994995839
[github_new_issue]: https://github.com/YaroslavTarka/rp_downtown_tits.vmf-fix/issues/new
[github_rp_bangclaw]: https://github.com/YaroslavTarka/rp_bangclaw.vmf-fix-
[vvis++_ficool2]: https://ficool2.github.io/HammerPlusPlus-Website/tools.html
[vvis++_VDC]: https://developer.valvesoftware.com/wiki/VVIS%2B%2B
