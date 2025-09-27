# Settings URL schemes for iOS 26

Settings front page
\
`prefs:root=ROOT`
\
\
Apple Account
\
`prefs:root=APPLE_ACCOUNT`
\
\
Apple Account > Personal Information (takes some time to load)
\
`prefs:root=APPLE_ACCOUNT&path=APPLE_ACCOUNT_CONTACT`
\
\
Apple Account > Sign-In & Security (takes some time to load)
\
`prefs:root=APPLE_ACCOUNT&path=PASSWORD_AND_SECURITY`
\
\
Apple Account > Sign-In & Security > Change Password (takes some time to load)
\
`prefs:root=APPLE_ACCOUNT&aaaction=changePassword`
\
\
Apple Account > Sign-In & Security > Recovery Contacts (takes some time to load)
\
`prefs:root=APPLE_ACCOUNT&aaaction=accountRecovery`
\
\
Apple Account > Sign-In & Security > Legacy Contact (takes some time to load)
\
`prefs:root=APPLE_ACCOUNT&aaaction=accountBeneficiary`
\
\
Apple Account > Payment & Shipping (takes some time to load)
\
`prefs:root=APPLE_ACCOUNT&path=PAYMENT_AND_SHIPPING`
\
\
Apple Account > Subscriptions (takes some time to load)
\
`prefs:root=APPLE_ACCOUNT&path=SUBSCRIPTIONS`
\
\
Apple Account > iCloud > Storage
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP`
\
\
Apple Account > iCloud > Storage > Change Storage Plan
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CHANGE_STORAGE_PLAN`
\
\
Apple Account > iCloud > Saved to iCloud
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass`
\
\
Apple Account > iCloud > Saved to iCloud > iCloud Photos
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.CloudPhotos`
\
\
Apple Account > iCloud > Saved to iCloud > iCloud Drive
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Ubiquity`
\
\
Apple Account > iCloud > Saved to iCloud > Notes
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Notes`
\
\
Apple Account > iCloud > Saved to iCloud > iCloud Messages
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Messages`
\
\
Apple Account > iCloud > Saved to iCloud > iCloud Calendar
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Calendars`
\
\
Apple Account > iCloud > Saved to iCloud > Health
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Health`
\
\
Apple Account > iCloud > Backup
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/BACKUP`
\
\
Apple Account > iCloud > Backup > All Device Backups > _current device_ > Backup Details
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CURRENT_DEVICE_BACKUP`
\
\
Apple Account > iCloud > Private Relay
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/INTERNET_PRIVACY`
\
\
Apple Account > iCloud > Hide My Email
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/PRIVATE_EMAIL_MANAGE`
\
\
Apple Account > iCloud > Advanced Data Protection
\
`prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/ICLOUD_ADP_SPECIFIER_NAME`
\
\
Apple Account > iCloud > unknown function, seems to do something because of the spinning wheel that briefly appears, could possibly be used to force sync
\
`prefs:root=APPLE_ACCOUNT&aaaction=CDP&command=rejoin`
\
\
Apple Account > Family Set Up
\
`prefs:root=APPLE_ACCOUNT&aaaction=setupFamily`
\
\
Appple Account > Find My
\
`prefs:root=APPLE_ACCOUNT&path=LOCATION_SHARING`
\
\
Apple Account > Media & Purchases
\
`prefs:root=APPLE_ACCOUNT&path=STORE_SERVICE`
\
\
Apple Account > Sign in with Apple
\
`prefs:root=APPLE_ACCOUNT&path=SIWA_SERVICE`
\
\
Apple Account > Contact Key Verification
\
`prefs:root=APPLE_ACCOUNT&path=TRANSPARENCY`
\
\
Wi-Fi
\
`prefs:root=WIFI`
\
\
Wi-Fi > Info button (current network details)
\
`prefs:root=WIFI&path=NetworkDetails`
\
\
Cellular
\
`prefs:root=MOBILE_DATA_SETTINGS_ID`
\
\
Cellular > Cellular Data Options
\
`prefs:root=MOBILE_DATA_SETTINGS_ID&path=CELLULAR_DATA_OPTIONS`
\
\
Cellular > Cellular Data > Show All > Cellular Data Usage
\
`prefs:root=MOBILE_DATA_SETTINGS_ID&path=SHOW_ALL`
\
\
Battery
\
`prefs:root=BATTERY_USAGE`
\
\
Battery > Battery Health & Charging (older or lower end models)
\
`prefs:root=BATTERY_USAGE&path=BATTERY_HEALTH_TITLE`
\
\
Battery > Charging Options (newer or higher end models)
\
`prefs:root=BATTERY_USAGE&path=CHARGING_OPTIONS_IDENTIFIER`
\
\
Accessibility > Audio & Visual > Call Audio Routing
\
`prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING`
\
\
Accessibility > Audio & Visual > Call Audio Routing > Auto-Answer Calls
\
`prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer`
\
\
Accessibility > Touch > Call Audio Routing
\
`prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING`
\
\
Accessibility > Touch > Call Audio Routing > Auto-Answer Calls
\
`prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer`
\
\
Wallpaper
\
`prefs:root=Wallpaper`
\
\
Payment & Contactless
\
`prefs:root=PASSBOOK`
\
\
Apps
\
`settings-navigation://com.apple.Settings.Apps`
\
&emsp;/
\
`app-prefs://*` (* or any word works)
\
\
Apps > Default apps
\
`app-prefs://com.apple.Settings.Apps.DefaultApps`
\
&emsp;/
\
`app-prefs://&target=com.apple.settings.default-applications`
\
&emsp;/
\
`settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.DefaultApps`
\
\
Apps > _bundle identifier for any app, also third party_
\
`settings-navigation://com.apple.Settings.Apps/bundle_identifier`
\
&emsp;/
\
`app-prefs//bundle_identifier` (not recommended, reportedly doesn't work with certain indentifiers)
\
\
Apps > Phone > Show My Caller ID
\
`prefs:root=Phone&path=CALLING_LINE_ID_RESTRICTION_TELEPHONY_SETTINGS`
\
\
Apps > Safari > Default Browser App (button)
\
`prefs:root=SAFARI#com.apple.settings.DefaultBrowser`
\
\
Apps > Safari > Search Engine
\
`prefs:root=SAFARI&path=SEARCH_ENGINE_SETTING`
\
\
Apps > Safari > Also Use in Private Browsing (switch)
\
`prefs:root=SAFARI#PRIVATE_BROWSING_USES_NORMAL_BROWSING_SEARCH_ENGINE_SELECTION`
\
\
Apps > Safari > Search Enginge Suggestions (switch)
\
`prefs:root=SAFARI#SEARCH_SUGGESTION_SETTING`
\
\
Apps > Safari > Safari Suggestions (switch)
\
`prefs:root=SAFARI#SIRI_SUGGESTIONS`
\
\
Apps > Safari > Quick Website Search
\
`prefs:root=SAFARI&path=SITE_SPECIFIC_SEARCH`
\
\
Apps > Safari > Preload Top Hit (switch)
\
`prefs:root=SAFARI#ENABLE_PREFETCHING`
\
\
Apps > Safari > AutoFill
\
`prefs:root=SAFARI&path=AUTO_FILL`
\
\
Apps > Safari > Start Page Favorites
\
`prefs:root=SAFARI&path=FAVORITES_FOLDER`
\
\
Apps > Safari > Extensions
\
`prefs:root=SAFARI&path=WEB_EXTENSIONS`
\
\
Apps > Safari > Downloads
\
`prefs:root=SAFARI&path=DOWNLOADS`
\
\
Apps > Safari > Open Links > _(in a) New Tab (and switch to it) or (in a new tab) In Background_
\
`prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPHONE` (iPhone)
\
`prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPAD` (iPad)
\
\
Apps > Safari > Require Passcode to Unlock Private Browsing (swtich)
\
`prefs:root=SAFARI#PrivateBrowsingRequiresAuthentication`
\
\
Apps > Safari > Not Secure Connection Warning (switch)
\
`prefs:root=SAFARI#WARN_ABOUT_INSECURE_CONNECTIONS`
\
\
Apps > Safari > Import (button)
\
`prefs:root=SAFARI#IMPORT_BUTTON`
\
\
Apps > Safari > Export (button)
\
`prefs:root=SAFARI#EXPORT_BUTTON`
\
\
Apps > Safari > Export (dialog)
\
`prefs:root=SAFARI&action=showExportSheet`
\
\
Apps > Safari > Clear History and Website Data (button)
\
`prefs:root=SAFARI#CLEAR_HISTORY_AND_DATA`
\
\
Apps > Safari > Settings for Websites (section)
\
`prefs:root=SAFARI#SPACE_CELL_FOR_PER_SITE_SETTINGS_SYNC_TOGGLE`
\
\
Apps > Safari > Advanced
\
`prefs:root=SAFARI&path=ADVANCED`
\
\
Apps > Safari > Advanced > Website Data
\
`prefs:root=SAFARI&path=ADVANCED/REMOVE_WEBSITE_DATA`
