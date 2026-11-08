# Ad Shield

Ad Shield blocks ads in the Android apps you choose, mostly games. It runs entirely on your phone: there's no account, no server and no subscription.

## Download

Get the latest **AdShield-x.x.apk** from the **[Releases](https://github.com/Smithers-tech/AdShield-releases/releases/latest)** page. Open it on your phone and tap **Install**. If Android asks, allow your browser to install apps.

Requires Android 12 or newer.

## What it does

- Pick which apps to protect, and set each one to:
  - **Off**: the app isn't touched.
  - **Block ads**: ad and tracking addresses are blocked, and everything else works.
  - **Block internet**: the app can't go online at all.
- Uses Android's VPN feature locally, on the phone. Only the apps you choose go through it, and only their web address lookups are checked. Everything else on your phone is untouched.
- Has a built-in list of mobile ad networks, plus the public [StevenBlack hosts list](https://github.com/StevenBlack/hosts), updated weekly on Wi-Fi.
- Has a request log that shows what each app looked up. Tap an entry to block or allow it.
- Starts by itself after a restart, shows no permanent notification and is light on battery.

## Tips

- After changing an app's mode, force-stop that app once: long-press its icon, then **App info → Force stop**.
- Another VPN (for example NordVPN) pauses Ad Shield while it's on. Tap the notification to turn blocking back on afterwards.
- "Watch an ad for a reward" buttons usually stop working in protected games.
