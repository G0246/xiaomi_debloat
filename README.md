# Xiaomi Debloat

**Last updated: 03/12/2025**

## About

A curated list of apps from the **Xiaomi Pad 6 Pro** that can be safely disabled or uninstalled without disrupting system services.

### How to Use

To disable or uninstall these apps, you can use:
- **Android SDK Platform Tools** (ADB) - Official Android debugging tool
- **Universal Android Debloater** - GUI tool for debloating Android devices
- Other Android debloat applications of your choice

## Apps that I disabled

> **Note:** This list represents a conservative debloat configuration for the Chinese model Xiaomi Pad 6 Pro, optimized for international use with Google services. The selection prioritizes system stability while removing unnecessary bloatware.

| Name | Package | Description |
|------|---------|-------------|
| Analytics | com.miui.analytics | Who wants spyware? |
| Mi Game Service | com.xiaomi.migameservice | Not necessary for global games |
| Wireless display extension | com.xiaomi.miralink | Extends your screen to Windows computer, optional |
| Interconnectivity services | com.milink.service | For casting and device-to-device communication, disabled due to wasting background resources |
| Xiaomi HyperAI XiaoAi | com.miui.voiceassist | Not used to this voice assistant and not very useful to me |
| Xiaomi HyperAI Engine | com.xiaomi.aicr | XiaoAi components (LLMs), disabled due to wasting background resources |
| Game Service | com.xiaomi.gamecenter.sdk.service | Not necessary for global games |
| Device interconnectivity services | com.xiaomi.mirror | For screen mirroring, disabled due to infrequent use |
| Feedback | com.miui.bugreport | No comment, optional |



## Apps that are pre-disabled/hidden on a fresh install of Xiaomi Pad 6 Pro
| Name | Package | Description |
|------|---------|-------------|
| DeviceLockController | com.android.devicelockcontroller | Some kind of screen lock controller? |
| Nfc Service | com.android.nfc | Provides NFC service, no on board NFC |
| Package installer | com.android.packageinstaller | The Android package API that Xiaomi destroyed and replaced with their own |
| Family Guard | com.miui.greenguard | Provides parental controls, uninstall button just hides it from app list |
| Education Center | com.xiaomi.kidspace | Educational app, uninstall button just hides it from app list |

## Xiaomi/Oppo apps complete list

> **Note:** This list may not be complete even tho I have checked it one by one. App names and descriptions have been translated or fetched from official sources by me to the best of my ability. Some apps may not be available on global devices, and names may vary between MIUI and HyperOS3.

