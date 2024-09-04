# Макет проекта
<a href="https://www.figma.com/file/FEeiiGLOsE7ktXbPpBxYoD/Custom-dropdown?type=design&amp;node-id=0%3A1&amp;mode=design&amp;t=eXRJnWC6Xsuw0qR4-1" rel="nofollow">Макет проекта</a>

## О проекте
Данный проект - блог-кастомайзер, через панель настроек можно менять оформление страницы

**Стек**:  
HTML, SCSS, TypeScript, Webpack, React

**Реализованный функционал**:
- из готовых компонентов собрана бокавая открывающаяся панель настроек стилей страницы
- настроена передача данных между компонентами
- текущее состояние стилей страницы берется и записывается в localStorage

**Структура проекта**:
- src/ — исходные файлы проекта
- src/components/ — папка с JS компонентами

**Важные файлы**:
- public/index.html — HTML-файл главной страницы
- src/index.tsx — точка входа приложения
- src/constants/articleProps.ts — файл с константами и типами


## Установка и запуск
Для установки и запуска проекта необходимо выполнить команды

```
npm install
npm run start
```

## Сборка

```
npm run build
```

## Storybook
Для запуска Storybook выполните:

```
npm run storybook
```
