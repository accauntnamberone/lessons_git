 Попробуйте настроить это дома на своих компах, потому что тут в классе в след. раз прийдется это настраивать.

1. Нужно установить Node.js (https://nodejs.org/) - ставим рекомендуемую версию
2. Ставим GIT (https://git-scm.com/downloads) - устанавливаем от сюда
3. После пункта 2 появится в пуске Git - git-bash (запускаем его, откроется окно терминала)
4. Выполняем в нем команду npm install gulp -g
5.В этом терминале идем в папку что я прислал (СW6) и выполняем команду npm install.
6.Там же выполняем команду gulp watch

После этого при изменении scss файла файл css будет сам генериться по новому.
Попробуйте дописать какое-то свойство в scss файл и сохранить и если появится изменения в css файле то тогда все ОК.


npm config set registry "http://registry.npmjs.org"

npm config set proxy http://dn140488sdn1:dn140488sdn@proxy.pbank.com.ua:8080

npm config set strict-ssl false

npm install -g -d yo