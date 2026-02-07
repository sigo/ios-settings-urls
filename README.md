# Settings URL schemes for iOS 26

\
_Settings main page_
~~~yaml
settings-navigation://com.apple.Settings
~~~
\
\
_Apple Account_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount
~~~
_Apple Account > Personal Information <sub>some delay</sub>_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/APPLE_ACCOUNT_CONTACT
~~~
_Apple Account > Sign-In & Security <sub>some delay</sub>_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/PASSWORD_AND_SECURITY
~~~
_Apple Account > Sign-In & Security > Recovery Contacts <sub>some delay</sub>_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/?aaaction=accountRecovery
~~~
_Apple Account > Sign-In & Security > Legacy Contact <sub>some delay</sub>_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/?aaaction=accountBeneficiary
~~~
_Apple Account > Payment & Shipping <sub>some delay</sub>_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/PAYMENT_AND_SHIPPING
~~~
_Apple Account > Subscriptions <sub>some delay</sub>_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/SUBSCRIPTIONS
~~~
_Apple Account > iCloud <sub>see the iCloud main section for more URLs</sub>_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/ICLOUD_SERVICE
~~~
_Apple Account > Family_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount?aaaction=showFamilySettings
~~~
_Apple Account > Media & Purchases_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/STORE_SERVICE
~~~
_Apple Account > Sign in with Apple_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/SIWA_SERVICE
~~~
_Apple Account > Contact Key Verification_
~~~yaml
settings-navigation://com.apple.Settings.AppleAccount/TRANSPARENCY
~~~
\
\
_Family_
~~~yaml
settings-navigation://com.apple.Settings.Family
~~~
_Family > Subscriptions_
~~~yaml
settings-navigation://com.apple.Settings.Family?familyPath=/subscriptions
~~~
\
\
_Wi-Fi_
~~~yaml
settings-navigation://com.apple.Settings.WiFi
~~~
_Wi-Fi > [current network] &#X24D8;_
~~~yaml
settings-navigation://com.apple.Settings.WiFi/NetworkDetails
~~~
\
\
_Bluetooth_
~~~yaml
settings-navigation://com.apple.Settings.Bluetooth
~~~
_Bluetooth > AirPods &#X24D8; <sub>use the MAC address of your AirPods as identifier – can be retrieved using a computer</sub>_
~~~yaml
settings-navigation://com.apple.Settings.Bluetooth/HeadphoneDetail/?identifier=00:00:00:00:00:00
~~~
\
\
_Cellular_
~~~yaml
settings-navigation://com.apple.Settings.Cellular
~~~
_Cellular > Cellular Data (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#MOBILE_DATA_SETTINGS
~~~
_Cellular > Cellular Data Options_
~~~yaml
settings-navigation://com.apple.Settings.Cellular/CELLULAR_DATA_OPTIONS
~~~
_Cellular > Cellular Data Options > Data Mode_
~~~yaml
settings-navigation://com.apple.Settings.Cellular/CELLULAR_DATA_OPTIONS/DATA_MODE
~~~
_Cellular > Network Selection (button)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#CELLULAR_NETWORK_TELEPHONY_SETTINGS
~~~
_Cellular > My Number (button)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#PHONEBOOK_TELEPHONY_SETTINGS
~~~
_Cellular > Wi-Fi Calling (button)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#WIFI_CALLING_TELEPHONY_SETTINGS
~~~
_Cellular > Calls on Other Devices (button)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#PRIMARY_CLOUD_CALLING
~~~
_Cellular > SIM PIN (button)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#SIM_PASSCODE_TELEPHONY_SETTINGS
~~~
_Cellular > Add eSIM (button)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#ADD_CELLULAR_PLAN
~~~
_Cellular > Cellular Data > Show All > Cellular Data Usage_
~~~yaml
settings-navigation://com.apple.Settings.Cellular/SHOW_ALL
~~~
_Cellular > Wi-Fi Assist (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#Wi-Fi%20Assist
~~~
_Cellular > iCloud Drive (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#iCloud%20Drive
~~~
_Cellular > iCloud Backup (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#iCloud%20Backup
~~~
_Cellular > Enable Cellular Usage Statistics (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#Enable%20Cellular%20Usage%20Statistics
~~~
_Cellular > Reset Statistics (button)_
~~~yaml
settings-navigation://com.apple.Settings.Cellular#Reset%20Statistics
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
settings-navigation://com.apple.Settings.Battery
~~~
_Battery > Battery Health & Charging <sub>device specific</sub>_
~~~yaml
settings-navigation://com.apple.Settings.Battery/BATTERY_HEALTH_TITLE
~~~
_Battery > Charging Options <sub>device specific</sub>_
~~~yaml
settings-navigation://com.apple.Settings.Battery/CHARGING_OPTIONS_IDENTIFIER
~~~
_Battery > Battery Percentage (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Battery#BATTERY_PERCENTAGE_IDENTIFIER
~~~
_Battery > Low Power Mode (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Battery#LOW_POWER_MODE_IDENTIFIER
~~~
\
\
_VPN (switch)_
~~~yaml
settings-navigation://com.apple.Settings#com.apple.Settings.VPN
~~~
\
\
_General_
~~~yaml
settings-navigation://com.apple.Settings.General
~~~
\
\
_General > About_
~~~yaml
settings-navigation://com.apple.Settings.General/About
~~~
_General > About > iOS Version_
~~~yaml
settings-navigation://com.apple.Settings.General/About/SW_VERSION_SPECIFIER
~~~
_General > About > Certificate Trust Settings_
~~~yaml
settings-navigation://com.apple.Settings.General/About/CERT_TRUST_SETTINGS
~~~
\
\
_General > Software Update_
~~~yaml
settings-navigation://com.apple.Settings.General/SOFTWARE_UPDATE_LINK
~~~
_General > Software Update > Automatic Updates_
~~~yaml
settings-navigation://com.apple.Settings.General/SOFTWARE_UPDATE_LINK/SUAutomaticUpdateButton
~~~
_General > Software Update > Beta Updates_
~~~yaml
settings-navigation://com.apple.Settings.General/SOFTWARE_UPDATE_LINK/SUAutomaticUpdateButton
~~~
\
\
_General > iPhone Storage_
~~~yaml
settings-navigation://com.apple.Settings.General/STORAGE_MGMT
~~~
_General > iPhone Storage > [bundle identifier]_
~~~yaml
settings-navigation://com.apple.Settings.General/STORAGE_MGMT/bundle_identifier
~~~
\
\
_General > AppleCare & Warranty_
~~~yaml
settings-navigation://com.apple.Settings.General/COVERAGE
~~~
\
\
_General > Health Data_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Health
~~~
_General > Health Data > Health Details_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Health/HEALTH_DETAILS_ITEM
~~~
_General > Health Data > Medical ID_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Health/MEDICAL_ID_ITEM
~~~
_General > Health Data > Data Access & Devices_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Health/SOURCES_ITEM
~~~
\
\
_General > AirDrop_
~~~yaml
settings-navigation://com.apple.Settings.General/AIRDROP_LINK
~~~
_General > AirDrop > Start Sharing By – Bringing Devices Together (switch) <sub>buggy highlighting</sub>_
~~~yaml
settings-navigation://com.apple.Settings.General/AIRDROP_LINK#AIRDROP_NFC_ID
~~~
_General > AirDrop > Out of Range – Use Cellular Data (switch) <sub>buggy highlighting</sub>_
~~~yaml
settings-navigation://com.apple.Settings.General/AIRDROP_LINK#AIRDROP_CELLULAR_USAGE_ID
~~~
_General > AirDrop > Manage Known AirDrop Contacts_
~~~yaml
contacts-sensitive:///list/other-known
~~~
\
\
_General > AirPlay & Continuity_
~~~yaml
settings-navigation://com.apple.Settings.General/CONTINUITY_SPEC
~~~
\
\
_General > Picture in Picture_
~~~yaml
settings-navigation://com.apple.Settings.General/PiP_SPEC
~~~
\
\
_General > Screen Capture_
~~~yaml
settings-navigation://com.apple.Settings.General/SCREEN_CAPTURE
~~~
\
\
_General > Local Capture_
~~~yaml
settings-navigation://com.apple.Settings.General/LOCAL_CAPTURE
~~~
\
\
_General > Matter Accessories_
~~~yaml
settings-navigation://com.apple.Settings.General/MATTER_ACCESSORIES
~~~
\
\
_General > Home Button (button) <sub>device specific</sub>_
~~~yaml
settings-navigation://com.apple.Settings.General#HOME_BUTTON
~~~
\
\
_General > AutoFill & Passwords_
~~~yaml
settings-navigation://com.apple.Settings.General/AUTOFILL
~~~
\
\
_General > Background App Refresh_
~~~yaml
settings-navigation://com.apple.Settings.General/AUTO_CONTENT_DOWNLOAD
~~~
\
\
_General > Date & Time_
~~~yaml
settings-navigation://com.apple.Settings.General/DATE_AND_TIME
~~~
_General > Date & Time > 24-Hour Time (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/DATE_AND_TIME#24_HOUR_TIME
~~~
_General > Date & Time > Set Automatically (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/DATE_AND_TIME#SET_AUTOMATICALLY
~~~
_General > Date & Time > Time Zone (button)_
~~~yaml
settings-navigation://com.apple.Settings.General/DATE_AND_TIME#TIME_ZONE
~~~
\
\
_General > Dictionary_
~~~yaml
settings-navigation://com.apple.Settings.General/DICTIONARY
~~~
\
\
_General > Fonts_
~~~yaml
settings-navigation://com.apple.Settings.General/FONT_SETTING
~~~
_General > Fonts > System Fonts_
~~~yaml
settings-navigation://com.apple.Settings.General/FONT_SETTING/SYSTEM_FONTS
~~~
_General > Fonts > My Fonts_
~~~yaml
settings-navigation://com.apple.Settings.General/FONT_SETTING/USER_FONTS
~~~
_General > Fonts > More Fonts_
~~~yaml
settings-navigation://com.apple.Settings.General/FONT_SETTING/MORE_FONTS
~~~
\
\
_General > Keyboard_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard
~~~
_General > Keyboard > Keyboards_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard/KEYBOARDS
~~~
_General > Keyboard > Text Replacement_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard/USER_DICTIONARY
~~~
_General > Keyboard > One-Handed Keyboard_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard/ReachableKeyboard
~~~
_General > Keyboard > Character Preview (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardAllowPaddle
~~~
_General > Keyboard > Haptic Feedback (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardVisceral
~~~
_General > Keyboard > Sound (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#keyboard-audio
~~~
_General > Keyboard > Hardware Keyboard_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard/HardwareKeyboard
~~~
_General > Keyboard > Auto-Capitalization (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardAutocapitalization
~~~
_General > Keyboard > Auto-Correction (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardAutocorrection
~~~
_General > Keyboard > Predictive Text (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardPrediction
~~~
_General > Keyboard > Show Math Results (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardMathExpressionCompletion
~~~
_General > Keyboard > Check Spelling (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardCheckSpelling
~~~
_General > Keyboard > Enable Caps Lock (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardCapsLock
~~~
_General > Keyboard > Slide to Type (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardContinuousPathEnabled
~~~
_General > Keyboard > Delete Slide-to-Type by Word (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardContinuousPathDeleteWholeWord
~~~
_General > Keyboard > “.” Shortcut (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardPeriodShortcut
~~~
_General > Keyboard > Enable Dictation (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#Dictation
~~~
_General > Keyboard > Dictation – Auto-Punctuation (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#AutoPunctuationSetting
~~~
_General > Keyboard > Dictation Languages_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard/DictationSettings
~~~
_General > Keyboard > Dictation Shortcut_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard/DictationHWShortcut
~~~
_General > Keyboard > English – Show Predictions In-Line_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#KeyboardInlineCompletion
~~~
_General > Keyboard > Emoji – Stickers_
~~~yaml
settings-navigation://com.apple.Settings.General/Keyboard#ShowStickers
~~~
\
\
_General > Language & Region_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL
~~~
_General > Language & Region > Add Language_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL/ADD_PREFERRED_LANGUAGE
~~~
_General > Language & Region > Region_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL/LOCALE
~~~
_General > Language & Region > Calendar_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL/CALENDAR
~~~
_General > Language & Region > Temperature_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL/TEMPERATURE_UNIT
~~~
_General > Language & Region > Measurement System_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL/MEASUREMENT_SYSTEM
~~~
_General > Language & Region > First Day of Week_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL/FIRST_WEEKDAY
~~~
_General > Language & Region > Date Format_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL/DATE_FORMAT
~~~
_General > Language & Region > Number Format_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL/NUMBER_FORMAT
~~~
_General > Language & Region > Live Text (switch)_
~~~yaml
settings-navigation://com.apple.Settings.General/INTERNATIONAL#LIVE_TEXT_CELL
~~~
\
\
_General > Trackpad & Mouse_
~~~yaml
settings-navigation://com.apple.Settings.General/POINTERS
~~~
\
\
_General > VPN & Device Management_
~~~yaml
settings-navigation://com.apple.Settings.General/ManagedConfigurationList
~~~
_General > VPN & Device Management > VPN_
~~~yaml
settings-navigation://com.apple.Settings.General/ManagedConfigurationList/VPN
~~~
\
\
_General > Legal & Regulatory_
~~~yaml
settings-navigation://com.apple.Settings.General/LEGAL_AND_REGULATORY
~~~
\
\
_General > Transfer or Reset iPhone_
~~~yaml
settings-navigation://com.apple.Settings.General/Reset
~~~
_General > Transfer or Reset iPhone > Reset > Reset Network Settings (dialog)_
~~~yaml
settings-navigation://com.apple.Settings.General/ResetNetworkSettings
~~~
\
\
_General > Shut Down (button)_
~~~yaml
settings-navigation://com.apple.Settings.General#SHUTDOWN_LABEL
~~~
\
\
_Accessibility_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility
~~~
\
\
_Accessibility > VoiceOver_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/VOICEOVER_TITLE
~~~
\
\
_Accessibility > Zoom_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/ZOOM_TITLE
~~~
\
\
_Accessibility > Hover Text_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/HOVERTEXT_TITLE
~~~
\
\
_Accessibility > Display & Text Size_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT
~~~
_Accessibility > Display & Text Size > Bold Text (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/ENHANCE_TEXT_LEGIBILITY
~~~
_Accessibility > Display & Text Size > Larger Text_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/LARGER_TEXT
~~~
_Accessibility > Display & Text Size > Show Borders (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/BUTTON_SHAPES
~~~
_Accessibility > Display & Text Size > On/Off Labels (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/ON_OFF_LABELS
~~~
_Accessibility > Display & Text Size > Reduce Transparency (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/REDUCE_TRANSPARENCY
~~~
_Accessibility > Display & Text Size > Increase Contrast (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/TEXT_COLORS_DARKEN
~~~
_Accessibility > Display & Text Size > Differentiate Without Color (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/DIFFERENTIATE_WITHOUT_COLOR
~~~
_Accessibility > Display & Text Size > Prefer Horizontal Text (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/PREFER_HORIZONTAL_TEXT
~~~
_Accessibility > Display & Text Size > Smart Invert (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/SMART_INVERT
~~~
_Accessibility > Display & Text Size > Classic Invert (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/CLASSIC_INVERT
~~~
_Accessibility > Display & Text Size > Color Filters_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR
~~~
_Accessibility > Display & Text Size > Color Filters > Color Filters (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR#FILTER_COLOR_ENABLED
~~~
_Accessibility > Display & Text Size > Color Filters > Grayscale (option)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR#GRAYSCALE
~~~
_Accessibility > Display & Text Size > Color Filters > Red/Green Filter [Protanopia] (option)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR#RED_ADJUST
~~~
_Accessibility > Display & Text Size > Color Filters > Green/Red Filter [Deuteranopia] (option)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR#GREEN_ADJUST
~~~
_Accessibility > Display & Text Size > Color Filters > Blue/Yellow Filter [Tritanopia] (option)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR#BLUE_ADJUST
~~~
_Accessibility > Display & Text Size > Color Filters > Color Tint (option)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/DISPLAY_FILTER_COLOR#SINGLE_COLOR_ADJUST
~~~
_Accessibility > Display & Text Size > Reduce White Point (switch/slider)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/WHITE_POINT
~~~
_Accessibility > Display & Text Size > Auto-Brightness (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DISPLAY_AND_TEXT/AUTO_BRIGHTNESS
~~~
\
\
_Accessibility > Motion_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/MOTION_TITLE
~~~
_Accessibility > Motion > Reduce Motion (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/MOTION_TITLE#REDUCE_MOTION
~~~
_Accessibility > Motion > Prefer Cross-Fade Transitions (switch) <sup>If Reduce Motion is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/MOTION_TITLE/REDUCE_MOTION_REDUCE_SLIDE_ANIMATIONS
~~~
_Accessibility > Motion > Vehicle Motion Clues_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/MOTION_TITLE/MotionCues
~~~
_Accessibility > Motion > Dim Flashing Lights (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/MOTION_TITLE/PHOTOSENSITIVE_MITIGATION
~~~
_Accessibility > Motion > Auto-Play Animated Images (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/MOTION_TITLE/REDUCE_MOTION_AUTOPLAY_ANIMATED_IMAGES
~~~
_Accessibility > Motion > Auto-Play Video Previews (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/MOTION_TITLE/REDUCE_MOTION_AUTOPLAY_VIDEO_PREVIEWS
~~~
_Accessibility > Motion > Auto-Play Message Effects (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/MOTION_TITLE/ReduceMotionAutoplayMessagesEffects
~~~
_Accessibility > Motion > Prefer Non-Blinking Cursor (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/MOTION_TITLE/PREFER_NONBLINKING_CURSOR
~~~
\
\
_Accessibility > Read & Speak_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SPEECH_TITLE
~~~
_Accessibility > Read & Speak > Accessibility Reader_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SPEECH_TITLE/AccessibilityReader
~~~
_Accessibility > Read & Speak > Speak Screen_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SPEECH_TITLE/SpeakScreen
~~~
_Accessibility > Read & Speak > Speak Selection_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SPEECH_TITLE/SpeakSelection
~~~
\
\
_Accessibility > Audio Descriptions_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/DESCRIPTIVE_VIDEO
~~~
\
\
_Accessibility > Touch_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE
~~~
_Accessibility > Touch > AssistiveTouch_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE
~~~
_Accessibility > Touch > AssistiveTouch > Assistive Touch (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/EnableAssistiveTouchSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Customize Top Level Menu_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AssistiveTouchCustomize
~~~
_Accessibility > Touch > AssistiveTouch > Single-Tap_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/TapSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Double-Tap_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/DoubleTapSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Double-Tap > Double-Tap Timeout_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/DoubleTapSpecifier/ASTDoubleTapTimeoutSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Long Press_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/LongPressSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Long Press > Long Press Duration_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/LongPressSpecifier/ASTLongPressDurationSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Create New Gesture_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/CreateCustomGesture
~~~
_Accessibility > Touch > AssistiveTouch > Dwell Control (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/DwellEnabledSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Idle Opacity_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/IdleOpacity
~~~
_Accessibility > Touch > AssistiveTouch > Devices_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AssistiveTouchMouseDevices
~~~
_Accessibility > Touch > AssistiveTouch > Sound on Click (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/MouseClickSounds
~~~
_Accessibility > Touch > AssistiveTouch > Always Show Menu (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AlwaysShowMenu
~~~
_Accessibility > Touch > AssistiveTouch > Perform Touch Gestures (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/MouseBehavesLikeFinger
~~~
_Accessibility > Touch > AssistiveTouch > Use Game Controller (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/EnableAssistiveTouchGameControllerSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Sound Actions_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/SOUND_ACTIONS
~~~
_Accessibility > Touch > Reachability (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/REACHABILITY
~~~
_Accessibility > Touch > Haptic Touch_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/ForceTouch
~~~
_Accessibility > Touch > Haptic Touch > Fast (option)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/ForceTouch#HapticTouchFastIdentifier
~~~
_Accessibility > Touch > Touch Accomodations_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/TOUCH_ACCOMMODATIONS
~~~
_Accessibility > Touch > Touch Accomodations > Touch Accomodations (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/TOUCH_ACCOMMODATIONS/TOUCH_ACCOMMODATIONS_SWITCHER
~~~
_Accessibility > Touch > Touch Accomodations > Hold Duration (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/TOUCH_ACCOMMODATIONS/HoldDuration
~~~
_Accessibility > Touch > Touch Accomodations > Ignore Repeat (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/TOUCH_ACCOMMODATIONS/IgnoreRepeat
~~~
_Accessibility > Touch > Shake to Undo (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/SHAKE_TO_UNDO
~~~
_Accessibility > Touch > Vibration (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/VIBRATION
~~~
_Accessibility > Touch > Prevent Lock to End Call (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/LockButtonIgnore
~~~
_Accessibility > Touch > Call Audio Routing_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING
~~~
_Accessibility > Touch > Call Audio Routing > Auto-Answer Calls_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
_Accessibility > Touch > Back Tap_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/BackTap
~~~
_Accessibility > Touch > Back Tap > Double Tap_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/BackTap/DoubleTap
~~~
_Accessibility > Touch > Back Tap > Triple Tap_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE/BackTap/TripleTap
~~~
_Accessibility > Touch  > Prefer Single-Touch Actions (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TOUCH_REACHABILITY_TITLE#Prefer%20Single-Touch%20Actions
~~~
\
\
_Accessibility > Switch Control_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/ScannerSwitchTitle
~~~
\
\
_Accessibility > Voice Control_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/CommandAndControlTitle
~~~
\
\
_Accessibility > Eye Tracking_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/OnDeviceEyeTracking
~~~
\
\
_Accessibility > Head Tracking_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AST_HEAD_TRACKING
~~~
\
\
_Accessibility > Home Button <sub>device specific</sub>_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/HOME_CLICK_TITLE
~~~
\
\
_Accessibility > Face ID & Attention_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/FACE_ID
~~~
_Accessibility > Face ID & Attention > Attention Aware Features (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/FACE_ID/AttentionAware
~~~
\
\
_Accessibility > Control Nearby Devices_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/CONTROL_NEARBY_DEVICES
~~~
_Accessibility > Control Nearby Devices > Control Nearby Devices (button)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/CONTROL_NEARBY_DEVICES/CONTROL_NEARBY_DEVICES
~~~
\
\
_Accessibility > Hearing Devices_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/HEARING_AID_TITLE
~~~
\
\
_Accessibility > Hearing Control Center_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/HEARING_CONTROL_CENTER
~~~
\
\
_Accessibility > Sound & Name Recognition_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SOUND_AND_NAME_RECOGNITION_TITLE
~~~
\
\
_Accessibility > RTT/TTY_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/RTT
~~~
\
\
_Accessibility > Audio & Visual_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE
~~~
_Accessibility > Audio & Visual > Headphone Accommodations_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/AXPAEnableSpecID
~~~
_Accessibility > Audio & Visual > Headphone Accommodations > Custom Audio Setup_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/AXPAEnableSpecID#AXPAPersonalAudioSetupSpecID
~~~
_Accessibility > Audio & Visual > Background Sounds_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/AXCSEnableSpecID
~~~
_Accessibility > Audio & Visual > Background Sounds > Background Sounds (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/AXCSEnableSpecID#CSFeatureToggleSpecID
~~~
_Accessibility > Audio & Visual > Live Listen_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/AXLLEnableSpecID
~~~
_Accessibility > Audio & Visual > Mono Audio (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/AXPAMonoSpecID
~~~
_Accessibility > Audio & Visual > Always Show Volume Controls (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/AXPAAlwaysShowVolumeControlSpecID
~~~
_Accessibility > Audio & Visual > Add Voice Isolation (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE#ExtendedVoiceIsolationSpecID
~~~
_Accessibility > Audio & Visual > Headphone Notifications (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/AXHeadphoneNotificationsSpecID
~~~
_Accessibility > Audio & Visual > Balance (slider)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/LeftRightBalance
~~~
_Accessibility > Audio & Visual > Add Audio in Calls_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/MIX_TO_UPLINK
~~~
_Accessibility > Audio & Visual > Call Audio Routing_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING
~~~
_Accessibility > Audio & Visual > Call Audio Routing > Auto-Answer Calls_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/LED_FLASH
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts > Flash for Alerts (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/LED_FLASH#FLASH_FOR_ALERTS
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts > LED Flash (option)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/LED_FLASH#VISUAL_ALERT_TYPE_LED
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts > Screen (option)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/LED_FLASH#VISUAL_ALERT_TYPE_SCREEN
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts > Both (option)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/LED_FLASH#VISUAL_ALERT_TYPE_BOTH
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts > Flash While Unlocked (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/LED_FLASH#LED_FLASH_WHILE_UNLOCKED
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts > Flash in Silent Mode (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AUDIO_VISUAL_TITLE/LED_FLASH#LED_RINGER_SWITCH_CONTROL
~~~
\
\
_Accessibility > Subtitles & Captioning_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SUBTITLES_CAPTIONING
~~~
_Accessibility > Subtitles & Captioning > Closed Captions + SDH (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SUBTITLES_CAPTIONING#PREFER_SDH
~~~
_Accessibility > Subtitles & Captioning > Style_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SUBTITLES_CAPTIONING/currentTheme
~~~
_Accessibility > Subtitles & Captioning > Style > Create New Style_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SUBTITLES_CAPTIONING/currentTheme/CreateNewStyle
~~~
_Accessibility > Subtitles & Captioning > Show Audio Transcriptions (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SUBTITLES_CAPTIONING/SHOW_AUDIO_TRANSCRIPTIONS
~~~
_Accessibility > Subtitles & Captioning > Show when Muted (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SUBTITLES_CAPTIONING/SHOW_WHEN_MUTED
~~~
_Accessibility > Subtitles & Captioning > Show on Skip Back (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/SUBTITLES_CAPTIONING/SHOW_ON_SKIP_BACK
~~~
\
\
_Accessibility > Live Captions_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/LIVE_TRANSCRIPTION
~~~
\
\
_Accessibility > Live Speech_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/LIVE_SPEECH_TITLE
~~~
_Accessibility > Live Speech > Phrases_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/LIVE_SPEECH_TITLE/PHRASES
~~~
_Accessibility > Live Speech > Phrases > + (button)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/LIVE_SPEECH_TITLE/PHRASES#CREATE_CUSTOM_CATEGORY
~~~
\
\
_Accessibility > Personal Voice_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/PERSONAL_VOICE_TITLE
~~~
\
\
_Accessibility > Vocal Shortcuts_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/ADAPTIVE_VOICE_SHORTCUTS_TITLE
~~~
\
\
_Accessibility > Keyboards & Typing_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/KEYBOARDS
~~~
\
\
_Accessibility > AirPods_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AIRPODS
~~~
_Accessibility > AirPods > Spatial Audio Head Tracking – Follow iPhone (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/AIRPODS#SPATIAL_AUDIO_SWITCH
~~~
\
\
_Accessibility > Guided Access_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/GUIDED_ACCESS_TITLE
~~~
_Accessibility > Guided Access > Passcode Settings_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/GUIDED_ACCESS_TITLE/GuidedAccessSecurityLinkList
~~~
_Accessibility > Guided Access > Passcode Settings > Set Guided Access Passcode (button)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/GUIDED_ACCESS_TITLE/GuidedAccessSecurityLinkList#GAXPinButton
~~~
_Accessibility > Guided Access > Time Limits_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/GUIDED_ACCESS_TITLE/GuidedAccessTimeRestrictionsLinkList
~~~
_Accessibility > Guided Access > Time Limits > Alarm – Sound_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/GUIDED_ACCESS_TITLE/GuidedAccessTimeRestrictionsLinkList/GUIDED_ACCESS_TIME_RESTRICTIONS_SOUND_TITLE#GUIDED_ACCESS_TIME_RESTRICTIONS_SOUND_TITLE
~~~
_Accessibility > Guided Access > Time Limits > Alarm – Speak (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/GUIDED_ACCESS_TITLE/GuidedAccessTimeRestrictionsLinkList#GUIDED_ACCESS_TIME_RESTRICTIONS_SPEAK_TITLE
~~~
_Accessibility > Guided Access > Accessibility Shortcut (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/GUIDED_ACCESS_TITLE#GuidedAccessEnableAXFeatures
~~~
_Accessibility > Guided Access > Display Auto-Lock_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/GUIDED_ACCESS_TITLE/GuidedAccessAutoLockTime#GuidedAccessAutoLockTime
~~~
\
\
_Accessibility > Assistive Access_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/CLARITY_UI_TITLE
~~~
\
\
_Accessibility > Accessibility Shortcut_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/TRIPLE_CLICK_TITLE
~~~
\
\
_Accessibility > Per-App Settings_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE
~~~
_Accessibility > Per-App Settings > Show Hidden Apps_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/PROTECTED_APPS_SHOW_HIDDEN_TITLE
~~~
_Accessibility > Per-App Settings > Add App (dialog)_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/AX_ADD_BUTTON_IDENTIFIER
~~~
_Accessibility > Per-App Settings > [bundle identifier] <sub>as long as you have added the app there, otherwise goes to the parent page</sub>_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Bold Text_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/ENHANCE_TEXT_LEGIBILITY
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Larger Text_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/LARGER_TEXT
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Show Borders_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/BUTTON_SHAPES
~~~
_Accessibility > Per-App Settings > [bundle identifier] > On/Off Labels_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/ON_OFF_LABELS
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Reduce Transparency_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/REDUCE_TRANSPARENCY
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Increase Contrast_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/TEXT_COLORS_DARKEN
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Differentiate Without Color_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/DIFFERENTIATE_WITHOUT_COLOR
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Prefer Horizontal Text_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/PREFER_HORIZONTAL_TEXT
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Smart Invert_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/SMART_INVERT
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Reduce Motion_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/REDUCE_MOTION
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Prefer Croos-Fade Transitions_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/REDUCE_MOTION_REDUCE_SLIDE_ANIMATIONS
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Auto-Play Video Previews_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/REDUCE_MOTION_AUTOPLAY_VIDEO_PREVIEWS
~~~
_Accessibility > Per-App Settings > [bundle identifier] > Prefer Non-Blinking Cursor_
~~~yaml
settings-navigation://com.apple.Settings.Accessibility/APP_AX_SETTINGS_TITLE/bundle_identifier/PREFER_NONBLINKING_CURSOR
~~~
\
\
_Action Button <sub>device specific</sub>_
~~~yaml
settings-navigation://com.apple.Settings.ActionButton
~~~
\
\
_Camera_
~~~yaml
settings-navigation://com.apple.Settings.Camera
~~~
_Camera > Record Video_
~~~yaml
settings-navigation://com.apple.Settings.Camera/CameraVideoSettingsList
~~~
_Camera > Record Slo-mo_
~~~yaml
settings-navigation://com.apple.Settings.Camera/CameraSlomoSettingsList
~~~
_Camera > Formats_
~~~yaml
settings-navigation://com.apple.Settings.Camera/CameraFormatsSettingsList
~~~
_Camera > Preserve Settings_
~~~yaml
settings-navigation://com.apple.Settings.Camera/CameraPreserveSettingsSwitch
~~~
_Camera > Use Volume Up for Burst (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#VOLUME_UP_BURST
~~~
_Camera > Scan QR Codes (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#CameraQRBannerSwitch
~~~~
_Camera > Show Detected Text (swtich)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#TEXT_ANALYSIS
~~~
_Camera > Composition – Grid (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#CameraGridSwitch
~~~
_Camera > Composition – Level (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#CameraGridSwitch
~~~
_Camera > Mirror Front Camera (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#MIRROR
~~~
_Camera > Indicators_
~~~yaml
settings-navigation://com.apple.Settings.Camera/CameraIndicatorsSettingsList
~~~
_Camera > Photographic Styles (button)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#PHOTOGRAPHIC_STYLES
~~~
_Camera > Prioritize Faster Shooting (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#CAM_CAPTURE_DYNAMIC_SHUTTER_SWITCH
~~~
_Camera > Lock Screen Swipe to Open Camera (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#LOCK_SCREEN_SWIPE_SWITCH
~~~
_Camera > Messages – Save Captures to Photo Library (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Camera#CAM_SAVE_MESSAGES_ASSETS_PHOTO_LIBRARY_SWITCH
~~~
\
\
_Control Center_
~~~yaml
settings-navigation://com.apple.Settings.ControlCenter
~~~
_Control Center > Access Within Apps (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ControlCenter#ACCESS_WITHIN_APP
~~~
_Control Center > Reset Control Center_
~~~yaml
settings-navigation://com.apple.Settings.ControlCenter#RESET_CONTROL_CENTER
~~~
\
\
_Display & Brightness_
~~~yaml
settings-navigation://com.apple.Settings.Display
~~~
_Display & Brightness > Appearance (section)_
~~~yaml
settings-navigation://com.apple.Settings.Display#DEVICE_APPEARANCE
~~~
_Display & Brightness > Appearance > Automatic (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Display#AUTOMATIC
~~~
_Dispaly & Brightness > Liquid Glass_
~~~yaml
settings-navigation://com.apple.Settings.Display/LIQUID_GLASS
~~~
_Display & Brightness > Text Size_
~~~yaml
settings-navigation://com.apple.Settings.Display/TEXT_SIZE
~~~
_Display & Brightness > Bold Text (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Display#BOLD_TEXT
~~~
_Display & Brightness > Brightness (slider)_
~~~yaml
settings-navigation://com.apple.Settings.Display#BRIGHTNESS
~~~
_Display & Brightness > True Tone (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Display#WHITE_BALANCE
~~~
_Display & Brightness > Night Shift_
~~~yaml
settings-navigation://com.apple.Settings.Display/BLUE_LIGHT_REDUCTION
~~~
_Display & Brightness > Auto-Lock_
~~~yaml
settings-navigation://com.apple.Settings.Display/AUTOLOCK
~~~
_Display & Brightness > Raise to Wake (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Display#RAISE_TO_WAKE
~~~
_Display & Brightness > Display Zoom_
~~~yaml
settings-navigation://com.apple.Settings.Display/MAGNIFY
~~~
\
\
_Home Screen & App Library_
~~~yaml
settings-navigation://com.apple.Settings.HomeScreenAndAppLibrary
~~~
_Home Screen & App Library > Notifications Badges – Show in App Library (switch)_
~~~yaml
settings-navigation://com.apple.Settings.HomeScreenAndAppLibrary#BADGES_IN_APP_LIBRARY
~~~
_Home Screen & App Library > Search – Show on Home Screen (switch)_
~~~yaml
settings-navigation://com.apple.Settings.HomeScreenAndAppLibrary#SHOW_SEARCH_ON_HOME_SCREEN
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
settings-navigation://com.apple.Settings.Siri
~~~
\
\
_StandBy_
~~~yaml
settings-navigation://com.apple.Settings.StandBy
~~~
_StandBy > Display <sub>device specific</sub>_
~~~yaml
settings-navigation://com.apple.Settings.StandBy/ALWAYS_ON_DISPLAY_OPTIONS
~~~
_StandBy > StandBy (switch)_
~~~yaml
settings-navigation://com.apple.Settings.StandBy#AMBIENT_MODE_ENABLED
~~~
_StandBy > Night Mode (switch)_
~~~yaml
settings-navigation://com.apple.Settings.StandBy#BUMP_TO_WAKE_ENABLED
~~~
_StandBy > Show Notifications (switch)_
~~~yaml
settings-navigation://com.apple.Settings.StandBy#NOTIFICATIONS_ENABLED
~~~
_StandBy > Show Preview on Tap Only (switch)_
~~~yaml
settings-navigation://com.apple.Settings.StandBy#NOTIFICATIONS_PREVIEW
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
_Notifications_
~~~yaml
settings-navigation://com.apple.Settings.Notifications
~~~
_Notifications > Scheduled Summary_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/SCHEDULED_DELIVERY_ID
~~~
_Notifications > Show Previews_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/SHOW_PREVIEW_GROUP_ID
~~~
_Notifications > Screen Sharing_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/SCREENSHARING_ID
~~~
_Notifications > Announce Notifications (button)_
~~~yaml
settings-navigation://com.apple.Settings.Notifications#SPOKEN_NOTIFICATIONS_ID
~~~
_Notifications > Siri Suggestions_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/SIRI_SUGGESTIONS_ID
~~~
_Notifications > [bundle identifier]_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/bundle_identifier
~~~
_Notifications > [bundle identifier] > Banner Style_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/bundle_identifier/BANNER_STYLE_ID
~~~
_Notifications > [bundle identifier] > Show Previews_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/bundle_identifier/SHOW_PREVIEW_GROUP_ID
~~~
_Notifications > [bundle identifier] > Notification Grouping_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/bundle_identifier/NOTIFICATION_GROUPING_APP_ID
~~~
_Notifications > [bundle identifier] > Customize Notifications_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/bundle_identifier/custom
~~~
\
\
_Sounds & Haptics_
~~~yaml
settings-navigation://com.apple.Settings.Sounds
~~~
_Sounds & Haptics > Microphone (button)_
~~~yaml
settings-navigation://com.apple.Settings.Sounds#MICROPHONE
~~~
_Sounds & Haptics > Change with Buttons (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Sounds#CHANGE_WITH_BUTTONS
~~~
_Sounds & Haptics > Haptics (button)_
~~~yaml
settings-navigation://com.apple.Settings.Sounds#HAPTICS
~~~
_Sounds & Haptics > Ringtone_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/Ringtone
~~~
_Sounds & Haptics > Text Tone_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/Text_Messages
~~~
_Sounds & Haptics > New Voicemail_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/Voicemail
~~~
_Sounds & Haptics > New Mail (button)_
~~~yaml
settings-navigation://com.apple.Settings.Sounds#NEW_MAIL
~~~
_Sounds & Haptics > Sent Mail_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/SENT_MAIL
~~~
_Sounds & Haptics > Celendar Alerts_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/Calendar%20Alarm
~~~
_Sounds & Haptics > Reminder Alerts_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/Reminder%20Alerts
~~~
_Sounds & Haptics > Default Alerts_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/DEFAULT_ALERTS
~~~
_Sounds & Haptics > Keyboard Feedback_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/KEYBOARD_FEEDBACK
~~~
_Sounds & Haptics > Lock Sound_
~~~yaml
settings-navigation://com.apple.Settings.Sounds#LOCK_SOUND_SWITCH
~~~
_Sounds & Haptics > Built-In Speaker > Volume Limit_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/VOLUME_LIMIT
~~~
_Sounds & Haptics > Reduce Loud Sounds_
~~~yaml
settings-navigation://com.apple.Settings.Sounds#LATE_NIGHT_MODE_SWITCH
~~~
_Sounds & Haptics > Headphone Safety_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/HEADPHONE_LEVEL_LIMIT_SETTING
~~~
_Sounds & Haptics > Personalized Spatial Audio_
~~~yaml
settings-navigation://com.apple.Settings.Sounds/PERSONALIZED_SPATIAL_AUDIO
~~~
\
\
_Focus_
~~~yaml
settings-navigation://com.apple.Settings.Focus
~~~
_Focus > Share Across Devices (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Focus#Share%20Across%20Devices
~~~
_Focus > Focus Status_
~~~yaml
settings-navigation://com.apple.Settings.Focus/Focus%20Status
~~~
\
\
_Screen Time_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime
~~~
_Screen Time > See All App & Website Activity <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/SCREEN_TIME_SUMMARY
~~~
_Screen Time > See All App & Website Activity – Week (tab) <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/SCREEN_TIME_SUMMARY/WEEK
~~~
_Screen Time > See All App & Website Activity – Day (tab) <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/SCREEN_TIME_SUMMARY/DAY
~~~
_Screen Time > See All App & Website Activity – Most Used (section) <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/SCREEN_TIME_SUMMARY/Most%20Used
~~~
_Screen Time > See All App & Website Activity – Pickups (section) <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/SCREEN_TIME_SUMMARY/Pickups
~~~
_Screen Time > See All App & Website Activity – Notifications (section) <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/SCREEN_TIME_SUMMARY/Notifications
~~~
_Screen Time > See All App & Website Activity – Notifications > [bundle identifier] <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/SCREEN_TIME_SUMMARY/bundle_identifier
~~~
_Screen Time > Downtime <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/DOWNTIME
~~~
_Screen Time > App Limits <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/APP_LIMITS
~~~
_Screen Time > Always Allowed <sup>If App & Website Activity is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/ALWAYS_ALLOWED
~~~
_Screen Time > Screen Distance_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/EYE_DISTANCE
~~~
_Screen Time > Screen Distance > Screen Distance (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/EYE_DISTANCE/Screen%20Distance
~~~
_Screen Time > Communication Limits_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/COMMUNICATION_LIMITS
~~~
_Screen Time > Communication Limits > During Screen Time_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/COMMUNICATION_LIMITS/During%20Screen%20Time
~~~
_Screen Time > Communication Limits > During Downtime_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/COMMUNICATION_LIMITS/During%20Downtime
~~~
_Screen Time > Communication Safety_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/COMMUNICATION_SAFETY
~~~
_Screen Time > Communication Safety > Communication Safety (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/COMMUNICATION_SAFETY/Communication%20Safety
~~~
_Screen Time > Communication Safety > View Child Safety Resources_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/COMMUNICATION_SAFETY/View%20Child%20Safety%20Resources
~~~
_Screen Time > Communication Safety > Improve Communication Safety (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/COMMUNICATION_SAFETY/Improve%20Communication%20Safety
~~~
_Screen Time > Content & Privacy Restrictions_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY
~~~
_Screen Time > Content & Privacy Restrictions > View Profiles_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/View%20Profiles
~~~
_Screen Time > Content & Privacy Restrictions > Content & Privacy Restrictions (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Content%20%26%20Privacy%20Restrictions
~~~
_Screen Time > Content & Privacy Restrictions > iTunes & App Store Purchases_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/PURCHASES
~~~
_Screen Time > Content & Privacy Restrictions > iTunes & App Store Purchases > Installing Apps_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/PURCHASES/Installing%20Apps
~~~
_Screen Time > Content & Privacy Restrictions > iTunes & App Store Purchases > Deleting Apps_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/PURCHASES/Deleting%20Apps
~~~
_Screen Time > Content & Privacy Restrictions > iTunes & App Store Purchases > In-app Purchases_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/PURCHASES/In-app%20Purchases
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > Mail (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/Mail
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > Safari (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/Safari
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > FaceTime (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/FaceTime
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > SharePlay (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/SharePlay
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > Camera (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/Camera
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > Wallet (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/Wallet
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > AirDrop (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/AirDrop
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > CarPlay (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/CarPlay
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > Book Store (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/Book%20Store
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > Podcasts (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/Podcasts
~~~
_Screen Time > Content & Privacy Restrictions > Allowed Apps & Features > News (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ALLOWED_APPS/News
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Music, Podcasts, News, Fitness_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Music,%20Podcasts,%20News,%20Fitness
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Music Videos_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Music%20Videos
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Music Profiles_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Music%20Profiles
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Movies_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Movies
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Movies > Show Movies in the Cloud (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Movies/Show%20Movies%20in%20the%20Cloud
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > TV Shows_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/TV%20Shows
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > TV Shows > Show TV Shows in the Cloud (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/TV%20Shows/Show%20TV%20Shows%20in%20the%20Cloud
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Books_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Books
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > App Clips_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/App%20Clips
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Multiplayer Games_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Multiplayer%20Games
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Adding Friends_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Adding%20Friends
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Connect with Friends_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Connect%20with%20Friends
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Screen Recording_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Screen%20Recording
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Nearby Multiplayer_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Nearby%20Multiplayer
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Privacy Changes_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Profile%20Privacy%20Changes
~~~
_Screen Time > Content & Privacy Restrictions > App Store, Media, Web, & Games > Avatar & Nickname Changes_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/CONTENT_RESTRICTIONS/Avatar%20%26%20Nickname%20Changes
~~~
_Screen Time > Content & Privacy Restrictions > Intelligence & Siri_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/SIRI_AND_INTELLIGENCE_RESTRICTIONS
~~~
_Screen Time > Content & Privacy Restrictions > Intelligence & Siri > Apple Intelligence – Image Creation_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/SIRI_AND_INTELLIGENCE_RESTRICTIONS/Image%20Creation
~~~
_Screen Time > Content & Privacy Restrictions > Intelligence & Siri > Apple Intelligence – Writing Tools_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/SIRI_AND_INTELLIGENCE_RESTRICTIONS/Writing%20Tools
~~~
_Screen Time > Content & Privacy Restrictions > Intelligence & Siri > Intelligence Extensions_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/SIRI_AND_INTELLIGENCE_RESTRICTIONS/Intelligence%20Extensions
~~~
_Screen Time > Content & Privacy Restrictions > Intelligence & Siri > Siri & Dictation (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/SIRI_AND_INTELLIGENCE_RESTRICTIONS/Siri%20%26%20Dictation
~~~
_Screen Time > Content & Privacy Restrictions > Intelligence & Siri > Siri – Web Search Content_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/SIRI_AND_INTELLIGENCE_RESTRICTIONS/Web%20Search%20Content
~~~
_Screen Time > Content & Privacy Restrictions > Intelligence & Siri > Siri – Explicit Language_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/SIRI_AND_INTELLIGENCE_RESTRICTIONS/Explicit%20Language
~~~
_Screen Time > Content & Privacy Restrictions > Intelligence & Siri > Math Results_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/SIRI_AND_INTELLIGENCE_RESTRICTIONS/Math%20Results
~~~
_Screen Time > Content & Privacy Restrictions > Location Services_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Location%20Services
~~~
_Screen Time > Content & Privacy Restrictions > Location Services > Location Services (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Location%20Services/Location%20Services
~~~
_Screen Time > Content & Privacy Restrictions > Location Services > Location Alerts (button)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Location%20Services/LOCATION_SERVICES_MASTER
~~~
_Screen Time > Content & Privacy Restrictions > Location Services > Share My Location (button)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Location%20Services/LOCATION_SHARING
~~~
_Screen Time > Content & Privacy Restrictions > Location Services > App Clips (button)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Location%20Services/APP_CLIPS
~~~
_Screen Time > Content & Privacy Restrictions > Location Services > [bundle identifier] (button)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Location%20Services/bundle_identifier
~~~
_Screen Time > Content & Privacy Restrictions > Location Services > System Services (button)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Location%20Services/SYSTEM_SERVICES
~~~
_Screen Time > Content & Privacy Restrictions > Share My Location_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Share%20My%20Location
~~~
_Screen Time > Content & Privacy Restrictions > Privacy (section)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Privacy
~~~
_Screen Time > Content & Privacy Restrictions > Allow Changes to Passcode & Face ID_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Passcode%20%26%20Face%20ID
~~~
_Screen Time > Content & Privacy Restrictions > Allow Changes to Accounts_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Accounts
~~~
_Screen Time > Content & Privacy Restrictions > Allow Changes to Cellular Data_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Cellular%20Data
~~~
_Screen Time > Content & Privacy Restrictions > Allow Changes to Reduce Loud Audio_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Reduce%20Loud%20Audio
~~~
_Screen Time > Content & Privacy Restrictions > Allow Changes to Speaker Volume Limit_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Speaker%20Volume%20Limit
~~~
_Screen Time > Content & Privacy Restrictions > Allow Changes to Driving Focus_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Driving%20Focus
~~~
_Screen Time > Content & Privacy Restrictions > Allow Changes to TV Provider_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/TV%20Provider
~~~
_Screen Time > Content & Privacy Restrictions > Allow Changes to Background App Activity_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/Background%20App%20Activity
~~~
_Screen Time > Lock Screen Time Settings (button)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime#Lock%20Screen%20Time%20Settings
~~~
_Screen Time > Share Across Devices (switch)_
~~~yaml
settings-navigation://com.apple.Settings.ScreenTime#Share%20Across%20Devices
~~~
\
\
_Touch ID & Passcode_
~~~yaml
settings-navigation://com.apple.Settings.Passcode
~~~
_Touch ID & Passcode > Change Passcode (button)_
~~~yaml
settings-navigation://com.apple.Settings.Passcode#CHANGE_PASSCODE
~~~
_Touch ID & Passcode > Require Passcode_
~~~yaml
settings-navigation://com.apple.Settings.Passcode/PASSCODE_REQ
~~~
_Touch ID & Passcode > Erase Data (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Passcode#WIPE_DEVICE
~~~
\
\
_Emergency SOS_
~~~yaml
settings-navigation://com.apple.Settings.SOS
~~~
_Emergency SOS > Call with Hold and Release (switch)_
~~~yaml
settings-navigation://com.apple.Settings.SOS#CALL_WITH_HOLD
~~~
_Emergency SOS > Call with 5 Button Presses (switch)_
~~~yaml
settings-navigation://com.apple.Settings.SOS#CALL_WITH_PRESSES
~~~
_Emergency SOS > Set up Emergency Contacts in Health (button)_
~~~yaml
settings-navigation://com.apple.Settings.SOS#OPEN_HEALTH
~~~
\
\
_Privacy & Security_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity
~~~
_Privacy & Security > Location Services_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCATION
~~~
_Privacy & Security > Location Services > Location Alerts_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCATION/LOCATION_SERVICES_MASTER
~~~
_Privacy & Security > Location Services > Share My Location_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCATION/LOCATION_SHARING
~~~
_Privacy & Security > Location Services > App Clips_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCATION/APP_CLIPS
~~~
_Privacy & Security > Location Services > [bundle identifier]_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCATION/bundle_identifier
~~~
_Privacy & Security > Location Services > System Services_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCATION/SYSTEM_SERVICES
~~~
_Privacy & Security > Tracking_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/USER_TRACKING
~~~
_Privacy & Security > Calendars_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/CALENDARS
~~~
_Privacy & Security > Contacts_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/CONTACTS
~~~
_Privacy & Security > Files & Folders_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/FILEACCEESS
~~~
_Privacy & Security > Health Data_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/HEALTH_DATA
~~~
_Privacy & Security > Home Accessories_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/WILLOW
~~~
_Privacy & Security > Media & Apple Music_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/MEDIALIBRARY
~~~
_Privacy & Security > Passkeys Access for Web Browsers_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/PASSKEYS
~~~
_Privacy & Security > Photos_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/PHOTOS
~~~
_Privacy & Security > Reminders_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/REMINDERS
~~~
_Privacy & Security > Wallet_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/WALLET
~~~
_Privacy & Security > Accessories_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/ACCESSORY_SETUP
~~~
_Privacy & Security > Bluetooth_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/BT_PERIPHERAL
~~~
_Privacy & Security > Camera_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/CAMERA
~~~
_Privacy & Security > Contactless & NFC_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/CONTACTLESS_NFC
~~~
_Privacy & Security > Critical Messages_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/CRITICAL_MESSAGES
~~~
_Privacy & Security > Local Network_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCAL_NETWORK
~~~
_Privacy & Security > Microphone_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/MICROPHONE
~~~
_Privacy & Security > Motion & Fitness_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/MOTION
~~~
_Privacy & Security > Nearby Interactions_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/NEARBY_INTERACTIONS
~~~
_Privacy & Security > Paired Devices_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/PAIRED_DEVICES
~~~
_Privacy & Security > Research Sensor & Usage Data_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/ALMANAC
~~~
_Privacy & Security > Speech Recognition_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/SPEECH_RECOGNITION
~~~
_Privacy & Security > Journaling Suggestions_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/JOURNALING_SUGGESTIONS
~~~
_Privacy & Security > Blocked Contacts_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/BLOCKLIST
~~~
_Privacy & Security > Safety Check_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/SAFETY_CHECK
~~~
_Privacy & Security > Sensitive Content Warning_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/NUDITY_DETECTION
~~~
_Privacy & Security > Analytics & Improvements_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/PROBLEM_REPORTING
~~~
_Privacy & Security > Apple Advertising_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/ADVERTISING
~~~
_Privacy & Security > App Privacy Report_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/PRIVACY_REPORT
~~~
_Privacy & Security > Background Security Improvements_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/BACKGROUND_SECURITY_IMPROVEMENTS
~~~
_Privacy & Security > Stolen Device Protection_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/STOLEN_DEVICE_PROTECTION
~~~
_Privacy & Security > Lockdown Mode_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCKDOWN_MODE
~~~
\
\
_Game Center_
~~~yaml
settings-navigation://com.apple.Settings.GameCenter
~~~
_Game Center > Customize Profile_
~~~yaml
settings-navigation://com.apple.Settings.GameCenter/EDIT_PROFILE
~~~
_Game Center > All Friends_
~~~yaml
settings-navigation://com.apple.Settings.GameCenter/ALL_FRIENDS
~~~
_Game Center > Friends Requests_
~~~yaml
settings-navigation://com.apple.Settings.GameCenter/FRIEND_REQUESTS
~~~
_Game Center > Invite Friends_
~~~yaml
settings-navigation://com.apple.Settings.GameCenter/INVITE_FRIENDS
~~~
\
\
_iCloud_
~~~yaml
settings-navigation://com.apple.Settings.iCloud
~~~
_iCloud > Storage_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/STORAGE_AND_BACKUP
~~~
_iCloud > Storage > Change Storage Plan_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/STORAGE_AND_BACKUP/CHANGE_STORAGE_PLAN
~~~
_iCloud > Saved to iCloud_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass
~~~
_iCloud > Saved to iCloud > iCloud Photos_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.CloudPhotos
~~~
_iCloud > Saved to iCloud > iCloud Drive_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Ubiquity
~~~
_iCloud > Saved to iCloud > iCloud Mail_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail
~~~
_iCloud > Saved to iCloud > iCloud Mail > Addresses_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail/ALIASES
~~~
_iCloud > Saved to iCloud > iCloud Mail > iCloud Mail Cleanup_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail/ICLOUD_MAIL_CLEANUP
~~~
_iCloud > Saved to iCloud > iCloud Mail > iCloud Mail Rules_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail/SERVER_SIDE_RULES
~~~
_iCloud > Saved to iCloud > iCloud Mail > Auto-Reply_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail/AUTO_REPLY
~~~
_iCloud > Saved to iCloud > iCloud Mail > Mail Forwarding <sub>some delay</sub>_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail/MAIL_FORWARDING
~~~
_iCloud > Saved to iCloud > iCloud Mail > Mailbox Behaviors_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail/MAILBOX_BEHAVIORS
~~~
_iCloud > Saved to iCloud > iCloud Mail > Import Messages_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail/MAIL_IMPORT
~~~
_iCloud > Saved to iCloud > iCloud Mail > Signing and Encryption_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail/END_TO_END_ENCRYPTION
~~~
_iCloud > Saved to iCloud > iCloud Mail > Custom Email Domain <sub>some delay</sub>_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Mail/BYOD_SETTING_SPECIFIER_ID
~~~
_iCloud > Saved to iCloud > Passwords & Keychan_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.KeychainSync
~~~
_iCloud > Saved to iCloud > Notes_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Notes
~~~
_iCloud > Saved to iCloud > Messages in iCloud_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Messages
~~~
_iCloud > Saved to iCloud > Health_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Health
~~~
_iCloud > Saved to iCloud > iCloud Calendar_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/com.apple.Dataclass.Calendars
~~~
_iCloud > Backup_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/BACKUP
~~~
_iCloud > Backup > All Device Backups > [current device] > Backup Details_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/STORAGE_AND_BACKUP/CURRENT_DEVICE_BACKUP
~~~
_iCloud > Private Relay_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/INTERNET_PRIVACY
~~~
_iCloud > Hide My Email <sub>some delay</sub>_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/PRIVATE_EMAIL_MANAGE
~~~
_iCloud > Advanced Data Protection_
~~~yaml
settings-navigation://com.apple.Settings.iCloud/ICLOUD_ADP_SPECIFIER_NAME
~~~
\
\
_Wallet & Apple Pay_
~~~yaml
settings-navigation://com.apple.Settings.Wallet
~~~
_Wallet & Apple Pay > Apple Pay Defaults_
~~~yaml
settings-navigation://com.apple.Settings.Wallet/applePayDefaults
~~~
\
\
_Apps_
~~~yaml
settings-navigation://com.apple.Settings.Apps
~~~
\
\
_Apps > Default Apps_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.DefaultApps
~~~
\
\
_Apps > [bundle identifier]_
~~~yaml
settings-navigation://com.apple.Settings.Apps/bundle_identifier
~~~
\
\
_Apps > AirPort Utility_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.airport.mobileairportutility
~~~
\
\
_Apps > App Store_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.AppStore
~~~
\
\
_Apps > Apple Store_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.store.Jolly
~~~
\
\
_Apps > Books_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks
~~~
_Apps > Books > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#SIRI
~~~
_Apps > Books > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#SEARCH
~~~
_Apps > Books > Background App Refresh (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#Background%20App%20Refresh
~~~
_Apps > Books > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#PREFERRED_LANGUAGE
~~~
_Apps > Books > Automatic Downloads – Purchases from Other Devices (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#AllowAutoDownloadsForPurchasesFromOtherDevices
~~~
_Apps > Books > Cellular Data – Automatic Downloads (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#AllowAutoDownloadOnCellular
~~~
_Apps > Books > Cellular Data – Downloads (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#Downloads
~~~
_Apps > Books > Syncing – Home (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#HOME
~~~
_Apps > Books > Syncing – iCloud Drive (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#BCSyncICloudDrive
~~~
_Apps > Books > Reading Menu Position_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#Reading%20Menu%20Position%20Options
~~~
_Apps > Books > Reading – Auto-Hyphenation (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#BKAutoHyphenation
~~~
_Apps > Books > Reading – Both Margins Advance (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#BKLeftTapTurnToNext
~~~
_Apps > Books > Reading – Automatically Invert Images (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#IMAGE_FILTER
~~~
_Apps > Books > Reading – Show Status Bar (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#BKReaderShowStatusBar
~~~
_Apps > Books > Reading – Page Navigation (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#BKPageTurnStyle
~~~
_Apps > Books > Reading Goals (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#READING_GOALS
~~~
_Apps > Books > Reading Goals – Inlcude PDFs (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#BKReadingGoalsIncludePDFsUserDefaultsKey
~~~
_Apps > Books > Clear Reading Goals (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#BKReadingGoalsShouldClearDataKey
~~~
_Apps > Books > Search – Book Store (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#BKIncludeBookStoreResultsInSearch
~~~
_Apps > Books > Audiobooks – Skip Forward_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks/BKAudioBookSkipForward
~~~
_Apps > Books > Audiobooks – Skip Back_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks/BKAudioBookSkipBackward
~~~
_Apps > Books > External Controls – Next/Previous (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#Next/Previous
~~~
_Apps > Books > External Controls – Skip Forward/Back (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#Skip%20Forward/Back
~~~
_Apps > Books > Reset Identifier (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks#BAResetAnalyticsUserID
~~~
_Apps > Books > Acknowledgements_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iBooks/Acknowledgements
~~~
\
\
_Apps > Calculator_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.calculator
~~~
\
\
_Apps > Calendar_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal
~~~
_Apps > Calendar > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal#SIRI
~~~
_Apps > Calendar > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal#SEARCH
~~~
_Apps > Calendar > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal#PREFERRED_LANGUAGE
~~~
_Apps > Calendar > Calendar Accounts (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal#ACCOUNTS
~~~
_Apps > Calendar > Calendar Accounts > Add Account_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/ADD_ACCOUNT
~~~
_Apps > Calendar > Time Zone Override_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/timeZoneOverride
~~~
_Apps > Calendar > Alternate Calendars_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/alternateCalendars
~~~
_Apps > Calendar > Sync_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/syncDuration
~~~
_Apps > Calendar > Default Alert Times_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/defaultAlertTimes
~~~
_Apps > Calendar > Default Alert Times > Birthdays_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/defaultAlertTimes/birthdaysDefaultAlertTimes
~~~
_Apps > Calendar > Default Alert Times > Events_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/defaultAlertTimes/timedEventsDefaultAlertTimes
~~~
_Apps > Calendar > Default Alert Times > All-Day Events_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/defaultAlertTimes/allDayEventsDefaultAlertTimes
~~~
_Apps > Calendar > Duration for New Events_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/durationForNewEvents
~~~
_Apps > Calendar > Start Week On_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/startWeekOn
~~~
_Apps > Calendar > Default Calendar_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilecal/defaultCalendar
~~~
\
\
_Apps > Classical_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.music.classical
~~~
\
\
_Apps > Clock_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobiletimer
~~~
\
\
_Apps > Compass_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.compass
~~~
_Apps > Compass > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.compass#SIRI
~~~
_Apps > Compass > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.compass#SEARCH
~~~
_Apps > Compass > Use True North (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.compass#USE_TRUE_NORTH
~~~
\
\
_Apps > Configurator_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.ios.configurator
~~~
\
\
_Apps > Contacts_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook
~~~
_Apps > Contacts > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook#SIRI
~~~
_Apps > Contacts > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook#SEARCH
~~~
_Apps > Contacts > Contacts Accounts_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook/ACCOUNTS
~~~
_Apps > Contacts > Contacts Accounts > Add Account_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook/ADD_ACCOUNT
~~~
_Apps > Contacts > Sort Order_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook/ContactsSortOrder
~~~
_Apps > Contacts > Display Order_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook/PersonNameOrder
~~~
_Apps > Contacts > Short Name_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook/PersonShortName
~~~
_Apps > Contacts > My Info_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook/MeCard
~~~
_Apps > Contacts > Import SIM Contacts (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileAddressBook#SIMImport
~~~
\
\
_Apps > FaceTime_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime
~~~
_Apps > FaceTime > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#SIRI
~~~
_Apps > FaceTime > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#SEARCH
~~~
_Apps > FaceTime > Notifications (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#NOTIFICATIONS
~~~
_Apps > FaceTime > Sensitive Content Warning (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#NUDITY_DETECTION
~~~
_Apps > FaceTime > Default Calling App (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#com.apple.settings.DefaultPhoneCalls
~~~
_Apps > FaceTime > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#PREFERRED_LANGUAGE
~~~
_Apps > FaceTime > Incoming Calls_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime/INCOMING_CALL_STYLE
~~~
_Apps > FaceTime > Announce Calls_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime/ANNOUNCE_CALLS
~~~
_Apps > FaceTime > FaceTime (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#FACETIME_ENABLED_ID
~~~
_Apps > FaceTime > SharePlay_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime/SHAREPLAY_SETTINGS
~~~
_Apps > FaceTime > Silence Unknown Callers (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#DIRECT_TO_VOICEMAIL
~~~
_Apps > FaceTime > Call Filtering – Unknow Callers (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#FILTER_AS_NEW_CALLERS
~~~
_Apps > FaceTime > Call Filtering – FaceTime Spam (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime#FILTER_SPAM
~~~
_Apps > FaceTime > Blocked Contacts_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.facetime/BLOCKLIST_SETTINGS_MAIN_SPECIFIER_IDENTIFIER
~~~
\
\
_Apps > Files_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.DocumentsApp
~~~
\
\
_Apps > Final Cut Camera_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.FinalCutApp.companion
~~~
\
\
_Apps > Freeform_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform
~~~
_Apps > Freeform > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform#SIRI
~~~
_Apps > Freeform > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform#SEARCH
~~~
_Apps > Freeform > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform#PREFERRED_LANGUAGE
~~~
_Apps > Freeform > Snap to Grid (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform#SNAP_TO_GRID
~~~
_Apps > Freeform > Center Guides (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform#CENTER_GUIDES
~~~
_Apps > Freeform > Edge Guides (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform#EDGE_GUIDES
~~~
_Apps > Freeform > Spacing Guides (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform#SPACING_GUIDES
~~~
_Apps > Freeform > Privacy – Reset Identifier (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform#RESET_IDENTIFIER
~~~
_Apps > Freeform > Math Results (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.freeform#MATH_HINTS
~~~
\
\
_Apps > Games_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.games
~~~
\
\
_Apps > GarageBand_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilegarageband
~~~
\
\
_Apps > iMovie_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.iMovie
~~~
\
\
_Apps > Journal_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal
~~~
_Apps > Journal > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#SIRI
~~~
_Apps > Journal > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#SEARCH
~~~
_Apps > Journal > Live Activities (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#Live%20Activities
~~~
_Apps > Journal > Background App Refresh (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#Background%20App%20Refresh
~~~
_Apps > Journal > Journaling Suggestions > Privacy & Security_
~~~yaml
settings-navigation://com.apple.Settings.PrivacyAndSecurity/JOURNALING_SUGGESTIONS
~~~
_Apps > Journal > Journaling Suggestions > Notifications_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/com.apple.momentsd.MOUserNotifications
~~~
_Apps > Journal > Journaling Suggestions > Notifications > Banner Style_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/com.apple.momentsd.MOUserNotifications/BANNER_STYLE_ID
~~~
_Apps > Journal > Journaling Suggestions > Notifications > Show Previews_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/com.apple.momentsd.MOUserNotifications/SHOW_PREVIEW_GROUP_ID
~~~
_Apps > Journal > Journaling Suggestions > Notifications > Notification Grouping_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/com.apple.momentsd.MOUserNotifications/NOTIFICATION_GROUPING_APP_ID
~~~
_Apps > Journal > Journaling Suggestions > Notifications > Customize Notifications_
~~~yaml
settings-navigation://com.apple.Settings.Notifications/com.apple.momentsd.MOUserNotifications/custom
~~~
_Apps > Journal > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#PREFERRED_LANGUAGE
~~~
_Apps > Journal > Add Current Location (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#addCurrentLocation
~~~
_Apps > Journal > Add Entry Title (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#addEntryTitle
~~~
_Apps > Journal > Lock Journal (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#lockJournal
~~~
_Apps > Journal > Save to Photos (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#saveToPhotos
~~~
_Apps > Journal > Health Access (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#journalHealth
~~~
_Apps > Journal > Privacy – Reset Identifier (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.journal#resetAnalyticsID
~~~
\
\
_Apps > Keynote_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Keynote
~~~
\
\
_Apps > Magnifier_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Magnifier
~~~
\
\
_Apps > Mail_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail
~~~
_Apps > Mail > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#SIRI
~~~
_Apps > Mail > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#SEARCH
~~~
_Apps > Mail > Notifications (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#NOTIFICATIONS
~~~
_Apps > Mail > Default Mail App (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#DEFAULT_MAIL_APP
~~~
_Apps > Mail > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#PREFERRED_LANGUAGE
~~~
_Apps > Mail > Mail Accounts_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/ACCOUNTS
~~~
_Apps > Mail > Mail Accounts > Add Account_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/ADD_ACCOUNT
~~~
_Apps > Mail > Notifications_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/NOTIFICATIONS
~~~
_Apps > Mail > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#SIRI
~~~
_Apps > Mail > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#SEARCH
~~~
_Apps > Mail > Show Contact Photos (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#SHOW_CONTACT_PHOTOS
~~~
_Apps > Mail > Show To/Cc Labels (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#SHOW_TOCC_INDICATOR
~~~
_Apps > Mail > Preview_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/LINES_OF_PREVIEW
~~~
_Apps > Mail > Delete or Move Message Action_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/DELETE_OR_MOVE_MESSAGE_ACTION
~~~
_Apps > Mail > Mark Message as Read (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#Mark%20Message%20as%20Read
~~~
_Apps > Mail > Swipe Options_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/SWIPE_OPTIONS
~~~
_Apps > Mail > Ask Before Deleting (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#ASK_BEFORE_DELETING
~~~
_Apps > Mail > Privacy Protection (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#PRIVACY_PROTECTION
~~~
_Apps > Mail > Search_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/SEARCH_PREFERENCE
~~~
_Apps > Mail > Follow Up Suggestions (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#Follow%20Up%20Suggestions
~~~
_Apps > Mail > Organize by Thread (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#ORGANIZE_BY_THREAD
~~~
_Apps > Mail > Collapse Read Messages (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#COLLAPSE_READ_MESSAGES
~~~
_Apps > Mail > Most Recent Message on Top (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#MOST_RECENT_MESSAGE_ON_TOP
~~~
_Apps > Mail > Complete Threads (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#COMPLETE_THREADS
~~~
_Apps > Mail > Muted Thread Action_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/MUTED_THREAD_ACTION
~~~
_Apps > Mail > Blocked Sender Options_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/BLOCKED_SENDER_OPTIONS
~~~
_Apps > Mail > Blocked_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/BLOCKED_SENDERS
~~~
_Apps > Mail > Always Bcc Myself (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#ALWAYS_BCC_MYSELF
~~~
_Apps > Mail > Mark Addresses_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/MARK_ADDRESSES
~~~
_Apps > Mail > Increase Quote Level_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/INCREASE_QUOTE_LEVEL
~~~
_Apps > Mail > Include Attachments with Replies_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/INCLUDE_ATTACHMENTS_WITH_REPLIES
~~~
_Apps > Mail > Add Link Previews (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#ADD_LINK_PREVIEWS
~~~
_Apps > Mail > Signature_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/SIGNATURE
~~~
_Apps > Mail > Load Remote Images (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail#LOAD_REMOTE_IMAGES
~~~
_Apps > Mail > Undo Send Delay_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilemail/UNDO_SEND_DELAY
~~~
\
\
_Apps > Maps_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps
~~~
_Apps > Maps > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#SIRI
~~~
_Apps > Maps > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#SEARCH
~~~
_Apps > Maps > Notifications (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#NOTIFICATIONS
~~~
_Apps > Maps > Background App Refresh (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#Background%20App%20Refresh
~~~
_Apps > Maps > Preferred Type of Travel – Driving (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#TransportTypePreferenceDrivingID
~~~
_Apps > Maps > Preferred Type of Travel – Walking (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#TransportTypePreferenceWalkingID
~~~
_Apps > Maps > Preferred Type of Travel – Transit (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#TransportTypePreferenceTransitID
~~~
_Apps > Maps > Preferred Type of Travel – Cycling (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#TransportTypePreferenceBicycleID
~~~
_Apps > Maps > Directions – Driving_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps/DrivingLinkPreferenceID
~~~
_Apps > Maps > Directions – Walking_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps/WalkingLinkPreferenceID
~~~
_Apps > Maps > Directions – Transit_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps/TransitLinkPreferenceID
~~~
_Apps > Maps > Directions – Cycling_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps/CyclingLinkPreferenceID
~~~
_Apps > Maps > Spoken Directions_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps/NavigationGuidanceLinkPreferenceID
~~~
_Apps > Maps > Share ETA (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#ShareETAPreferenceID
~~~
_Apps > Maps > Blocked Contacts (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#BlockedContactsPreferenceID
~~~
_Apps > Maps > Air Quality Index (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#AirQualityPreferenceID
~~~
_Apps > Maps > Weather Condition (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#WeatherConditionsPreferenceID
~~~
_Apps > Maps > Map Labels > Always in English (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#LabelLanguageAlwaysUIPreferenceID
~~~
_Apps > Maps > Contribute to Maps – Ratings and Photos (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#RatingsAndPhotosPreferencesID
~~~
_Apps > Maps > Contribute to Maps – Show Ratings and Photos Suggestions (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#ShowRatingsAndPhotosSuggestionsPreferencesID
~~~
_Apps > Maps > Allow Photo Providers to Use Your Photos (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Maps#AllowPhotoProvidersPreferencesID
~~~
\
\
_Apps > Measure_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.measure
~~~
\
\
_Apps > Messages_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS
~~~
_Apps > Messages > Focus (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#Focus
~~~
_Apps > Messages > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#SIRI
~~~
_Apps > Messages > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#SEARCH
~~~
_Apps > Messages > Notifications (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#NOTIFICATIONS
~~~
_Apps > Messages > Sensitive Content Warning (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#NUDITY_DETECTION
~~~
_Apps > Messages > Default Messaging App (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#com.apple.settings.DefaultMessaging
~~~
_Apps > Messages > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#PREFERRED_LANGUAGE
~~~
_Apps > Messages > iMessage (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#MADRID_ENABLED_SWITCH
~~~
_Apps > Messages > Send & Receive_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/MADRID_ACCOUNTS_BUTTON
~~~
_Apps > Messages > iMessage Apps_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/IMESSAGE_APPS_BUTTON
~~~
_Apps > Messages > Share Name and Photo_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/NAME_AND_PHOTO_SHARING_BUTTON
~~~
_Apps > Messages > Shared With You_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/SHARED_WITH_YOU_BUTTON
~~~
_Apps > Messages > Screen Unknown Senders (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#FILTER_NEW_SENDERS_SWITCH
~~~
_Apps > Messages > Allow Notifications <sup>If Screen Unknown Senders is enabled</sup>_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/NOTIFICATIONS_UNKNOWN_SENDERS_BUTTON
~~~
_Apps > Messages > Show Contact Photo (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#CONTACT_PHOTO_SWITCH
~~~
_Apps > Messages > Text Message Forwarding_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/SMS_RELAY_DEVICES
~~~
_Apps > Messages > Send Read Receipts (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#READ_RECEIPTS_SWITCH
~~~
_Apps > Messages > Send as Text Message (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#SEND_AS_SMS_SWITCH
~~~
_Apps > Messages > Show Subject Field (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#SHOW_SUBJECT_FIELD_SWITCH
~~~
_Apps > Messages > Character Count (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#CHARACTER_COUNT_SWITCH
~~~
_Apps > Messages > Blocked Contacts_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/BLOCKLIST_SETTINGS_MAIN_SPECIFIER_IDENTIFIER
~~~
_Apps > Messages > Keep Messages_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/KEEP_MESSAGES_BUTTON
~~~
_Apps > Messages > Mentions – Notify Me (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#MENTIONS_NOTIFY_ME_ID
~~~
_Apps > Messages > Audio Messages > Expire_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/EXPIRE_AUDIO_MESSAGES
~~~
_Apps > Messages > Audio Messages > Raise to Listen (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#RAISE_TO_LISTEN_SWITCH
~~~
_Apps > Messages > Send Low Quality Photo Previews (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS#PREVIEW_TRANSCODING_SWITCH
~~~
_Apps > Messages > Messages for Business_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.MobileSMS/BUSINESS_CHAT_BUTTON
~~~
\
\
_Apps > Music_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music
~~~
_Apps > Music > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#SIRI
~~~
_Apps > Music > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#SEARCH
~~~
_Apps > Music > Show Apple Music (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#com.apple.Music:AppleMusicEnabled
~~~
_Apps > Music > Join Apple Music (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#com.apple.Music:AppleMusicOffer
~~~
_Apps > Music > Show All Purchases (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#com.apple.Music:CloudPurchaseHistoryEnabled
~~~
_Apps > Music > Cellular Streaming (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#com.apple.Music:AudioQualityLowData
~~~
_Apps > Music > EQ_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music/com.apple.Music:EQ
~~~
_Apps > Music > Sound Check (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#com.apple.Music:SoundCheck
~~~
_Apps > Music > Song Transitions_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music/com.apple.Music:SongTransitions
~~~
_Apps > Music > Downloaded Music (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#com.apple.Music:MusicUsageDescription
~~~
_Apps > Music > Download over Cellular (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#com.apple.Music:CellularDownloadsAllowed
~~~
_Apps > Music > Automatic Downloads (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#com.apple.Music:MusicAutomaticDownload
~~~
_Apps > Music > Animated Art_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music/com.apple.Music:motionMode
~~~
_Apps > Music > Home Sharing – Sign In (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Music#com.apple.Music:HomeSharingSignInButton
~~~
\
\
_Apps > Notes_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes
~~~
_Apps > Notes > Notes Accounts_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes/ACCOUNTS
~~~
_Apps > Notes > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes#SIRI
~~~
_Apps > Notes > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes#SEARCH
~~~
_Apps > Notes > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes#PREFERRED_LANGUAGE
~~~
_Apps > Notes > Default Account (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes#DEFAULT_ACCOUNT
~~~
_Apps > Notes > Password (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes#PASSWORD
~~~
_Apps > Notes > “On My iPhone” Account (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes#LOCAL_ACCOUNT
~~~
_Apps > Notes > Mention Notifications (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes#MENTION_NOTIFICATIONS
~~~
_Apps > Notes > Sort Notes By_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes/SORT_TYPE
~~~
_Apps > Notes > Sort Checked Items_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes#SORT_CHECKED_ITEMS
~~~
_Apps > Notes > Notes Backgrounds_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes/ALLOW_DARK_BACKGROUNDS
~~~
_Apps > Notes > Access Notes from Lock Screen_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilenotes/ACCESS_FROM_LOCK_SCREEN
~~~
\
\
_Apps > Numbers_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Numbers
~~~
\
\
_Apps > Pages_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Pages
~~~
\
\
_Apps > Passwords_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Passwords
~~~
\
\
_Apps > Phone_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone
~~~
_Apps > Phone > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#SIRI
~~~
_Apps > Phone > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#SEARCH
~~~
_Apps > Phone > Notifications (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#NOTIFICATIONS
~~~
_Apps > Phone > Default Calling App (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#com.apple.settings.DefaultPhoneCalls
~~~
_Apps > Phone > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#PREFERRED_LANGUAGE
~~~
_Apps > Phone > Incoming Calls_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone/INCOMING_CALL_STYLE
~~~
_Apps > Phone > Announce Calls_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone/ANNOUNCE_CALLS
~~~
_Apps > Phone > My Number (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#PHONEBOOK_TELEPHONY_SETTINGS
~~~
_Apps > Phone > SharePlay (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#SHAREPLAY_SETTINGS
~~~
_Apps > Phone > Wi-Fi Calling (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#WIFI_CALLING_TELEPHONY_SETTINGS
~~~
_Apps > Phone > Calls on Other Devices_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone/PRIMARY_CLOUD_CALLING
~~~
_Apps > Phone > Respond with Text_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone/REPLY_WITH_MESSAGES
~~~
_Apps > Phone > Call Forwarding (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#CALL_FORWARDING_TELEPHONY_SETTINGS
~~~
_Apps > Phone > Call Waiting (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#CALL_WAITING_TELEPHONY_SETTINGS
~~~
_Apps > Phone > Audio Call Recording_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone/CALL_RECORDING
~~~
_Apps > Phone > Show My Caller ID (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#CALLING_LINE_ID_RESTRICTION_TELEPHONY_SETTINGS
~~~
_Apps > Phone > Haptics (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#CALL_HAPTICS
~~~
_Apps > Phone > Silence Unknown Callers (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#DIRECT_TO_VOICEMAIL
~~~
_Apps > Phone > Call Filtering – Unknown Callers (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone#FILTER_AS_NEW_CALLERS
~~~
_Apps > Phone > SMS/Call Reporting_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone/CLASSIFICATION_AND_REPORTING
~~~
_Apps > Phone > Blocked Contacts_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilephone/BLOCKLIST_SETTINGS_MAIN_SPECIFIER_IDENTIFIER
~~~
\
\
_Apps > Photomator_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.pixelmatorteam.pixelmator.touch.x.photo
~~~
\
\
_Apps > Photos_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow
~~~
_Apps > Photos > iCloud Photos (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#iCloudPhotosSwitch
~~~
_Apps > Photos > Optimize iPhone Storage (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#iCloudOptimizeStorageOption
~~~
_Apps > Photos > Download and Keep Origianls (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#iCloudKeepOriginalsOption
~~~
_Apps > Photos > Shared Library (dialog)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow/SharedLibrarySettingsButton
~~~~
_Apps > Photos > Shared Albums (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#SharedStreamsSwitch
~~~
_Apps > Photos > Approve wirh Mac to Unlock (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#PhotosContentPrivacySwitch
~~~
_Apps > Photos > Show Hidden Album (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#PhotosHiddenAlbumSwitch
~~~
_Apps > Photos > Show Recently Viewed & Shared (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#PhotosRecentlyViewedAndSharedAlbumSwitch
~~~
_Apps > Photos > Cellular Data (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow/CellularDataGroup#CellularDataLinkList
~~~
_Apps > Photos > Auto-Play Motion (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#VideoAutoplaySwitch
~~~
_Apps > Photos > Loop Videos (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#VideoAutoloopSwitch
~~~
_Apps > Photos > Memories – Reset Suggested Memories (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#ResetBlacklistedMemoryFeatures
~~~
_Apps > Photos > Memories – Reset People & Pets Suggestions (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#ResetPeopleFeedback
~~~
_Apps > Photos > Memories – Show Holiday Events (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#MEMORIES_HOLIDAY_CALENDAR_EVENTS_SWITCH
~~~
_Apps > Photos > Show Featured Content (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#FeaturedContentAllowedSwitch
~~~
_Apps > Photos > Transfer to Mac or PC – Automatic (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#TransferAutomaticOption
~~~
_Apps > Photos > Transfer to Mac or PC – Keep Origianls (option)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#TransferKeepOriginalsOption
~~~
_Apps > Photos > Enhanced Visual Search (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#VisualSearchSwitch
~~~
_Apps > Photos > Control for Creating Spatial Photos (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobileslideshow#AlchemizeButtonEnabledSwitch
~~~
\
\
_Apps > Podcasts_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.podcasts
~~~
\
\
_Apps > Preview_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Preview
~~~
\
\
_Apps > Reminders_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders
~~~
_Apps > Reminders > Reminders Accounts (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#ACCOUNTS
~~~
_Apps > Reminders > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#SIRI
~~~
_Apps > Reminders > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#SEARCH
~~~
_Apps > Reminders > Notifications (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#NOTIFICATIONS
~~~
_Apps > Reminders > Alarms (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#Alarms
~~~
_Apps > Reminders > Liva Activities (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#Live%20Activities
~~~
_Apps > Reminders > Background App Refresh (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#Background%20App%20Refresh
~~~
_Apps > Reminders > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#PREFERRED_LANGUAGE
~~~
_Apps > Reminders > Default List_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders/DEFAULT_LIST
~~~
_Apps > Reminders > All-Day Reminders – Today Notification (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#TODAY_NOTIFICATIONS
~~~
_Apps > Reminders > All-Day Reminders – Time (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#Time
~~~
_Apps > Reminders > Show as Overdue (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#SHOW_AS_OVERDUE
~~~
_Apps > Reminders > Time Zone_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders/TIME_ZONE_OVERRIDE
~~~
_Apps > Reminders > Badge Count – Include Due Today (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#INCLUDE_DUE_TODAY
~~~
_Apps > Reminders > Assigned Reminders – Mute Notifications (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#MUTE_NOTIFICATIONS
~~~
_Apps > Reminders > When Adding Reminders – Show Suggestions (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#SHOW_SUGGESTIONS
~~~
_Apps > Reminders > Urgent Reminders – Complete from Alarms_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#URGENT_REMINDERS
~~~
_Apps > Reminders > Grocery Categorization – Add Language_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders/ADD_LANGUAGE
~~~
_Apps > Reminders > Reset Grocery Categories (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.reminders#RESET_CATEGORIES
~~~
\
\
_Apps > Safari_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari
~~~
_Apps > Safari > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#SIRI
~~~
_Apps > Safari > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#SEARCH
~~~
_Apps > Safari > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#PREFERRED_LANGUAGE
~~~
_Apps > Safari > Default Browser App (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#com.apple.settings.DefaultBrowser
~~~
_Apps > Safari > Search Engine_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/SEARCH_ENGINE_SETTING
~~~
_Apps > Safari > Also Use in Private Browsing (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#PRIVATE_BROWSING_USES_NORMAL_BROWSING_SEARCH_ENGINE_SELECTION
~~~
_Apps > Safari > Search Enginge Suggestions (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#SEARCH_SUGGESTION_SETTING
~~~
_Apps > Safari > Safari Suggestions (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#SIRI_SUGGESTIONS
~~~
_Apps > Safari > Show Recent Searches (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#SHOW_RECENT_SEARCHES
~~~
_Apps > Safari > Quick Website Search_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/SITE_SPECIFIC_SEARCH
~~~
_Apps > Safari > Preload Top Hit (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#ENABLE_PREFETCHING
~~~
_Apps > Safari > AutoFill_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/AUTO_FILL
~~~
_Apps > Safari > Start Page Favorites_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/FAVORITES_FOLDER
~~~
_Apps > Safari > Extensions_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/WEB_EXTENSIONS
~~~
_Apps > Safari > Downloads_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/DOWNLOADS
~~~
_Apps > Safari > Open Links <sup>iPhone</sup>_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/OPEN_LINKS_IN_BACKGROUND_IPHONE
~~~
_Apps > Safari > Open Links <sup>iPad</sup>_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/OPEN_LINKS_IN_BACKGROUND_IPAD
~~~
_Apps > Safari > Hide IP Address (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/Hide%20IP%20Address
~~~
_Apps > Safari > Require Passcode to Unlock Private Browsing (swtich)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#PrivateBrowsingRequiresAuthentication
~~~
_Apps > Safari > Not Secure Connection Warning (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#WARN_ABOUT_INSECURE_CONNECTIONS
~~~
_Apps > Safari > Import (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#IMPORT_BUTTON
~~~
_Apps > Safari > Export (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#EXPORT_BUTTON
~~~
_Apps > Safari > Export (dialog)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari&action=showExportSheet
~~~
_Apps > Safari > Clear History and Website Data (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#CLEAR_HISTORY_AND_DATA
~~~
_Apps > Safari > Settings for Websites (section)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari#SPACE_CELL_FOR_PER_SITE_SETTINGS_SYNC_TOGGLE
~~~
_Apps > Safari > Advanced_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/ADVANCED
~~~
_Apps > Safari > Advanced > Website Data_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.mobilesafari/ADVANCED/REMOVE_WEBSITE_DATA
~~~
\
\
_Apps > Shortcuts_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.shortcuts
~~~
_Apps > Shortcuts > Language (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.shortcuts#PREFERRED_LANGUAGE
~~~
_Apps > Shortcuts > Advanced_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.shortcuts/ShortcutsAdvancedSettings
~~~
_Apps > Shortcuts > Legal Notices_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.shortcuts/ShortcutsLegalNotices
~~~
\
\
_Apps > Support_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.supportapp
~~~
\
\
_Apps > TestFlight_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.TestFlight
~~~
\
\
_Apps > Tips_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.tips
~~~
\
\
_Apps > Translate_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Translate
~~~
_Apps > Translate > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Translate#SIRI
~~~
_Apps > Translate > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Translate#SEARCH
~~~
_Apps > Translate > Background App Refresh (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Translate#Background%20App%20Refresh
~~~
_Apps > Translate > Default Translation App (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Translate#com.apple.settings.DefaultTranslation
~~~
_Apps > Translate > Languages_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Translate/DOWNLOADED_LANGUAGES_SPECIFIER
~~~
_Apps > Translate > On-Device Mode_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Translate#OnDeviceOnly
~~~
\
\
_Apps > Voice Memos_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.VoiceMemos
~~~
\
\
_Apps > Wallet_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Passbook
~~~
\
\
_Apps > Weather_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.weather
~~~
_Apps > Weather > Siri (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.weather#SIRI
~~~
_Apps > Weather > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.weather#SEARCH
~~~
_Apps > Weather > Search (button)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.weather#PREFERRED_LANGUAGE
~~~
_Apps > Weather > Temperature Unit_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.weather#TEMPERATURE_UNIT
~~~
_Apps > Weather > Locations – Home and Work (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.weather#HOME_WORK_SHOW_LABELS
~~~
_Apps > Weather > Locations – Suggested Locations (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.weather#USE_SIGNIFICANT_LOCATIONS
~~~
_Apps > Weather > Privacy – Reset Indentifier (switch)_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.weather#PRIVACY_RESET
~~~
\
\
_Apps > Hidden Apps_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.HiddenApps
~~~
<br/>
<br/>
<br/>
