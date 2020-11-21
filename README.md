# test
use this plugin to update remote library <https://github.com/bomberstudios/check-for-library-updates/archive/master.zip>

or check repo <https://github.com/bomberstudios/check-for-library-updates>

```

Indeed, we're currently checking once per hour (but are open to fine tune that, or use other polling mechanisms if the need is there).

Meanwhile, you can use these two workaround for faster updates:

Use this plugin I made to force an update check immediately.
Set the hidden preference checkForLibraryUpdatesPeriod to the number of minutes you want to wait between checks (i.e: defaults write com.bohemiancoding.sketch3 checkForLibraryUpdatesPeriod -int 10 will check every 10 minutes)
Hope it helps!

```
