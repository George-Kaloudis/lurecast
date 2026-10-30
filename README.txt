LureCast - your fishing helper
==============================

WHAT IT DOES
- Gets your GPS position (or search a village) and pulls live weather, wind
  speed + direction, gusts, waves and sea temperature from Open-Meteo
  (free, no account; it has wave data, which Freemeteo doesn't offer as an API).
- START FISHING: set the spot (bottom, depth, water colour, surface, birds,
  fish activity; light/wind/sea are auto-filled from the weather). It then
  gives you one lure at a time from YOUR box, with the colour, how to work it,
  how many casts, and why.
    "Did it - no action. Next"  -> a different zone / lure family
    "Follow / missed hit"        -> stays in that zone, tries a new colour
    "Fish on!"                   -> logs lure, colour, retrieve and conditions
  Quick chips (Birds diving, Fish busting, Bait in close) re-plan instantly.
  For Fiiish Black Minnow it also picks the body colour and the head (Search 28 g
  or Offshore 40 g).
- START EGING: moon phase, squid-jig colour for the light, and a cycle of
  cadences (snap and fall, long fall, mid-water, bottom drag, move along).
- WHAT I'M BRINGING: every lure you own with an on/off switch (plus All/None
  per group). Only packed lures get suggested. "Fishing from: Boat" unlocks
  the trolling minnow and a trolling retrieve.
- Screen stays awake while a session is running.

HOW TO USE IT
On this PC: double-click index.html (Chrome/Edge/Firefox). Allow location.

On your phone (to install it as an app with an icon):
  GPS only works on a phone when the app is opened over https, so host the
  folder somewhere free, e.g.:
  1. Go to https://app.netlify.com/drop and drag this whole LureCast folder in.
  2. Open the link it gives you on your phone.
  3. Android Chrome: menu > "Add to Home screen" / "Install app".
     iPhone Safari: Share > "Add to Home Screen".
  It then opens full-screen like a normal app and works offline (weather
  needs signal; you can still set conditions by hand).

FILES
  index.html            the whole app
  manifest.webmanifest  app name/icon for "install"
  sw.js                 offline support
  icon.svg              app icon
