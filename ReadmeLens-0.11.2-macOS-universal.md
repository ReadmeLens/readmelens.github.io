ReadmeLens v0.11.2

Fixes update checking never actually detecting an update.

- CFBundleVersion (what Sparkle compares, not the display version) was
  hardcoded to 1 in every build, so no release ever looked newer than
  another to it — this is the first release Sparkle can actually see
  as newer than the last

