# Kordy releases

Update feed of the Kordy desktop app (Velopack). The app checks the latest release at start and installs it on its next launch.

Installer: the `Kordy-<rid>-Setup.pkg` asset of the latest release.

`min-version.txt` is the oldest version allowed to run: an installed app below it shows "Update required" and updates before anything else. Raise it when a release must not be skipped.
