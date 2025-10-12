🌎 Карта, взятая за основу: `rp_bangclaw_yellow`

🔮 Ссылка на [**VMF-исходник**](https://github.com/YaroslavTarka/rp_bangclaw.vmf-fix-)

> [!NOTE]
**Данный проект находится в постоянной разработке**.  
Когда мы будем уверены, что проект **rp_bangclaw_green** готов, мы выложим его в формате **BSP** в **WORKSHOP**.  
Также пользователи смогут получить доступ к исходному **VMF-файлу** в данном **GitHub**.

### 🔧 Для разработчиков

1. **Скачайте или клонируйте репозиторий**  
Репозиторий содержит все исходные VMF-файлы и дополнительный контент
2. **Скопируйте папку content по директории**  
`GarrysMod/garrysmod/addons`

### ⚙️ Настройки компиляции

**VBSP:**  _без параметров_  
**VVIS:**  _без параметров_  
**VRAD:** `-StaticPropPolys -TextureShadows -StaticPropLighting -LDR -Final`

В файл `GarrysMod/garrysmod/lights.rad` были добавлены следующие строки:

```
forcetextureshadow props/de_inferno/tree_small.mdl
forcetextureshadow props/de_inferno/tree_large.mdl
forcetextureshadow props_c17/fence01a.mdl
forcetextureshadow props_c17/fence01b.mdl
forcetextureshadow props_c17/fence03a.mdl
forcetextureshadow metal/metalfence001a
```

🔗 **Разработчики**
- [**Tarka**][steam_tarka]
- [**Web_Artur**][steam_webartur]

<!-- Links -->

[steam_webartur]: https://steamcommunity.com/profiles/76561198115550963
[steam_tarka]: https://steamcommunity.com/profiles/76561198994995839
[github_new_issue]: https://github.com/YaroslavTarka/rp_downtown_tits.vmf-fix/issues/new