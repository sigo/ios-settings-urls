# Settings URL schemes for iOS 26

_Settings front page_
\
`prefs:root=ROOT`
\
\
_Apple Account_
\
`prefs:root=APPLE_ACCOUNT`
\
\
_Apple Account > Personal Information (takes some time to load)_
\
`prefs:root=APPLE_ACCOUNT&path=APPLE_ACCOUNT_CONTACT`
\
\
_Apple Account > Sign-In & Security (takes some time to load)_
\
`prefs:root=APPLE_ACCOUNT&path=PASSWORD_AND_SECURITY`
\
\
_Apple Account > Sign-In & Security > Change Password (takes some time to load)_
\
`prefs:root=APPLE_ACCOUNT&aaaction=changePassword`
\
\
_Apple Account > Sign-In & Security > Recovery Contacts (takes some time to load)_
\
`prefs:root=APPLE_ACCOUNT&aaaction=accountRecovery`
\
\
_Apple Account > Sign-In & Security > Legacy Contact (takes some time to load)_
\
`prefs:root=APPLE_ACCOUNT&aaaction=accountBeneficiary`
\
\
_Apple Account > Payment & Shipping (takes some time to load)_
\
`prefs:root=APPLE_ACCOUNT&path=PAYMENT_AND_SHIPPING`
\
\
_Apple Account > Subscriptions (takes some time to load)_
\
`prefs:root=APPLE_ACCOUNT&path=SUBSCRIPTIONS`
\
\
_Apple Account > iCloud > Storage_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP`
\
\
_Apple Account > iCloud > Storage > Change Storage Plan_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CHANGE_STORAGE_PLAN`
\
\
_Apple Account > iCloud > Saved to iCloud_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass`
\
\
_Apple Account > iCloud > Saved to iCloud > iCloud Photos_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.CloudPhotos`
\
\
_Apple Account > iCloud > Saved to iCloud > iCloud Drive_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Ubiquity`
\
\
_Apple Account > iCloud > Saved to iCloud > Notes_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Notes`
\
\
_Apple Account > iCloud > Saved to iCloud > iCloud Messages_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Messages`
\
\
_Apple Account > iCloud > Saved to iCloud > iCloud Calendar_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Calendars`
\
\
_Apple Account > iCloud > Saved to iCloud > Health_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Health`
\
\
_Apple Account > iCloud > Backup_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/BACKUP`
\
\
_Apple Account > iCloud > Backup > All Device Backups > _current device_ > Backup Details_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CURRENT_DEVICE_BACKUP`
\
\
_Apple Account > iCloud > Private Relay_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/INTERNET_PRIVACY`
\
\
_Apple Account > iCloud > Hide My Email_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/PRIVATE_EMAIL_MANAGE`
\
\
_Apple Account > iCloud > Advanced Data Protection_
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/ICLOUD_ADP_SPECIFIER_NAME`
\
\
_Apple Account > iCloud > unknown function, seems to do something because of the spinning wheel that briefly appears, could possibly be used to force sync_
\
`prefs:root=APPLE_ACCOUNT&aaaction=CDP&command=rejoin`
\
\
_Apple Account > Family Set Up_
\
`prefs:root=APPLE_ACCOUNT&aaaction=setupFamily`
\
\
_Appple Account > Find My_
\
`prefs:root=APPLE_ACCOUNT&path=LOCATION_SHARING`
\
\
_Apple Account > Media & Purchases_
\
`prefs:root=APPLE_ACCOUNT&path=STORE_SERVICE`
\
\
_Apple Account > Sign in with Apple_
\
`prefs:root=APPLE_ACCOUNT&path=SIWA_SERVICE`
\
\
_Apple Account > Contact Key Verification_
\
`prefs:root=APPLE_ACCOUNT&path=TRANSPARENCY`
\
\
_Wi-Fi_
\
`prefs:root=WIFI`
\
\
_Wi-Fi > Info button (current network details)_
\
`prefs:root=WIFI&path=NetworkDetails`
\
\
_Cellular_
\
`prefs:root=MOBILE_DATA_SETTINGS_ID`
\
\
_Cellular > Cellular Data Options_
\
`prefs:root=MOBILE_DATA_SETTINGS_ID&path=CELLULAR_DATA_OPTIONS`
\
\
_Cellular > Cellular Data > Show All > Cellular Data Usage_
\
`prefs:root=MOBILE_DATA_SETTINGS_ID&path=SHOW_ALL`
\
\
_Battery_
\
`prefs:root=BATTERY_USAGE`
\
\
_Battery > Battery Health & Charging (older or lower end models)_
\
`prefs:root=BATTERY_USAGE&path=BATTERY_HEALTH_TITLE`
\
\
_Battery > Charging Options (newer or higher end models)_
\
`prefs:root=BATTERY_USAGE&path=CHARGING_OPTIONS_IDENTIFIER`
\
\
_Accessibility > Audio & Visual > Call Audio Routing_
\
`prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING`
\
\
_Accessibility > Audio & Visual > Call Audio Routing > Auto-Answer Calls_
\
`prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer`
\
\
_Accessibility > Touch > Call Audio Routing_
\
`prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING`
\
\
_Accessibility > Touch > Call Audio Routing > Auto-Answer Calls_
\
`prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer`
\
\
_Wallpaper_
\
`prefs:root=Wallpaper`
\
\
_Payment & Contactless_
\
`prefs:root=PASSBOOK`
\
\
_Apps_
\
`settings-navigation://com.apple.Settings.Apps`
\
&emsp;_or_
\
`app-prefs://*` (* or any word works)
\
\
_Apps > Default apps_
\
`app-prefs://com.apple.Settings.Apps.DefaultApps`
\
&emsp;_or_
\
`app-prefs://&target=com.apple.settings.default-applications`
\
&emsp;_or_
\
`settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.DefaultApps`
\
\
_Apps > bundle identifier for any app, also third party_
\
`settings-navigation://com.apple.Settings.Apps/bundle_identifier`
\
&emsp;_or_
\
`app-prefs//bundle_identifier` (not recommended, reportedly doesn't work with certain identifiers)
\
\
_Apps > Phone > Show My Caller ID_
\
`prefs:root=Phone&path=CALLING_LINE_ID_RESTRICTION_TELEPHONY_SETTINGS`
\
\
_Apps > Safari > Default Browser App (button)_
\
`prefs:root=SAFARI#com.apple.settings.DefaultBrowser`
\
\
_Apps > Safari > Search Engine_
\
`prefs:root=SAFARI&path=SEARCH_ENGINE_SETTING`
\
\
_Apps > Safari > Also Use in Private Browsing (switch)_
\
`prefs:root=SAFARI#PRIVATE_BROWSING_USES_NORMAL_BROWSING_SEARCH_ENGINE_SELECTION`
\
\
_Apps > Safari > Search Enginge Suggestions (switch)_
\
`prefs:root=SAFARI#SEARCH_SUGGESTION_SETTING`
\
\
_Apps > Safari > Safari Suggestions (switch)_
\
`prefs:root=SAFARI#SIRI_SUGGESTIONS`
\
\
_Apps > Safari > Quick Website Search_
\
`prefs:root=SAFARI&path=SITE_SPECIFIC_SEARCH`
\
\
_Apps > Safari > Preload Top Hit (switch)_
\
`prefs:root=SAFARI#ENABLE_PREFETCHING`
\
\
_Apps > Safari > AutoFill_
\
`prefs:root=SAFARI&path=AUTO_FILL`
\
\
_Apps > Safari > Start Page Favorites_
\
`prefs:root=SAFARI&path=FAVORITES_FOLDER`
\
\
_Apps > Safari > Extensions_
\
`prefs:root=SAFARI&path=WEB_EXTENSIONS`
\
\
_Apps > Safari > Downloads_
\
`prefs:root=SAFARI&path=DOWNLOADS`
\
\
_Apps > Safari > Open Links > (in a) New Tab (and switch to it) or (in a new tab) In Background_
\
`prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPHONE` <sup><i>iPhone</i></sup>
\
`prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPAD` <sup><i>iPad</i></sup>
\
\
_Apps > Safari > Require Passcode to Unlock Private Browsing (swtich)_
\
`prefs:root=SAFARI#PrivateBrowsingRequiresAuthentication`
\
\
_Apps > Safari > Not Secure Connection Warning (switch)_
\
`prefs:root=SAFARI#WARN_ABOUT_INSECURE_CONNECTIONS`
\
\
_Apps > Safari > Import (button)_
\
`prefs:root=SAFARI#IMPORT_BUTTON`
\
\
_Apps > Safari > Export (button)_
\
`prefs:root=SAFARI#EXPORT_BUTTON`
\
\
_Apps > Safari > Export (dialog)_
\
`prefs:root=SAFARI&action=showExportSheet`
\
\
_Apps > Safari > Clear History and Website Data (button)_
\
`prefs:root=SAFARI#CLEAR_HISTORY_AND_DATA`
\
\
_Apps > Safari > Settings for Websites (section)_
\
`prefs:root=SAFARI#SPACE_CELL_FOR_PER_SITE_SETTINGS_SYNC_TOGGLE`
\
\
_Apps > Safari > Advanced_
\
`prefs:root=SAFARI&path=ADVANCED`
\
\
_Apps > Safari > Advanced > Website Data_
\
`prefs:root=SAFARI&path=ADVANCED/REMOVE_WEBSITE_DATA`