| Name | Package | Description |
| ------ | --------- | ------------- |
|  | android | Android system core package, provides basic system functions |
|  | android.aosp.overlay | AOSP (Android Open Source Project) overlay, provides basic functions for devices |
|  | android.miui.home.launcher.res | MIUI launcher resources, manages home screen and app drawer |
|  | android.miui.overlay | MIUI system UI overlay |
|  | android.overlay.common | Universal system overlay, applicable to general settings for multiple devices |
|  | android.overlay.target | Target device system overlay, provides device-specific functions |
|  | android.qvaoverlay.common | Universal QVA overlay, possibly related to video enhancement |
| Mi Doc Viewer (WPS Edition) | cn.wps.moffice_eng.xiaomi.lite |  |
|  | com.aiunit.aon | AI unit app |
|  | com.android.adservices.api | Advertising service API, supports ad-related functions |
|  | com.android.apps.tag | NFC tag management app |
|  | com.android.backupconfirm | Backup confirmation service, ensures backup operation security |
| Print Service | com.android.bips | Basic printing service, supports device printing functions |
| Bluetooth | com.android.bluetooth | Android Bluetooth service, manages device Bluetooth functions |
| Bluetooth MIDI Service | com.android.bluetoothmidiservice | Bluetooth MIDI service, supports MIDI connection for music devices |
| Bookmark Provider | com.android.bookmarkprovider |  |
| Browser | com.android.browser | System browser app |
| Calendar | com.android.calendar |  |
|  | com.android.calllogbackup | Call log backup service |
| Camera | com.android.camera | System camera app for taking photos and videos |
|  | com.android.camera.overlay | Camera app overlay, manages camera functions |
|  | com.android.cameraextensions | Camera extension service, provides enhanced camera functions |
| Captive Portal Login | com.android.captiveportallogin | Captive portal login service, supports authentication for public Wi-Fi |
|  | com.android.carrierconfig | Carrier configuration service, manages carrier-related config files |
|  | com.android.carrierconfig.overlay.common | Universal carrier config overlay |
|  | com.android.carrierconfig.overlay.miui | MIUI carrier config overlay |
|  | com.android.carrierconfig.overlay.product | Carrier config overlay app |
| Carrier Default App | com.android.carrierdefaultapp | Default carrier app, manages carrier-related settings |
|  | com.android.cellbroadcastreceiver | Emergency broadcast receiver, receives emergency broadcasts from government or carriers |
|  | com.android.cellbroadcastreceiver.overlay.common | Universal cellular broadcast receiver overlay service |
| Cell Broadcast Service | com.android.cellbroadcastservice | Cellular broadcast service, supports emergency broadcast functions |
| Certificate Installer | com.android.certinstaller | Certificate installer, manages device certificate installation and authentication |
| Companion Device Manager | com.android.companiondevicemanager | Companion device manager, manages connection and interaction with other devices |
|  | com.android.connectivity.resources | Handles device connectivity resources, may involve network and connection management |
|  | com.android.connectivity.resources.overlay.oplus | Connectivity resources overlay app |
| Contacts | com.android.contacts | Android contacts app, manages contact information |
|  | com.android.cts.ctsshim | Android Compatibility Test Suite (CTS) Shim app, supports device compatibility testing |
|  | com.android.cts.priv.ctsshim | CTS (Compatibility Test Suite) private component for compatibility testing |
| Clock | com.android.deskclock |  |
| DeviceLockController | com.android.devicelockcontroller | Android device lock controller, manages device lock and security features |
| Basic Interactive Screensaver | com.android.dreams.basic | Basic screensaver management |
| Photo Screensaver | com.android.dreams.phototable |  |
| Dynamic System Updates | com.android.dynsystem | Dynamic system service, supports dynamic system updates and switching |
| Email | com.android.email |  |
| Emergency Information | com.android.emergency | Emergency service, provides help in emergency situations |
| External Storage | com.android.externalstorage | External storage management service, manages SD cards and other external storage |
| File Manager | com.android.fileexplorer | File explorer, manages device files and directories |
|  | com.android.hotspot2.osulogin | Hotspot 2.0 login service, manages device Hotspot 2.0 connections |
| HTML Viewer | com.android.htmlviewer | HTML viewer for viewing HTML files on device |
| Phone | com.android.incallui | Incoming call UI, manages call interface display |
|  | com.android.incallui.overlay | Call UI overlay, manages call user interface |
| Input Devices | com.android.inputdevices | Input device management, supports connection of various input devices |
| Corner Notch | com.android.internal.display.cutout.emulation.corner | Corner cutout emulation service, adapts to devices with corner cutouts |
| Double Notch | com.android.internal.display.cutout.emulation.double | Double display cutout emulation service for simulating device screens with two cutouts |
| Punch Hole | com.android.internal.display.cutout.emulation.hole | Hole punch emulation service for single camera hole |
| Tall Notch | com.android.internal.display.cutout.emulation.tall | Tall cutout emulation service, adapts to devices with tall cutouts |
| Waterfall Notch | com.android.internal.display.cutout.emulation.waterfall | Waterfall screen emulation service, adapts to devices with waterfall screens |
| Gestural Navigation | com.android.internal.systemui.navbar.gestural | Internal system UI service for gesture navigation bar |
| Gestural Navigation | com.android.internal.systemui.navbar.gestural_extra_wide_back | Internal system UI service for extra-wide gesture navigation bar, provides wider back gesture |
| Gestural Navigation | com.android.internal.systemui.navbar.gestural_narrow_back | Internal system UI service for narrow gesture navigation bar |
| Gestural Navigation | com.android.internal.systemui.navbar.gestural_wide_back | Internal system UI service for wide gesture navigation bar |
| 3-Button Navigation | com.android.internal.systemui.navbar.threebutton | Internal system UI service for three-button navigation bar |
| Key Chain | com.android.keychain | System service for managing and storing encryption keys |
|  | com.android.localtransport | Local transport service, may be used for data transfer |
| Fused Location | com.android.location.fused | Fused location service, integrates multiple positioning methods to improve location accuracy |
| Work Setup | com.android.managedprovisioning | Device management provisioning service |
|  | com.android.managedprovisioning.overlay | Managed device configuration overlay |
| Messaging | com.android.mms | SMS app, manages device SMS and MMS functions |
|  | com.android.mms.service | SMS and MMS service, supports messaging functions |
|  | com.android.modulemetadata | Manages Android module metadata |
| MTP Host | com.android.mtp | Media Transfer Protocol (MTP) service, manages file transfer between device and computer |
| Network Manager | com.android.networkstack.inprocess | In-process network stack service, manages network connections |
|  | com.android.networkstack.overlay | Network stack overlay, manages network functions |
|  | com.android.networkstack.tethering.inprocess | Network sharing (hotspot) service processing |
| Nfc Service | com.android.nfc | Android NFC service, provides Near Field Communication functionality |
|  | com.android.ondevicepersonalization.services | On-device personalization service, provides personalized recommendations and settings |
|  | com.android.ons | ONS (Operator Network Service), manages device network connections |
|  | com.android.overlay.cngmstelecomm | China-customized Google Mobile Services telecom overlay |
|  | com.android.overlay.gmscontactprovider | Overlay service providing Google Mobile Services (GMS) contact-related functions |
|  | com.android.overlay.gmssettingprovider | Google Mobile Services settings provider overlay |
|  | com.android.overlay.gmssettings | Google Mobile Services settings overlay |
|  | com.android.overlay.gmstelecomm | Google Mobile Services communication overlay, manages communication-related Google services |
|  | com.android.overlay.gmstelephony | Google Mobile Services telephony overlay |
|  | com.android.overlay.systemui | System UI overlay, manages interface display |
| Package installer | com.android.packageinstaller | Android package installer, handles APK installation and management |
|  | com.android.pacprocessor | PAC (Proxy Auto-Config) processor, manages network proxy configuration |
| Permission Controller | com.android.permissioncontroller | Permission controller, manages app permission requests and allocation |
| Phone Services | com.android.phone | Phone app, manages device phone functions |
|  | com.android.phone.overlay.common | Universal phone app overlay, manages device phone functions |
|  | com.android.phone.overlay.miui | MIUI phone app overlay, customizes phone-related UI and functions |
| Print Spooler | com.android.printspooler | Print spooler service, manages device printing functions |
| Homescreen Tips | com.android.protips |  |
| Blocked Numbers Storage | com.android.providers.blockednumber | Content provider for managing blocked numbers |
| Calendar Storage | com.android.providers.calendar | Calendar content provider, manages calendar and events |
| Contacts Storage | com.android.providers.contacts | System contacts provider, manages contacts database |
| Downloads | com.android.providers.downloads | System download manager, manages file downloads |
| Download Manager | com.android.providers.downloads.ui |  |
|  | com.android.providers.media | Media content provider, manages media file storage and access |
| Media Storage | com.android.providers.media.module | Media content provider module, manages media file storage and access |
| Settings Storage | com.android.providers.settings | Settings provider, manages system settings storage and access |
|  | com.android.providers.settings.overlay | Settings provider overlay, manages system settings storage and access |
| Telephony Storage | com.android.providers.telephony | Telephony provider, manages device phone and SMS functions |
| User Dictionary | com.android.providers.userdictionary | User dictionary provider, manages user-defined vocabulary |
| Setup Wizard | com.android.provision | Provisioning service, supports device initial setup and configuration |
|  | com.android.proxyhandler | Proxy handler service, manages network proxy settings |
| Quick Search Box | com.android.quicksearchbox | Quick search box, provides quick search function on device |
|  | com.android.remoteprovisioner | Remote provisioner service, supports remote device management |
|  | com.android.safetycenter.resources | Safety center resources, supports device security functions |
|  | com.android.sdksandbox | SDK sandbox, provides app development testing environment |
|  | com.android.se | Secure element service, manages device secure elements (e.g., SIM card, NFC) |
|  | com.android.se.overlay.target | Secure element (SE) overlay, manages device security functions |
| Call Management | com.android.server.telecom | Telecom service, manages device communication functions |
|  | com.android.server.telecom.overlay.common | Universal telecom service overlay |
|  | com.android.server.telecom.overlay.miui | MIUI-customized telecom service overlay |
| Settings | com.android.settings | System settings app, manages various device settings |
|  | com.android.settings.intelligence | Smart settings service, provides intelligent suggestions and auto-configuration |
|  | com.android.settings.overlay.common | Universal settings overlay, manages device settings interface and functions |
|  | com.android.settings.overlay.miui | MIUI-customized settings app overlay |
|  | com.android.sharedstoragebackup | Shared storage backup service |
|  | com.android.shell | System shell command-line tool |
|  | com.android.simappdialog | SIM app dialog service, manages SIM card-related settings dialogs |
|  | com.android.smspush | SMS push service, supports SMS push and reception |
| Sound Picker | com.android.soundpicker |  |
| Sound Recorder | com.android.soundrecorder |  |
|  | com.android.statementservice | Service for statement files |
| SIM Toolkit | com.android.stk | SIM card toolkit service, supports carrier SIM card functions |
|  | com.android.stk.overlay.miui | STK (SIM Toolkit) service overlay in MIUI, manages SIM toolkit functions |
| Storage Manager | com.android.storagemanager | Storage manager, manages device storage space |
| System UI | com.android.systemui | System UI, manages system user interface |
|  | com.android.systemui.gesture.line.overlay | System gesture line overlay, provides gesture navigation functions |
|  | com.android.systemui.navigation.bar.overlay | Navigation bar overlay, manages system navigation bar style |
|  | com.android.systemui.overlay.charging.anim.siphon_wireless | Wireless charging animation overlay for SystemUI app |
|  | com.android.systemui.overlay.common | Universal system UI overlay, applicable to UI settings for multiple devices |
|  | com.android.systemui.overlay.miui | MIUI system UI overlay, customizes system user interface |
| Black Theme | com.android.theme.color.black |  |
| Cinnamon Theme | com.android.theme.color.cinnamon |  |
|  | com.android.theme.font.notoserifsource | Noto Serif font theme pack |
| Circular Icon Pack | com.android.theme.icon_pack.circular.android |  |
| Circular Icon Pack | com.android.theme.icon_pack.circular.launcher |  |
| Circular Icon Pack | com.android.theme.icon_pack.circular.settings |  |
| Circular Icon Pack | com.android.theme.icon_pack.circular.systemui |  |
| Circular Icon Pack | com.android.theme.icon_pack.circular.themepicker |  |
| Filled Icon Pack | com.android.theme.icon_pack.filled.android |  |
| Filled Icon Pack | com.android.theme.icon_pack.filled.launcher |  |
| Filled Icon Pack | com.android.theme.icon_pack.filled.settings |  |
| Filled Icon Pack | com.android.theme.icon_pack.filled.systemui |  |
| Filled Icon Pack | com.android.theme.icon_pack.filled.themepicker |  |
| Themes | com.android.thememanager | Theme manager, manages device theme and appearance settings |
| System Tracing | com.android.traceur | Traceur is a debugging tool in Android for recording system trace information |
| System Updates | com.android.updater | System update manager, responsible for software updates |
|  | com.android.uwb.resources | Ultra-wideband (UWB) resource service, manages UWB communication functions |
| Google Play Store | com.android.vending | Google Play Store app, provides app download and update services |
|  | com.android.vpndialogs | VPN dialogs service, manages VPN connection user interface |
|  | com.android.wallpaper.livepicker | Live wallpaper picker, manages live wallpaper settings |
|  | com.android.wallpaperbackup | Wallpaper backup service, saves and restores wallpaper settings |
|  | com.android.wallpapercropper | Wallpaper cropper tool, adjusts wallpaper size to fit screen |
|  | com.android.wifi.dialog | Wi-Fi dialog service, manages Wi-Fi connection user interface |
| WLAN Resources | com.android.wifi.resources | Wi-Fi resource service, manages device Wi-Fi connections |
|  | com.android.wifi.resources.overlay.common | Universal Wi-Fi resource overlay, manages device Wi-Fi connections and settings |
|  | com.android.wifi.resources.overlay.kalama | Wi-Fi resource overlay for Kalama devices |
|  | com.android.wifi.resources.overlay.target | Wi-Fi resource overlay, customizes device Wi-Fi settings |
|  | com.android.wifi.resources.xiaomi | Xiaomi Wi-Fi resource management |
| Baidu Maps | com.baidu.BaiduMap |  |
| Baidu Input (Mi Edition) | com.baidu.input_mi |  |
| Baidu | com.baidu.searchbox |  |
| Catch Log | com.bsp.catchlog | BSP log capture tool for debugging and error reporting |
|  | com.coloros.video | ColorOS video app |
| Tomato Novel | com.dragon.read |  |
| Universal Remote | com.duokan.phone.remotecontroller |  |
| Reader | com.duokan.reader |  |
| Alipay | com.eg.android.AlipayGphone |  |
| FIDO UAF ASM | com.fido.asm | FIDO (Fast IDentity Online) authentication module, supports biometric authentication |
|  | com.fido.uafclient | FIDO UAF client app |
| FIDO UAF Client | com.fido.xiaomi.uafclient |  |
| Fingerprint Extension | com.fingerprints.extension.service |  |
| GF Manager | com.goodix.fingerprint |  |
|  | com.goodix.fingerprint.setting | Goodix fingerprint settings service, manages fingerprint recognition functions |
| Fingerprint Test | com.goodix.gftest |  |
|  | com.google.android.cellbroadcastreceiver.overlay.miui | Google emergency broadcast receiver overlay in MIUI |
|  | com.google.android.cellbroadcastservice.overlay.miui | Google emergency broadcast service overlay in MIUI |
| Config Updater | com.google.android.configupdater | Google config updater, updates configuration files on device |
| Files | com.google.android.documentsui | Google document UI for file management and operations |
| Android Services Library | com.google.android.ext.services | Google extension services, provides additional functions and support for Android |
| Android Shared Library | com.google.android.ext.shared | Google shared extension services, supports sharing functions |
| Google Play Services | com.google.android.gms | Google Play Services, provides Google-related core services |
|  | com.google.android.gms.location.history | Google location history service |
| Google Services Framework | com.google.android.gsf | Google Services Framework, supports infrastructure for Google Play and other Google services |
| Android Accessibility Suite | com.google.android.marvin.talkback | Google TalkBack service, provides voice feedback for visually impaired users |
| Google One Time Init | com.google.android.onetimeinitializer | Google one-time init service for setting up initial device configuration |
|  | com.google.android.overlay.gmsconfig | Google Mobile Services configuration overlay service |
|  | com.google.android.overlay.modules.ext.services | Google extension service module overlay, provides extension functions related to Google services |
|  | com.google.android.printservice.recommendation | Google print service recommendation, supports device printing functions |
| Google Contacts Sync | com.google.android.syncadapters.contacts |  |
| Android System WebView | com.google.android.webview | Google WebView component for displaying web content in apps |
|  | com.heytap.tas | HeyTap TAS app |
|  | com.ifaa.seccam | IFAA (Internet Finance Authentication Alliance) secure camera service for security authentication |
| iFlytek Input (Mi Edition) | com.iflytek.inputmethod.miui |  |
| Permissions | com.lbe.security.miui | LBE security service, provides MIUI security protection functions |
| Mi Wallpaper Carousel | com.mfashiongallery.emag |  |
| Health | com.mi.health |  |
| Mi Live Assistant | com.mi.liveassistant |  |
| Interconnectivity services | com.milink.service | Xiaomi device interconnectivity service, supports casting and device-to-device communication |
| Mi Wallet | com.mipay.wallet |  |
| Mi Sound | com.miui.accessibility | MIUI accessibility service, supports device use for disabled users |
| Analytics | com.miui.analytics | MIUI analytics service, collects usage data and statistics |
|  | com.miui.aod | MIUI always-on display feature, shows lock screen clock and notifications |
| Audio Effect | com.miui.audioeffect | MIUI audio effect management service, provides audio enhancement and configuration |
|  | com.miui.audiomonitor | Audio monitoring service, may be used for recording or audio analysis |
| Backup | com.miui.backup | MIUI backup service, supports data backup and recovery |
| Feedback | com.miui.bugreport | MIUI feedback and bug report service, allows users to submit feedback and reports |
| Calculator | com.miui.calculator |  |
|  | com.miui.carlink | MIUI car link service |
|  | com.miui.catcherpatch | MIUI catcher patch service, may be used for catching errors or data |
| CIT | com.miui.cit | MIUI CIT (hardware detection tool) for device hardware testing |
| Cleaner | com.miui.cleanmaster |  |
| Launcher Cloud Backup | com.miui.cloudbackup | MIUI cloud backup service, supports cloud data backup |
| Mi Cloud | com.miui.cloudservice | MIUI cloud service, supports data cloud sync and backup |
| Cloud Service Sysbase | com.miui.cloudservice.sysbase |  |
| Compass | com.miui.compass |  |
| Content Catcher | com.miui.contentcatcher | MIUI content catcher service, may be used for intelligent content recognition and operation |
| Content Extension | com.miui.contentextension | MIUI content extension service, supports content extension functions |
|  | com.miui.core | MIUI core service, provides basic system function support |
|  | com.miui.daemon | MIUI daemon, may be used for system monitoring and performance optimization |
|  | com.miui.dmregservice | MIUI device management registration service |
| Bokeh | com.miui.extraphoto | MIUI extra photo service, may be used for photo management or editing |
|  | com.miui.face.overlay.miui | MIUI face recognition overlay |
| FM Radio | com.miui.fm |  |
| FM Service | com.miui.fmservice |  |
| Floating Windows | com.miui.freeform | MIUI freeform mode service, supports multitasking operations |
| Gallery | com.miui.gallery |  |
| Family Guard | com.miui.greenguard | MIUI parental control service, provides family protection and child safety features |
| MIUI Security Component | com.miui.guardprovider | MIUI guard provider app, provides security protection functions |
| System Launcher | com.miui.home | MIUI home app, manages device home screen and app layout |
| Mi Mover | com.miui.huanji |  |
| Quick Apps | com.miui.hybrid | MIUI hybrid app framework, supports hybrid app development and operation |
| Smart Life | com.miui.hybrid.accessory | MIUI hybrid accessory service, supports hybrid app development and operation |
| Repair Mode | com.miui.maintenancemode | MIUI maintenance mode, used for device maintenance or troubleshooting |
|  | com.miui.mediaviewer | MIUI media viewer for viewing photos, videos and other content |
|  | com.miui.micloudsync | MIUI cloud sync service, supports data synchronization in cloud |
|  | com.miui.miinput | MIUI input method, provides text input functions |
| Services & Feedback | com.miui.miservice | MIUI service, may involve device connection with MIUI account |
| Mi Share | com.miui.mishare.connectivity | MIUI Mi Share connectivity service, supports fast file sharing |
| Sound Enhancement | com.miui.misound | MIUI audio effect management service, provides audio enhancement and configuration |
|  | com.miui.miwallpaper | MIUI wallpaper management service, provides live wallpaper and theme functions |
|  | com.miui.miwallpaper.overlay.customize | Custom wallpaper overlay service |
|  | com.miui.miwallpaper.wallpaperoverlay.config.overlay | MIUI wallpaper overlay, manages wallpaper settings and configuration |
| Content Center | com.miui.newhome |  |
| Mi Drive | com.miui.newmidrive |  |
| Mi Pay | com.miui.nextpay | MIUI payment service, supports next-generation payment technology |
| Notes | com.miui.notes |  |
| Notifications | com.miui.notification | MIUI notification management service, handles system notifications |
|  | com.miui.otaprovision | MIUI OTA (Over-The-Air) provisioning service, manages system OTA updates |
| Package Installer | com.miui.packageinstaller | MIUI package installer, manages app installation and updates |
| App Vault | com.miui.personalassistant | MIUI personal assistant, provides smart assistant functions |
| Frequent Phrases | com.miui.phrase | MIUI phrase management service, may be used for input method phrase functions |
| Music | com.miui.player |  |
| Battery & Performance | com.miui.powerkeeper | Battery management, optimizes battery usage and life |
|  | com.miui.privacycomputing | MIUI privacy computing, protects user privacy and data |
| CIT QR | com.miui.qr | MIUI QR code service, manages QR code generation and scanning |
|  | com.miui.rom | MIUI ROM management service, may involve firmware updates or management |
| Screen Recorder | com.miui.screenrecorder |  |
| Screenshot | com.miui.screenshot | MIUI screenshot service, supports device screenshot functions |
| System Service Component | com.miui.securityadd | MIUI security add-on, provides additional security protection |
| Security | com.miui.securitycenter | MIUI security center, provides system security protection functions |
| Security Core | com.miui.securitycore | MIUI security core service, protects system security |
| Mi Security Keyboard | com.miui.securityinputmethod | MIUI secure input method, provides secure text input functions |
|  | com.miui.settings.rro.device.hide.statusbar.overlay | Hide status bar overlay service |
|  | com.miui.settings.rro.device.systemui.overlay | MIUI settings system UI overlay |
|  | com.miui.settings.rro.device.type.overlay | MIUI settings device type overlay |
| Smart Travel | com.miui.smarttravel |  |
|  | com.miui.system | MIUI system core, provides basic system functions and services |
|  | com.miui.system.overlay | MIUI system overlay, customizes system user interface and functions |
| MSA | com.miui.systemAdSolution | MIUI system ad solution, may be used for ad display and management |
|  | com.miui.systemui.carriers.overlay | MIUI carrier UI overlay, customizes carrier-related UI |
|  | com.miui.systemui.devices.overlay | MIUI device UI overlay, customizes UI for different devices |
|  | com.miui.systemui.overlay.devices.android | MIUI device system UI overlay |
| Third-party App Exception Analysis | com.miui.thirdappassistant |  |
| Quick Ball | com.miui.touchassistant | MIUI touch assistant, provides quick action functions |
|  | com.miui.translation.kingsoft | Kingsoft dictionary MIUI-customized translation service |
|  | com.miui.translation.xmcloud | Xiaomi cloud translation service, supports translation functions |
|  | com.miui.translationservice | MIUI translation service, supports text translation functions |
| Mi Smart Card | com.miui.tsmclient | Supports NFC payment and security management |
|  | com.miui.uireporter | MIUI UI reporter for collecting UI usage data |
| Mi Video | com.miui.video |  |
|  | com.miui.vipservice | MIUI VIP service, provides premium services or support for users |
| Global Roaming | com.miui.virtualsim |  |
| Xiaomi HyperAI XiaoAi | com.miui.voiceassist | Xiaomi voice assistant service, provides voice control and AI assistant functions |
|  | com.miui.voiceassistoverlay | MIUI voice assistant overlay, supports voice assistant functions |
| Voice Wakeup | com.miui.voicetrigger | MIUI voice trigger service, supports voice wake-up for device |
|  | com.miui.vpnsdkmanager | VPN SDK management, supports VPN functions |
|  | com.miui.vsimcore | MIUI virtual SIM core service, manages virtual SIM card functions |
|  | com.miui.wallpaper.overlay.customize | MIUI wallpaper customization overlay, supports personalized wallpaper settings |
| Weather | com.miui.weather2 |  |
|  | com.miui.wmsvc | MIUI wireless management service, manages wireless connections and device communication |
| Yellow Pages | com.miui.yellowpage | MIUI yellow pages service, provides phone book and business information |
|  | com.miuix.editor | MIUI editor for editing images or videos |
|  | com.mobiletools.systemhelper | System helper tool, may provide system optimization and management functions |
|  | com.modemdebug | Modem debug tool for debugging mobile communication modules |
|  | com.oplus.account | Account app |
|  | com.oplus.aiunit--AIUnit | AIUnit app |
|  | com.oplus.athena | Athena app |
|  | com.oplus.atlas--AtlasService | Atlas service app |
|  | com.oplus.consumerIRApp | Consumer IR app |
|  | com.oplus.customize.coreapp | Customize core app |
|  | com.oplus.eid | EID app |
|  | com.oplus.ether | Ether app |
|  | com.oplus.framework.rro.oppo | Oppo framework resource overlay app |
|  | com.oplus.framework_bluetooth.overlay | Bluetooth framework overlay app |
|  | com.oplus.interconnectcollectkit | Internet collect kit app |
|  | com.oplus.lfeh | LFEH app |
|  | com.oplus.matter | Matter app |
|  | com.oplus.metis | Metis app |
|  | com.oplus.nas | NAS app |
|  | com.oplus.ndsf | NDSF app |
|  | com.oplus.nrMode | NR mode app |
|  | com.oplus.obrain | OBrain app |
|  | com.oplus.ocloud | OCloud app |
|  | com.oplus.olc | OLC app |
|  | com.oplus.onetrace | OneTrace app |
|  | com.oplus.pantanal.ums | Pantanal UMS app |
|  | com.oplus.powermonitor | Power monitor app |
|  | com.oplus.qualityprotect | Quality protect app |
|  | com.oplus.sauhelper | SAU helper app |
|  | com.oplus.smartengine | Smart engine app |
|  | com.oplus.stdsp | Stdsp app |
|  | com.oplus.subsys | Subsystem app |
|  | com.oplus.themestore | Theme store app |
|  | com.oplus.vdc | VDC app |
|  | com.oplus.viewtalk | ViewTalk app |
|  | com.oplus.vip | VIP app |
|  | com.oplus.virtualcomm | Virtual comm app |
|  | com.oplus.wifibackuprestore | WiFi backup and restore app |
|  | com.oplus.wifitest | WiFi test app |
|  | com.oppo.community | Oppo community app |
|  | com.oppo.insta | Oppo Insta app |
|  | com.oppo.instant.local.service--Deliver | Server - Local delivery server app |
| iQIYI | com.qiyi.video |  |
| Conference URI Dialer | com.qti.confuridialer |  |
|  | com.qti.dcf | Qualcomm DCF (Dynamic Color Filter) service, optimizes display |
|  | com.qti.diagservices | Qualcomm diagnostic service, may be used for device troubleshooting |
|  | com.qti.dpmserviceapp | Qualcomm device policy management service |
|  | com.qti.phone | Qualcomm phone-related service, supports phone functions |
|  | com.qti.qcc | Qualcomm QCC service, may be used for device fast charging |
|  | com.qti.qualcomm.datastatusnotification | Qualcomm data status notification service |
| Device Info | com.qti.qualcomm.deviceinfo | Qualcomm device info service, provides device hardware and software information |
|  | com.qti.service.colorservice | Qualcomm color management service, optimizes display |
|  | com.qti.snapdragon.qdcm_ff | Qualcomm Snapdragon display calibration management service, optimizes device display |
| X-Divert | com.qti.xdivert |  |
|  | com.qualcomm.atfwd | Qualcomm remote AT command forwarding service |
|  | com.qualcomm.embms | Qualcomm eMBMS service, supports enhanced multicast broadcast service |
|  | com.qualcomm.location | Qualcomm location service, supports device positioning functions |
|  | com.qualcomm.qcrilmsgtunnel | Qualcomm QCRIL message tunnel service, manages message transmission |
|  | com.qualcomm.qti.autoregistration | Qualcomm auto-registration service, may be used for automatic device network or service registration |
|  | com.qualcomm.qti.biometrics.fingerprint.service | Qualcomm biometric fingerprint service, manages fingerprint recognition functions |
| CNE App | com.qualcomm.qti.cne | Qualcomm connectivity engine, optimizes network connections |
|  | com.qualcomm.qti.confdialer | Qualcomm conference dialer service |
|  | com.qualcomm.qti.devicestatisticsservice | Device statistics service, collects and analyzes device usage data |
|  | com.qualcomm.qti.dynamicddsservice | Qualcomm dynamic data service, manages multi-SIM card data connections |
|  | com.qualcomm.qti.gpudrivers.kalama.api33 | Qualcomm Kalama device GPU driver API 33 |
| Adreno Graphics Drivers | com.qualcomm.qti.gpudrivers.lito.api30 |  |
|  | com.qualcomm.qti.lpa | Qualcomm local personal assistant service |
| Performance Mode | com.qualcomm.qti.performancemode | Qualcomm performance mode service, optimizes device performance |
| Power Off Alarm | com.qualcomm.qti.poweroffalarm | Qualcomm power-off alarm service, supports alarm function when device is powered off |
|  | com.qualcomm.qti.powersavemode | Qualcomm power save mode service, manages device power saving functions |
|  | com.qualcomm.qti.qcolor | Qualcomm QColor service, manages color configuration |
|  | com.qualcomm.qti.qms.service.trustzoneaccess | Qualcomm trust zone access service, manages device trust zone functions |
|  | com.qualcomm.qti.remoteSimlockAuth | Qualcomm remote SIM lock authentication service |
|  | com.qualcomm.qti.ridemodeaudio | Qualcomm ride mode audio service |
| QtiWifiService | com.qualcomm.qti.server.qtiwifi | Qualcomm Wi-Fi service, manages device Wi-Fi functions |
| SIM Contacts | com.qualcomm.qti.simcontacts |  |
|  | com.qualcomm.qti.telephonyservice | Qualcomm telephony service, manages phone communication-related functions |
|  | com.qualcomm.qti.uceShimService | Qualcomm UCE (Unified Communication Enhancement) service |
|  | com.qualcomm.qti.uim | Qualcomm UIM (User Identity Module) service, manages SIM card functions |
|  | com.qualcomm.qti.uimGbaApp | Qualcomm UIM GBA (Generic Bootstrapping Architecture) app |
|  | com.qualcomm.qti.workloadclassifier | Qualcomm workload classifier, optimizes device performance and resource allocation |
|  | com.qualcomm.qti.xrcb | Qualcomm XRCB service, may be related to augmented reality (AR) |
|  | com.qualcomm.qtil.btdsda | Qualcomm Bluetooth service (BTDSDA), manages device Bluetooth connections |
|  | com.qualcomm.timeservice | Qualcomm time service, manages device time synchronization |
|  | com.qualcomm.uimremoteclient | Qualcomm remote UIM (User Identity Module) client, manages SIM card functions |
|  | com.qualcomm.uimremoteserver | Qualcomm remote SIM management service |
|  | com.qualcomm.wfd.service | Qualcomm wireless display service, supports wireless display functions like Miracast |
|  | com.quicinc.voice.activation | Qualcomm voice activation service, supports voice wake-up functions |
| eID Service | com.rongcard.eid | Rongcard eID service, may be used for identity verification |
|  | com.rongcard.eidapi | Rongcard EID API app |
| Weibo | com.sina.weibo | A Chinese microblogging (weibo) app |
| Sogou Input (Mi Edition) | com.sohu.inputmethod.sogou.xiaomi | Sogou input method Xiaomi edition, provides text input functions |
| Toutiao (News App) | com.ss.android.article.news | Chinese news and information content platform |
| Douyin (TikTok) | com.ss.android.ugc.aweme | A Chinese social media and short-form online video platform |
| Taote (Taobao Deals) | com.taobao.litetao | Another variant of Taobao |
| Taobao | com.taobao.taobao | A Chinese online shopping platform |
| Tencent Video | com.tencent.qqlive |  |
|  | com.tencent.soter.soterserver | Tencent Soter service, supports security authentication and payment functions |
| UC Browser | com.UCMobile |  |
| UnionPay TSM (Mi Edition) | com.unionpay.tsmservice.mi | Xiaomi UnionPay TSM (Trusted Service Manager) service, supports UnionPay payments |
| WAPI Certificate | com.wapi.wapicertmanage | WAPI (WLAN Authentication and Privacy Infrastructure) authentication management |
| Mi Store System Component | com.xiaomi.ab |  |
| Mi Account | com.xiaomi.account | Xiaomi account management, supports account login and sync |
| AI Assistant | com.xiaomi.aiasst.service | Xiaomi AI assistant service, provides AI assistant functions |
| AI Assistant Vision | com.xiaomi.aiasst.vision | Xiaomi AI assistant vision service, supports AI assistant visual recognition functions |
| Xiaomi HyperAI Engine | com.xiaomi.aicr | Xiaomi AI engine service, provides AI processing and LLM capabilities |
|  | com.xiaomi.aireco | Xiaomi AI recommendation service, provides personalized content recommendations |
|  | com.xiaomi.aon | Xiaomi always-on-display service, manages screen always-on display functions |
|  | com.xiaomi.barrage | Xiaomi barrage service, may be used for bullet screen functions in videos or live streams |
|  | com.xiaomi.bluetooth | Xiaomi Bluetooth service, manages device Bluetooth functions |
| Satellite Positioning | com.xiaomi.bsp.gps.nps |  |
| Camera Calibration | com.xiaomi.cameratools | Xiaomi camera tools, provides advanced camera functions and settings |
| digitalkey | com.xiaomi.digitalkey | Xiaomi digital key service, may be used for smart home or car unlocking |
| Driving Mode | com.xiaomi.drivemode |  |
| Find Device | com.xiaomi.finddevice | Xiaomi find device service, helps users locate lost devices |
| Game Center | com.xiaomi.gamecenter |  |
| Game Service | com.xiaomi.gamecenter.sdk.service | Xiaomi game center SDK service, provides game-related functions and optimizations |
|  | com.xiaomi.gnss.polaris | Xiaomi GNSS (Global Navigation Satellite System) service |
| Joyose | com.xiaomi.joyose | Xiaomi entertainment or game-related service |
| Tianxing Finance | com.xiaomi.jr |  |
| Education Center | com.xiaomi.kidspace | Xiaomi kids mode and educational content service for children |
| Fused Location Service | com.xiaomi.location.fused | Xiaomi fused location service, integrates multiple positioning methods to improve location accuracy |
| MiMacro | com.xiaomi.macro | Xiaomi macro service, may be used for automated task management |
| GetApps | com.xiaomi.market | Xiaomi app market, provides app download and update services |
| Network Location | com.xiaomi.metoknlp | Xiaomi location service, may be related to NLP (Natural Language Processing) |
| Mi Connect Service | com.xiaomi.mi_connect_service | Xiaomi Mi Connect service, manages connections between Xiaomi devices |
| System TTS Engine | com.xiaomi.mibrain.speech |  |
| com.xiaomi.micloudsdk.SdkApplication | com.xiaomi.micloud.sdk | Xiaomi cloud service SDK, supports cloud storage and sync |
| Mi Game Service | com.xiaomi.migameservice | Xiaomi game service, provides game optimization and management functions |
| Mi Cast | com.xiaomi.miplay_client |  |
| Wireless display extension | com.xiaomi.miralink | Xiaomi Miracast service, extends screen to external displays including Windows computers |
|  | com.xiaomi.mircs | Xiaomi IRC (Internet Relay Chat) service |
| Device interconnectivity services | com.xiaomi.mirror | Xiaomi screen mirroring service, enables wireless display to other devices |
| Xiaomi Connected Car Service | com.xiaomi.mis | Xiaomi connected car service application |
| Mi Settings | com.xiaomi.misettings | Xiaomi settings service, manages device system settings |
| Modem Test | com.xiaomi.mtb | Xiaomi MTB service, may be related to Xiaomi toolkit |
| otrpbroker | com.xiaomi.otrpbroker | Xiaomi OTRP (One-Time Password) broker service, manages one-time password functions |
| Mi Credit Payment | com.xiaomi.payment | Xiaomi payment app, supports Xiaomi payment services |
| Power Checker | com.xiaomi.powerchecker |  |
| Scanner | com.xiaomi.scanner |  |
| Mi Store | com.xiaomi.shop |  |
| Mi SIM Activation | com.xiaomi.simactivate.service | Xiaomi SIM card activation service |
| Mi Home | com.xiaomi.smarthome |  |
|  | com.xiaomi.touchservice | Xiaomi touch service, manages touchscreen interaction |
| Mi Community | com.xiaomi.vipaccount |  |
|  | com.xiaomi.xaee | Xiaomi XAEE service, may be related to security or privacy protection |
| Mi Service Framework | com.xiaomi.xmsf | Xiaomi push service framework, supports push notification functions |
|  | com.xiaomi.xmsfkeeper | Xiaomi message service keeper, maintains normal operation of messaging services |
| Youpin | com.xiaomi.youpin |  |
| Pinduoduo | com.xunmeng.pinduoduo |  |
|  | miui.systemui.plugin | MIUI system UI plugin, provides extended UI functions |
|  | oplus.frameworkres.overlay.display.product | Display product resource overlay app |
|  | org.codeaurora.ims | Code Aurora IMS service, supports IP Multimedia Subsystem functions |
|  | org.ifaa.aidl.manager | IFAA (Internet Finance Authentication Alliance) AIDL manager service, supports identity authentication functions |
|  | org.mipay.android.manager | Xiaomi payment manager, manages Xiaomi payment-related functions |
|  | vendor.qti.hardware.cacert.server | Qualcomm hardware CA certificate server, manages device certificate authentication |
|  | vendor.qti.imsrcs | Qualcomm IMS RCS service, supports enhanced messaging services |
|  | vendor.qti.iwlan | Qualcomm IWLAN (Integrated Wireless LAN) service, manages wireless network connections |
|  | vendor.qti.qesdk.sysservice | Qualcomm device SDK system service app |

## Credits

Huge thanks to the following contributors for helping to complete and verify this list:

- **startx** - Partial debloat entries from Zhihu
- **篮橙** - Provides original MIUI 14 app list from CSDN blog

---

## Disclaimer

**⚠️ USE AT YOUR OWN RISK**

I am not responsible for any damages, issues, or problems that may occur to your device as a result of using this list. Disabling or uninstalling system apps may cause unexpected behavior or system instability. It is your responsibility to decide whether to proceed with debloating your device.

Always create a backup before making any system modifications.
