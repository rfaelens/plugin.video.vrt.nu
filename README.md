[![GitHub release](https://img.shields.io/github/release/pietje666/plugin.video.vrt.nu.svg)](https://github.com/pietje666/plugin.video.vrt.nu/releases)
[![Build Status](https://travis-ci.org/pietje666/plugin.video.vrt.nu.svg?branch=master)](https://travis-ci.org/pietje666/plugin.video.vrt.nu)
[![License: GPLv3](https://img.shields.io/badge/License-GPLv3-yellow.svg)](https://opensource.org/licenses/GPLv3)
[![Contributors](https://img.shields.io/github/contributors/pietje666/plugin.video.vrt.nu.svg)](https://github.com/pietje666/plugin.video.vrt.nu/graphs/contributors)
[![Donate!](https://img.shields.io/static/v1.svg?label=&message=Donate!&color=lightgrey&logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6C58R2PNAWTNW&source=url)

# VRT.NU Kodi addon

**plugin.video.vrt.nu** is a [Kodi](https://kodi.tv/) add-on used to watch all live video streams *and* all video-on-demand
content available on [VRT NU](https://www.vrt.be/vrtnu/).

VRT NU is the video-on-demand platform of VRT, Flanders' public broadcasting service.

## Installing

In Kodi, simply search for `VRT NU`, and install the add-on.

Alternatively, you can download a ZIP archive from the [GitHub releases](https://github.com/pietje666/plugin.video.vrt.nu/releases)
or the [Kodi plugin page](https://kodi.tv/addon/plugins-video-add-ons/vrt-nu-0) and install it directly in Kodi
using the **Install via Zip** option.

## Using the plugin

The [VRT NU](https://www.vrt.be/vrtnu) platform requires users to sign in before gaining access to video-on-demand content. Users can
sign in with a user name and password, or sign in with their Google, or Facebook account.

This plugin currently only supports signing in using the first method (user name and password). If you already
have a VRT NU account and sign in with another method, it is easy to get a password:

- Sign out of your VRT NU account;
- Click **Inloggen met e-mail**;
- Click the **Wachtwoord vergeten?** hyperlink, and enter your email address.

You will receive an email that allows you to set a password. Use that password to enter in the plugin when
prompted.

For more information about the VRT.NU Kodi addon, look at [our GitHub Wiki page](https://github.com/pietje666/plugin.video.vrt.nu/wiki).

## Reporting issues
You can report issues at [our GitHub project](https://github.com/pietje666/plugin.video.vrt.nu) or
you can send a message to [our Facebook page](https://www.facebook.com/kodivrtnu/).

## Releases

#### v1.7.1 (2019-03-28)
- Remove the inputstream.adaptive requirement for Krypton

#### v1.7.0 (2019-03-26)
- Fix the categories web-scraping (@mediaminister)
- Add full proxy support (@dagwieers)
- Indicate when content will disappear in the next 3 months (@dagwieers)
- Indicate when content is geo-blocked (@dagwieers)
- Add fanart to menus (@dagwieers)
- Fix issue related to missing sound (@mediaminister)
- Improve main menu listing (@dagwieers)
- Use VRT.NU search API for most information gathering (@mediaminister)
- Added Dutch translation (@mediaminister)
- Added "Most recent" menu item (@mediaminister)
- Fix roaming for live streams (@mediaminister)
- Add Python 3 compatibility (@dagwieers)
- Added automated testing using Travis CI (@dagwieers)

#### v1.6.0 (2019-03-07)
- Use VRT search api (greatly improves stability)
- Fix for users with Non ASCII compatible user path
- Fix for roaming token

#### v1.5.2 (2019-01-28)
- Bug fix where the vrt token would be stored in a wrong format
- Inputstream helper for easier widevine installation
- Token resets when settings are being changed

#### v1.5.1 (2019-01-20)
- Fixed subtitle issue where subtitles would always be visible (@mediaminister)
- Fixed categories (@mediaminister)
- Roaming support added (@mediaminister)

#### v1.5.0 (2018-12-27)
 - 720p Livestreams when enabling in settings + having kodi 18 + having widevine.dll present (@mediaminister)
 - Fixed bug where watched icon was not showing in Kodi 18
 - Implemented different way of working with subtitles (@mediaminister)

#### v1.4.3 (2018-11-07)
 - Livestreams working again

#### v1.4.2 (2018-10-11)
 - Changed way of working with urls when a season is refering to href="#"

#### v1.4.1 (2018-09-24)
- Adapted plugin to new vrtnu layout for showing multiple seasons

#### v1.4.0 (2018-09-20)
- Using the new vrtnu login method and video services
- Fixed bug where some videos would not be able to play (@dagwieers)

#### v1.3.4 (2018-09-10)
- Fixed A-Z menu to parse the new vrtnu layout

#### v1.3.3 (2018-09-02)
- Fixed bug where some items would not want to play
- Fixed bug where some videos would only show one episodes while multiple episodes are present
- Updated Requests and Beautifulsoup modules

#### v1.3.2 (2018-08-03)
- Changed way of selecting multiple episodes, this fixes a bug where the "active" episodes would not be shown

#### v1.3.1 (2018-07-20)
- Changed way of selecting item title for single videos

#### v1.3.0 (2018-07-14)
- Adapted code to new vrtnu website layout, this fixes a bug where only the first episode would be shown while multiple episodes are present

#### v1.2.0 (2018-06-17)
- Changed live streaming mechanism

#### v1.1.2 (2018-06-14)
- New stream links for live streaming (@yorickps)

#### v1.1.1 (2017-03-13)
- Fixed bug where seasons do not show when there is one malfunctioning

#### v1.1.0 (2017-12-15)
- Refactored internal code

#### v1.0.0 (2017-10-01)
- Fixed issue where all the videos would not be able to play, implemented new way of getting the streaming urls
- Fixed bug where a single video would not be listed when there is also a part "ANDEREN BEKEKEN OOK" present
- New versioning system now starting from 1.0.0

#### v0.0.7 (2017-09-09)
- Fixed bug where dates were not always shown

#### v0.0.6 (2017-08-06)
- Fixed ordering bug for videos

#### v0.0.5 (2017-07-24)
- Fixed broken Sporza logo 

#### v0.0.4 (2017-07-20)
- Added Sporza livestream
- Added dates to videos (@stevenv)
- Fixed bug where seasons did not get listed

#### v0.0.3 (2017-05-22)
- Fixed broken livestreams

#### v0.0.2 (2017-05-07)
- Fixed installation issue

#### v0.0.1 (2017-05-01)
- Initial working release

## Donating
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6C58R2PNAWTNW&source=url)
