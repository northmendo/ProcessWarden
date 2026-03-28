![Process Warden App Icon](docs/images/app-icon.png)

# Process Warden

Process Warden is my modern Android replacement for Appzuku.

Appzuku proved the demand for direct app cleanup, force-stop shortcuts, and background restriction workflows. Process Warden is the maintained premium rewrite: cleaner UI, stronger automation, in-app licensing, OTA updates, and a much tighter long-term product surface.

This repository is the official distribution channel for signed Process Warden APK releases. It does not contain source code.

## What Process Warden Does
- Force-stop the current foreground app.
- Force-stop selected apps manually from the Apps tab.
- Run configured background cleanup against saved app lists.
- Apply, verify, and reapply Android background restrictions.
- Automate cleanup on a schedule, on screen-off, or under RAM-threshold conditions.
- Temporarily lift restrictions for selected apps on a repeating schedule, then restore them automatically.
- Expose premium quick actions through a widget, Quick Settings tiles, and a launcher shortcut.
- Keep logs and history so you can see what actually happened.

## What Is New Compared To Appzuku
- Premium Polar licensing with device activation, device deactivation, and offline grace handling.
- GitHub Releases based OTA updates from inside the app.
- Modern Kotlin + Compose rewrite.
- In-app language selection with `Auto` follow-system behavior.
- Shipped Simplified Chinese and Brazilian Portuguese support.
- Temporary Restriction Lift automation: let selected restricted apps run for a set amount of time on a repeating schedule, then automatically restore their restrictions.
- Safer backup/import behavior and a cleaner Appzuku migration path.

## Core Features
- Manual app killing from the Apps tab.
- Saved app lists for repeatable cleanup targeting.
- Periodic kill, screen-off kill, and RAM-threshold automation.
- Background restriction verification and repair.
- Temporary Restriction Lift for controlled recovery windows.
- Widget, Quick Settings tiles, and launcher shortcut premium actions.
- Kill history, top offenders, and restriction logs.
- Backup/restore plus legacy Appzuku import.
- External automation API for Tasker, MacroDroid, and similar tools.

## Requirements
- Android 6.0 or newer for the app itself.
- Android 11 or newer for background restriction management.
- Shizuku or root for kill and restriction operations.
- Internet access for:
  - first license validation
  - periodic revalidation
  - Polar portal access
  - OTA update checks

## Install and First Run
1. Download the latest signed APK from the Releases page.
2. Enable installation from unknown sources on your Android device if prompted.
3. Install the APK manually.
4. Launch Process Warden.
5. Review and accept the EULA when prompted.
6. Start checkout or trial through Polar, or paste an existing license key.
7. Activate the license key on the device.
8. Grant Shizuku or root access if you want kill and restriction features to work.

## Licensing
- Process Warden is a paid product.
- On first launch, the app requires EULA acceptance and a valid Polar license key.
- Billing, trial handling, subscription management, and customer device management are handled through Polar.
- After a successful validation, the app can continue working offline for up to 14 days before another live validation is required.
- The app includes an in-app `Deactivate This Device` action plus a Polar customer-portal link.

## Screenshots
| Apps Tab | App Actions |
| --- | --- |
| ![Apps Tab](docs/images/screenshot-apps.jpg) | ![App Actions](docs/images/screenshot-apps-actions.jpg) |

| Automation Tab | Settings Tab |
| --- | --- |
| ![Automation Tab](docs/images/screenshot-automation.jpg) | ![Settings Tab](docs/images/screenshot-settings.jpg) |

## Support
- License and billing support: https://polar.sh/northmendo-tech-services/portal
- Product distribution and release history: this repository's Releases page





