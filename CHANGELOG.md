## [2.17.7](https://github.com/RocketChat/Rocket.Chat.Electron/compare/2.17.6...2.17.7) (2020-02-11)


### Bug Fixes

* Spell checking dictionaries files encoded as UTF-8 ([18b9524](https://github.com/RocketChat/Rocket.Chat.Electron/commit/18b95241a9df47751c5d67a55c5e2cf73e2763ca))



## [2.17.6](https://github.com/RocketChat/Rocket.Chat.Electron/compare/2.17.5...2.17.6) (2020-02-11)


### Bug Fixes

* Rollback to plain-text Hunspell dictionaries ([#1514](https://github.com/RocketChat/Rocket.Chat.Electron/issues/1514)) ([0f16d32](https://github.com/RocketChat/Rocket.Chat.Electron/commit/0f16d32845faf5b9a9b475db3c34420d982cb6bc))



## [2.17.5](https://github.com/RocketChat/Rocket.Chat.Electron/compare/2.17.4...2.17.5) (2020-02-04)


### Bug Fixes

* Handle unset enabled dictionaries ([2e3f203](https://github.com/RocketChat/Rocket.Chat.Electron/commit/2e3f20397f8b39d70e7e9261c20145b9e6987e91))
* Ignore Hunspell dictionaries on MacOS ([cccca77](https://github.com/RocketChat/Rocket.Chat.Electron/commit/cccca775e40c101798a870ee3f2ced79fdee20a3))



## [2.17.4](https://github.com/RocketChat/Rocket.Chat.Electron/compare/2.17.3...2.17.4) (2020-02-04)


### Bug Fixes

* Broken spell checking dictionary selection ([c11600c](https://github.com/RocketChat/Rocket.Chat.Electron/commit/c11600ca509c8c1806c734b189a33981b5ba002e))



## [2.17.3](https://github.com/RocketChat/Rocket.Chat.Electron/compare/2.17.2...2.17.3) (2020-01-30)


### Bug Fixes

* Screen sharing in Jitsi ([#1486](https://github.com/RocketChat/Rocket.Chat.Electron/issues/1486)) ([d7d463a](https://github.com/RocketChat/Rocket.Chat.Electron/commit/d7d463ae3cef91410525eb42d1333e3e18996d34))



<a name="2.17.2"></a>
## 2.17.2 (2019-12-19)


### Bug Fixes

- [#1450](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1450) Windows select boxes
- [#1447](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1447) TouchBar buttons



<a name="2.17.1"></a>
## 2.17.1 (2019-12-10)


### Bug Fixes

- [#1436](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1436) Disable hardenedRuntime



<a name="2.17.0"></a>
# 2.17.0 (2019-12-02)


### Bug Fixes

- [#1402](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1402) Embed dialogs
- [#1410](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1410) Enable websecurity
- [#1415](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1415) Fetch avatar images for notifications without CORS
- [#1412](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1412) Loading error view updates
- [#1417](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1417) Main window state handling
- [#1409](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1409) Non context-aware native modules
- [#1419](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1419) Preload script issues
- [#1381](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1381) Update dialog events


### Improvements

- [#1418](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1418) Focus main window on second app instance event
- [#1416](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1416) Infer content type for notification icon
- [#1414](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1414) Lean main process
- [#1380](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1380) Notifications on Gnome
- [#1392](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1392) Update to Electron 7


<details>
<summary>Others</summary>

- [#1401](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1401) Update TouchBar API usage
</details>



<a name="2.16.2"></a>
## 2.16.2 (2019-11-07)


### Bug Fixes

- [#1381](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1381) Update dialog events


### Improvements

- [#1380](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1380) Notifications on Gnome



<a name="2.16.1"></a>
## 2.16.1 (2019-11-04)


### Bug Fixes

- [#1365](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1365) powerMonitor API usage
- [#1366](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1366) Spellchecker setup



<a name="2.16.0"></a>
# 2.16.0 (2019-10-11)


### Bug Fixes

- [#1275](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1275) Ignore spurious did-fail load, fixes [#1273](https://github.com/RocketChat/Rocket.Chat.Electron/issues/1273).


### Improvements

- [#1325](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1325) Add console warning to self-XSS
- [#1312](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1312) Fixes and updates French translations


<details>
<summary>Others</summary>

- [#1347](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1347) MacOS build
- [#1343](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1343) Reenable webviews
- [#1346](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1346) Revert Linux artifacts names
- [#1342](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1342) Update dependencies
- [#1344](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1344) Update tasks and metadata
- [#1306](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1306) Bump eslint-utils from 1.3.1 to 1.4.2
- [#1305](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1305) Bump js-yaml from 3.12.2 to 3.13.0
- [#1304](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1304) Bump lodash from 4.17.11 to 4.17.15
- [#1307](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1307) Bump lodash.merge from 4.6.1 to 4.6.2
- [#1308](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1308) Bump mixin-deep from 1.3.1 to 1.3.2
</details>



<a name="2.15.5"></a>
## 2.15.5 (2019-08-09)


### Hot fix

- Bugsnag dependency error


<a name="2.15.4"></a>
## 2.15.4 (2019-08-08)


<details>
<summary>Others</summary>

- [#1198](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1198) Add a module to handle deep links following the documentation
- [#1244](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1244) Add Simplified Chinese translation file
- [#1287](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1287) Reenable Bugsnag error tracking
- [#1196](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1196) Safely compute initials for server name on sidebar
</details>


### Bug Fixes

- [#1286](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1286) "Show window on unread changed" not working
- [#1285](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1285) Remove missing variable reference
- [#1264](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1264) Resolves issue with timing out when Rocket.Chat is in the background …



<a name="2.15.3"></a>
## 2.15.3 (2019-04-30)


### Bug Fixes

- [#1198](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1198) Add a module to handle deep links following the documentation
- [#1196](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1196) Safely compute initials for server name on sidebars



<a name="2.15.2"></a>
## 2.15.2 (2019-04-16)


### Bug Fixes

- [#1188](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1188) Apply workaround for undo and redo actions
- [#1189](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1189) Multiple language selection on spellchecking
- [#1164](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1164) Only set user presence as online when auto away detection is disabled
- [#1125](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1125) Sidebar and badges
- [#1187](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1187) Update crashes when host is unreachable


### New Features

- [#1157](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1157) Add Traditional Chinese translation



<a name="2.15.1"></a>
## 2.15.1 (2019-03-13)


### Improvements

- [#1117](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1117) Updated Japanese translation


### Bug Fixes

- [#1132](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1132) Apply memoization to spell checking
- [#1124](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1124) Away detection
- [#1129](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1129) Mac App Store startup issue
- [#1140](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1140) Preload scripts compatibility
- [#1133](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1133) Re-enable download links
- [#1130](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1130) Reply notifications in MacOS
- [#1123](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1123) Update button
- [#1115](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1115) Auto reload server



<a name="2.15.0"></a>
# 2.15.0 (2019-02-24)


### Bug Fixes

- [#1028](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1028) The behavior of clicking links when running RocketChat with subdir.
- [#1099](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1099) Updates preloads scripts to be compatible with Rocket.Chat >0.74.0
- [#1101](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1101) Use Electron notifications


### Improvements

- [#1096](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1096) i18next
- [#1093](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1093) New tray icons
- [#1045](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1045) Pages and preload script changes
- [#1076](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1076) Remove update-remind-later-dialog


<details>
<summary>Others</summary>

- [#1081](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1081) Disable artifact collection by AppVeyor
- [#1074](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1074) Fix for basic-auth servers connect
- [#1080](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1080) Fix remember window state on load
</details>


### New Features

- [#919](https://github.com/RocketChat/Rocket.Chat.Electron/pull/919) Add "save image" to context menu
- [#1030](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1030) Add Japanese translation.
- [#995](https://github.com/RocketChat/Rocket.Chat.Electron/pull/995) Automatic reload on error page
- [#1044](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1044) Support for MacBooks Touch Bar


### BREAKING CHANGES

- [#1036](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1036) Update dependencies



<a name="2.14.7"></a>
## 2.14.7 (2019-01-09)


### Bug Fixes

- Main window destroyed when closing on MacOS



<a name="2.14.6"></a>
## 2.14.6 (2018-12-06)


### Bug Fixes

- Add strings specifying why some permissions are needed in MacOS
- Fix servers.json path resolution



<a name="2.14.5"></a>
## 2.14.5 (2018-12-04)


### Improvements

- [#1010](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1010) Remove unused modules


### Bug Fixes

- [#1026](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1026) Add additional condition for option "Show on unread"
- [#1005](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1005) Disable FreeDesktopNotification actions for Unity desktop
- [#1025](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1025) Remove dependencies related to the npm's event-stream incident
- [#1019](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1019) Rollback notifications for Windows



<a name="2.14.4"></a>
## 2.14.4 (2018-11-21)


### Bug Fixes

- [#1001](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1001) Check for updates response when an error occurs
- [#978](https://github.com/RocketChat/Rocket.Chat.Electron/pull/978) Fallback notifications for Windows 7
- [#1000](https://github.com/RocketChat/Rocket.Chat.Electron/pull/1000) Notification errors
- [#990](https://github.com/RocketChat/Rocket.Chat.Electron/pull/990) Speed up servers.json loading


<details>
<summary>Others</summary>

- [#987](https://github.com/RocketChat/Rocket.Chat.Electron/pull/987) Update Russian translation
</details>



<a name="2.14.3"></a>
## 2.14.3 (2018-11-14)


### Bug Fixes

- [#978](https://github.com/RocketChat/Rocket.Chat.Electron/pull/978) Fallback notifications for Windows 7



<a name="2.14.2"></a>
## 2.14.2 (2018-11-13)


### Bug Fixes

- [#960](https://github.com/RocketChat/Rocket.Chat.Electron/pull/960) Dictionaries path detection in spell checker
- [#967](https://github.com/RocketChat/Rocket.Chat.Electron/pull/967) Main window closing behavior for Linux
- [#969](https://github.com/RocketChat/Rocket.Chat.Electron/pull/969) Notifications redesigned
- [#949](https://github.com/RocketChat/Rocket.Chat.Electron/pull/949) Reset app data under Windows
- [#959](https://github.com/RocketChat/Rocket.Chat.Electron/pull/959) System tray, dock, task bar and main window issues


### Improvements

- [#968](https://github.com/RocketChat/Rocket.Chat.Electron/pull/968) Node 11 support



<a name="2.14.1"></a>
## 2.14.1 (2018-10-25)


### New Features

- [#914](https://github.com/RocketChat/Rocket.Chat.Electron/pull/914) Tray tooltip


### Improvements

- [#933](https://github.com/RocketChat/Rocket.Chat.Electron/pull/933) App (main) page
- [#932](https://github.com/RocketChat/Rocket.Chat.Electron/pull/932) Report issue menu item links to desktop app repository


### Bug Fixes

- [#936](https://github.com/RocketChat/Rocket.Chat.Electron/pull/936) Autoupdate in MacOS
- [#927](https://github.com/RocketChat/Rocket.Chat.Electron/pull/927) Disable autoupdates
- [#938](https://github.com/RocketChat/Rocket.Chat.Electron/pull/938) Move about menu item for MacOS
- [#926](https://github.com/RocketChat/Rocket.Chat.Electron/pull/926) Preload issues
- [#922](https://github.com/RocketChat/Rocket.Chat.Electron/pull/922) Server icon not displayed on sidebar if server url ending with a trailing slash
- [#941](https://github.com/RocketChat/Rocket.Chat.Electron/pull/941) Window closing behavior for Linux environments without a system tray



<a name="2.14.0"></a>
# 2.14.0 (2018-10-11)


### New Features

- [#899](https://github.com/RocketChat/Rocket.Chat.Electron/pull/899) Optional status on tray for MacOS
- [#905](https://github.com/RocketChat/Rocket.Chat.Electron/pull/905) Add copy link in the context menu
- [#907](https://github.com/RocketChat/Rocket.Chat.Electron/pull/907) Disable autoupdate on windows installer
- [#911](https://github.com/RocketChat/Rocket.Chat.Electron/pull/911) Documentation to disable Autoupdates

### Improvements

- [#887](https://github.com/RocketChat/Rocket.Chat.Electron/pull/887) Update ESLint rules following Rocket.Chat guidelines


### Bug Fixes

- [#889](https://github.com/RocketChat/Rocket.Chat.Electron/pull/889) About dialog
- [#895](https://github.com/RocketChat/Rocket.Chat.Electron/pull/895) Menus
- [#884](https://github.com/RocketChat/Rocket.Chat.Electron/pull/884) Show tray icon status again
- [#900](https://github.com/RocketChat/Rocket.Chat.Electron/pull/900) Tray icon module
- [#902](https://github.com/RocketChat/Rocket.Chat.Electron/pull/902) Tray icon sizes for Linux
- [#912](https://github.com/RocketChat/Rocket.Chat.Electron/pull/912) Condition to quit on window close
- [#913](https://github.com/RocketChat/Rocket.Chat.Electron/pull/913) Show window on second instance running


<details>
<summary>Others</summary>

- [#916](https://github.com/RocketChat/Rocket.Chat.Electron/pull/916) Change back and forward shortcuts
</details>



<a name="2.13.3"></a>
## 2.13.3 (2018-09-18)


### Improvements

- [#881](https://github.com/RocketChat/Rocket.Chat.Electron/pull/881) End-to-end tests
- [#882](https://github.com/RocketChat/Rocket.Chat.Electron/pull/882) Set new DMG background


### Bug Fixes

- [#884](https://github.com/RocketChat/Rocket.Chat.Electron/pull/884) Show tray icon status again
- [#875](https://github.com/RocketChat/Rocket.Chat.Electron/pull/875) Toggled tray icon notifications
- [#880](https://github.com/RocketChat/Rocket.Chat.Electron/pull/880) Tray icon toggle crashes in MacOS
- [#869](https://github.com/RocketChat/Rocket.Chat.Electron/pull/869) Window state errors on save when antivirus software is present



<a name="2.13.2"></a>
## 2.13.2 (2018-09-10)


### Bug Fixes
- Dependencies updated
- Window state persistency triggering redefined
- AppId for Windows setups recovered
- Linux package names fixed
- Fixed multiple issues in provisioning profiles and entitlements for MacOS builds

<a name="2.13.1"></a>
## 2.13.1 (2018-08-30)


Fixes for MacOS and Windows builds.



<a name="2.13.0"></a>
# 2.13.0 (2018-08-27)


### New Features

- [#838](https://github.com/RocketChat/Rocket.Chat.Electron/pull/838) Russian translation
- [#837](https://github.com/RocketChat/Rocket.Chat.Electron/pull/837) Auto update fixes and settings enforcement


### Improvements

- [#821](https://github.com/RocketChat/Rocket.Chat.Electron/pull/821) Always force download of uploaded files
- [#824](https://github.com/RocketChat/Rocket.Chat.Electron/pull/824) Background process rearranged


### Bug Fixes

- [#817](https://github.com/RocketChat/Rocket.Chat.Electron/pull/817) Disabled update in builds for Mac App Store
- [#836](https://github.com/RocketChat/Rocket.Chat.Electron/pull/836) Window state persistency
- [#825](https://github.com/RocketChat/Rocket.Chat.Electron/pull/825) macOS menubar icon extra space removed
- [#835](https://github.com/RocketChat/Rocket.Chat.Electron/pull/835) Support On-Premise Jitsi screen sharing
- [#818](https://github.com/RocketChat/Rocket.Chat.Electron/pull/818) Fixed dock icon badge counter showing zero



<a name="2.12.1"></a>
## 2.12.1 (2018-08-14)

### Bug Fixes

- macOS dock badge fixed



<a name="2.12.0"></a>
# 2.12.0 (2018-08-04)


### New Features

- [#790](https://github.com/RocketChat/Rocket.Chat.Electron/pull/790) add pluralize
- [#777](https://github.com/RocketChat/Rocket.Chat.Electron/pull/777) New image for error page
- [#760](https://github.com/RocketChat/Rocket.Chat.Electron/pull/760) Notification on app icon
- [#776](https://github.com/RocketChat/Rocket.Chat.Electron/pull/776) Updated with new logo


### Bug Fixes

- [#778](https://github.com/RocketChat/Rocket.Chat.Electron/pull/778) Add snap build back
- [#791](https://github.com/RocketChat/Rocket.Chat.Electron/pull/791) Mac osx menubar color


<details>
<summary>Others</summary>

- [#785](https://github.com/RocketChat/Rocket.Chat.Electron/pull/785) Replace last couple of icons
</details>



<a name="2.11.0"></a>
# 2.11.0 (2018-06-10)


### New Features

- [#562](https://github.com/RocketChat/Rocket.Chat.Electron/pull/562) Add option to install language dictionaries
- [#691](https://github.com/RocketChat/Rocket.Chat.Electron/pull/691) Add german translation


### Bug Fixes

- [#670](https://github.com/RocketChat/Rocket.Chat.Electron/pull/670) Add & to menu items to avoid alt-shift menu popup
- [#685](https://github.com/RocketChat/Rocket.Chat.Electron/pull/685) CSS option in main.less
- [#742](https://github.com/RocketChat/Rocket.Chat.Electron/pull/742) cve 2018 1000136
- [#710](https://github.com/RocketChat/Rocket.Chat.Electron/pull/710) recompress PNG files lossless



<a name="2.10.5"></a>
## 2.10.5 (2018-02-07)

### Bug Fixes
- Dependencies updated



<a name="2.10.4"></a>
## 2.10.4 (2018-02-05)

### Bug Fixes
- macOS bundle version fixed



<a name="2.10.3"></a>
## 2.10.3 (2018-02-02)

### Bug Fixes
- Dependencies updated



<a name="2.10.2"></a>
## 2.10.2 (2018-01-26)


<details>
<summary>Others</summary>

- [#521](https://github.com/RocketChat/Rocket.Chat.Electron/pull/521) Mas entitlements
- [#520](https://github.com/RocketChat/Rocket.Chat.Electron/pull/520) npm deps update
</details>



<a name="2.10.1"></a>
# 2.10.1 (2017-11-09)

### Bug Fixes
- [#597](https://github.com/RocketChat/Rocket.Chat.Electron/pull/597) Fix MacOS dmg build


<a name="2.10.0"></a>
# 2.10.0 (2017-10-27)

### New Features
- [#552](https://github.com/RocketChat/Rocket.Chat.Electron/pull/552) Add context menu option for links
- [#556](https://github.com/RocketChat/Rocket.Chat.Electron/pull/556) Sidebar redesign and dynamic background color
- [#539](https://github.com/RocketChat/Rocket.Chat.Electron/pull/539) Adds drag and drop for servers in the sidebar
- [#533](https://github.com/RocketChat/Rocket.Chat.Electron/pull/533) New shortcut for moving back/forward between rooms

### Bug Fixes
- [#521](https://github.com/RocketChat/Rocket.Chat.Electron/pull/521) Fixes OSX build for AppStore
- [#546](https://github.com/RocketChat/Rocket.Chat.Electron/pull/546) Fixed wrong window size on loading screen
- [#532](https://github.com/RocketChat/Rocket.Chat.Electron/pull/532) Restores the help menu on Windows and Linux
- [#526](https://github.com/RocketChat/Rocket.Chat.Electron/pull/526) Fix notifications not opening the correct room


<a name="2.9.0"></a>
# 2.9.0 (2017-08-23)


### New Features

- [#320](https://github.com/RocketChat/Rocket.Chat.Electron/pull/320) Allow reply notifications on Mac OS
- [#490](https://github.com/RocketChat/Rocket.Chat.Electron/pull/490) Default servers improvements
- [#509](https://github.com/RocketChat/Rocket.Chat.Electron/pull/509) Add missing Services menu in application menu on macOS


### Bug Fixes

- [#494](https://github.com/RocketChat/Rocket.Chat.Electron/pull/494) Adding ESLint and fixing lint errors
- [#465](https://github.com/RocketChat/Rocket.Chat.Electron/pull/465) Fix bug in spellcheck
- [#512](https://github.com/RocketChat/Rocket.Chat.Electron/pull/512) Fix minimized start on Windows
- [#464](https://github.com/RocketChat/Rocket.Chat.Electron/pull/464) Remove duplicate notification on windows 7
- [#453](https://github.com/RocketChat/Rocket.Chat.Electron/pull/453) Read update settings from install location


<a name="2.8.0"></a>
# 2.8.0 (2017-05-17)


### New Features

- [#416](https://github.com/RocketChat/Rocket.Chat.Electron/pull/416) Snap build

### Bug Fixes

- [#440](https://github.com/RocketChat/Rocket.Chat.Electron/pull/440) Fix bug on some OS versions on about window, closes [#427](https://github.com/RocketChat/Rocket.Chat.Electron/issues/427)
- [#445](https://github.com/RocketChat/Rocket.Chat.Electron/pull/445) Fix bug when closing app in fullscreen




<a name="2.7.0"></a>
# 2.7.0 (2017-04-26)


### New Features

- [#411](https://github.com/RocketChat/Rocket.Chat.Electron/pull/411) Auto update when new version is released
- [#423](https://github.com/RocketChat/Rocket.Chat.Electron/pull/423) Open host from add new server page if it exists


### Bug Fixes

- [#417](https://github.com/RocketChat/Rocket.Chat.Electron/pull/417) Don't open dev tools on about, and show message when no updates
- [#425](https://github.com/RocketChat/Rocket.Chat.Electron/pull/425) Make sure app quits on mac on update
- [#426](https://github.com/RocketChat/Rocket.Chat.Electron/pull/426) Reduce drag region to fix manual scroll
- [#415](https://github.com/RocketChat/Rocket.Chat.Electron/pull/415) Updated README with servers.json instructions


<a name="2.6.1"></a>
## 2.6.1 (2017-04-04)

### Bug Fixes
- [#412](https://github.com/RocketChat/Rocket.Chat.Electron/pull/412) Fix bug with highlighting text & drag region on macOS


<a name="2.6.0"></a>
# 2.6.0 (2017-03-29)


### Bug Fixes

- [#384](https://github.com/RocketChat/Rocket.Chat.Electron/pull/384) Fix download file issue
- [#390](https://github.com/RocketChat/Rocket.Chat.Electron/pull/390) Fix speed issues with spellcheck on windows
- [#391](https://github.com/RocketChat/Rocket.Chat.Electron/pull/391) Only show reload screen if main webview error


<details>
<summary>Others</summary>

- [#336](https://github.com/RocketChat/Rocket.Chat.Electron/pull/336) Make it sexier in macOS
</details>

## 2.5.0 - 2017-Mar-05

- Add Fedora Dev Dependencies
- Allow opening of file urls
- Changed the function name and the switch is replaced with `icon-tray${title}.png`);
- Fix speed issues with spell check on Windows
- Fixed to put tray object in mainWindow
- Handle urls using click listener
- Load server config from file and tidy menu
- Show reload screen when server fails to load

## 2.4.0 - 2017-Fev-06

- Add .nvmrc
- Add download section to readme
- Add option to hide tray icon
- Add option to remove user data on uninstall
- Add option to toggle menu on windows and linux
- Allow multiple dictionaries if not using hunspell
- Capitalize menu items
- Fix blank notification issue
- Fix dictionaries path
- Fix issue with notification taking focus, and resize
- Fix issue with some notifications being blank
- Fix issues with desktop entry on linux
- Fix multiple certificate notifications and replacing webview with image
- Fix notification height with mulitple monitors
- Fix speed issues with spell check
- Improve design of screen selection
- Initial changes to enable screen share
- Keep user online if they are still active on their system
- Make windows notification unselectable
- Open link in app if internal url
- Prevent error from tray when window reloads
- Save disabled dictionary preference
- Set notification as inactive so it doesnt take focus from window
- Stop redirect when dragging image/url into window
- Update .editorconfig to match eslint
- Update jQuery to 3.1.1
- Update spectron 3.4. to 3.5.0

## 2.3.0 - 2017-Jan-24

- Add loading screen
- Add options of all users or current user for Windows install
- Add run at startup option on Windows
- Fix issues with Windows 7 notifications

## 2.2.3 - 2017-Jan-20

- Dependencies update

## 2.2.2 - 2017-Jan-20

- Fix client zoom keys the opposite way to be expected.
- Debounce window saveState call to avoid Error: EPERM: operation not permitted

## 2.2.1 - 2017-Jan-19

- Added left button click to taskbar-icon to show main window
- Fix various quirks with the windows installer

## 2.2.0 - 2017-Jan-11

### Upgrade electron-builder to 11.2.4

- Fix context menu

## 2.1.0 - 2017-Jan-10

- Better file organization
- Use [electron-builder](https://github.com/electron-userland/electron-builder) to generate our packages and installers
- Fix Spell Checker for all platforms
- Add builds for windows x32 and x64
- Add build automation with Travis and AppVeyor
- Fixed notifications on Windows 7
- Fixed post installation error messages on Windows 7

## 2.0.0 - 2016-Dec-26

### Upgrade electron to 1.4.13

## 1.3.1 - 2016-Apr-06

- Add underline keyboard shortcuts for Windows and Linux (#50)
- Add window min size 400px x 600px
- Prevent save window size for hidden windows
- Save state on window resize and move

## 1.3.0 - 2016-Apr-05

- Ask users to allow or deny when connecting to a server with invalid SSL
- HTTP Basic Authentication support (#144)
- Improve error handling for connecting to server (#143)
- OS X client - every word typed is highlighted as being misspelled (#162)
- Possibility to install without creating shortcut (#96)
- Restoring maximized window from tray restores to not maximized window size (#151)
- Save hidden state at Windows logout (#156)

## 1.2.0 - 2016-Mar-21

### Update electron-prebuilt to 0.36.10

- Add the "about" panel for windows and linux (#138)
- Add zoom options (#137)
- Application close (#123)
- Application crash when hiding or closing the app (#109)
- Do not add a big red dot on side bar for servers with unread messages (#132)
- Enable multilanguage spell checker; Allow user to set languages. (#124)
- Fix "Close Window" on OS X minimizes (#72)
- Improve spellchecker (#122)
- Improvements/huspell dicts (#128)
- Mac desktop client: Reload minimizes instead (#129)
- Open DevTools for active server (#136)
- Open DevTools for selected server instead of Electron (#133)
- Option to start the client hidden (#118)
- Prevent cache of server icon
- Reload current server instead of all application (#135)
- Right click reload server (#134)
- Spellchecker language not autodetecting on OS X (#119)
- Spellchecker not showing correct suggestions (#121)

## 1.1.0 - 2016-Feb-29

- Add server screen font not present on Windows (#100)
- Change Server Should be Add Server (#90)
- Close Now Closes the Application (#89)
- Have hotkeys to switch between Rocket chat instances. (#81)
- Make the taskbar blink when mentioned (#68)
- Open the app after installing on windows (#37)
- Option to change the install folder (#41)
- Right click -> copy / paste (#32)
- RIght click on URLs doesn't work cleanly in a cross-platform way. (#95)
- Start client with windows logon (#57)
- Tray icon on Windows requires triple click (#77)

> Special thanks to @floriangoeldi

## 1.0.0 - 2016-Feb-19

### Update electron to v0.36.4

- Add files to make branding easily
- Add spellchecker
- Create class to manage servers
- Create class to manage sidebar (servers list)
- Create class to manage webviews
- If you inform a server address with HTTPS we will fallback to HTTP if necessary
- Improve file upload getting file from inside the web view instead of from the main view and transmit to the webview via IPC
- Improve offline message
- Load all servers on aplication startup to enable notifications for all servers
- Load the last server and last room on application load or refresh
- Move all images to /app/images
- Now you can inform the server address without protocol, we will try HTTPS and then HTTP
- Open correct server from desktop notification
- Reactive tray icon
- Remove coffee-script dependency
- Remove font Roboto
- Remove unused CSS/LESS
- Show total of unreads in the application icon (OS X)
- Sidebar design improvement
- Sidebar now have a new button to add new servers
- Sidebar shows server's alert badge
- Sidebar shows server's icon or initials
- Sidebar shows server's title on mouse over
- Sidebar shows server's unread count
- Use webviews to allow multiple servers online at the same time

## 0.10.0 - 2015-Nov-11

### Update Electron to 0.34.0

## 0.9.0 - 2015-Oct-23

- Option to hide server's list

## 0.8.0 - 2015-Sep-14

### Update Electron to 0.32.2

## 0.7.0 - 2015-Aug-26

- Now you can add multiple servers

## 0.6.0 - 2015-Aug-07

### Updated Electron to 0.31.0

-  New demo URL

## 0.5.0 - 2015-Jul-27

### Upgrade electron to 0.30.2

- Better error message
- Disabled _tray.setTitle(title); until it can be optional
- Fix crash when closing app from try in OS X
- Fixed oAuth logins
- Increase start window size
- Listen for double-clicked event on tray to minimize/restore window
- Move window to front when click to show in tray
- Open http links as external
- Remove unnecessary files from OSX and Windows release
- Rename application executable and helpers
- Update Icons

## 0.4.0 - 2015-Jul-16

- Upgrade electron to 0.30.0 (Images from non HTTPS urls are displayed now)
- Improve icons for Windows
- Start using Coffee-Script

## 0.3.0 - 2015-Jul-15

- Tray icon
- Improve app icons

## 0.2.0 - 2015-Jul-10

- New app icon for OS X
- New background for dmg file
- Add application and context menus
