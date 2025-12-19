# Setting up Get More Ram
1. Open [this link](https://github.com/hugeBlack/GetMoreRam/releases/download/nightly/Entitlement.ipa) to download Get More Ram (appears as `Entitlement.ipa` in Files). This application increases the memory limit on apps which is imposed by iOS/iPadOS. It can boost performance for apps such as DolphiniOS, and is required for apps such as MeloNX and Amethyst.
2. Install Get More Ram to LiveContainer and launch it.
3. Navigate to Settings and select "Sign In". Use your Apple Account credentials to log in. If the app crashes, just try again.
4. Navigate to "App IDs" and select "Refresh".
5. Select anything including "livecontainer" or "liveprocess", and select "Add Increased Memory Limit". If a bunch of text appears underneath with no mention of an error, you did it correctly.
6. Navigate back to SideStore, and reinstall LiveContainer via the [.ipa](https://github.com/LiveContainer/LiveContainer/releases/download/nightly/LiveContainer.ipa) so the new entitlement takes effect. (Note: If your LiveContainer expires \[you go 7 days without refreshing] you will need to repeat this page's process).

## Next:
Navigate to StikDebug's Settings page and scroll to the bottom. Is "TXM" or "Non-TXM" displayed:
- [TXM](./setup-txm.md)
- [Non-TXM](./end.md)
