# Tweaks

Collection of Windows Tweaks for Performance, Latency, Privacy & Gaming.
I don't take credits for such registrys.
      
<details>
<summary><b>Privacy.reg</b></summary>
<br>

Windows Registry Editor Version 5.00  

### ;Disable apps access - Appointments
```
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\appointments]
"Value"="Deny"
      
[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\appointments]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\appointments]
"Value"="Deny"    
```
### ;Disable apps access - Call History

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\phoneCallHistory]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\phoneCallHistory]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\phoneCallHistory]
"Value"="Deny"
  
### ;Disable apps access - Camera

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\webcam]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\webcam]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\webcam]
"Value"="Deny"


### ;Disable apps access - Contacts 

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\contacts]
"Value"="Deny"

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\contacts]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\contacts]
"Value"="Deny"

### ;Disable apps access - Diagnostic Information

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\appDiagnostics]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\appDiagnostics]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\appDiagnostics]
"Value"="Deny"
    
### ;Disable apps access - Documents Library

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\documentsLibrary]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\documentsLibrary]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\documentsLibrary]
"Value"="Deny"
  
### ;Disable apps access - Email

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\email]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\email]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\email]
"Value"="Deny"

### ;Disable apps access - File System

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\broadFileSystemAccess]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\broadFileSystemAccess]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\broadFileSystemAccess]
"Value"="Deny"


### ;Disable apps access - Messages (Text or MMS)

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\chat]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\chat]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\chat]
"Value"="Deny"
    
### ;Disable apps access - Notifications

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\userNotificationListener]
"Value"="Deny"

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\userNotificationListener]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\userNotificationListener]
"Value"="Deny"

  
### ;Disable apps access - Phone Calls

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\phoneCall]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\phoneCall]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\phoneCall]
"Value"="Deny"

### ;Disable apps access - Pictures Library

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\picturesLibrary]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\picturesLibrary]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\picturesLibrary]
"Value"="Deny"

### ;Disable apps access - Radios

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\radios]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\radios]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\radios]
"Value"="Deny"
    
### ;Disable apps access - Shary and sync info with non-explicity paired wireless devices


[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\DeviceAccess\Global\LooselyCoupled]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\DeviceAccess\Global\LooselyCoupled]
"Value"="Deny"
  
### ;Disable apps access - Tasks

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\userDataTasks]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\userDataTasks]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\userDataTasks]
"Value"="Deny"

### ;Disable apps access - User account info

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\userAccountInformation]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\userAccountInformation]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\userAccountInformation]
"Value"="Deny"

### ;Disable apps access - Videos Library

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\videosLibrary]
"Value"="Deny"

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\videosLibrary]
"Value"="Deny"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\videosLibrary]
"Value"="Deny"
    
### ;Disable experience improvement program (NVIDIA driver)

[HKEY_CURRENT_USER\SOFTWARE\NVIDIA Corporation\NVControlPanel2\Client]
"OptInOrOutPreference"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\NVIDIA Corporation\NVControlPanel2\Client]
"OptInOrOutPreference"=dword:00000000
  
### ;Disable Experimentation

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PolicyManager\current\device\System]
"AllowExperimentation"=dword:00000000

### ;Disable Location services

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PolicyManager\current\device\System]
"AllowLocation"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\LocationAndSensors]
"DisableWindowsLocationProvider"=dword:00000001
"DisableLocationScripting"=dword:00000001
"DisableLocation"=dword:00000001

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows Search]
"AllowSearchToUseLocation"=dword:00000000

### ;Disable Telemetry

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\DataCollection]
"AllowTelemetry"=dword:00000000

[HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\CrashControl\StorageTelemetry]
"DeviceDumpEnabled"=dword:00000000

[HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\DiagTrack]
"Start"=dword:00000004

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\DataCollection]
"AllowTelemetry"=dword:00000000

[HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\WMI\Autologger\AutoLogger-Diagtrack-Listener]
"Start"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\AppCompat]
"AITEnable"=dword:00000000

[HKEY_CURRENT_USER\Policies\Microsoft\Windows\CloudContent]
"DisableTailoredExperiencesWithDiagnosticData"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Policies\Microsoft\Windows\CloudContent]
"DisableTailoredExperiencesWithDiagnosticData"=dword:00000001

[HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\dmwappushservice]
"Start"=dword:00000004
    
### ;Disable Automatic Installation of sponsored apps (Consumer Experience)

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent]
"DisableWindowsConsumerFeatures"=dword:00000001
  
### ;Disable automatically connect to hotspots temporarily to see if paid network services are avaiable.

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WcmSvc\wifinetworkmanager\features]
"PaidWifi"=dword:00000000

### ;Disable automatically connect to suggested open hotspots

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WcmSvc\wifinetworkmanager\features]
"WiFiSenseOpen"=dword:00000000

### ;Disable automatic installation of suggested apps (Promotional tiles such as Minecraft, Candy Crush, Flipboard etc.)\

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SilentInstalledAppsEnabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SilentInstalledAppsEnabled"=dword:00000000
    
