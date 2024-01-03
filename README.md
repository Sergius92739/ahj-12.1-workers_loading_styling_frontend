[![Build status](https://ci.appveyor.com/api/projects/status/26m6aafgf8tbq8cs/branch/master?svg=true)](https://ci.appveyor.com/project/Sergius92739/ahj-12-1-workers-loading-styling-frontend/branch/master)

#### Deployment: <a href="https://sergius92739.github.io/ahj-12.1-workers_loading_styling_frontend/">Github Pages</a>
#### Backend: <a href="https://github.com/Sergius92739/ahj-12.1-workers_loading_styling_backend">Repository</a>
#### Server: <a href="https://ahj-12-1.sergem.xyz/">Облачный сервер</a>

---

### Loading Styling

#### Легенда

Сейчас модно показывать интерфейсы загрузки вроде следующего:

![](./pic/loading.png)

#### Описание

Реализуйте подобный интерфейс, закешировав статические ресурсы и показывая данный внешний вид до момента загрузки данных.

Обратите внимание, даже если у пользователя нет подключения, страница всё равно должна отображаться, но в режиме "загрузки" и после неудачной попытки соединения переходить в режим:

![](./pic/loading-2.png)

Для эмуляции задержки можете самостоятельно написать middleware для koa, или посмотреть на существующие вроде [koa-slow](https://github.com/bahmutov/koa-slow)

Напоминаем, что для кэширования вы можете воспользоваться плагином Workbox.
