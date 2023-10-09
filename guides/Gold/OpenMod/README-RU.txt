--- UnturnedGuard Gold для OpenMod Установка

От sunnamed434, обращаться по любым вопросам: 
Discord: sunnamed
UnturnedGuard Discord: https://discord.gg/jc4FPg6H6S
GitHub: https://github.com/sunnamed434 / https://github.com/UnturnedGuard
Email: sunnamed434@proton.me

Нашли ошибку в переводе? Что-то не так? Сделайте свое изменение или дополнение к гайду по установке здесь:
https://github.com/UnturnedGuard/UnturnedGuard-install-guide

>>> Установка
Процесс первой установки

1. Выключите сервер (если запущен)

2. Отключите HotReload
Откройте файл OpenMod\openmod.yaml и уставите hotreloading на false и не забудьте сохранить файл

3. Запустите сервер и ждите пока он полностью запустится

4. Вызовите следующие команды:
om install LiteDB@5.0.16
om install Microsoft.EntityFrameworkCore.Tools@3.1.32
om install Microsoft.EntityFrameworkCore.Design@3.1.32
om install Pomelo.EntityFrameworkCore.MySql@3.2.7
om install Discord.Net.Webhook@3.12.0
om install Lib.Harmony@2.2.2
om install SteamWebAPI2@4.2.0

5. Дождитесь пока полность установятся библиотеки которые были вызванны через команду

6. Выключите сервер

7. Скопируйте контент который находится в папках plugins и libraries из установленного лоадера, в схожие и указанные папки: 
Жмите на вставить с заменой файлы, если просит!
 
plugins -> OpenMod\plugins
libraries -> OpenMod\plugins

8. Open configuration of the plugin
- OpenMod\plugins\UnturnedGuardGoldBootstrapper.OpenMod\config.yaml

9. Настройте конфигурацию плагина
DebugMode: Нужен только для специальных случаев, менять только в том случае, если вас попросили разработчики
LicenseKey: Лицензионный ключ

10. Запустите сервер

11. Готово!

Если вам нужна помощь, у вас есть вопрос, или хотите отправить найденных баг, то сюда: https://discord.gg/jc4FPg6H6S

>>> Update
Процесс обновления, если до этого лоадер уже был установлен

1. Выключите сервер (если запущен)

2. Скопируйте контент который находится в папках plugins и libraries из установленного лоадера, в схожие и указанные папки: 
Жмите на вставить с заменой файлы, если просит!
 
plugins -> OpenMod\plugins
libraries -> OpenMod\plugins
 
3. Запустите сервер

4. Готово!

Если вам нужна помощь, у вас есть вопрос, или хотите отправить найденных баг, то сюда: https://discord.gg/jc4FPg6H6S