### ;Disable Clipboard History

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System]
"AllowClipboardHistory"=dword:00000000
  
### ;Disable Cloud optimized content (Programmable Taskbar)

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent]
"DisableCloudOptimizedContent"=dword:00000001

### ;Disable Collect application inventory

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\AppCompat]
"DisableInventory"=dword:00000001

### ;Disable Collect contacts to let Windows and Cortana better understand you

[HKEY_CURRENT_USER\Software\Microsoft\InputPersonalization\TrainedDataStore]
"HarvestContacts"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\InputPersonalization\TrainedDataStore]
"HarvestContacts"=dword:00000000
    
### ;Disable Collect typed text to let windows and cortana better understand you

[HKEY_CURRENT_USER\Software\Policies\Microsoft\InputPersonalization]
"RestrictImplicitTextCollection"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Policies\Microsoft\InputPersonalization]
"RestrictImplicitTextCollection"=dword:00000001
  
### ;Disable Collect written text (ink) to let Windows and Cortana better understand you

[HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\InputPersonalization]
"RestrictImplicitInkCollection"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Policies\Microsoft\InputPersonalization]
"RestrictImplicitInkCollection"=dword:00000001

### ;Disable Cortana

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows Search]
"AllowCortana"=dword:00000000

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"ShowCortanaButton"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"ShowCortanaButton"=dword:00000000

### ;Disable Cortana - Activity recommendations when switching devices

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Search]
"HistoryViewEnabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Search]
"HistoryViewEnabled"=dword:00000000
    
### ;Disable Cortana - Use my signed-in devices history

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]
"DeviceHistoryEnabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Search]
"DeviceHistoryEnabled"=dword:00000000
  
### ;Disable Feedback Frequency

[HKEY_CURRENT_USER\Software\Microsoft\Siuf\Rules]
"NumberOfSIUFInPeriod"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Siuf\Rules]
"NumberOfSIUFInPeriod"=dword:00000000

### ;Disable Let apps on user's other devices open apps and continue experiences on this device

[HKEY_CURRENT_USER\Software\Microsoft\Siuf\Rules]
"NumberOfSIUFInPeriod"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Siuf\Rules]
"NumberOfSIUFInPeriod"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\SmartGlass]
"UserAuthPolicy"=dword:00000000

### ;Disable Let apps on user's other devices use Bluetooth to open apps and continue experiences on this device

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\SmartGlass]
"UserAuthPolicy"=dword:00000000
"BluetoothPolicy"=dword:00000000
    
### ;Disable app running in the background

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]
"GlobalUserDisabled"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]
"GlobalUserDisabled"=dword:00000001

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]
"BackgroundAppGlobalToggle"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Search]
"BackgroundAppGlobalToggle"=dword:00000000
  
### ;Disable apps use user advertising ID for experiences across apps
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\AdvertisingInfo]
"Enabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\AdvertisingInfo]
"Enabled"=dword:00000000

### ;Disable Microsoft provide more tailored experiences with relevant tips and recommendations by using your diagnostic data
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Privacy]
"TailoredExperiencesWithDiagnosticDataEnabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Privacy]
"TailoredExperiencesWithDiagnosticDataEnabled"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent]
"DisableTailoredExperiencesWithDiagnosticData"=dword:00000001


### ;Disable Skype (if installed) help you connect with friends in your address book and verify your mobile number

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\OOBE\AppSettings]
"Skype-UserConsentAccepted"=dword:00000000
    
### ;Disable websites provide locally relevant content by accesing user language list

[HKEY_CURRENT_USER\Control Panel\International\User Profile]
"HttpAcceptLanguageOptOut"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Control Panel\International\User Profile]
"HttpAcceptLanguageOptOut"=dword:00000001


### ;Disable Windows collect my activities from this PC ("Timeline")

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System]
"EnableActivityFeed"=dword:00000000
"PublishUserActivities"=dword:00000000
"UploadUserActivities"=dword:00000000

### ;Disable Windows to track app launches to improve Start and search results

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"Start_TrackProgs"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"Start_TrackProgs"=dword:00000000

### ;Disable Windows track opened documents to populate Jump Lists

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"Start_TrackDocs"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"Start_TrackDocs"=dword:00000000

### ;Disable Ocassionally show suggestions in StartMenu

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SystemPaneSuggestionsEnabled"=dword:00000000
"SubscribedContent-338388Enabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SystemPaneSuggestionsEnabled"=dword:00000000
"SubscribedContent-338388Enabled"=dword:00000000

### ;Disable Online speech recognition services

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\InputPersonalization]
"AllowInputPersonalization"=dword:00000000

### ;Disable Personalize your speech, typing and inking input by sending your input data to Microsoft

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Personalization\Settings]
"AcceptedPrivacyPolicy"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Personalization\Settings]
"AcceptedPrivacyPolicy"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\TextInput]
"AllowLinguisticDataCollection"=dword:00000000

