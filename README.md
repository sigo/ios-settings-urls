# Settings URL schemes for iOS 26

\
<sub>Settings main page</sub></sub>
~~~yaml
prefs:root=ROOT
~~~
\
\
<sub>Apple Account</sub></sub>
~~~yaml
prefs:root=APPLE_ACCOUNT
~~~
<sub>Apple Account > Personal Information _(may take a while to load)_</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=APPLE_ACCOUNT_CONTACT
~~~
<sub>Apple Account > Sign-In & Security _(may take a while to load)_</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=PASSWORD_AND_SECURITY
~~~
<sub>Apple Account > Sign-In & Security > Change Password _(may take a while to load)_</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=changePassword
~~~
<sub>Apple Account > Sign-In & Security > Recovery Contacts _(may take a while to load)_</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=accountRecovery
~~~
<sub>Apple Account > Sign-In & Security > Legacy Contact _(may take a while to load)_</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=accountBeneficiary
~~~
<sub>Apple Account > Payment & Shipping _(may take a while to load)_</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=PAYMENT_AND_SHIPPING
~~~
<sub>Apple Account > Subscriptions _(may take a while to load)_</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=SUBSCRIPTIONS
~~~
<sub>Apple Account > iCloud</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE
~~~
<sub>Apple Account > iCloud > Storage</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP
~~~
<sub>Apple Account > iCloud > Storage > Change Storage Plan</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CHANGE_STORAGE_PLAN
~~~
<sub>Apple Account > iCloud > Saved to iCloud</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass
~~~
<sub>Apple Account > iCloud > Saved to iCloud > iCloud Photos</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.CloudPhotos
~~~
<sub>Apple Account > iCloud > Saved to iCloud > iCloud Drive</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Ubiquity
~~~
<sub>Apple Account > iCloud > Saved to iCloud > Notes</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Notes
~~~
<sub>Apple Account > iCloud > Saved to iCloud > iCloud Messages</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Messages
~~~
<sub>Apple Account > iCloud > Saved to iCloud > iCloud Calendar</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Calendars
~~~
<sub>Apple Account > iCloud > Saved to iCloud > Health</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Health
~~~
<sub>Apple Account > iCloud > Backup</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/BACKUP
~~~
<sub>Apple Account > iCloud > Backup > All Device Backups > (current device) > Backup Details</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CURRENT_DEVICE_BACKUP
~~~
<sub>Apple Account > iCloud > Private Relay</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/INTERNET_PRIVACY
~~~
<sub>Apple Account > iCloud > Hide My Email _(may take a while to load)_</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/PRIVATE_EMAIL_MANAGE
~~~
<sub>Apple Account > iCloud > Advanced Data Protection</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/ICLOUD_ADP_SPECIFIER_NAME
~~~
<sub>Apple Account > Family Set Up</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=setupFamily
~~~
<sub>Apple Account > Find My</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=LOCATION_SHARING
~~~
<sub>Apple Account > Media & Purchases</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=STORE_SERVICE
~~~
<sub>Apple Account > Sign in with Apple</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=SIWA_SERVICE
~~~
<sub>Apple Account > Contact Key Verification</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=TRANSPARENCY
~~~
\
\
<sub>Airplane Mode (switch) _(centers it on the screen, but doesn't highlight it)_</sub>
~~~yaml
prefs:root=ROOT#AIRPLANE_MODE
~~~
\
\
<sub>Wi-Fi</sub>
~~~yaml
prefs:root=WIFI
~~~
<sub>Wi-Fi > (current network) > &#9432;</sub>
~~~yaml
prefs:root=WIFI&path=NetworkDetails
~~~
\
\
<sub>Cellular</sub>
~~~yaml
prefs:root=MOBILE_DATA_SETTINGS_ID
~~~
<sub>Cellular > Cellular Data Options</sub>
~~~yaml
prefs:root=MOBILE_DATA_SETTINGS_ID&path=CELLULAR_DATA_OPTIONS
~~~
<sub>Cellular > Cellular Data > Show All > Cellular Data Usage</sub>
~~~yaml
prefs:root=MOBILE_DATA_SETTINGS_ID&path=SHOW_ALL
~~~
\
\
<sub>Personal Hotspot</sub>
~~~yaml
settings-navigation://com.apple.Settings.PersonalHotspot
~~~
\
\
<sub>Battery</sub>
~~~yaml
prefs:root=BATTERY_USAGE
~~~
<sub>Battery > Battery Health & Charging _(device-dependant)_</sub>
~~~yaml
prefs:root=BATTERY_USAGE&path=BATTERY_HEALTH_TITLE
~~~
<sub>Battery > Charging Options _(device-dependant)_</sub>
~~~yaml
prefs:root=BATTERY_USAGE&path=CHARGING_OPTIONS_IDENTIFIER
~~~
<sub>Battery > Battery Percentage (switch)</sub>
~~~yaml
prefs:root=BATTERY_USAGE#BATTERY_PERCENTAGE_IDENTIFIER
~~~
<sub>Battery > Low Power Mode (switch)</sub>
~~~yaml
prefs:root=BATTERY_USAGE#LOW_POWER_MODE_IDENTIFIER
~~~
\
\
<sub>VPN (switch) _(centers it on the screen, but doesn't highlight it)_</sub>
~~~yaml
prefs:root=ROOT#VPN
~~~
\
\
<sub>General</sub>
~~~yaml
prefs:root=General
~~~
<sub>General > About</sub>
~~~yaml
prefs:root=General&path=About
~~~
<sub>General > About > iOS Version</sub>
~~~yaml
prefs:root=General&path=About/SW_VERSION_SPECIFIER
~~~
<sub>General > About > Certificate Trust Settings</sub>
~~~yaml
prefs:root=General&path=About/CERT_TRUST_SETTINGS
~~~
<sub>General > Software Update</sub>
~~~yaml
prefs:root=General&path=SOFTWARE_UPDATE_LINK
~~~
<sub>General > Software Update > Automatic Updates</sub>
~~~yaml
prefs:root=General&path=SOFTWARE_UPDATE_LINK/SUAutomaticUpdateButton
~~~
<sub>General > Software Update > Beta Updates</sub>
~~~yaml
prefs:root=General&path=SOFTWARE_UPDATE_LINK/SUAutomaticUpdateButton
~~~
<sub>General > iPhone Storage</sub>
~~~yaml
prefs:root=General&path=STORAGE_MGMT
~~~
<sub>General > AppleCare & Warranty</sub>
~~~yaml
prefs:root=General&path=COVERAGE
~~~
<sub>General > Health Data</sub>
~~~yaml
prefs:root=General&path=HEALTH_DATA
~~~
<sub>General > AirDrop</sub>
~~~yaml
prefs:root=General&path=AIRDROP_LINK
~~~
<sub>General > Picture in Picture</sub>
~~~yaml
prefs:root=General&path=PiP_SPEC
~~~
<sub>General > Screen Capture</sub>
~~~yaml
prefs:root=General&path=SCREEN_CAPTURE
~~~
<sub>General > CarPlay</sub>
~~~yaml
prefs:root=General&path=CARPLAY
~~~
<sub>General > Matter Accessories</sub>
~~~yaml
prefs:root=General&path=MATTER_ACCESSORIES
~~~
<sub>General > AutoFill & Passwords</sub>
~~~yaml
settings-navigation://com.apple.Settings.General/AUTOFILL
~~~
<sub>General > Background App Refresh</sub>
~~~yaml
prefs:root=General&path=AUTO_CONTENT_DOWNLOAD
~~~
<sub>General > Date & Time</sub>
~~~yaml
prefs:root=General&path=DATE_AND_TIME
~~~
<sub>General > Dictionary</sub>
~~~yaml
prefs:root=General&path=DICTIONARY
~~~
<sub>General > Fonts</sub>
~~~yaml
prefs:root=General&path=FONT_SETTING
~~~
<sub>General > Fonts > System Fonts</sub>
~~~yaml
prefs:root=General&path=FONT_SETTING/SYSTEM_FONTS
~~~
<sub>General > Fonts > My Fonts</sub>
~~~yaml
prefs:root=General&path=FONT_SETTING/USER_FONTS
~~~
<sub>General > Fonts > More Fonts</sub>
~~~yaml
prefs:root=General&path=FONT_SETTING/MORE_FONTS
~~~
<sub>General > Keyboard</sub>
~~~yaml
prefs:root=General&path=Keyboard
~~~
<sub>General > Keyboard > Keyboards</sub>
~~~yaml
prefs:root=General&path=Keyboard/KEYBOARDS
~~~
<sub>General > Keyboard > Text Replacement</sub>
~~~yaml
prefs:root=General&path=Keyboard/USER_DICTIONARY
~~~
<sub>General > Keyboard > One-Handed Keyboard</sub>
~~~yaml
prefs:root=General&path=Keyboard/ReachableKeyboard
~~~
<sub>General > Language & Region</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL
~~~
<sub>General > Language & Region > Add Language</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/ADD_PREFERRED_LANGUAGE
~~~
<sub>General > Language & Region > Region</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/LOCALE
~~~
<sub>General > Language & Region > Calendar</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/CALENDAR
~~~
<sub>General > Language & Region > Temperature</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/TEMPERATURE_UNIT
~~~
<sub>General > Language & Region > Measurement System</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/MEASUREMENT_SYSTEM
~~~
<sub>General > Language & Region > First Day of Week</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/FIRST_WEEKDAY
~~~
<sub>General > Language & Region > Date Format</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/DATE_FORMAT
~~~
<sub>General > Language & Region > Number Format</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/NUMBER_FORMAT
~~~
<sub>General > Language & Region > Live Text (switch)</sub>
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL#LIVE_TEXT_CELL
~~~
<sub>General > Trackpad & Mouse</sub>
~~~yaml
settings-navigation://com.apple.Settings.General/POINTERS
~~~
<sub>General > TV Provider</sub>
~~~yaml
settings-navigation://com.apple.Settings.General/TV_PROVIDER
~~~
\
\
<sub>Accessibility</sub>
~~~yaml
prefs:root=ACCESSIBILITY
~~~
<sub>Accessibility > Display & Text Size</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT
~~~
<sub>Accessibility > Display & Text Size > Bold Text (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/ENHANCE_TEXT_LEGIBILITY
~~~
<sub>Accessibility > Display & Text Size > Larger Text</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/LARGER_TEXT
~~~
<sub>Accessibility > Display & Text Size > Button Shapes (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/BUTTON_SHAPES
~~~
<sub>Accessibility > Display & Text Size > On/Off Labels (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/ON_OFF_LABELS
~~~
<sub>Accessibility > Display & Text Size > Reduce Transparency (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/REDUCE_TRANSPARENCY
~~~
<sub>Accessibility > Display & Text Size > Increase Contrast (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/TEXT_COLORS_DARKEN
~~~
<sub>Accessibility > Display & Text Size > Differentiate Without Color (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/DIFFERENTIATE_WITHOUT_COLOR
~~~
<sub>Accessibility > Display & Text Size > Prefer Horizontal Text (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/PREFER_HORIZONTAL_TEXT
~~~
<sub>Accessibility > Display & Text Size > Smart Invert (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/SMART_INVERT
~~~
<sub>Accessibility > Display & Text Size > Classic Invert (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/CLASSIC_INVERT
~~~
<sub>Accessibility > Display & Text Size > Color Filters</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR
~~~
<sub>Accessibility > Display & Text Size > Reduce White Point (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/WHITE_POINT
~~~
<sub>Accessibility > Display & Text Size > Auto-Brightness (switch)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/AUTO_BRIGHTNESS
~~~
<sub>Accessibility > Audio & Visual > Call Audio Routing</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING
~~~
<sub>Accessibility > Audio & Visual > Call Audio Routing > Auto-Answer Calls</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
<sub>Accessibility > Touch > Call Audio Routing</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING
~~~
<sub>Accessibility > Touch > Call Audio Routing > Auto-Answer Calls</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
<sub>Accessibility > AirPods</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=AIRPODS
~~~
<sub>Accessibility > Per-App Settings</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE
~~~
<sub>Accessibility > Per-App Settings > \[app's bundle identifier] (as long as you have added the app there, otherwise goes to the parent page)</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE/bundle_identifier
~~~
\
\
<sub>Display & Brightness</sub>
~~~yaml
prefs:root=DISPLAY
~~~
<sub>Display & Brightness > Appearance (section)</sub>
~~~yaml
prefs:root=DISPLAY#DEVICE_APPEARANCE
~~~
<sub>Display & Brightness > Appearance > Automatic (switch)</sub>
~~~yaml
prefs:root=DISPLAY#AUTOMATIC
~~~
<sub>Display & Brightness > Text Size</sub>
~~~yaml
prefs:root=DISPLAY&path=TEXT_SIZE
~~~
<sub>Display & Brightness > Bold Text (switch)</sub>
~~~yaml
prefs:root=DISPLAY#BOLD_TEXT
~~~
<sub>Display & Brightness > Brightness (slider)</sub>
~~~yaml
prefs:root=DISPLAY#BRIGHTNESS
~~~
<sub>Display & Brightness > True Tone (switch)</sub>
~~~yaml
prefs:root=DISPLAY#WHITE_BALANCE
~~~
<sub>Display & Brightness > Night Shift</sub>
~~~yaml
prefs:root=DISPLAY&path=BLUE_LIGHT_REDUCTION
~~~
<sub>Display & Brightness > Auto-Lock</sub>
~~~yaml
prefs:root=DISPLAY&path=AUTOLOCK
~~~
<sub>Display & Brightness > Raise to Wake (switch)</sub>
~~~yaml
prefs:root=DISPLAY#RAISE_TO_WAKE
~~~
<sub>Display & Brightness > Display Zoom</sub>
~~~yaml
prefs:root=DISPLAY&path=MAGNIFY
~~~
\
<sub>Home Screen & App Library</sub>
~~~yaml
settings-navigation://com.apple.Settings.HomeScreenAndAppLibrary
~~~
\
\
<sub>Search</sub>
~~~yaml
settings-navigation://com.apple.Settings.Search
~~~
\
\
<sub>Siri</sub>
~~~yaml
prefs:root=SIRI
~~~
\
\
<sub>StandBy</sub>
~~~yaml
settings-navigation://com.apple.Settings.StandBy
~~~
\
\
<sub>Sounds & Haptics</sub>
~~~yaml
prefs:root=Sounds
~~~
<sub>Sounds & Haptics > Haptics</sub>
~~~yaml
prefs:root=Sounds&path=HAPTICS
~~~
<sub>Sounds & Haptics > Keyboard Feedback</sub>
~~~yaml
prefs:root=Sounds&path=KEYBOARD_FEEDBACK
~~~
<sub>Sounds & Haptics > Built-In Speaker > Volume Limit</sub>
~~~yaml
prefs:root=Sounds&path=VOLUME_LIMIT
~~~
<sub>Sounds & Haptics > Headphone Safety</sub>
~~~yaml
prefs:root=Sounds&path=HEADPHONE_LEVEL_LIMIT_SETTING
~~~
<sub>Sounds & Haptics > Personalized Spatial Audio</sub>
~~~yaml
prefs:root=Sounds&path=PERSONALIZED_SPATIAL_AUDIO
~~~
\
\
<sub>Wallpaper</sub>
~~~yaml
settings-navigation://com.apple.Settings.Wallpaper
~~~
<sub>Wallpaper > Add New Wallpaper</sub>
~~~yaml
settings-navigation://com.apple.Settings.Wallpaper/addNewWallpaper
~~~
\
\
<sub>Privacy & Security</sub>
~~~yaml
prefs:root=Privacy
~~~
<sub>Privacy & Security > Blocked Contacts</sub>
~~~yaml
prefs:root=Privacy&path=BLOCKLIST
~~~
\
\
<sub>iCloud</sub>
~~~yaml
settings-navigation://com.apple.Settings.iCloud
~~~
\
\
<sub>Payment & Contactless</sub>
~~~yaml
prefs:root=PASSBOOK
~~~
\
\
<sub>Apps</sub>
~~~yaml
settings-navigation://com.apple.Settings.Apps
~~~
<sub>Apps > Default Apps</sub>
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.DefaultApps
~~~
<sub>Apps > \[bundle identifier for any app, also third party\]</sub>
~~~yaml
settings-navigation://com.apple.Settings.Apps/bundle_identifier
~~~
<sub>Apps > Compass</sub>
~~~yaml
prefs:root=COMPASS
~~~
<sub>Apps > Phone</sub>
~~~yaml
prefs:root=Phone
~~~
<sub>Apps > Phone > Wi-Fi Calling (switch)</sub>
~~~yaml
prefs:root=Phone#WIFI_CALLING_TELEPHONY_SETTINGS
~~~
<sub>Apps > Phone > Call Forwarding (switch)</sub>
~~~yaml
prefs:root=Phone#CALL_FORWARDING_TELEPHONY_SETTINGS
~~~
<sub>Apps > Phone > Call Waiting (switch)</sub>
~~~yaml
prefs:root=Phone#CALL_WAITING_TELEPHONY_SETTINGS
~~~
<sub>Apps > Phone > Show My Caller ID (switch)</sub>
~~~yaml
prefs:root=Phone#CALLING_LINE_ID_RESTRICTION_TELEPHONY_SETTINGS
~~~
<sub>Apps > Phone > Unknown Callers (switch)</sub>
~~~yaml
prefs:root=Phone#FILTER_AS_NEW_CALLERS
~~~
<sub>Apps > Phone > Blocked Contacts</sub>
~~~yaml
prefs:root=Privacy&path=BLOCKLIST
~~~
<sub>Apps > Safari > Default Browser App (button)</sub>
~~~yaml
prefs:root=SAFARI#com.apple.settings.DefaultBrowser
~~~
<sub>Apps > Safari > Search Engine</sub>
~~~yaml
prefs:root=SAFARI&path=SEARCH_ENGINE_SETTING
~~~
<sub>Apps > Safari > Also Use in Private Browsing (switch)</sub>
~~~yaml
prefs:root=SAFARI#PRIVATE_BROWSING_USES_NORMAL_BROWSING_SEARCH_ENGINE_SELECTION
~~~
<sub>Apps > Safari > Search Enginge Suggestions (switch)</sub>
~~~yaml
prefs:root=SAFARI#SEARCH_SUGGESTION_SETTING
~~~
<sub>Apps > Safari > Safari Suggestions (switch)</sub>
~~~yaml
prefs:root=SAFARI#SIRI_SUGGESTIONS
~~~
<sub>Apps > Safari > Quick Website Search</sub>
~~~yaml
prefs:root=SAFARI&path=SITE_SPECIFIC_SEARCH
~~~
<sub>Apps > Safari > Preload Top Hit (switch)</sub>
~~~yaml
prefs:root=SAFARI#ENABLE_PREFETCHING
~~~
<sub>Apps > Safari > AutoFill</sub>
~~~yaml
prefs:root=SAFARI&path=AUTO_FILL
~~~
<sub>Apps > Safari > Start Page Favorites</sub>
~~~yaml
prefs:root=SAFARI&path=FAVORITES_FOLDER
~~~
<sub>Apps > Safari > Extensions</sub>
~~~yaml
prefs:root=SAFARI&path=WEB_EXTENSIONS
~~~
<sub>Apps > Safari > Downloads</sub>
~~~yaml
prefs:root=SAFARI&path=DOWNLOADS
~~~
<sub>Apps > Safari > Open Links > New Tab \[switches to the new tab] or In Background \[doesn't leave the current tab]_

_<sub>– iPhone</sub></sub>
~~~yaml
prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPHONE
~~~

_<sub>– iPad</sub></sub>
~~~yaml
prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPAD
~~~
<sub>Apps > Safari > Hide IP Address (button)</sub>
~~~yaml
prefs:root=SAFARI&path=Hide%20IP%20Address
~~~
<sub>Apps > Safari > Require Passcode to Unlock Private Browsing (swtich)</sub>
~~~yaml
prefs:root=SAFARI#PrivateBrowsingRequiresAuthentication
~~~
<sub>Apps > Safari > Not Secure Connection Warning (switch)</sub>
~~~yaml
prefs:root=SAFARI#WARN_ABOUT_INSECURE_CONNECTIONS
~~~
<sub>Apps > Safari > Import (button)</sub>
~~~yaml
prefs:root=SAFARI#IMPORT_BUTTON
~~~
<sub>Apps > Safari > Export (button)</sub>
~~~yaml
prefs:root=SAFARI#EXPORT_BUTTON
~~~
<sub>Apps > Safari > Export (dialog)</sub>
~~~yaml
prefs:root=SAFARI&action=showExportSheet
~~~
<sub>Apps > Safari > Clear History and Website Data (button)</sub>
~~~yaml
prefs:root=SAFARI#CLEAR_HISTORY_AND_DATA
~~~
<sub>Apps > Safari > Settings for Websites (section)</sub>
~~~yaml
prefs:root=SAFARI#SPACE_CELL_FOR_PER_SITE_SETTINGS_SYNC_TOGGLE
~~~
<sub>Apps > Safari > Advanced</sub>
~~~yaml
prefs:root=SAFARI&path=ADVANCED
~~~
<sub>Apps > Safari > Advanced > Website Data</sub>
~~~yaml
prefs:root=SAFARI&path=ADVANCED/REMOVE_WEBSITE_DATA
~~~
