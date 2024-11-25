Signal is the obvious recommendation from cryptographers and information security experts as it is an easy to use app with properly implemented end-to-end encryption. It's worth noting that you have to verify safety numbers with contacts manually to ensure you've not suffered a [man-in-the-middle attack](https://en.m.wikipedia.org/wiki/Man-in-the-middle_attack).



Molly is an improved version of Signal for Android users. Regardless of the other features it provides, it fixes the egregious battery drain when not using FCM (push notifications via Google Play services). That's a good enough reason to use it.

The fix was [submitted](https://github.com/signalapp/Signal-Android/pull/13337) to Signal nearly over a year ago and they've completely ignored it. Someone with influence ought to convince them to merge it.

SimpleX is a newer messaging app which will likely take the place of Signal if things continue to not improve. It doesn't require a phone number (or email address) to sign up, anyone can host the servers (though you're not required to) and it prevents MITM attacks automatically as your public key is contained within the invite link/QR code you share to connect with people. SimpleX uses Signal's state-of-the-art [double ratchet algorithm](https://simplex.chat/docs/glossary.html#double-ratchet-algorithm). SimpleX is currently missing some features compared to Signal such as stories, built-in stickers & gifs (can be provided by keyboard app), group calls (expected by early 2025 at latest), built-in image editor, calls tab.

### Signal
- [Play Store](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms)

### Molly
-  [Accrescent](https://accrescent.app/app/im.molly.app)

### SimpleX
- [Play Store](https://play.google.com/store/apps/details?id=chat.simplex.app)
- [Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22chat.simplex.app%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fsimplex-chat%2Fsimplex-chat%22%2C%22author%22%3A%22simplex-chat%22%2C%22name%22%3A%22SimpleX%22%2C%22preferredApkIndex%22%3A2%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22dontSortReleasesList%5C%22%3Afalse%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22appName%5C%22%3A%5C%22%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D) (via GitHub)
