## Versions

## 1.1.6
    * Attempt fix for `loadInterstitial()` or `loadRewardedAd()` due to current Activity being null.
## 1.1.5
    * Fix `removeEventListener()` not working by explicitly calling `remove()`.
## 1.1.4
    * Fix Android banners not working for fast refreshes.
    * FIx iOS module's podspec pointing to invalid tag.
## 1.1.3
    * Ensure values such as user id is set before initializing SDK.
    * Add workaround for `getCurrentActivity()` returning `null`.
## 1.1.2
    * Fix `ConsentDialogState.UNKNOWN` being returned for `getConsentDialogState()` on iOS.
## 1.1.1
    * Fix `AppLovinMAX.removeEventListener()` crash.
## 1.1.0
    * Add support for native banner / MREC UI components via `<AppLovinMAX.AdView adUnitId={...} adFormat={...} />`.
## 1.0.0
    * Initial release with support for interstitials, rewarded ads, banners, and MRECs.
