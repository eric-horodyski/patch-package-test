# patch-package-test

How to test `patch-package`:

1. Run `npm install`
2. Check `node_modules/cordova-plugin-inappbrowser/src/ios/CDVWKInAppBrowser.m` LN294

If a comment `Shhh! I snuck in a comment.` exists, `patch-package` applied the patch from `/patches/cordova-plugin-inappbrowser+5.0.0.patch`.
