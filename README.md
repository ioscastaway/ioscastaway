# 👽 Crash-Landed on Planet Android

I used to be an iOS developer.

Then I fell for the Galaxy Fold 8 and, in a moment of questionable judgment, defected to Android.

Everything was going great.

Until Apple unveiled the iPhone Duo.

That was when the regret kicked in.

I knew Apple would eventually make a foldable.
I knew I should've trusted the process.
And yet here I am.

So instead of admitting I may have switched sides too soon, I've decided to do the only reasonable thing:

**rationalize my decision through engineering.**

This account is my attempt to explore everything Android lets me do that iOS never would — app-to-app interactions, system-level automation, unconventional interfaces, on-device AI, and whatever else I can get away with.

Consider this my field journal from Planet Android.

**An iOS developer's transition into an Android + AI developer.**

Let's see if I can make the defection worth it.

## Current status

🛸 Origin: Planet iOS<br>
💥 Crash site: Planet Android<br>
📱 Device: Galaxy Fold<br>
🧠 Previous life: iOS Developer<br>
🤖 New class: Android + AI Developer<br> <br>
Switch regret: ██████░░░░ 60%<br>
Android curiosity: ██████████ 100%

## Field journal

One repository per experiment. Each one ends with a numbered reason I don't regret switching, and
the running list lives here.

### Android × AI
- [cross-app-agent](https://github.com/ioscastaway/cross-app-agent) — a floating cat that listens,
  reads whatever app is on screen through the accessibility tree, and drives the phone.
  **Reason #05:** an AI agent gets much more interesting when it can see beyond its own app.

### Things Apple Would Never Let Me Do
- [cross-app-agent](https://github.com/ioscastaway/cross-app-agent) — same repository, other angle:
  overlays, a system-bound accessibility service, and a background service the OS keeps alive.
- [edge-rewire](https://github.com/ioscastaway/edge-rewire) — Safari's edge gestures for Samsung
  Internet: left edge back, right edge forward, and the first page of a tab is a wall instead of an
  exit. Two invisible strips carve the browser out of the system back gesture and press the
  browser's own toolbar buttons; every other app keeps stock navigation.
  **Reason #07:** the system's own gestures are negotiable, one app at a time.

### Evolving App
- [notification-brain](https://github.com/ioscastaway/notification-brain) — stage 1 of an app that
  is meant to fix itself one day. It dismisses the notifications you would have swiped anyway,
  keeps them in an archive you can undo from, and rewrites its own rules from a chip, a sentence in
  your own words, or nothing but the way you keep swiping. Every new rule is replayed against
  everything the old rule ever saw before it is allowed in.
  **Reason #08:** the phone's notifications are a data source, not just a distraction.

### Guest Pass to the Walled Garden
- [airpods-on-android](https://github.com/ioscastaway/airpods-on-android) — battery widget, connect
  card and pause-when-a-pod-comes-out, over the same accessory channel the iPhone uses. The beacon
  every Android AirPods app relies on turned out to be silent on AirPods 4; the fix was to open
  Apple's own L2CAP channel from a phone Apple did not build.
  **Reason #06:** my AirPods talk to my phone over Apple's own protocol, and the phone let me be the
  one to answer.

### Reasons so far
| # | Reason | Earned by |
|---|---|---|
| 05 | An AI agent gets much more interesting when it can see beyond its own app. | cross-app-agent |
| 06 | My AirPods talk to my phone over Apple's own protocol, and the phone let me be the one to answer. | airpods-on-android |
| 07 | The system's own gestures are negotiable, one app at a time. | edge-rewire |
| 08 | The phone's notifications are a data source, not just a distraction. | notification-brain |

_#01–#04 are reserved for the foldable, system-surface, cross-app and background-work experiments
that have not been written up yet._
