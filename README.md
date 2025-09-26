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
**Apple Account > iCloud >** unknown function, seems to do something because of the spinning wheel, could possibly be used to force sync
\
`prefs:root=APPLE_ACCOUNT&aaaction=CDP&command=rejoin`
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
**Apps**
\
`settings-navigation://com.apple.Settings.Apps`
- or

`app-prefs://*` (* or any word works)
\
\
**Apps > Default apps**
\
`app-prefs://com.apple.Settings.Apps.DefaultApps`
- or

`app-prefs://&target=com.apple.settings.default-applications`
- or
  
`settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.DefaultApps`
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
**Apps > Safari > Open Links** (in background or new front tab) - iPhone
\
`prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPHONE`
\
\
**Apps > Safari > Open Links** (in background or new front tab) - iPad
\
`prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPAD`
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