### ;Disable Pre-Installed apps

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"PreInstalledAppsEnabled"=dword:00000000
"PreInstalledAppsEverEnabled"=dword:00000000
"RemediationRequired"=dword:00000000
"SubscribedContent-314559Enabled"=dword:00000000
"SubscribedContent-280815Enabled"=dword:00000000
"SubscribedContent-314563Enabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"PreInstalledAppsEnabled"=dword:00000000
"PreInstalledAppsEverEnabled"=dword:00000000
"RemediationRequired"=dword:00000000
"SubscribedContent-314559Enabled"=dword:00000000
"SubscribedContent-280815Enabled"=dword:00000000
"SubscribedContent-314563Enabled"=dword:00000000

### ;Disable Pre-Installed OEM apps
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"OemPreInstalledAppsEnabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"OemPreInstalledAppsEnabled"=dword:00000000

### ;Disable Program Compatibility Assistant

[HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\AppCompat]
"DisablePCA"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Policies\Microsoft\Windows\AppCompat]
"DisablePCA"=dword:00000001


### ;Disable cloud search (Sources like OneDriver and SharePoint)

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows Search]
"AllowCloudSearch"=dword:00000000

### ;Disable Bing web results on StartMenu

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Search]
"BingSearchEnabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Search]
"BingSearchEnabled"=dword:00000000

### ;Disable Shared Experiences
[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System]
"EnableCdp"=dword:00000000

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\CDP]
"CdpSessionUserAuthzPolicy"=dword:00000000
"NearShareChannelUserAuthzPolicy"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\CDP]
"CdpSessionUserAuthzPolicy"=dword:00000000
"NearShareChannelUserAuthzPolicy"=dword:00000000

### ;Disable suggested content in the settings app

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SubscribedContent-338393Enabled"=dword:00000000
"SubscribedContent-353694Enabled"=dword:00000000
"SubscribedContent-353696Enabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SubscribedContent-338393Enabled"=dword:00000000
"SubscribedContent-353694Enabled"=dword:00000000
"SubscribedContent-353696Enabled"=dword:00000000

### ;Disable Windows welcome experience after updates
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SubscribedContent-310093Enabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SubscribedContent-310093Enabled"=dword:00000000


### ;Disable suggest ways I can finish setting up my device online

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\UserProfileEngagement]
"ScoobeSystemSettingEnabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\UserProfileEngagement]
"ScoobeSystemSettingEnabled"=dword:00000000

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager\Context\CloudExperienceHostIntent\Wireless]
"ScoobeCheckCompleted"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager\Context\CloudExperienceHostIntent\Wireless]
"ScoobeCheckCompleted"=dword:00000001

### ;Disable SmartScreen Filter to check web content (URLs) that Windows Store apps use

### ;Disable Typing insights

[HKEY_CURRENT_USER\Software\Microsoft\Input\Settings]
"InsightsEnabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Input\Settings]
"InsightsEnabled"=dword:00000000

### ;Disable Hotstop 2.0 Online Sign-Up to get connected

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WlanSvc\AnqpCache]
"OsuRegistrationStatus"=dword:00000000

### ;Disable page prediction to improve reading, speed up browsing. Your browsing data will be sent to Microsoft.

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Internet Explorer\FlipAhead]
"FPEnabled"=dword:00000000

### ; Disable Windows Spotlight (Tips and suggestions)

[HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CloudContent]
"DisableWindowsSpotlightFeatures"=dword:00000001
"ConfigureWindowsSpotlight"=dword:00000002
"IncludeEnterpriseSpotlight"=dword:00000000
"DisableWindowsSpotlightWindowsWelcomeExperience"=dword:00000001
"DisableWindowsSpotlightOnActionCenter"=dword:00000001
"DisableWindowsSpotlightOnSettings"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Policies\Microsoft\Windows\CloudContent]
"DisableWindowsSpotlightFeatures"=dword:00000001
"ConfigureWindowsSpotlight"=dword:00000002
"IncludeEnterpriseSpotlight"=dword:00000000
"DisableWindowsSpotlightWindowsWelcomeExperience"=dword:00000001
"DisableWindowsSpotlightOnActionCenter"=dword:00000001
"DisableWindowsSpotlightOnSettings"=dword:00000001

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent]
"DisableThirdPartySuggestions"=dword:00000001
"DisableSoftLanding"=dword:00000001

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SoftLandingEnabled"=dword:00000000
"RotatingLockScreenEnabled"=dword:00000000
"RotatingLockScreenOverlayEnabled"=dword:00000000
"SubscribedContent-202914Enabled"=dword:00000000
"SubscribedContent-338387Enabled"=dword:00000000
"SubscribedContent-338389Enabled"=dword:00000000
"SubscribedContent-353698Enabled"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]
"SoftLandingEnabled"=dword:00000000
"RotatingLockScreenEnabled"=dword:00000000
"RotatingLockScreenOverlayEnabled"=dword:00000000
"SubscribedContent-202914Enabled"=dword:00000000
"SubscribedContent-338387Enabled"=dword:00000000
"SubscribedContent-338389Enabled"=dword:00000000
"SubscribedContent-353698Enabled"=dword:00000000
 
