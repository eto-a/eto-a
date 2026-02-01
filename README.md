<div align="center">

# Artem Piskov • eto-a

Интерактивные **WebXR / WebGL** прототипы и тестовые билды (**Unity WebGL**, **UE4 HTML5**) — быстро, чисто, в реальном времени.

[Профиль](https://github.com/eto-a) • [Репозитории](https://github.com/eto-a?tab=repositories)

<br/>

<img alt="HTML5" src="https://img.shields.io/badge/HTML5-111?style=flat&logo=html5&logoColor=white">
<img alt="CSS3" src="https://img.shields.io/badge/CSS3-111?style=flat&logo=css3&logoColor=white">
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-111?style=flat&logo=javascript&logoColor=white">
<img alt="WebGL" src="https://img.shields.io/badge/WebGL-111?style=flat&logo=webgl&logoColor=white">
<img alt="WebXR" src="https://img.shields.io/badge/WebXR-111?style=flat&logo=webxr&logoColor=white">
<img alt="Unity" src="https://img.shields.io/badge/Unity-111?style=flat&logo=unity&logoColor=white">
<img alt="Unreal Engine" src="https://img.shields.io/badge/Unreal%20Engine-111?style=flat&logo=unrealengine&logoColor=white">

</div>

---

<a name="toc"></a>

## Содержание
- [Избранные проекты](#featured)
- [Фокус](#focus)
- [Техстек](#stack)
- [Сейчас](#now)
- [Коллаборация](#collab)
- [Ещё](#more)
- [Extras](#extras)

<a name="featured"></a>

## Избранные проекты

| Проект | Направление | Сигналы в репозитории | Ссылка |
|---|---|---|---|
| **webar** | Unity WebGL / web runtime | `Build/`, `TemplateData/`, `index.html` | [Repo](https://github.com/eto-a/webar) |
| **ARVT** | WebXR / браузерный AR/VR | `webxr.js`, `gl-matrix-min.js`, `Build/`, `TemplateData/` | [Repo](https://github.com/eto-a/ARVT) |
| **carwebxr** | Unity WebGL + экспериментальная обвязка | `Build/`, `TemplateData/`, `Native/`, `index.html` | [Repo](https://github.com/eto-a/carwebxr) |
| **WebGLTest** | Unity WebGL / тест сборки | `Build/`, `TemplateData/`, `index.html` | [Repo](https://github.com/eto-a/WebGLTest) |
| **html5test** | UE4 HTML5 export / хостинг теста | `UE4Game.js`, `.wasm`, `.data`, `.htaccess` | [Repo](https://github.com/eto-a/html5test) |
| **ZappatTest** | Web build / ассеты рядом с рантаймом | `StreamingAssets/`, `Build/`, `index.html` | [Repo](https://github.com/eto-a/ZappatTest) |

<a name="focus"></a>

## Фокус
- интерактивные прототипы для браузера: **WebGL** сцены, рантайм-обвязка, быстрый запуск
- **WebXR**-эксперименты: вход/трекинг/сцена/UX в VR/AR контуре
- сборки и выкладка **Unity WebGL** (структура `Build/` + `TemplateData/`)
- тестовые пайплайны и форматы экспорта (включая **UE4 HTML5**)

<a name="stack"></a>

## Техстек
**Бейджи:**  
<img alt="HTML5" src="https://img.shields.io/badge/HTML5-111?style=flat&logo=html5&logoColor=white">
<img alt="CSS3" src="https://img.shields.io/badge/CSS3-111?style=flat&logo=css3&logoColor=white">
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-111?style=flat&logo=javascript&logoColor=white">
<img alt="WebGL" src="https://img.shields.io/badge/WebGL-111?style=flat&logo=webgl&logoColor=white">
<img alt="WebXR" src="https://img.shields.io/badge/WebXR-111?style=flat&logo=webxr&logoColor=white">
<img alt="Unity" src="https://img.shields.io/badge/Unity-111?style=flat&logo=unity&logoColor=white">
<img alt="Unreal Engine" src="https://img.shields.io/badge/Unreal%20Engine-111?style=flat&logo=unrealengine&logoColor=white">

**Коротко:**
- **JavaScript/HTML/CSS**: загрузка, UI-обвязка, запуск билдов, минимальный “glue layer”
- **Unity WebGL**: выкладка и тестирование экспортов (`Build/`, `TemplateData/`)
- **WebXR**: браузерный VR/AR контур (эксперименты вокруг `webxr.js`)
- **UE4 HTML5**: тестовые экспорты (`UE4Game.js`, `.wasm`, `.data`)

<a name="now"></a>

## Сейчас
- собираю компактные демо-репозитории для **быстрого просмотра** и проверки окружения
- упрощаю структуру “билд → загрузка → старт” для WebGL/WebXR
- держу проекты в виде **малых, изолируемых экспериментов** (легко форкать / сравнивать)

<a name="collab"></a>

## Коллаборация (GitHub-native)
- **Баг/идея/улучшение**: открывайте **Issue** в репозитории проекта
- **Правка/улучшение**: делайте **Pull Request**
- **Вопрос по конкретному репо**: закрепляйте контекст ссылкой на файл/строку/шаг воспроизведения

Быстрый вход: [Список репозиториев](https://github.com/eto-a?tab=repositories)

<a name="more"></a>

## Ещё

<details>
<summary><b>Эксперименты / тестовые билды</b></summary>

- [webar](https://github.com/eto-a/webar) — Unity WebGL билд-структура и запуск
- [ARVT](https://github.com/eto-a/ARVT) — WebXR-обвязка + ассеты
- [carwebxr](https://github.com/eto-a/carwebxr) — Unity WebGL + доп. папки под эксперименты
- [WebGLTest](https://github.com/eto-a/WebGLTest) — минимальный тест WebGL билда
- [html5test](https://github.com/eto-a/html5test) — UE4 HTML5 экспорт для проверки хостинга
- [ZappatTest](https://github.com/eto-a/ZappatTest) — билд с `StreamingAssets/` рядом

</details>

<details>
<summary><b>Навигация</b></summary>

- [Профиль](https://github.com/eto-a)
- [Репозитории](https://github.com/eto-a?tab=repositories)
- [Stars](https://github.com/eto-a?tab=stars)

</details>

<a name="extras"></a>

## Extras
<img alt="Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=eto-a&hide_border=true&area=true">
