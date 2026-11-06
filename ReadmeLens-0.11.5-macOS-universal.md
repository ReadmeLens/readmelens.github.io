ReadmeLens v0.11.5

Opens the file you clicked straight away, without the welcome page first.

- Opening a .md from Finder, the Dock or `open -a` while ReadmeLens was
  not running showed the bundled welcome document for a moment before
  the real file. The file now opens the instant it arrives, and the
  welcome page appears only when the app is launched with no file
- Documents fade in when they open, including back and forward between
  files. Live reload on save still updates in place without animating,
  and Reduce Motion keeps it to a plain fade

