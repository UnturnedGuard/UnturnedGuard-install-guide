--- UnturnedGuard Experimental for RocketMod Installation

Brought you by sunnamed434, contact by any questions or concerns: 
Discord: sunnamed
UnturnedGuard Discord: https://discord.gg/jc4FPg6H6S
GitHub: https://github.com/sunnamed434 / https://github.com/UnturnedGuard
Email: sunnamed434@proton.me

Found a mistake in translation? Something is wrong? Make your change/addition to the installation guide here:
https://github.com/UnturnedGuard/UnturnedGuard-install-guide

>>> Installation
Process of the first installation

1. Stop the server (if running)

2. Copy the content of the Plugins and Libraries of the installed loader in the same folders: 
Press Replace the files in the destination button if asked!
Plugins -> Rocket\Plugins
Libraries -> Rocket\Libraries

3. Open configuration of the plugin
- Rocket\Plugins\UnturnedGuardExperimentalBootstrapper.RocketMod\UnturnedGuardExperimentalBootstrapper.RocketMod.configuration.xml

4. Configure the plugin configuration
DebugMode: For specific cases when you asked to do that by the guard devs
LicenseKey: Your licnese key

<?xml version="1.0" encoding="utf-8"?>
<UnturnedGuardBootstrapperConfiguration xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <DebugMode>false</DebugMode>
  <LicenseKey>Put your license key here</LicenseKey>
</UnturnedGuardBootstrapperConfiguration>

5. Run Server

6. Done!

If you need help or you have questions/want to report a bug: https://discord.gg/jc4FPg6H6S

>>> Update
Process of the updating if you already have installed bootstrapper before

1. Stop the server (if running)

2. Copy the content of the Plugins and Libraries of the installed loader in the same folders: 
Press Replace the files in the destination button if asked!
- `Rocket\Plugins`
- `Rocket\Libraries`
 
3. Run Server

4. Done!

If you need help or you have questions/want to report a bug: https://discord.gg/jc4FPg6H6S