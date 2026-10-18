## Small Mac apps

Small fixes for things macOS keeps getting wrong. None of them has a menu bar icon. Three run as a background agent
that uses about 3 MB of memory and no CPU while idle; CapsNow doesn't stay running at all.

| App | What it fixes |
| --- | --- |
| [NightKeys](https://github.com/fratayaydn/nightkeys) | The keyboard light comes on when you touch the trackpad. With NightKeys only the built-in keyboard wakes it. |
| [BalanceKeeper](https://github.com/fratayaydn/balancekeeper) | The left/right audio balance drifts off center by itself. BalanceKeeper puts it back. |
| [CapsNow](https://github.com/fratayaydn/capsnow) | Quick Caps Lock taps get ignored. CapsNow turns off the delay that causes it. |
| [MicKeeper](https://github.com/fratayaydn/mickeeper) | AirPods turn into a phone headset when macOS picks them as the mic, and an iPhone can grab it too. MicKeeper switches back to your real mic. |

Install any of them with Homebrew:

```sh
brew install --cask fratayaydn/tap/<name>
```

or grab the signed and notarized dmg from the app's releases page.

More about each app, with screenshots: [fratayaydn.github.io](https://fratayaydn.github.io)
