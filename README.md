# Settings URL schemes for iOS 26

\
<sub>__Settings main page__</sub>
~~~yaml
prefs:root=ROOT
~~~
\
\
<sub>__Apple Account__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT
~~~
<sub>__Apple Account > Personal Information _(may take a while to load)___</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=APPLE_ACCOUNT_CONTACT
~~~
<sub>__Apple Account > Sign-In & Security _(may take a while to load)___</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=PASSWORD_AND_SECURITY
~~~
<sub>__Apple Account > Sign-In & Security > Change Password _(may take a while to load)___</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=changePassword
~~~
<sub>__Apple Account > Sign-In & Security > Recovery Contacts _(may take a while to load)___</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=accountRecovery
~~~
<sub>__Apple Account > Sign-In & Security > Legacy Contact _(may take a while to load)___</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=accountBeneficiary
~~~
<sub>__Apple Account > Payment & Shipping _(may take a while to load)___</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=PAYMENT_AND_SHIPPING
~~~
<sub>__Apple Account > Subscriptions _(may take a while to load)___</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=SUBSCRIPTIONS
~~~
<sub>__Apple Account > iCloud__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE
~~~
<sub>__Apple Account > iCloud > Storage__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP
~~~
<sub>__Apple Account > iCloud > Storage > Change Storage Plan__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CHANGE_STORAGE_PLAN
~~~
<sub>__Apple Account > iCloud > Saved to iCloud__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass
~~~
<sub>__Apple Account > iCloud > Saved to iCloud > iCloud Photos__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.CloudPhotos
~~~
<sub>__Apple Account > iCloud > Saved to iCloud > iCloud Drive__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Ubiquity
~~~
<sub>__Apple Account > iCloud > Saved to iCloud > Notes__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Notes
~~~
<sub>__Apple Account > iCloud > Saved to iCloud > iCloud Messages__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Messages
~~~
<sub>__Apple Account > iCloud > Saved to iCloud > iCloud Calendar__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Calendars
~~~
<sub>__Apple Account > iCloud > Saved to iCloud > Health__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Health
~~~
<sub>__Apple Account > iCloud > Backup__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/BACKUP
~~~
<sub>__Apple Account > iCloud > Backup > All Device Backups > (current device) > Backup Details__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CURRENT_DEVICE_BACKUP
~~~
<sub>__Apple Account > iCloud > Private Relay__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/INTERNET_PRIVACY
~~~
<sub>__Apple Account > iCloud > Hide My Email _(may take a while to load)___</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/PRIVATE_EMAIL_MANAGE
~~~
<sub>__Apple Account > iCloud > Advanced Data Protection__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/ICLOUD_ADP_SPECIFIER_NAME
~~~
<sub>__Apple Account > Family Set Up__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=setupFamily
~~~
<sub>__Apple Account > Find My__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=LOCATION_SHARING
~~~
<sub>__Apple Account > Media & Purchases__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=STORE_SERVICE
~~~
<sub>__Apple Account > Sign in with Apple__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=SIWA_SERVICE
~~~
<sub>__Apple Account > Contact Key Verification__</sub>
~~~yaml
prefs:root=APPLE_ACCOUNT&path=TRANSPARENCY
~~~
\
\
<sub>__Airplane Mode (switch) _(centers it on the screen, but doesn't highlight it)___</sub>
~~~yaml
prefs:root=ROOT#AIRPLANE_MODE
~~~
\
\
<sub>__Wi-Fi__</sub>
~~~yaml
prefs:root=WIFI
~~~
<sub>__Wi-Fi > (current network) > &#9432;__</sub>
~~~yaml
prefs:root=WIFI&path=NetworkDetails
~~~
\
\
<sub>__Cellular__</sub>
~~~yaml
prefs:root=MOBILE_DATA_SETTINGS_ID
~~~
<sub>__Cellular > Cellular Data Options__</sub>
~~~yaml
prefs:root=MOBILE_DATA_SETTINGS_ID&path=CELLULAR_DATA_OPTIONS
~~~
<sub>__Cellular > Cellular Data > Show All > Cellular Data Usage__</sub>
~~~yaml
prefs:root=MOBILE_DATA_SETTINGS_ID&path=SHOW_ALL
~~~
\
\
<sub>__Personal Hotspot__</sub>
~~~yaml
settings-navigation://com.apple.Settings.PersonalHotspot
~~~
\
\
<sub>__Battery__</sub>
~~~yaml
prefs:root=BATTERY_USAGE
~~~
<sub>__Battery > Battery Health & Charging _(device-dependant)___</sub>
~~~yaml
prefs:root=BATTERY_USAGE&path=BATTERY_HEALTH_TITLE
~~~
<sub>__Battery > Charging Options _(device-dependant)___</sub>
~~~yaml
prefs:root=BATTERY_USAGE&path=CHARGING_OPTIONS_IDENTIFIER
~~~
<sub>__Battery > Battery Percentage (switch)__</sub>
~~~yaml
prefs:root=BATTERY_USAGE#BATTERY_PERCENTAGE_IDENTIFIER
~~~
<sub>__Battery > Low Power Mode (switch)__</sub>
~~~yaml
prefs:root=BATTERY_USAGE#LOW_POWER_MODE_IDENTIFIER
~~~
\
\
<sub>__VPN (switch) _(centers it on the screen, but doesn't highlight it)___</sub>
~~~yaml
prefs:root=ROOT#VPN
~~~
\
\
<sub>__General__</sub>
~~~yaml
prefs:root=General
~~~
<sub>__General > About__</sub>
~~~yaml
prefs:root=General&path=About
~~~
<sub>__General > About > iOS Version__</sub>
~~~yaml
prefs:root=General&path=About/SW_VERSION_SPECIFIER
~~~
<sub>__General > About > Certificate Trust Settings__</sub>
~~~yaml
prefs:root=General&path=About/CERT_TRUST_SETTINGS
~~~
<sub>__General > Software Update__</sub>
~~~yaml
prefs:root=General&path=SOFTWARE_UPDATE_LINK
~~~
<sub>__General > Software Update > Automatic Updates__</sub>
~~~yaml
prefs:root=General&path=SOFTWARE_UPDATE_LINK/SUAutomaticUpdateButton
~~~
<sub>__General > Software Update > Beta Updates__</sub>
~~~yaml
prefs:root=General&path=SOFTWARE_UPDATE_LINK/SUAutomaticUpdateButton
~~~
<sub>__General > iPhone Storage__</sub>
~~~yaml
prefs:root=General&path=STORAGE_MGMT
~~~
<sub>__General > AppleCare & Warranty__</sub>
~~~yaml
prefs:root=General&path=COVERAGE
~~~
<sub>__General > Health Data__</sub>
~~~yaml
prefs:root=General&path=HEALTH_DATA
~~~
<sub>__General > AirDrop__</sub>
~~~yaml
prefs:root=General&path=AIRDROP_LINK
~~~
<sub>__General > Picture in Picture__</sub>
~~~yaml
prefs:root=General&path=PiP_SPEC
~~~
<sub>__General > Screen Capture__</sub>
~~~yaml
prefs:root=General&path=SCREEN_CAPTURE
~~~
<sub>__General > CarPlay__</sub>
~~~yaml
prefs:root=General&path=CARPLAY
~~~
<sub>__General > Matter Accessories__</sub>
~~~yaml
prefs:root=General&path=MATTER_ACCESSORIES
~~~
<sub>__General > AutoFill & Passwords__</sub>
~~~yaml
settings-navigation://com.apple.Settings.General/AUTOFILL
~~~
<sub>__General > Background App Refresh__</sub>
~~~yaml
prefs:root=General&path=AUTO_CONTENT_DOWNLOAD
~~~
<sub>__General > Date & Time__</sub>
~~~yaml
prefs:root=General&path=DATE_AND_TIME
~~~
<sub>__General > Dictionary__</sub>
~~~yaml
prefs:root=General&path=DICTIONARY
~~~
<sub>__General > Fonts__</sub>
~~~yaml
prefs:root=General&path=FONT_SETTING
~~~
<sub>__General > Fonts > System Fonts__</sub>
~~~yaml
prefs:root=General&path=FONT_SETTING/SYSTEM_FONTS
~~~
<sub>__General > Fonts > My Fonts__</sub>
~~~yaml
prefs:root=General&path=FONT_SETTING/USER_FONTS
~~~
<sub>__General > Fonts > More Fonts__</sub>
~~~yaml
prefs:root=General&path=FONT_SETTING/MORE_FONTS
~~~
<sub>__General > Keyboard__</sub>
~~~yaml
prefs:root=General&path=Keyboard
~~~
<sub>__General > Keyboard > Keyboards__</sub>
~~~yaml
prefs:root=General&path=Keyboard/KEYBOARDS
~~~
<sub>__General > Keyboard > Text Replacement__</sub>
~~~yaml
prefs:root=General&path=Keyboard/USER_DICTIONARY
~~~
<sub>__General > Keyboard > One-Handed Keyboard__</sub>
~~~yaml
prefs:root=General&path=Keyboard/ReachableKeyboard
~~~
<sub>__General > Language & Region__</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL
~~~
<sub>__General > Language & Region > Add Language__</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/ADD_PREFERRED_LANGUAGE
~~~
<sub>__General > Language & Region > Region__</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/LOCALE
~~~
<sub>__General > Language & Region > Calendar__</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/CALENDAR
~~~
<sub>__General > Language & Region > Temperature__</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/TEMPERATURE_UNIT
~~~
<sub>__General > Language & Region > Measurement System__</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/MEASUREMENT_SYSTEM
~~~
<sub>__General > Language & Region > First Day of Week__</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/FIRST_WEEKDAY
~~~
<sub>__General > Language & Region > Date Format__</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/DATE_FORMAT
~~~
<sub>__General > Language & Region > Number Format__</sub>
~~~yaml
prefs:root=General&path=INTERNATIONAL/NUMBER_FORMAT
~~~
<sub>__General > Language & Region > Live Text (switch)__</sub>
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL#LIVE_TEXT_CELL
~~~
<sub>__General > Trackpad & Mouse__</sub>
~~~yaml
settings-navigation://com.apple.Settings.General/POINTERS
~~~
<sub>__General > TV Provider__</sub>
~~~yaml
settings-navigation://com.apple.Settings.General/TV_PROVIDER
~~~
\
\
<sub>__Accessibility__</sub>
~~~yaml
prefs:root=ACCESSIBILITY
~~~
<sub>__Accessibility > Display & Text Size__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT
~~~
<sub>__Accessibility > Display & Text Size > Bold Text (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/ENHANCE_TEXT_LEGIBILITY
~~~
<sub>__Accessibility > Display & Text Size > Larger Text__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/LARGER_TEXT
~~~
<sub>__Accessibility > Display & Text Size > Button Shapes (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/BUTTON_SHAPES
~~~
<sub>__Accessibility > Display & Text Size > On/Off Labels (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/ON_OFF_LABELS
~~~
<sub>__Accessibility > Display & Text Size > Reduce Transparency (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/REDUCE_TRANSPARENCY
~~~
<sub>__Accessibility > Display & Text Size > Increase Contrast (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/TEXT_COLORS_DARKEN
~~~
<sub>__Accessibility > Display & Text Size > Differentiate Without Color (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/DIFFERENTIATE_WITHOUT_COLOR
~~~
<sub>__Accessibility > Display & Text Size > Prefer Horizontal Text (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/PREFER_HORIZONTAL_TEXT
~~~
<sub>__Accessibility > Display & Text Size > Smart Invert (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/SMART_INVERT
~~~
<sub>__Accessibility > Display & Text Size > Classic Invert (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/CLASSIC_INVERT
~~~
<sub>__Accessibility > Display & Text Size > Color Filters__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR
~~~
<sub>__Accessibility > Display & Text Size > Reduce White Point (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/WHITE_POINT
~~~
<sub>__Accessibility > Display & Text Size > Auto-Brightness (switch)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/AUTO_BRIGHTNESS
~~~
<sub>__Accessibility > Audio & Visual > Call Audio Routing__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING
~~~
<sub>__Accessibility > Audio & Visual > Call Audio Routing > Auto-Answer Calls__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
<sub>__Accessibility > Touch > Call Audio Routing__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING
~~~
<sub>__Accessibility > Touch > Call Audio Routing > Auto-Answer Calls__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
<sub>__Accessibility > AirPods__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=AIRPODS
~~~
<sub>__Accessibility > Per-App Settings__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE
~~~
<sub>__Accessibility > Per-App Settings > \[app's bundle identifier] (as long as you have added the app there, otherwise goes to the parent page)__</sub>
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE/bundle_identifier
~~~
\
\
<sub>__Display & Brightness__</sub>
~~~yaml
prefs:root=DISPLAY
~~~
<sub>__Display & Brightness > Appearance (section)__</sub>
~~~yaml
prefs:root=DISPLAY#DEVICE_APPEARANCE
~~~
<sub>__Display & Brightness > Appearance > Automatic (switch)__</sub>
~~~yaml
prefs:root=DISPLAY#AUTOMATIC
~~~
<sub>__Display & Brightness > Text Size__</sub>
~~~yaml
prefs:root=DISPLAY&path=TEXT_SIZE
~~~
<sub>__Display & Brightness > Bold Text (switch)__</sub>
~~~yaml
prefs:root=DISPLAY#BOLD_TEXT
~~~
<sub>__Display & Brightness > Brightness (slider)__</sub>
~~~yaml
prefs:root=DISPLAY#BRIGHTNESS
~~~
<sub>__Display & Brightness > True Tone (switch)__</sub>
~~~yaml
prefs:root=DISPLAY#WHITE_BALANCE
~~~
<sub>__Display & Brightness > Night Shift__</sub>
~~~yaml
prefs:root=DISPLAY&path=BLUE_LIGHT_REDUCTION
~~~
<sub>__Display & Brightness > Auto-Lock__</sub>
~~~yaml
prefs:root=DISPLAY&path=AUTOLOCK
~~~
<sub>__Display & Brightness > Raise to Wake (switch)__</sub>
~~~yaml
prefs:root=DISPLAY#RAISE_TO_WAKE
~~~
<sub>__Display & Brightness > Display Zoom__</sub>
~~~yaml
prefs:root=DISPLAY&path=MAGNIFY
~~~
\
<sub>__Home Screen & App Library__</sub>
~~~yaml
settings-navigation://com.apple.Settings.HomeScreenAndAppLibrary
~~~
\
\
<sub>__Search__</sub>
~~~yaml
settings-navigation://com.apple.Settings.Search
~~~
\
\
<sub>__Siri__</sub>
~~~yaml
prefs:root=SIRI
~~~
\
\
<sub>__StandBy__</sub>
~~~yaml
settings-navigation://com.apple.Settings.StandBy
~~~
\
\
<sub>__Sounds & Haptics__</sub>
~~~yaml
prefs:root=Sounds
~~~
<sub>__Sounds & Haptics > Haptics__</sub>
~~~yaml
prefs:root=Sounds&path=HAPTICS
~~~
<sub>__Sounds & Haptics > Keyboard Feedback__</sub>
~~~yaml
prefs:root=Sounds&path=KEYBOARD_FEEDBACK
~~~
<sub>__Sounds & Haptics > Built-In Speaker > Volume Limit__</sub>
~~~yaml
prefs:root=Sounds&path=VOLUME_LIMIT
~~~
<sub>__Sounds & Haptics > Headphone Safety__</sub>
~~~yaml
prefs:root=Sounds&path=HEADPHONE_LEVEL_LIMIT_SETTING
~~~
<sub>__Sounds & Haptics > Personalized Spatial Audio__</sub>
~~~yaml
prefs:root=Sounds&path=PERSONALIZED_SPATIAL_AUDIO
~~~
\
\
<sub>__Wallpaper__</sub>
~~~yaml
settings-navigation://com.apple.Settings.Wallpaper
~~~
<sub>__Wallpaper > Add New Wallpaper__</sub>
~~~yaml
settings-navigation://com.apple.Settings.Wallpaper/addNewWallpaper
~~~
\
\
<sub>__Privacy & Security__</sub>
~~~yaml
prefs:root=Privacy
~~~
<sub>__Privacy & Security > Blocked Contacts__</sub>
~~~yaml
prefs:root=Privacy&path=BLOCKLIST
~~~
\
\
<sub>__iCloud__</sub>
~~~yaml
settings-navigation://com.apple.Settings.iCloud
~~~
\
\
<sub>__Payment & Contactless__</sub>
~~~yaml
prefs:root=PASSBOOK
~~~
\
\
<sub>__Apps__</sub>
~~~yaml
settings-navigation://com.apple.Settings.Apps
~~~
<sub>__Apps > Default Apps__</sub>
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.DefaultApps
~~~
<sub>__Apps > \[bundle identifier for any app, also third party\]__</sub>
~~~yaml
settings-navigation://com.apple.Settings.Apps/bundle_identifier
~~~
<sub>__Apps > Compass__</sub>
~~~yaml
prefs:root=COMPASS
~~~
<sub>__Apps > Phone__</sub>
~~~yaml
prefs:root=Phone
~~~
<sub>__Apps > Phone > Wi-Fi Calling (switch)__</sub>
~~~yaml
prefs:root=Phone#WIFI_CALLING_TELEPHONY_SETTINGS
~~~
<sub>__Apps > Phone > Call Forwarding (switch)__</sub>
~~~yaml
prefs:root=Phone#CALL_FORWARDING_TELEPHONY_SETTINGS
~~~
<sub>__Apps > Phone > Call Waiting (switch)__</sub>
~~~yaml
prefs:root=Phone#CALL_WAITING_TELEPHONY_SETTINGS
~~~
<sub>__Apps > Phone > Show My Caller ID (switch)__</sub>
~~~yaml
prefs:root=Phone#CALLING_LINE_ID_RESTRICTION_TELEPHONY_SETTINGS
~~~
<sub>__Apps > Phone > Unknown Callers (switch)__</sub>
~~~yaml
prefs:root=Phone#FILTER_AS_NEW_CALLERS
~~~
<sub>__Apps > Phone > Blocked Contacts__</sub>
~~~yaml
prefs:root=Privacy&path=BLOCKLIST
~~~
<sub>__Apps > Safari > Default Browser App (button)__</sub>
~~~yaml
prefs:root=SAFARI#com.apple.settings.DefaultBrowser
~~~
<sub>__Apps > Safari > Search Engine__</sub>
~~~yaml
prefs:root=SAFARI&path=SEARCH_ENGINE_SETTING
~~~
<sub>__Apps > Safari > Also Use in Private Browsing (switch)__</sub>
~~~yaml
prefs:root=SAFARI#PRIVATE_BROWSING_USES_NORMAL_BROWSING_SEARCH_ENGINE_SELECTION
~~~
<sub>__Apps > Safari > Search Enginge Suggestions (switch)__</sub>
~~~yaml
prefs:root=SAFARI#SEARCH_SUGGESTION_SETTING
~~~
<sub>__Apps > Safari > Safari Suggestions (switch)__</sub>
~~~yaml
prefs:root=SAFARI#SIRI_SUGGESTIONS
~~~
<sub>__Apps > Safari > Quick Website Search__</sub>
~~~yaml
prefs:root=SAFARI&path=SITE_SPECIFIC_SEARCH
~~~
<sub>__Apps > Safari > Preload Top Hit (switch)__</sub>
~~~yaml
prefs:root=SAFARI#ENABLE_PREFETCHING
~~~
<sub>__Apps > Safari > AutoFill__</sub>
~~~yaml
prefs:root=SAFARI&path=AUTO_FILL
~~~
<sub>__Apps > Safari > Start Page Favorites__</sub>
~~~yaml
prefs:root=SAFARI&path=FAVORITES_FOLDER
~~~
<sub>__Apps > Safari > Extensions__</sub>
~~~yaml
prefs:root=SAFARI&path=WEB_EXTENSIONS
~~~
<sub>__Apps > Safari > Downloads__</sub>
~~~yaml
prefs:root=SAFARI&path=DOWNLOADS
~~~
<sub>__Apps > Safari > Open Links > New Tab \[switches to the new tab] or In Background \[doesn't leave the current tab]_

_<sub>__– iPhone__</sub>__</sub>
~~~yaml
prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPHONE
~~~

_<sub>__– iPad__</sub>__</sub>
~~~yaml
prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPAD
~~~
<sub>__Apps > Safari > Hide IP Address (button)__</sub>
~~~yaml
prefs:root=SAFARI&path=Hide%20IP%20Address
~~~
<sub>__Apps > Safari > Require Passcode to Unlock Private Browsing (swtich)__</sub>
~~~yaml
prefs:root=SAFARI#PrivateBrowsingRequiresAuthentication
~~~
<sub>__Apps > Safari > Not Secure Connection Warning (switch)__</sub>
~~~yaml
prefs:root=SAFARI#WARN_ABOUT_INSECURE_CONNECTIONS
~~~
<sub>__Apps > Safari > Import (button)__</sub>
~~~yaml
prefs:root=SAFARI#IMPORT_BUTTON
~~~
<sub>__Apps > Safari > Export (button)__</sub>
~~~yaml
prefs:root=SAFARI#EXPORT_BUTTON
~~~
<sub>__Apps > Safari > Export (dialog)__</sub>
~~~yaml
prefs:root=SAFARI&action=showExportSheet
~~~
<sub>__Apps > Safari > Clear History and Website Data (button)__</sub>
~~~yaml
prefs:root=SAFARI#CLEAR_HISTORY_AND_DATA
~~~
<sub>__Apps > Safari > Settings for Websites (section)__</sub>
~~~yaml
prefs:root=SAFARI#SPACE_CELL_FOR_PER_SITE_SETTINGS_SYNC_TOGGLE
~~~
<sub>__Apps > Safari > Advanced__</sub>
~~~yaml
prefs:root=SAFARI&path=ADVANCED
~~~
<sub>__Apps > Safari > Advanced > Website Data__</sub>
~~~yaml
prefs:root=SAFARI&path=ADVANCED/REMOVE_WEBSITE_DATA
~~~
