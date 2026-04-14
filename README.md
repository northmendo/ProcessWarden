![Process Warden App Icon](docs/images/app-icon.png)

# Process Warden

Process Warden is a premium Android utility for force-stop workflows, automation, and background restriction management. It is the maintained successor to Appzuku, built for users who want deliberate control over app state instead of generic one-tap cleanup.

## Before You Buy

- This app is for Android power users who already know why they want Root or Shizuku.
- Root or Shizuku is required for the kill and background-restriction features that define the app.
- Process Warden is a paid, licensed product using Polar.
- After a successful validation, the app can keep working offline for up to 14 days before it needs to check the license again.
- Refunds are handled case by case, but are generally not offered because the checkout flow includes a 3-day trial period before any charges are applied.
- Older known-good releases remain on GitHub if you ever need to roll back.

If you are unsure whether this fits your setup, read the [FAQ](FAQ.md) before buying.

If you already installed it and want the full walkthrough, use the in-app guides under `Help & Links`, including `How Process Warden works` and `App Tour`.

## Screenshots

| Apps Tab | App Actions |
| --- | --- |
| <img src="docs/images/screenshot-apps.jpg" alt="Apps Tab" width="540"> | <img src="docs/images/screenshot-apps-actions.jpg" alt="App Actions" width="540"> |

| Automation Tab | Settings Tab |
| --- | --- |
| <img src="docs/images/screenshot-automation.jpg" alt="Automation Tab" width="540"> | <img src="docs/images/screenshot-settings.jpg" alt="Settings Tab" width="540"> |

## What It Does

Process Warden gives you repeatable control over apps that are noisy, greedy, or better kept asleep when you are not using them.

It also includes a reusable in-app help guide and onboarding tour so first-time users can learn the main flows without hunting through menus.

You can use it to:

- kill the current foreground app or selected apps from one place
- automate cleanup on a timer, on screen-off, or when RAM pressure crosses your threshold
- save and reapply Android background restrictions instead of rebuilding the same setup over and over
- temporarily lift those restrictions for selected apps, then restore them automatically on a schedule or with screen-on and screen-off triggers
- track what happened through history, logs, status, and update messaging

## Key Features

### App Control

- Kill one app, several selected apps, or the app you were just using.
- Use the Apps tab, launcher shortcut, Quick Settings tile, or widget depending on how you work.
- Search, sort, and multi-select running apps without the list jumping around.
- Keep direct visibility controls for system and persistent apps in the same Apps surface.

### Automation

- Run cleanup periodically, on screen-off, or only when RAM use crosses your threshold.
- Choose whitelist or blacklist behavior for background cleanup.
- Restore automation state after reboot and reopen.

### Background Restrictions

- Keep a saved list of apps that should stay background-restricted.
- Apply, reapply, verify, and repair restriction state without rebuilding the list.
- Handle drift and externally changed state through explicit prompts instead of silent failure.

### Temporary Restriction Lift

- Keep a separate target list for apps that need short exception windows.
- Lift restrictions on a timed schedule or while the screen is on, then restore them automatically.
- Prevent lifted apps from being immediately re-restricted or auto-killed while the lift is active.

### Updates and Backups

- Check for app updates and install new APKs from inside the app.
- Export Process Warden backups and import either Process Warden or legacy Appzuku backups.

### Licensing

- Process Warden uses Polar for checkout and license management.
- Users can manage their own licenses through the portal.
- Users can activate and deactivate licenses on their own devices whenever they want.
- You can also retrieve an existing license from inside the app during activation.

### Appearance and Language

- Choose system, light, or dark theme behavior.
- Change accent, chrome, separator, and text colors.
- Use `Auto` language mode or switch the app to English, Simplified Chinese, or Brazilian Portuguese.

## Requirements

- Android 6.0 or newer to run the app
- Android 11 or newer for the background restriction workflow
- Root or Shizuku for kill and restriction operations
- Internet access for:
  - first license validation
  - periodic license revalidation
  - Polar portal access
  - update checks
- Notification Access for:
  - update notifications

## Installation and First Run

1. Download the APK from the official GitHub Releases page.
2. Install it on the device.
3. Launch Process Warden.
4. Review and accept the EULA.
5. Start checkout through Polar, retrieve your license, or paste an existing key.
6. Activate the license on the device.
7. Grant Root or Shizuku access if you want the core kill and restriction features to function.

On first launch, Process Warden can show a short onboarding tour. You can replay it later from Settings under `Help & Links`.

## Automation and Integrations

Process Warden can integrate with automation tools such as Tasker and MacroDroid.

- Integration support is premium-only.
- It must be enabled in Settings before other apps can use it.
- The public README intentionally stays at the capability level rather than documenting the full command contract.

## FAQ / Support / License

- Read the [FAQ](FAQ.md) for buyer-focused answers about requirements, licensing, automation, backups, and stability.
- Use the GitHub issue tracker for product bugs and app behavior problems.
- Use the Polar portal for billing, subscription, trial, and license-management support.
- Use and distribution are governed by the bundled [EULA](EULA.md) and a valid Polar license.


