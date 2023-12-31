{
  "date": "2023-09-27",
  "keywords": [
    "cfg",
    "cfg file",
    "cfg wesnoth markup language file",
    "what is a cfg file",
    "how to open cfg file",
    "file",
    "cfg file extension",
    "extension"
  ],
  "author": {
    "display_name": "Shakeel Faiz"
  },
  "draft": "false",
  "toc": true,
  "title": "CFG File Format - Wesnoth Markup Language File",
  "description": "Научете за файловия формат на CFG Wesnoth Markup Language и API, които могат да създават и отварят CFG файлове.",
  "linktitle": "CFG Wesnoth",
  "menu": {
    "docs": {
      "identifier": "game-cfg-wesnoth",
      "parent": "game"
    }
  },
  "lastmod": "2023-09-27"
}

## Какво е CFG файл?

CFG файлът е известен още като **"Wesnoth Markup Language" (WML)**. Това е персонализиран език за маркиране, използван основно в играта „Battle for Wesnoth“, която е походова стратегическа игра. WML се използва за дефиниране и персонализиране на различни аспекти на играта, включително сценарии, кампании, единици и др. Това е начин модераторите и разработчиците да създават съдържание за играта.

Написан е във формат, който прилича на комбинация от XML и прост скрипт. Ето преглед на някои общи елементи и структури, които може да намерите в WML файл:

1. **Tags:** WML използва тагове, за да дефинира различни елементи в играта. Етикетите са оградени в ъглови скоби. Например:

```
[unit]
    type=Elvish Archer
    hitpoints=25
[/unit]
```
    
2. **Attributes:** В рамките на таговете можете да дефинирате атрибути, за да посочите свойства или стойности, свързани с елемента. В примера по-горе „type“ и „hitpoints“ са атрибути.
    
3. **Arrays and Arrays of Arrays:** Можете да създавате масиви от данни и дори масиви от масиви, за да дефинирате списъци с единици, типове терени или други елементи на играта.
    
4. **Conditional Statements::** WML поддържа условни изрази за контролиране на хода на играта. Например:

```
[if]
    condition=have_unit
    variable=x,y
[/if]
```
    
5.  **Loops:** Можете да използвате цикли, за да преминавате през списъци с елементи или да извършвате действия многократно.
    
6.  **Includes:** Можете да включите други WML файлове в основен WML файл, за да организирате и модулирате вашето съдържание.
    
7.  **Event Handlers:** Можете да дефинирате манипулатори на събития, за да задействате действия, когато се появят конкретни събития в играта.
    

Ето опростен пример за WML файл, който дефинира потребителска единица:

```
[unit_type]
    id=my_custom_unit
    name="Custom Unit"
    description="A unit created using WML."
    image="units/my_custom_unit.png"
    hitpoints=30
    movement_type=foot
[/unit_type]
```

## The Battle for Wesnoth

„The Battle for Wesnoth“ е популярна походова стратегическа игра с отворен код. Предлага се за множество платформи, включително Mac, Windows, Linux и др. Разработена от специализирана общност от доброволци, играта е известна със своя дълбок и увлекателен геймплей, както и с богатия си фантастичен свят.

Основните характеристики на "The Battle for Wesnoth" включват:

1. **Фентъзи обстановка:** Играта се развива във фантастичен свят с различни раси, включително хора, елфи, джуджета, орки и др. Историята и историята на играта са неразделна част от нейната привлекателност.
    
2. **Походова стратегия:** Играта е походова, където играчите отделят време, за да планират и изпълнят ходовете си върху шестоъгълни мрежи. Той съчетава тактическа битка със стратегическо вземане на решения.
    
3. **Кампании:** Играта предлага широка гама от кампании за един играч, всяка със собствен сюжет, герои и предизвикателства. Играчите могат да изследват различни разкази и сценарии.
    
4. **Мултиплейър:** "Wesnoth" поддържа онлайн мултиплейър, което позволява на играчите да се състезават един срещу друг в стратегически битки. Режимите за мултиплейър включват кооперативна игра и състезателни мачове.

## Как да отворя CFG файл?

CFG файловете, които обикновено се свързват с Wesnoth Markup Language (WML), използван в играта "The Battle for Wesnoth", могат лесно да се редактират с помощта на всеки стандартен текстов редактор. Тези файлове съдържат четим от човека код, написан на WML, който дефинира различни аспекти на играта, включително сценарии, единици и кампании.

Докато можете да използвате всеки текстов редактор, за да модифицирате CFG файлове, някои усъвършенствани текстови редактори като Emacs и Vi имат налични плъгини за подчертаване на WML синтаксис. Тези плъгини предоставят полезно цветово кодиране и форматиране, за да улеснят потребителите да разграничават различни елементи и структури в WML кода.

Програмите, които отварят или препращат към CFG файлове, включват

- The Battle for Wesnoth (Free) for (Windows, MAC, Linux)
- Microsoft Notepad

## Други CFG файлове

Ето други типове файлове, които използват файловото разширение **.cfg**.

**Settings**
- [CFG - Celestia Configuration File](/settings/cfg-celestia/)
- [CFG - Citrix Server Connection File](/settings/cfg-citrix/)
- [CFG - MAME Configuration File](/settings/cfg-mame/)
- [CFG - LightWave Configuration File](/settings/cfg-lightwave/)

**Game**
- [CFG - Wesnoth Markup Language File](/game/cfg-wesnoth/)
- [CFG - M.U.G.E.N Configuration File](/game/cfg-mugen/)
- [CFG - Source Engine Configuration File](/game/cfg-sourceengine/)

**System & Misc**
- [CFG - CFG File](/system/cfg/)
- [CFG - Cal3D Model Configuration File](/misc/cfg-cal3d/)

## Препратки
* [The Battle for Wesnoth](https://en.wikipedia.org/wiki/The_Battle_for_Wesnoth)