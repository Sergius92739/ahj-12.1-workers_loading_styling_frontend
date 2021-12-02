[![Build status](https://ci.appveyor.com/api/projects/status/vqh1ymrhy7rj9k6d/branch/master?svg=true)](https://ci.appveyor.com/project/Sergius92739/ahj-12-1-workers-loading-styling-frontend/branch/master)

#### Deployment: <a href="">Github Pages</a>
#### Backend: <a href="https://github.com/Sergius92739/ahj-12.1-workers_loading_styling_backend">Repository</a>
#### Server: <a href="https://ahj-workers-loading-styling.herokuapp.com/">Heroku</a>

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
