## Change Log

* Version 2.2.0 - 2022/11/15
	* Update LibQTip to 9.1.5-1-g4c6a3d8 (fix GetBackdrop error, thanks GeoRam2016)
	* Fix missing locale import (es.lua)
* Version 2.1.9 - 2022/10/27
	* TOC update for 10.0.0
	* Updated Ace3 to r1294
	* Fix minimap button click
* Version 2.1.8 WIP - 2022/07/30
	* Updated Ace3 to r1259
	* Remove unused dependencies
	* TOC update for 9.2.5
	* Added minimap button which allow usage without data broker
	* Added total balance
	* Changed indent to 2 spaces width
	* Added WoW Token price (thanks AcademicoMDP)
	* Added Guild Bank Money (thanks AcademicoMDP, disabled for now)
	* Added Spanish Locale (thanks osilvay, need review)
	* More German translations (need review)
* Version 2.1.7 - 2020/11/18
	* TOC update for 9.0.2
* Version 2.1.6 - 2020/11/03
	* Added an option to control the highlighting of the main LDB icon (set to false by default).
	* Update LibQTip to latest release (9.0.1.2) (and still correcting @debug@ comments in the process!)
	* Fix buggy TOC #Interface field in Classic Edition build.
* Version 2.1.5 - 2020/10/17
	* Update LibQTip to latest alpha (for frame backdrop compatibility).
	* Update Ace3 to r1241.
* Version 2.1.4 - 2019/10/10
	* Update LibQTip to r188
* Version 2.1.3 - 2019/10/10
	* Added manual-changelog to .pkgmeta so Twitch client doesn't get confused with 2 Changelog.md files in the archive.
* Version 2.1.2 - 2019/10/08
	* Enabled automated packaging via Travis CI
* Version 2.1.1 - Not released
* Version 2.1.0 - 2019/09/13
	* Added the "Session Threshold" option.
	* Updated Ace3 to r1227.
* Version 2.0.6 - 2019/07/16
	* Made frFr locale correctly display large number... without taint. Sigh.
* Version 2.0.5 - 2019/07/14
	* Made frFr locale correctly display large number.
	* Toc update for 8.2
* Version 2.0.4 - 2018/12/18
	* Simple Toc update for 8.1
* Version 2.0.3 - 2018/07/23
	* Now correctly calculates realm wealth when auditing a character for the first time.
* Version 2.0.2 - 2018/07/19
	* Toc update for WoW 8.0
	* Updated libs, now using Ace3 r1182
* Version 2.0.1 - 2018/03/30
	* New: Properly accounts for money gained outside of the game, ie. via the Battle.net mobile app
* Version 2.0.0 - 2018/01/20
	* New: Refactored the code to use a more efficient, timer-based strategy to reset the statistics
	* New: The **Session** stat is now preserved after a UI Reload
	* Several micro-optimizations
* Version 1.4.4 - 2017/12/17
	* Added German locale, thanks to [**Scarwolf**](https://github.com/Septh/WoW-Broker_Cash/pull/2)
* Version 1.4.3 - 2017/12/12
	* Fixed the addon not working on fresh installs (\*sigh\*). [Thanks to **kkrzyzak** for pointing out](https://github.com/Septh/WoW-Broker_Cash/issues/1)
* Version 1.4.2 - 2017/12/12
	* Minor fixes. Weekly stat should reset correctly now
* Version 1.4.1 - 2017/12/04
	* Some more internal optimizations
	* Corrected a flaw in the stats reset logic. Should work as expected now
* Version 1.4.0 - 2017/11/12
	* Some internal optimizations
	* Consolidated the **Show Copper** and **Show Silver** options into a single **Show Silver and Copper** option
	* Added an option to disable the secondary (aka. details) tooltip
	* Added an **Ever** statistic that will never be reset
* Version 1.3.3 - 2017/09/21
	* Toc update for 7.3
	* Using the latest Ace3 files (r1166)
* Version 1.3.2 - 2017/04/05
	* Fixed a stupid bug that prevented the display of copper and silver amounts in sub-tooltip
	* Removed an unwanted global
* Version 1.3.1 - 2017/03/29
	* Toc update for 7.2
	* Fixed a bug that occured when a char spent all his money
* Version 1.3.0 - 2016/12/11
	* Added options to hide copper and silver amounts in both the LDB display and the dropdown menu
* Version 1.2.1 - 2016/11/03
	* Don't highlight the LDB frame if the display is Bazooka
	* Forgot to localize the dialog buttons
* Version 1.2.0 - 2016/11/02
	* Added the ability to reset or delete a character's stats
* Version 1.1.0 - 2016/10/26
	* Toc update for 7.1
* Version 1.1.0 - 2016/10/21
	* Also show wealth variation per realm
* Version 1.0.3 - 2016/10/21
	* Use `BreakUpLargeNumbers()` for a nicer main LDB text
* Version 1.0.2 - 2016/10/20
	* Fix Lua errors when connecting a char for the first time
* Version 1.0.1 - 2016/10/17
	* Highlight LDB frame on tooltip show
* Version 1.0.0
	* Initial release
