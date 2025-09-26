# Settings URL schemes for iOS 26

**Settings front page**
\
`prefs:root=ROOT`
\
\
**Apple Account**
\
`prefs:root=APPLE_ACCOUNT`
\
\
**Apple Account > iCloud > Storage**
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP`
\
\
**Apple Account > iCloud > Saved to iCloud**
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass`
\
\
**Apple Account > iCloud > Backup > All Device Backups >** (current device) **> Backup Details**
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/LOCAL_BACKUP`
\
\
**Apple Account > iCloud >** unknown function, seems to do something because of the spinning wheel, could possibly be used to force sync
\
`prefs:root=APPLE_ACCOUNT&aaaction=CDP&command=rejoin`
\
\
**Wi-Fi**
\
`prefs:root=WIFI`
\
\
**Wi-Fi > Info button** (current network details)
\
`prefs:root=WIFI&path=NetworkDetails`
\
\
**Cellular**
\
`prefs:root=MOBILE_DATA_SETTINGS_ID`
\
\
**Cellular > Cellular Data Options**
\
`prefs:root=MOBILE_DATA_SETTINGS_ID&path=CELLULAR_DATA_OPTIONS`
\
\
**Cellular > Cellular Data > Show All > Cellular Data Usage**
\
`prefs:root=MOBILE_DATA_SETTINGS_ID&path=SHOW_ALL`
\
\
**Battery**
\
`prefs:root=BATTERY_USAGE`
\
\
**Battery > Battery Health & Charging** (older or lower end models)
\
`prefs:root=BATTERY_USAGE&path=BATTERY_HEALTH_TITLE`
\
\
**Battery > Charging Options** (newer or higher end models)
\
`prefs:root=BATTERY_USAGE&path=CHARGING_OPTIONS_IDENTIFIER`
\
\
**Accessibility > Audio & Visual > Call Audio Routing**
\
`prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING`
\
\
**Accessibility > Audio & Visual > Call Audio Routing > Auto-Answer Calls**
\
`prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer`
\
\
**Accessibility > Touch > Call Audio Routing**
\
`prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING`
\
\
**Accessibility > Touch > Call Audio Routing > Auto-Answer Calls**
\
`prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer`
\
\
**Wallpaper**
\
`prefs:root=Wallpaper`
\
\
**Payment & Contactless**
\
`prefs:root=PASSBOOK`
\
\
**Apps**
\
`settings-navigation://com.apple.Settings.Apps`
\
&emsp;or
\
`app-prefs://*` (* or any word works)
\
\
**Apps > Default apps**
\
`app-prefs://com.apple.Settings.Apps.DefaultApps`
\
&emsp;or
\
`app-prefs://&target=com.apple.settings.default-applications`
\
&emsp;or
\
`settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.DefaultApps`
\
\
**Apps >** bundle identifier for any app, also third party
\
`settings-navigation://com.apple.Settings.Apps/`_+ the bundle identifier_
\
&emsp;or
\
`app-prefs//`_+ the bundle identifier_ (not recommended, reportedly doesn't work with certain indentifiers)
\
\
**Apps > Phone > Show My Caller ID**
\
`prefs:root=Phone&path=CALLING_LINE_ID_RESTRICTION_TELEPHONY_SETTINGS`
\
\
**Apps > Safari > Default Browser App** (button)
\
`prefs:root=SAFARI#com.apple.settings.DefaultBrowser`
\
\
**Apps > Safari > Search Engine**
\
`prefs:root=SAFARI&path=SEARCH_ENGINE_SETTING`
\
\
**Apps > Safari > Also Use in Private Browsing** (switch)
\
`prefs:root=SAFARI#PRIVATE_BROWSING_USES_NORMAL_BROWSING_SEARCH_ENGINE_SELECTION`
\
\
**Apps > Safari > Search Enginge Suggestions** (switch)
\
`prefs:root=SAFARI#SEARCH_SUGGESTION_SETTING`
\
\
**Apps > Safari > Safari Suggestions** (switch)
\
`prefs:root=SAFARI#SIRI_SUGGESTIONS`
\
\
**Apps > Safari > Quick Website Search**
\
`prefs:root=SAFARI&path=SITE_SPECIFIC_SEARCH`
\
\
**Apps > Safari > Preload Top Hit** (switch)
\
`prefs:root=SAFARI#ENABLE_PREFETCHING`
\
\
**Apps > Safari > AutoFill**
\
`prefs:root=SAFARI&path=AUTO_FILL`
\
\
**Apps > Safari > Start Page Favorites**
\
`prefs:root=SAFARI&path=FAVORITES_FOLDER`
\
\
**Apps > Safari > Extensions**
\
`prefs:root=SAFARI&path=WEB_EXTENSIONS`
\
\
**Apps > Safari > Downloads**
\
`prefs:root=SAFARI&path=DOWNLOADS`
\
\
**Apps > Safari > Open Links** > _New Tab (and switch to it) or (New Tab) In Background_
\
`prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPHONE` (iPhone)
\
`prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPAD` (iPad)
\
\
**Apps > Safari > Require Passcode to Unlock Private Browsing** (swtich)
\
`prefs:root=SAFARI#PrivateBrowsingRequiresAuthentication`
\
\
**Apps > Safari > Not Secure Connection Warning** (switch)
\
`prefs:root=SAFARI#WARN_ABOUT_INSECURE_CONNECTIONS`
\
\
**Apps > Safari > Import** (button)
\
`prefs:root=SAFARI#IMPORT_BUTTON`
\
\
**Apps > Safari > Export** (button)
\
`prefs:root=SAFARI#EXPORT_BUTTON`
\
\
**Apps > Safari > Export** (dialog)
\
`prefs:root=SAFARI&action=showExportSheet`
\
\
**Apps > Safari > Clear History and Website Data** (button)
\
`prefs:root=SAFARI#CLEAR_HISTORY_AND_DATA`
\
\
**Apps > Safari > Settings for Websites** (section)
\
`prefs:root=SAFARI#SPACE_CELL_FOR_PER_SITE_SETTINGS_SYNC_TOGGLE`
\
\
**Apps > Safari > Advanced**
\
`prefs:root=SAFARI&path=ADVANCED`
\
\
**Apps > Safari > Advanced > Website Data**
\
`prefs:root=SAFARI&path=ADVANCED/REMOVE_WEBSITE_DATA`
