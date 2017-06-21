# Apache Sling - Bringing Back the Fun!

## CMS
- для чего (цели и задачи)
- как (пишем CMS сами)
- еще для чего\* (растущие запросы бизнеса)
- как\* (берем коробочный продукт)
- что внутри коробочного продукта

## Apache Jackrabbit
- назначение
- JSP-170 & API
- модели работы и взаимодействия с приложениями (bundled, контейнер, standalone)
- что под капотом
    - storage
    - workspace tree
    - node types
    - OAK
- performance
- кто использует (Apache Sling, Magnolia CMS etc)

## Apache Sling
- OSGI-powered JCR-based REST middleware
- зачем, назначения и концепция
- open source из хорошей семьи (Adobe)
- архитектура
    - Apache Felix
    - концепция OSGI
    - DI -- бандлы, компоненты и сервисы
- иерархия в WEB (+REST) == иерархия JCR
- resource resolver as controller
- resource type -- у каждой ноды свой тип, который можно...
- ...представить в любом виде (scripting (JSP, HTL, ESP etc (Ruby? Scala?))
- применения для сегодняшнего WEB -- серверный рендеринг, кэш и REST data-provider
- собственный JobManager
- тестирование
- performance
