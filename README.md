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
_Apple Account > Personal Information <sub>(may take a while to load)</sub>_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=APPLE_ACCOUNT_CONTACT
~~~
_Apple Account > Sign-In & Security <sub>(may take a while to load)</sub>_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=PASSWORD_AND_SECURITY
~~~
_Apple Account > Sign-In & Security > Change Password <sub>(may take a while to load)</sub>_
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=changePassword
~~~
_Apple Account > Sign-In & Security > Recovery Contacts <sub>(may take a while to load)</sub>_
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=accountRecovery
~~~
_Apple Account > Sign-In & Security > Legacy Contact <sub>(may take a while to load)</sub>_
~~~yaml
prefs:root=APPLE_ACCOUNT&aaaction=accountBeneficiary
~~~
_Apple Account > Payment & Shipping <sub>(may take a while to load)</sub>_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=PAYMENT_AND_SHIPPING
~~~
_Apple Account > Subscriptions <sub>(may take a while to load)</sub>_
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
_Apple Account > iCloud > Backup > All Device Backups > {current device} > Backup Details_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/STORAGE_AND_BACKUP/CURRENT_DEVICE_BACKUP
~~~
_Apple Account > iCloud > Private Relay_
~~~yaml
prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/INTERNET_PRIVACY
~~~
_Apple Account > iCloud > Hide My Email <sub>(may take a while to load)</sub>_
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
_AirPods <sub>(replace `00:00:00:00:00:00` with the AirPods' MAC address – not possible to find on iOS, but can be found with e.g. `system_profiler SPBluetoothDataType` on a Mac)</sub>_
~~~yaml
settings-navigation://com.apple.Settings.Bluetooth/HeadphoneDetail/?identifier=00:00:00:00:00:00
~~~
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
_Wi-Fi > {current network} >_ &#9432;
~~~yaml
prefs:root=WIFI&path=NetworkDetails
~~~
\
\
_Bluetooth_
~~~yaml
prefs:root=Bluetooth
~~~
_Bluetooth > AirPods >_ &#9432;
> _see `AirPods´ above_

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
_General > Home Button (button)_
~~~yaml
prefs:root=General#HOME_BUTTON
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
_General > VPN & Device Management_
~~~yaml
prefs:root=General&path=ManagedConfigurationList
~~~
_General > VPN & Device Management > VPN_
~~~yaml
prefs:root=General&path=ManagedConfigurationList/VPN
~~~
_General > Legal & Regulatory_
~~~yaml
prefs:root=General&path=LEGAL_AND_REGULATORY
~~~
_General > Transfer or Reset iPhone_
~~~yaml
prefs:root=General&path=Reset
~~~
_General > Transfer or Reset iPhone > Reset > Reset Network Settings (dialog)_
~~~yaml
prefs:root=General&path=ResetNetworkSettings
~~~
_General > Shut Down (button)_
~~~yaml
prefs:root=General#SHUTDOWN_LABEL
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
_Accessibility > Motion_
~~~yaml
prefs:root=ACCESSIBILITY&path=MOTION_TITLE
~~~
_Accessibility > Motion > Reduce Motion (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=MOTION_TITLE#REDUCE_MOTION
~~~
_Accessibility > Motion > Vehicle Motion Clues_
~~~yaml
prefs:root=ACCESSIBILITY&path=MOTION_TITLE/MotionCues
~~~
_Accessibility > Motion > Dim Flashing Lights (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=MOTION_TITLE/PHOTOSENSITIVE_MITIGATION
~~~
_Accessibility > Motion > Auto-Play Animated Images (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=MOTION_TITLE/REDUCE_MOTION_AUTOPLAY_ANIMATED_IMAGES
~~~
_Accessibility > Motion > Auto-Play Video Previews (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=MOTION_TITLE/REDUCE_MOTION_AUTOPLAY_VIDEO_PREVIEWS
~~~
_Accessibility > Motion > Auto-Play Message Effects (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=MOTION_TITLE/ReduceMotionAutoplayMessagesEffects
~~~
_Accessibility > Motion > Prefer Non-Blinking Cursor (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=MOTION_TITLE/PREFER_NONBLINKING_CURSOR
~~~
_Accessibility > Touch_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE
~~~
_Accessibility > Touch > AssistiveTouch_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE
~~~
_Accessibility > Touch > AssistiveTouch > Assistive Touch (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/EnableAssistiveTouchSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Customize Top Level Menu_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AssistiveTouchCustomize
~~~
_Accessibility > Touch > AssistiveTouch > Single-Tap_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/TapSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Double-Tap_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/DoubleTapSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Double-Tap > Double-Tap Timeout_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/DoubleTapSpecifier/ASTDoubleTapTimeoutSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Long Press_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/LongPressSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Long Press > Long Press Duration_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/LongPressSpecifier/ASTLongPressDurationSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Create New Gesture_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/CreateCustomGesture
~~~
_Accessibility > Touch > AssistiveTouch > Dwell Control (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/DwellEnabledSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Idle Opacity_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/IdleOpacity
~~~
_Accessibility > Touch > AssistiveTouch > Devices_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AssistiveTouchMouseDevices
~~~
_Accessibility > Touch > AssistiveTouch > Sound on Click (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/MouseClickSounds
~~~
_Accessibility > Touch > AssistiveTouch > Always Show Menu (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AlwaysShowMenu
~~~
_Accessibility > Touch > AssistiveTouch > Perform Touch Gestures (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/MouseBehavesLikeFinger
~~~
_Accessibility > Touch > AssistiveTouch > Use Game Controller (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/EnableAssistiveTouchGameControllerSpecifier
~~~
_Accessibility > Touch > AssistiveTouch > Sound Actions_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/SOUND_ACTIONS
~~~
_Accessibility > Touch > Reachability (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/REACHABILITY
~~~
_Accessibility > Touch > Haptic Touch_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/ForceTouch
~~~
_Accessibility > Touch > Haptic Touch > Fast (option)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/ForceTouch#HapticTouchFastIdentifier
~~~
_Accessibility > Touch > Touch Accomodations_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/TOUCH_ACCOMMODATIONS
~~~
_Accessibility > Touch > Touch Accomodations > Touch Accomodations (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/TOUCH_ACCOMMODATIONS/TOUCH_ACCOMMODATIONS_SWITCHER
~~~
_Accessibility > Touch > Touch Accomodations > Hold Duration (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/TOUCH_ACCOMMODATIONS/HoldDuration
~~~
_Accessibility > Touch > Touch Accomodations > Ignore Repeat (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/TOUCH_ACCOMMODATIONS/IgnoreRepeat
~~~
_Accessibility > Touch > Shake to Undo (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/SHAKE_TO_UNDO
~~~
_Accessibility > Touch > Vibration (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/VIBRATION
~~~
_Accessibility > Touch > Prevent Lock to End Call (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/LockButtonIgnore
~~~
_Accessibility > Touch > Call Audio Routing_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING
~~~
_Accessibility > Touch > Call Audio Routing > Auto-Answer Calls_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
_Accessibility > Touch > Back Tap_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/BackTap
~~~
_Accessibility > Touch > Back Tap > Double Tap_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/BackTap/DoubleTap
~~~
_Accessibility > Touch > Back Tap > Triple Tap_
~~~yaml
prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/BackTap/TripleTap
~~~
_Accessibility > Audio & Visual_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE
~~~
_Accessibility > Audio & Visual > Headphone Accommodations_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/AXPAEnableSpecID
~~~
_Accessibility > Audio & Visual > Headphone Accommodations > Custom Audio Setup_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/AXPAEnableSpecID#AXPAPersonalAudioSetupSpecID
~~~
_Accessibility > Audio & Visual > Background Sounds_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/AXCSEnableSpecID
~~~
_Accessibility > Audio & Visual > Background Sounds > Background Sounds (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/AXCSEnableSpecID#CSFeatureToggleSpecID
~~~
_Accessibility > Audio & Visual > Live Listen_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/AXLLEnableSpecID
~~~
_Accessibility > Audio & Visual > Mono Audio (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/AXPAMonoSpecID
~~~
_Accessibility > Audio & Visual > Always Show Volume Controls (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/AXPAAlwaysShowVolumeControlSpecID
~~~
_Accessibility > Audio & Visual > Add Voice Isolation (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE#ExtendedVoiceIsolationSpecID
~~~
_Accessibility > Audio & Visual > Headphone Notifications (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/AXHeadphoneNotificationsSpecID
~~~
_Accessibility > Audio & Visual > Balance (slider)_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/LeftRightBalance
~~~
_Accessibility > Audio & Visual > Add Audio in Calls_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/MIX_TO_UPLINK
~~~
_Accessibility > Audio & Visual > Call Audio Routing_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING
~~~
_Accessibility > Audio & Visual > Call Audio Routing > Auto-Answer Calls_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/LED_FLASH
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts > Flash While Unlocked (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/LED_FLASH#LED_FLASH_WHILE_UNLOCKED
~~~
_Accessibility > Audio & Visual > LED Flash for Alerts > Flash in Silent Mode (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE/LED_FLASH#LED_RINGER_SWITCH_CONTROL
~~~
_Accessibility > Subtitles & Captioning_
~~~yaml
prefs:root=ACCESSIBILITY&path=SUBTITLES_CAPTIONING
~~~
_Accessibility > Subtitles & Captioning > Closed Captions + SDH (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=SUBTITLES_CAPTIONING#PREFER_SDH
~~~
_Accessibility > Subtitles & Captioning > Style_
~~~yaml
prefs:root=ACCESSIBILITY&path=SUBTITLES_CAPTIONING/currentTheme
~~~
_Accessibility > Subtitles & Captioning > Style > Create New Style_
~~~yaml
prefs:root=ACCESSIBILITY&path=SUBTITLES_CAPTIONING/currentTheme/CreateNewStyle
~~~
_Accessibility > Subtitles & Captioning > Show Audio Transcriptions (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=SUBTITLES_CAPTIONING/SHOW_AUDIO_TRANSCRIPTIONS
~~~
_Accessibility > Subtitles & Captioning > Show when Muted (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=SUBTITLES_CAPTIONING/SHOW_WHEN_MUTED
~~~
_Accessibility > Subtitles & Captioning > Show on Skip Back (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=SUBTITLES_CAPTIONING/SHOW_ON_SKIP_BACK
~~~
_Accessibility > Live Speech_
~~~yaml
prefs:root=ACCESSIBILITY&path=LIVE_SPEECH_TITLE
~~~
_Accessibility > Live Speech > Phrases_
~~~yaml
prefs:root=ACCESSIBILITY&path=LIVE_SPEECH_TITLE/PHRASES
~~~
_Accessibility > Live Speech > Phrases > + (button)_
~~~yaml
prefs:root=ACCESSIBILITY&path=LIVE_SPEECH_TITLE/PHRASES#CREATE_CUSTOM_CATEGORY
~~~
_Accessibility > AirPods_
~~~yaml
prefs:root=ACCESSIBILITY&path=AIRPODS
~~~
_Accessibility > AirPods > Spatial Audio Head Tracking – Follow iPhone (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=AIRPODS#SPATIAL_AUDIO_SWITCH
~~~
_Accessibility > Guided Access_
~~~yaml
prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE
~~~
_Accessibility > Guided Access > Passcode Settings_
~~~yaml
prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE/GuidedAccessSecurityLinkList
~~~
_Accessibility > Guided Access > Time Limits_
~~~yaml
prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE/GuidedAccessTimeRestrictionsLinkList
~~~
_Accessibility > Guided Access > Time Limits > Alarm – Sound_
~~~yaml
prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE/GuidedAccessTimeRestrictionsLinkList/GUIDED_ACCESS_TIME_RESTRICTIONS_SOUND_TITLE#GUIDED_ACCESS_TIME_RESTRICTIONS_SOUND_TITLE
~~~
_Accessibility > Guided Access > Time Limits > Alarm – Speak (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE/GuidedAccessTimeRestrictionsLinkList#GUIDED_ACCESS_TIME_RESTRICTIONS_SPEAK_TITLE
~~~
_Accessibility > Guided Access > Accessibility Shortcut (switch)_
~~~yaml
prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE#GuidedAccessEnableAXFeatures
~~~
_Accessibility > Guided Access > Display Auto-Lock_
~~~yaml
prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE/GuidedAccessAutoLockTime#GuidedAccessAutoLockTime
~~~
_Accessibility > Accessibility Shortcut_
~~~yaml
prefs:root=ACCESSIBILITY&path=TRIPLE_CLICK_TITLE
~~~
_Accessibility > Per-App Settings_
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE
~~~
_Accessibility > Per-App Settings > {app bundle identifier} <sup>(as long as you have added the app there, otherwise goes to the parent page)</sup>_
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE/bundle_identifier
~~~
_Accessibility > Per-App Settings > Show Hidden Apps_
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE/PROTECTED_APPS_SHOW_HIDDEN_TITLE
~~~
_Accessibility > Per-App Settings > Add App (dialog)_
~~~yaml
prefs:root=ACCESSIBILITY&path=APP_AX_SETTINGS_TITLE/AX_ADD_BUTTON_IDENTIFIER
~~~
\
\
_Camera_
~~~yaml
prefs:root=CAMERA
~~~
_Camera > Record Video_
~~~yaml
prefs:root=CAMERA&path=CameraVideoSettingsList
~~~
_Camera > Record Slo-mo_
~~~yaml
prefs:root=CAMERA&path=CameraSlomoSettingsList
~~~
_Camera > Formats_
~~~yaml
prefs:root=CAMERA&path=CameraFormatsSettingsList
~~~
_Camera > Preserve Settings_
~~~yaml
prefs:root=CAMERA&path=CameraPreserveSettingsSwitch
~~~
_Camera > Scan QR Codes (switch)_
~~~yaml
prefs:root=CAMERA#CameraQRBannerSwitch
~~~~
_Camera > Composition – Grid (switch)_
~~~yaml
prefs:root=CAMERA#CameraGridSwitch
~~~
_Camera > Composition – Level (switch)_
~~~yaml
prefs:root=CAMERA#CameraGridSwitch
~~~
\
\
_Control Center_
~~~yaml
prefs:root=ControlCenter
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
prefs:root=HOME_SCREEN
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
prefs:root=NOTIFICATIONS_ID
~~~
_Notifications > Scheduled Summary_
~~~yaml
prefs:root=NOTIFICATIONS_ID&path=SCHEDULED_DELIVERY_ID
~~~
_Notifications > {app bundle identifier}_
~~~yaml
prefs:root=NOTIFICATIONS_ID&path=bundle_identifier
~~~
_Notifications > {app bundle identifier} > Customize Notifications_
~~~yaml
prefs:root=NOTIFICATIONS_ID&path=bundle_identifier/custom
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
_Sounds & Haptics > Ringtone_
~~~yaml
prefs:root=Sounds&path=Ringtone
~~~
_Sounds & Haptics > Text Tone_
~~~yaml
prefs:root=Sounds&path=Text_Messages
~~~
_Sounds & Haptics > New Voicemail_
~~~yaml
prefs:root=Sounds&path=Voicemail
~~~
_Sounds & Haptics > Sent Mail_
~~~yaml
prefs:root=Sounds&path=SENT_MAIL
~~~
_Sounds & Haptics > Celendar Alerts_
~~~yaml
prefs:root=Sounds&path=Calendar%20Alarm
~~~
_Sounds & Haptics > Reminder Alerts_
~~~yaml
prefs:root=Sounds&path=Reminder%20Alerts
~~~
_Sounds & Haptics > Default Alerts_
~~~yaml
prefs:root=Sounds&path=DEFAULT_ALERTS
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
_Focus_
~~~yaml
settings-navigation://com.apple.Settings.Focus
~~~
_Focus > Focus Status_
~~~yaml
settings-navigation://com.apple.Settings.Focus/Focus%20Status
~~~
\
\
_Screen Time_
~~~yaml
prefs:root=SCREEN_TIME
~~~
_Screen Time > See All App & Web Site Activity_
~~~yaml
prefs:root=SCREEN_TIME&path=SCREEN_TIME_SUMMARY
~~~
_Screen Time > Downtime_
~~~yaml
prefs:root=SCREEN_TIME&path=DOWNTIME
~~~
_Screen Time > App Limits_
~~~yaml
prefs:root=SCREEN_TIME&path=APP_LIMITS
~~~
_Screen Time > Always Allowed_
~~~yaml
prefs:root=SCREEN_TIME&path=ALWAYS_ALLOWED
~~~
_Screen Time > Screen Distance_
~~~yaml
prefs:root=SCREEN_TIME&path=EYE_DISTANCE
~~~
_Screen Time > Communication Limits_
~~~yaml
prefs:root=SCREEN_TIME&path=COMMUNICATION_LIMITS
~~~
_Screen Time > Communication Safety_
~~~yaml
prefs:root=SCREEN_TIME&path=COMMUNICATION_SAFETY
~~~
_Screen Time > Content & Privacy Restrictions_
~~~yaml
prefs:root=SCREEN_TIME&path=CONTENT_PRIVACY
~~~
\
\
_Touch ID & Passcode_
~~~yaml
prefs:root=PASSCODE
~~~
_Touch ID & Passcode > Change Passcode (button)_
~~~yaml
prefs:root=PASSCODE#CHANGE_PASSCODE
~~~
_Touch ID & Passcode > Require Passcode_
~~~yaml
prefs:root=PASSCODE&path=PASSCODE_REQ
~~~
_Touch ID & Passcode > Erase Data (switch)_
~~~yaml
prefs:root=PASSCODE#WIPE_DEVICE
~~~
\
\
_Emergency SOS_
~~~yaml
prefs:root=EMERGENCY_SOS
~~~
_Emergency SOS > Set up Emergency Contacts in Health (button)_
~~~yaml
prefs:root=EMERGENCY_SOS#EMERGENCY_CONTACTS
~~~
\
\
_Privacy & Security_
~~~yaml
prefs:root=Privacy
~~~
_Privacy & Security > Location Services_
~~~yaml
prefs:root=Privacy&path=LOCATION
~~~
_Privacy & Security > Location Service > App Clips_
~~~yaml
prefs:root=Privacy&path=LOCATION/APP_CLIPS
~~~
_Privacy & Security > Location Services > System Services_
~~~yaml
prefs:root=Privacy&path=LOCATION/SYSTEM_SERVICES
~~~
_Privacy & Security > Tracking_
~~~yaml
prefs:root=Privacy&path=USER_TRACKING
~~~
_Privacy & Security > Calendars_
~~~yaml
prefs:root=Privacy&path=CALENDARS
~~~
_Privacy & Security > Contacts_
~~~yaml
prefs:root=Privacy&path=CONTACTS
~~~
_Privacy & Security > Health Data_
~~~yaml
prefs:root=Privacy&path=HEALTH_DATA
~~~
_Privacy & Security > Home Accessories_
~~~yaml
prefs:root=Privacy&path=WILLOW
~~~
_Privacy & Security > Media & Apple Music_
~~~yaml
prefs:root=Privacy&path=MEDIALIBRARY
~~~
_Privacy & Security > Passkeys Access for Web Browsers_
~~~yaml
prefs:root=Privacy&path=PASSKEYS
~~~
_Privacy & Security > Photos_
~~~yaml
prefs:root=Privacy&path=PHOTOS
~~~
_Privacy & Security > Reminders_
~~~yaml
prefs:root=Privacy&path=REMINDERS
~~~
_Privacy & Security > Wallet_
~~~yaml
prefs:root=Privacy&path=WALLET
~~~
_Privacy & Security > Bluetooth_
~~~yaml
prefs:root=Privacy&path=BT_PERIPHERAL
~~~
_Privacy & Security > Camera_
~~~yaml
prefs:root=Privacy&path=CAMERA
~~~
_Privacy & Security > Local Network_
~~~yaml
prefs:root=Privacy&path=LOCAL_NETWORK
~~~
_Privacy & Security > Microphone_
~~~yaml
prefs:root=Privacy&path=MICROPHONE
~~~
_Privacy & Security > Motion & Fitness_
~~~yaml
prefs:root=Privacy&path=MOTION
~~~
_Privacy & Security > Nearby Interactions_
~~~yaml
prefs:root=Privacy&path=NEARBY_INTERACTIONS
~~~
_Privacy & Security > Paired Devices_
~~~yaml
prefs:root=Privacy&path=PAIRED_DEVICES
~~~
_Privacy & Security > Research Sensor & Usage Data_
~~~yaml
prefs:root=Privacy&path=ALMANAC
~~~
_Privacy & Security > Speech Recognition_
~~~yaml
prefs:root=Privacy&path=SPEECH_RECOGNITION
~~~
_Privacy & Security > Journaling Suggestions_
~~~yaml
prefs:root=Privacy&path=JOURNALING_SUGGESTIONS
~~~
_Privacy & Security > Blocked Contacts_
~~~yaml
prefs:root=Privacy&path=BLOCKLIST
~~~
_Privacy & Security > Safety Check_
~~~yaml
prefs:root=Privacy&path=SAFETY_CHECK
~~~
_Privacy & Security > Sensitive Content Warning_
~~~yaml
prefs:root=Privacy&path=NUDITY_DETECTION
~~~
_Privacy & Security > Analytics & Improvements_
~~~yaml
prefs:root=Privacy&path=PROBLEM_REPORTING
~~~
_Privacy & Security > Apple Advertising_
~~~yaml
prefs:root=Privacy&path=ADVERTISING
~~~
_Privacy & Security > App Privacy Report_
~~~yaml
prefs:root=Privacy&path=PRIVACY_REPORT
~~~
_Privacy & Security > Lockdown Mode_
~~~yaml
prefs:root=Privacy&path=LOCKDOWN_MODE
~~~
\
\
_iCloud <sup>(see also `Apple Account > iCloud´)</sup>_
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
_Apps > {app bundle identifier}_
~~~yaml
settings-navigation://com.apple.Settings.Apps/bundle_identifier
~~~
_Apps > Compass_
~~~yaml
prefs:root=COMPASS
~~~
_Apps > Compass > Use True North (switch)_
~~~yaml
prefs:root=COMPASS#USE_TRUE_NORTH
~~~
_Apps > Contacts_
~~~yaml
prefs:root=CONTACTS
~~~
_Apps > Contacts > Contacts Accounts_
~~~yaml
settings-navigation://com.apple.Settings.InternetAccounts
~~~
_Apps > Contacts > Contacts Accounts > Add Account_
~~~yaml
prefs:root=CONTACTS&path=ADD_ACCOUNT
~~~
_Apps > Contacts > Sort Order_
~~~yaml
prefs:root=CONTACTS&path=ContactsSortOrder
~~~
_Apps > Contacts > Display Order_
~~~yaml
prefs:root=CONTACTS&path=PersonNameOrder
~~~
_Apps > Contacts > Short Name_
~~~yaml
prefs:root=CONTACTS&path=PersonShortName
~~~
_Apps > Contacts > My Info_
~~~yaml
prefs:root=CONTACTS&path=MeCard
~~~
_Apps > Contacts > Import SIM Contacts (button)_
~~~yaml
prefs:root=CONTACTS#SIMImport
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
_Apps > Safari > Show Recent Searches (switch)_
~~~yaml
prefs:root=SAFARI#SHOW_RECENT_SEARCHES
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
_Apps > Safari > Open Links > New Tab <sub>(switches to the new tab)</sub> or In Background <sub>(doesn't leave the current tab)</sub>_

&emsp;<sub>_iPhone:_</sub>
~~~yaml
prefs:root=SAFARI&path=OPEN_LINKS_IN_BACKGROUND_IPHONE
~~~

&emsp;<sub>_iPad:_</sub>
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
_Apps > Hidden Apps_
~~~yaml
settings-navigation://com.apple.Settings.Apps/com.apple.Settings.Apps.HiddenApps
~~~
