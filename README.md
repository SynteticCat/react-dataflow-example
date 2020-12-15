# React dataflow

Очень долго не мог понять, что же такое Redux, наверное стоит всего навсего уделить этому больше времени,
в этом репозитории я разберусь в терминологии Redux и сделаю копию приложения по этой [статье](https://github.com/devSchacht/translations/tree/master/articles/tal-kol-redux-step-by-step-a-simple-and-robust-workflow-for-real-life-apps). По сути это пересказ статьи, так что вам нужен не этот репозиторий для понимания redux, а ссылка выше =)

# Пара слов о терминологии и применении Redux

## Flux
Чтобы понять, что такое Redux, сначала поймем, что такое Flux - это архитектурный подход к разработке пользовательского интерфейса веб-приложений, сочетающийся с реактивным программированием (не знаю, что это, но видимо имеет отношение к React) и однонаправленным потоком данных (Это то, что и реализует Redux!).
  
Flux упрощает разработку, создавая однонаправленный поток данных, эту идею и реализует библиотека Redux  
  
## Redux 
Redux - это библиотека управления состоянием приложений на JavaScript и одна из самых популярных реализаций идей Flux.


## Попробуем?
Redux часто используется вместе с React, давайте попробуем организовать приложение с использованием этих технологий.
Продуманный redux может реализовать несколько паттернов к примеру для работы с асинхронными данными. Что использовать? Саги, Промисы или Санки? 
Мы используем Санки по примеру из статьи. Но ввиду того, что мы используем Саги в проекте, потом попробуем все переделать на Саги!

## Что делаем?
- приложение точь в точь по статье на санках
- вторую версию приложения по статье на сагах
