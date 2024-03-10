# 📦 Sassify Type-of
Набор утилит (функций на языке CSS-препроцессора [Sass](https://github.com/sass)) для определения типов данных.

![Весрия пакета на npm](https://img.shields.io/npm/v/@sassify/type-of?label=%40sassify%2Ftype-of)
![Список языков](https://img.shields.io/github/languages/count/sassify/type-of?color=%23ff0056)
![Топ язык в репо](https://img.shields.io/github/languages/top/sassify/type-of?color=%23ff0056)
![Кол-во открытых ишью](https://img.shields.io/github/issues-raw/sassify/type-of)
![Кол-во открытых PR](https://img.shields.io/github/issues-pr-raw/sassify/type-of)
![Лицензия](https://img.shields.io/github/license/sassify/type-of)
![Версия зависимости `sass`](https://img.shields.io/github/package-json/dependency-version/sassify/type-of/sass/main?color=%23d94390)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/sassify/type-of)
![GitHub contributors](https://img.shields.io/github/contributors/sassify/type-of)
![GitHub last commit](https://img.shields.io/github/last-commit/sassify/type-of)

## Начало работы
Для начала необходимо установить npm-пакет `@sassify/type-of`:

```sh
npm install --save-dev @sassify/type-of
```

После установки зависимости в свой проект, импортируйте модуль Sassify Type-of:

```scss
@use 'node_modules/@sassify/type-of' as types;
```

Теперь все функции из Sassify Type-of доступна через пространство `types`:

```scss
// _styles.scss
$isDark: true;

@if types.is-bool($isDark) {
  // ...
}
```

> Весь код Sassify Type-of задокументирован с помощью комментариев SassDoc. Документация доступна по [этой](https://sassify.github.io/type-of/) ссылке.

## Сообщество
У проекта Sassify нет какого-либо сервера в Discord, но есть Telegram &mdash; [@sassify](https://t.me/sassify).

## Версии
Для обеспечения прозрачности цикла выпуска и стремления поддерживать обратную совместимость Sassify поддерживается в соответствии с рекомендациями [Semantic Versioning](https://semver.org/). Иногда я ошибаюсь, но я придерживаюсь этих правил, когда это возможно.

## Благодарности
Несмотря на то, что я умудрился как-то гармонично (надеюсь) уложить все эти функции, я не могу не выразить огромную благодарность след. персонажам:
- [Kitty Giraudel](https://github.com/KittyGiraudel) - за большое количество кода и статей по Sass,
- [takamoso](https://github.com/takamoso) - за полезный код,
- [Sindre Sorhus](https://github.com/sindresorhus) - за полезный код,
- разработчикам CSS-препроцессора [Sass](https://sass-lang.com/) - за непосредственно Sass,
- всем тем у кого я учился (хоть я и не помню ваши имена).

## Лицензия
Проект распространяется по свободной лицензии [MIT](./LICENSE), однако в проекте используются труды иных людей, чьё авторство я также обозначил в местах, где используется их код.
