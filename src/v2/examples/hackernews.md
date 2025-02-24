---
title: Клон HackerNews
type: examples
order: 12
---

> Это клон HackerNews, построенный на Firebase API, Vue 2.0 + Vue Router + Vuex, с использованием серверной отрисовки.

{% raw %}
<div style="max-width: 600px;">
  <a href="https://github.com/vuejs/vue-hackernews-2.0" target="_blank" rel="noopener noreferrer">
    <img style="width: 100%;" src="../../images/hn.png">
  </a>
</div>
{% endraw %}

> [Пример](https://vue-hn.herokuapp.com/)
> Примечание: приложению, возможно, потребуется некоторое время на развёртывание, если никто не просматривал его в течение длительного периода.
>
> [[Источник](https://github.com/vuejs/vue-hackernews-2.0)]

## Возможности

- Серверная отрисовка
  - Связка Vue + Vue Router + Vuex
  - Предварительное получение данных на сервере
  - Клиентское состояние и гидратация DOM
- Использование однофайловых компонентов
  - Горячая замена модулей в development-окружении
  - Экстракция CSS в production-окружении
- Обновление списка в реальном времени с FLIP-анимацией

## Обзор архитектуры

[<img width="973" alt="Обзор архитектуры клона HackerNews" src="/images/hn-architecture.png">](../../images/hn-architecture.png)
