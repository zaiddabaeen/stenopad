# Steno Pad

The web pages of Steno Pad, a voice recorder for iPhone and iPad (and Macs with Apple silicon)
that transcribes on the device. Nothing is uploaded and there is no account.

Published with GitHub Pages at https://zaiddabaeen.github.io/stenopad/

- `index.html`: the app's page, which sends people to the App Store
  (https://apps.apple.com/app/id6822729510, live once Apple approves the app). It looks like the
  store pictures: ruled sheets in the app's highlighter colours, with real screens of the app.
- `privacy-policy.html`: the privacy policy the App Store listing and the app link to.
- `support.html`: answers to common questions, and where to write: support@z-proj.com.
- `images/`: the app icon, and screens of the app taken by `Scripts/screenshots.sh` in the app's
  folder (`build/listing/screens/iphone`), made smaller.

The pages are plain HTML with no scripts, no trackers and nothing loaded from elsewhere. The
lettering is the system's own: SF Rounded where the browser offers it (Safari), heavy system
lettering elsewhere. A push to `main` publishes them.
