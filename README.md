noscript
========
[![Build Status](https://travis-ci.org/yandex-ui/noscript.png?branch=master)](https://travis-ci.org/yandex-ui/noscript)
[![NPM version](https://badge.fury.io/js/noscript.png)](http://badge.fury.io/js/noscript)
[![Dependency Status](https://david-dm.org/yandex-ui/noscript.png)](https://david-dm.org/yandex-ui/noscript)

JS MVC framework

#### Changelog

##### 0.1.3 (28.08.2013)
- Новый `ns.page.history` объект для манипуляций с историей приложения
- Исправлена проблема с конкурентными async-обновлениями.
- Исправлен баг в `ns.router` с реврайтом урлов с параметрами (например, `/page1?foo=bar`)
- У `ns.Model` появился метод `destroyWith` [#149](https://github.com/yandex-ui/noscript/pull/149)

##### 0.1.1
- Fix #146 `ns.action` поломал инициализацию наноблоков
- #129 Ошибка при setData для модели коллекции без split
- Merge pull request #131 from yandex-ui/collection-key
- Merge pull request #141 from yandex-ui/view-collection-async
- Merge pull request #139 from yandex-ui/view-collection-doc
- Merge pull request #143 from yandex-ui/ns-page-typo


##### 0.1.0
Более менее стабильная версия. Попытка начать версионировать процесс.

