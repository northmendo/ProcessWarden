# Process Warden FAQ

## What is Process Warden?
Process Warden is a premium Android utility for force-stopping apps, automating cleanup, and managing Android background restrictions. It is meant for power users who want direct control instead of generic task-killer behavior.

## Is this the same as Appzuku?
No. Process Warden is the maintained successor to Appzuku. It keeps the core workflow but uses a newer Kotlin/Compose codebase, a proper licensing model, OTA updates, and expanded background-restriction tools.

## Who is this app for?
It is for users who already know they want this kind of control. If you do not understand Root or Shizuku, this is probably not the right app for you.

## Do I need Root or Shizuku?
Yes, for kill actions and background restriction features. The app needs either Root or Shizuku shell access to actually stop apps or change restriction state.

## Does the app work without Root or Shizuku?
Some screens still open, but the main kill and restriction features will not function. Buying the app without one of those permissions is not useful.

## What does the home-screen shortcut do?
It kills the app you were just in before invoking the shortcut. It is designed for launcher shortcuts and gesture mappings that trigger the shortcut from the home surface.

## Why does the shortcut sometimes need recents instead of the current foreground app?
When a launcher or gesture invokes the shortcut, Android often puts the launcher in front by the time the shortcut activity runs. Process Warden resolves the previous app from recents so it kills the right target instead of the launcher or itself.

## What can the app kill?
You can kill a single app, multiple selected apps, the current foreground app, or a configured background-kill set. The app also supports widget, tile, and automation-based kill flows.

## Does selection mode reorder the list?
No. When you select apps, the list keeps its current order so it is easier to compare entries. Search also stays available while multi-select is active.

## Can it run automatically?
Yes. You can run periodic cleanup, screen-off cleanup, and RAM-threshold-gated cleanup. The app can also restore its automation state after boot.

## What are background restrictions?
Process Warden can save a list of apps that should stay background-restricted, reapply them later, and verify whether Android drifted away from the saved state.

## What is Temporary Restriction Lift?
It temporarily exempts selected restricted apps for a defined window, then restores restrictions automatically afterward. It is useful when you need an app to run briefly without losing your saved restriction setup.

## How does licensing work?
The app is commercial and license-gated. You buy or trial it through Polar, then activate the device with your license key. There is also offline grace after a successful validation.

## Can I move my license to another device?
Yes, but device limits depend on the tier you bought. If you have already used all of your activation slots, deauthorize an old device first in the Polar customer portal, then activate the new one: https://polar.sh/northmendo-tech-services/portal

## Does the app need internet access?
Yes, for license validation, periodic revalidation, Polar portal access to get your keys, and OTA update checks. Offline use works for up to 14 days before the app needs to check whether your license is still valid.

## How do updates work?
The app checks GitHub Releases for updates, downloads the APK, and then hands off to the installer through an in-app update flow.

## Can I back up my settings?
Yes. You can export and import Process Warden backups, and you can also import legacy Appzuku backups.

## Does the backup include my automation token?
No. The automation API token is intentionally kept out of backups.

## Can I use Tasker or MacroDroid?
Yes, if you enable the external automation API in Settings and supply the correct auth token.

## What if a kill action fails?
The usual reasons are missing Root/Shizuku permission, an invalid package target, or a device state that prevents shell execution. The app shows a message instead of pretending the action succeeded.

## How do I learn the app?
The first launch can show a short App Tour. You can reopen it later from `Settings` under `Help & Links`, alongside the written `How Process Warden works` guide.

## Why does back not immediately exit the app?
Process Warden routes back to `Apps` first and then asks for a few root back presses before it exits. That is deliberate, so you do not leave the app by accident.

## Is this app safe to use on system apps?
You can expose system apps in the UI, but killing or restricting the wrong system component can break notifications, widgets, keyboards, VPNs, accessibility services, or device stability. Use it carefully.

## Do you support refunds?
Refunds are handled case by case, but I generally do not offer refunds because the checkout flow includes a trial period when available.

## Where do I get help?
Use the issue tracker on the current GitHub repository for product issues. Billing, trial, subscription, and device-management support goes through the Polar portal.

## Why is the app premium?
Because it depends on ongoing maintenance, licensing, update delivery, and support. This is not a free consumer app with one-time functionality.

## Is the app stable?
It is actively developed and I test each release, but occasional bugs can still happen. I try to catch them before publishing, and I keep older known-good releases on GitHub so you can roll back if needed.

## What should I check before buying?
Make sure you know whether you will use Root or Shizuku, confirm your device is supported, and understand that the app is for deliberate app/process control rather than casual one-tap cleanup.

## Can I test it before committing?
That depends on the checkout plan available through Polar. If a trial is available for the tier you choose, use that first, because that is the best way to confirm it fits your setup.
