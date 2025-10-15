# 🏙️ rp_bangclaw_green

### 🌎 Основан на: [`rp_bangclaw_yellow`][github_rp_bangclaw]

**rp_bangclaw_green** — это расширенное и переосмысленное видение оригинальной карты **rp_bangclaw**.  
Мы решили разграничить и аккуратно реализовать все свои идеи, чтобы сделать карту именно такой, какой по нашему мнению она должна была быть изначально

> [!NOTE]
> **Проект находится в активной разработке.**  
> Когда карта будет готова, мы опубликуем:  
> - 📦 **Скомпилированную BSP-версию**  
> - 🛠️ Версию в **Steam Workshop**

### 🔧 Для разработчиков

1. **Скачайте или клонируйте репозиторий**  
   Репозиторий содержит все исходные VMF-файлы и дополнительный контент
2. **Скопируйте папку `content` в директорию:**  
   ```
   ..\steamapps\common\GarrysMod\garrysmod\addons
   ```

### 🐞 Сообщить об ошибке

Нашли ошибку, баг или хотите предложить улучшение?  
[Создайте issue][github_new_issue] или напишите в **Discord**: `yaroslavtarka`

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
| **VVIS**    | _без параметров_                                                    |
| **VRAD**    | `-StaticPropPolys -TextureShadows -StaticPropLighting -LDR -Final`  |

### 👥 Разработчики

- [**Tarka**][steam_tarka] 🛠️
- [**Web_Artur**][steam_webartur] 🌿

### 📌 Ссылки

- 📂 [Оригинальный репозиторий карты `rp_bangclaw_yellow`][github_rp_bangclaw]

<!-- Links -->
[steam_webartur]: https://steamcommunity.com/profiles/76561198115550963
[steam_tarka]: https://steamcommunity.com/profiles/76561198994995839
[github_new_issue]: https://github.com/YaroslavTarka/rp_downtown_tits.vmf-fix/issues/new
[github_rp_bangclaw]: https://github.com/YaroslavTarka/rp_bangclaw.vmf-fix-