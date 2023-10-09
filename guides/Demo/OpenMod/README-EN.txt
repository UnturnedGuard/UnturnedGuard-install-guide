--- UnturnedGuard Demo for OpenMod Installation

Brought you by sunnamed434, contact by any questions or concerns: 
Discord: sunnamed
UnturnedGuard Discord: https://discord.gg/jc4FPg6H6S
GitHub: https://github.com/sunnamed434 / https://github.com/UnturnedGuard
Email: sunnamed434@proton.me

Found a mistake in translation? Something is wrong? Make your change/addition to the installation guide here:
https://github.com/UnturnedGuard/UnturnedGuard-install-guide

>>> Installation
Process of the first installation

1. Stop the server if running

2. Disable HotReload
Go to the OpenMod\openmod.yaml file, and set hotreloading to false, and don't forget to save the file

3. Run server and wait until full load

4. Execute commands:
om install LiteDB@5.0.16
om install Microsoft.EntityFrameworkCore.Tools@3.1.32
om install Microsoft.EntityFrameworkCore.Design@3.1.32
om install Pomelo.EntityFrameworkCore.MySql@3.2.7
om install Discord.Net.Webhook@3.12.0
om install Lib.Harmony@2.2.2
om install SteamWebAPI2@4.2.0

5. Stop the server

6. Copy the content of the Plugins and Libraries of the installed loader in the same folders:
Press Replace the files in the destination button if asked!
 
plugins -> OpenMod\plugins
libraries -> OpenMod\plugins

7. Open configuration of the plugin
- OpenMod\plugins\UnturnedGuardDemoBootstrapper.OpenMod\config.yaml

8. Configure the plugin configuration
DebugMode: For specific cases when you asked to do that by the guard devs
AdvertisePlugin: means that you will see in Lobby of your server in Unturned Plugins page that Guard is installed, set false to disable it (not required).

# Set to true to enable DebugMode, enable only if asked or you want to get more debug information.
DebugMode: false

9. Run Server

10. Done!

If you need help or you have questions/want to report a bug: https://discord.gg/jc4FPg6H6S

>>> Update
Process of the updating if you already have installed bootstrapper before

1. Stop the server (if running)

2. Copy the content of the Plugins and Libraries of the installed loader in the same folders:
Press Replace the files in the destination button if asked!
 
plugins -> OpenMod\plugins
libraries -> OpenMod\plugins
 
3. Run Server

4. Done!

If you need help or you have questions/want to report a bug: https://discord.gg/jc4FPg6H6S