# Settings URL schemes for iOS 26

\
_Settings main page_
~~~yaml
prefs:root=ROOT
~~~
\
\
_Apple Account_
~~~yaml
prefs:root=APPLE_ACCOUNT
~~~
_Apple Account > Personal Information <sup>(may take a while to load)</sup>_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=APPLE_ACCOUNT_CONTACT
~~~
_Apple Account > Sign-In & Security <sup>(may take a while to load)</sup>_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=PASSWORD_AND_SECURITY
~~~
_Apple Account > Sign-In & Security > Change Password <sup>(may take a while to load)</sup>_
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=changePassword
~~~
_Apple Account > Sign-In & Security > Recovery Contacts <sup>(may take a while to load)</sup>_
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=accountRecovery
~~~
_Apple Account > Sign-In & Security > Legacy Contact <sup>(may take a while to load)</sup>_
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=accountBeneficiary
~~~
_Apple Account > Payment & Shipping <sup>(may take a while to load)</sup>_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=PAYMENT_AND_SHIPPING
~~~
_Apple Account > Subscriptions <sup>(may take a while to load)</sup>_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=SUBSCRIPTIONS
~~~
_Apple Account > iCloud_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE
~~~
_Apple Account > iCloud > Storage_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP
~~~
_Apple Account > iCloud > Storage > Change Storage Plan_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CHANGE_STORAGE_PLAN
~~~
_Apple Account > iCloud > Saved to iCloud_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass
~~~
_Apple Account > iCloud > Saved to iCloud > iCloud Photos_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.CloudPhotos
~~~
_Apple Account > iCloud > Saved to iCloud > iCloud Drive_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Ubiquity
~~~
_Apple Account > iCloud > Saved to iCloud > Notes_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Notes
~~~
_Apple Account > iCloud > Saved to iCloud > iCloud Messages_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Messages
~~~
_Apple Account > iCloud > Saved to iCloud > iCloud Calendar_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Calendars
~~~
_Apple Account > iCloud > Saved to iCloud > Health_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.Health
~~~
_Apple Account > iCloud > Backup_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/BACKUP
~~~
_Apple Account > iCloud > Backup > All Device Backups > `current device` > Backup Details_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CURRENT_DEVICE_BACKUP
~~~
_Apple Account > iCloud > Private Relay_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/INTERNET_PRIVACY
~~~
_Apple Account > iCloud > Hide My Email <sup>(may take a while to load)</sup>_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/PRIVATE_EMAIL_MANAGE
~~~
_Apple Account > iCloud > Advanced Data Protection_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/ICLOUD_ADP_SPECIFIER_NAME
~~~
_Apple Account > Family Set Up_
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=setupFamily
~~~
_Apple Account > Find My_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=LOCATION_SHARING
~~~
_Apple Account > Media & Purchases_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=STORE_SERVICE
~~~
_Apple Account > Sign in with Apple_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=SIWA_SERVICE
~~~
_Apple Account > Contact Key Verification_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=TRANSPARENCY
~~~
\
\
_AirPods_
\
\
_[see Bluetooth > AirPods]_
\
\
\
\
_Airplane Mode (switch) <sub>(centers it on the screen, but doesn't highlight it)</sub>_
~~~yaml
prefs:root=ROOT#AIRPLANE_MODE
~~~
\
\
_Wi-Fi_
~~~yaml
prefs:root=WIFI
~~~
_Wi-Fi > `current network` > &#9432;_
~~~yaml
prefs:root=WIFI&path=NetworkDetails
~~~
\
\
_Bluetooth_
~~~yaml
prefs:root=Bluetooth
~~~
\
\
_Bluetooth > AirPods <sub>(replace `XX:XX:XX:XX:XX:XX` with AirPods' MAC address - find it with e.g. `system_profiler SPBluetoothDataType` on a Mac)_
~~~yaml
settings-navigation://com.apple.Settings.Bluetooth/HeadphoneDetail/?identifier=XX:XX:XX:XX:XX:XX
~~~
\
\
_Cellular_
~~~yaml
prefs:root=MOBILE_DATA_SETTINGS_ID
~~~
_Cellular > Cellular Data Options_
~~~yaml
prefs:root=MOBILE_DATA_SETTINGS_ID&path=CELLULAR_DATA_OPTIONS
~~~
_Cellular > Cellular Data > Show All > Cellular Data Usage_
~~~yaml
prefs:root=MOBILE_DATA_SETTINGS_ID&path=SHOW_ALL
~~~
\
\
_Personal Hotspot_
~~~yaml
settings-navigation://com.apple.Settings.PersonalHotspot
~~~
\
\
_Battery_
~~~yaml
prefs:root=BATTERY_USAGE
~~~
_Battery > Battery Health & Charging <sup>(device-dependant)</sup>_
~~~yaml
prefs:root=BATTERY_USAGE&path=BATTERY_HEALTH_TITLE
~~~
_Battery > Charging Options <sup>(device-dependant)</sup>_
~~~yaml
prefs:root=BATTERY_USAGE&path=CHARGING_OPTIONS_IDENTIFIER
~~~
_Battery > Battery Percentage (switch)_
~~~yaml
prefs:root=BATTERY_USAGE#BATTERY_PERCENTAGE_IDENTIFIER
~~~
_Battery > Low Power Mode (switch)_
~~~yaml
prefs:root=BATTERY_USAGE#LOW_POWER_MODE_IDENTIFIER
~~~
\
\
_VPN (switch) <sub>(centers it on the screen, but doesn't highlight it)</sub>_
~~~yaml
prefs:root=ROOT#VPN
~~~
\
\
_General_
~~~yaml
prefs:root=General
~~~
_General > About_
~~~yaml
prefs:root=General&path=About
~~~
_General > About > iOS Version_
~~~yaml
prefs:root=General&path=About/SW_VERSION_SPECIFIER
~~~
_General > About > Certificate Trust Settings_
~~~yaml
prefs:root=General&path=About/CERT_TRUST_SETTINGS
~~~
_General > Software Update_
~~~yaml
prefs:root=General&path=SOFTWARE_UPDATE_LINK
~~~
_General > Software Update > Automatic Updates_
~~~yaml
prefs:root=General&path=SOFTWARE_UPDATE_LINK/SUAutomaticUpdateButton
~~~
_General > Software Update > Beta Updates_
~~~yaml
prefs:root=General&path=SOFTWARE_UPDATE_LINK/SUAutomaticUpdateButton
~~~
_General > iPhone Storage_
~~~yaml
prefs:root=General&path=STORAGE_MGMT
~~~
_General > AppleCare & Warranty_
~~~yaml
prefs:root=General&path=COVERAGE
~~~
_General > Health Data_
~~~yaml
prefs:root=General&path=HEALTH_DATA
~~~
_General > AirDrop_
~~~yaml
prefs:root=General&path=AIRDROP_LINK
~~~
_General > Picture in Picture_
~~~yaml
prefs:root=General&path=PiP_SPEC
~~~
_General > Screen Capture_
~~~yaml
prefs:root=General&path=SCREEN_CAPTURE
~~~
_General > CarPlay_
~~~yaml
prefs:root=General&path=CARPLAY
~~~
_General > Matter Accessories_
~~~yaml
prefs:root=General&path=MATTER_ACCESSORIES
~~~
_General > AutoFill & Passwords_
~~~yaml
settings-navigation://com.apple.Settings.General/AUTOFILL
~~~
_General > Background App Refresh_
~~~yaml
prefs:root=General&path=AUTO_CONTENT_DOWNLOAD
~~~
_General > Date & Time_
~~~yaml
prefs:root=General&path=DATE_AND_TIME
~~~
_General > Dictionary_
~~~yaml
prefs:root=General&path=DICTIONARY
~~~
_General > Fonts_
~~~yaml
prefs:root=General&path=FONT_SETTING
~~~
_General > Fonts > System Fonts_
~~~yaml
prefs:root=General&path=FONT_SETTING/SYSTEM_FONTS
~~~
_General > Fonts > My Fonts_
~~~yaml
prefs:root=General&path=FONT_SETTING/USER_FONTS
~~~
_General > Fonts > More Fonts_
~~~yaml
prefs:root=General&path=FONT_SETTING/MORE_FONTS
~~~
_General > Keyboard_
~~~yaml
prefs:root=General&path=Keyboard
~~~
_General > Keyboard > Keyboards_
~~~yaml
prefs:root=General&path=Keyboard/KEYBOARDS
~~~
_General > Keyboard > Text Replacement_
~~~yaml
prefs:root=General&path=Keyboard/USER_DICTIONARY
~~~
_General > Keyboard > One-Handed Keyboard_
~~~yaml
prefs:root=General&path=Keyboard/ReachableKeyboard
~~~
_General > Language & Region_
~~~yaml
prefs:root=General&path=INTERNATIONAL
~~~
_General > Language & Region > Add Language_
~~~yaml
prefs:root=General&path=INTERNATIONAL/ADD_PREFERRED_LANGUAGE
~~~
_General > Language & Region > Region_
~~~yaml
prefs:root=General&path=INTERNATIONAL/LOCALE
~~~
_General > Language & Region > Calendar_
~~~yaml
prefs:root=General&path=INTERNATIONAL/CALENDAR
~~~
_General > Language & Region > Temperature_
~~~yaml
prefs:root=General&path=INTERNATIONAL/TEMPERATURE_UNIT
~~~
_General > Language & Region > Measurement System_
~~~yaml
prefs:root=General&path=INTERNATIONAL/MEASUREMENT_SYSTEM
~~~
_General > Language & Region > First Day of Week_
~~~yaml
prefs:root=General&path=INTERNATIONAL/FIRST_WEEKDAY
~~~
_General > Language & Region > Date Format_
~~~yaml
prefs:root=General&path=INTERNATIONAL/DATE_FORMAT
~~~
_General > Language & Region > Number Format_
~~~yaml
prefs:root=General&path=INTERNATIONAL/NUMBER_FORMAT
~~~
_General > Language & Region > Live Text (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL#LIVE_TEXT_CELL
~~~
_General > Trackpad & Mouse_
~~~yaml
settings-navigation://com.apple.Settings.General/POINTERS
~~~
_General > TV Provider_
~~~yaml
settings-navigation://com.apple.Settings.General/TV_PROVIDER
~~~
\
\
_Accessibility_
~~~yaml
prefs:root=ACCESSIBILITY
~~~
_Accessibility > Display & Text Size_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT
~~~
_Accessibility > Display & Text Size > Bold Text (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/ENHANCE_TEXT_LEGIBILITY
~~~
_Accessibility > Display & Text Size > Larger Text_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/LARGER_TEXT
~~~
_Accessibility > Display & Text Size > Button Shapes (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/BUTTON_SHAPES
~~~
_Accessibility > Display & Text Size > On/Off Labels (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/ON_OFF_LABELS
~~~
_Accessibility > Display & Text Size > Reduce Transparency (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/REDUCE_TRANSPARENCY
~~~
_Accessibility > Display & Text Size > Increase Contrast (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/TEXT_COLORS_DARKEN
~~~
_Accessibility > Display & Text Size > Differentiate Without Color (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/DIFFERENTIATE_WITHOUT_COLOR
~~~
_Accessibility > Display & Text Size > Prefer Horizontal Text (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/PREFER_HORIZONTAL_TEXT
~~~
_Accessibility > Display & Text Size > Smart Invert (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/SMART_INVERT
~~~
_Accessibility > Display & Text Size > Classic Invert (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/CLASSIC_INVERT
~~~
_Accessibility > Display & Text Size > Color Filters_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR
~~~
_Accessibility > Display & Text Size > Reduce White Point (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/WHITE_POINT
~~~
_Accessibility > Display & Text Size > Auto-Brightness (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/AUTO_BRIGHTNESS
~~~
_Accessibility > Audio & Visual > Call Audio Routing_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING
~~~
_Accessibility > Audio & Visual > Call Audio Routing > Auto-Answer Calls_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
_Accessibility > Touch > Call Audio Routing_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING
~~~
_Accessibility > Touch > Call Audio Routing > Auto-Answer Calls_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
_Accessibility > AirPods_
~~~yaml
prefs:root=ACCESSIBILITY&path=AIRPODS
~~~
_Accessibility > Per-App Settings_
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE
~~~
_Accessibility > Per-App Settings > `app's bundle identifier` <sup>(as long as you have added the app there, otherwise goes to the parent page)</sup>_
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE/bundle_identifier
~~~
\
\
_Display & Brightness_
~~~yaml
prefs:root=DISPLAY
~~~
_Display & Brightness > Appearance (section)_
~~~yaml
prefs:root=DISPLAY#DEVICE_APPEARANCE
~~~
_Display & Brightness > Appearance > Automatic (switch)_
~~~yaml
prefs:root=DISPLAY#AUTOMATIC
~~~
_Display & Brightness > Text Size_
~~~yaml
prefs:root=DISPLAY&path=TEXT_SIZE
~~~
_Display & Brightness > Bold Text (switch)_
~~~yaml
prefs:root=DISPLAY#BOLD_TEXT
~~~
_Display & Brightness > Brightness (slider)_
~~~yaml
prefs:root=DISPLAY#BRIGHTNESS
~~~
_Display & Brightness > True Tone (switch)_
~~~yaml
prefs:root=DISPLAY#WHITE_BALANCE
~~~
_Display & Brightness > Night Shift_
~~~yaml
prefs:root=DISPLAY&path=BLUE_LIGHT_REDUCTION
~~~
_Display & Brightness > Auto-Lock_
~~~yaml
prefs:root=DISPLAY&path=AUTOLOCK
~~~
_Display & Brightness > Raise to Wake (switch)_
~~~yaml
prefs:root=DISPLAY#RAISE_TO_WAKE
~~~
_Display & Brightness > Display Zoom_
~~~yaml
prefs:root=DISPLAY&path=MAGNIFY
~~~
\
\
_Home Screen & App Library_
~~~yaml
settings-navigation://com.apple.Settings.HomeScreenAndAppLibrary
~~~
\
\
_Search_
~~~yaml
settings-navigation://com.apple.Settings.Search
~~~
\
\
_Siri_
~~~yaml
prefs:root=SIRI
~~~
\
\
_StandBy_
~~~yaml
settings-navigation://com.apple.Settings.StandBy
~~~
\
\
_Sounds & Haptics_
~~~yaml
prefs:root=Sounds
~~~
_Sounds & Haptics > Haptics_
~~~yaml
prefs:root=Sounds&path=HAPTICS
~~~
_Sounds & Haptics > Keyboard Feedback_
~~~yaml
prefs:root=Sounds&path=KEYBOARD_FEEDBACK
~~~
_Sounds & Haptics > Built-In Speaker > Volume Limit_
~~~yaml
prefs:root=Sounds&path=VOLUME_LIMIT
~~~
_Sounds & Haptics > Headphone Safety_
~~~yaml
prefs:root=Sounds&path=HEADPHONE_LEVEL_LIMIT_SETTING
~~~
_Sounds & Haptics > Personalized Spatial Audio_
~~~yaml
prefs:root=Sounds&path=PERSONALIZED_SPATIAL_AUDIO
~~~
\
\
_Wallpaper_
~~~yaml
settings-navigation://com.apple.Settings.Wallpaper
~~~
_Wallpaper > Add New Wallpaper_
~~~yaml
settings-navigation://com.apple.Settings.Wallpaper/addNewWallpaper
~~~
\
\
_Privacy & Security_
~~~yaml
prefs:root=Privacy
~~~
_Privacy & Security > Blocked Contacts_
~~~yaml
prefs:root=Privacy&path=BLOCKLIST
~~~
\
\
_iCloud_
~~~yaml
settings-navigation://com.apple.Settings.iCloud
~~~
\
\
_Payment & Contactless_
~~~yaml
prefs:root=PASSBOOK
~~~
\
\
_Apps_
~~~yaml
settings-navigation://com.apple.Settings.Apps
~~~
_Apps > Default Apps_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.DefaultApps
~~~
_Apps > `bundle identifier for any app, also third party`_
~~~yaml
settings-navigation://com.apple.Settings.Apps/bundle_identifier
~~~
_Apps > Compass_
~~~yaml
prefs:root=COMPASS
~~~
_Apps > Phone_
~~~yaml
prefs:root=Phone
~~~
_Apps > Phone > Wi-Fi Calling (switch)_
~~~yaml
prefs:root=Phone#WIFI_CALLING_TELEPHONY_SETTINGS
~~~
_Apps > Phone > Call Forwarding (switch)_
~~~yaml
prefs:root=Phone#CALL_FORWARDING_TELEPHONY_SETTINGS
~~~
_Apps > Phone > Call Waiting (switch)_
~~~yaml
prefs:root=Phone#CALL_WAITING_TELEPHONY_SETTINGS
~~~
_Apps > Phone > Show My Caller ID (switch)_
~~~yaml
prefs:root=Phone#CALLING_LINE_ID_RESTRICTION_TELEPHONY_SETTINGS
~~~
_Apps > Phone > Unknown Callers (switch)_
~~~yaml
prefs:root=Phone#FILTER_AS_NEW_CALLERS
~~~
_Apps > Phone > Blocked Contacts_
~~~yaml
prefs:root=Privacy&path=BLOCKLIST
~~~
_Apps > Safari > Default Browser App (button)_
~~~yaml
prefs:root=SAFARI#com.apple.settings.DefaultBrowser
~~~
_Apps > Safari > Search Engine_
~~~yaml
prefs:root=SAFARI&path=SEARCH_ENGINE_SETTING
~~~
_Apps > Safari > Also Use in Private Browsing (switch)_
~~~yaml
prefs:root=SAFARI#PRIVATE_BROWSING_USES_NORMAL_BROWSING_SEARCH_ENGINE_SELECTION
~~~
_Apps > Safari > Search Enginge Suggestions (switch)_
~~~yaml
prefs:root=SAFARI#SEARCH_SUGGESTION_SETTING
~~~
_Apps > Safari > Safari Suggestions (switch)_
~~~yaml
prefs:root=SAFARI#SIRI_SUGGESTIONS
~~~
_Apps > Safari > Quick Website Search_
~~~yaml
prefs:root=SAFARI&path=SITE_SPECIFIC_SEARCH
~~~
_Apps > Safari > Preload Top Hit (switch)_
~~~yaml
prefs:root=SAFARI#ENABLE_PREFETCHING
~~~
_Apps > Safari > AutoFill_
~~~yaml
prefs:root=SAFARI&path=AUTO_FILL
~~~
_Apps > Safari > Start Page Favorites_
~~~yaml
prefs:root=SAFARI&path=FAVORITES_FOLDER
~~~
_Apps > Safari > Extensions_
~~~yaml
prefs:root=SAFARI&path=WEB_EXTENSIONS
~~~
_Apps > Safari > Downloads_
~~~yaml
prefs:root=SAFARI&path=DOWNLOADS
~~~
_Apps > Safari > Open Links > New Tab <sup>(switches to the new tab)</sup> or In Background <sup>(doesn't leave the current tab)</sup>_

<sub>_– iPhone_</sub>
~~~yaml
prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPHONE
~~~

<sub>_– iPad_</sub>
~~~yaml
prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPAD
~~~
_Apps > Safari > Hide IP Address (button)_
~~~yaml
prefs:root=SAFARI&path=Hide%20IP%20Address
~~~
_Apps > Safari > Require Passcode to Unlock Private Browsing (swtich)_
~~~yaml
prefs:root=SAFARI#PrivateBrowsingRequiresAuthentication
~~~
_Apps > Safari > Not Secure Connection Warning (switch)_
~~~yaml
prefs:root=SAFARI#WARN_ABOUT_INSECURE_CONNECTIONS
~~~
_Apps > Safari > Import (button)_
~~~yaml
prefs:root=SAFARI#IMPORT_BUTTON
~~~
_Apps > Safari > Export (button)_
~~~yaml
prefs:root=SAFARI#EXPORT_BUTTON
~~~
_Apps > Safari > Export (dialog)_
~~~yaml
prefs:root=SAFARI&action=showExportSheet
~~~
_Apps > Safari > Clear History and Website Data (button)_
~~~yaml
prefs:root=SAFARI#CLEAR_HISTORY_AND_DATA
~~~
_Apps > Safari > Settings for Websites (section)_
~~~yaml
prefs:root=SAFARI#SPACE_CELL_FOR_PER_SITE_SETTINGS_SYNC_TOGGLE
~~~
_Apps > Safari > Advanced_
~~~yaml
prefs:root=SAFARI&path=ADVANCED
~~~
_Apps > Safari > Advanced > Website Data_
~~~yaml
prefs:root=SAFARI&path=ADVANCED/REMOVE_WEBSITE_DATA
~~~
