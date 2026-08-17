# MDB Takeoff Assistant — version feed

`latest.json` names the newest released build. The app reads it on launch and
tells the user when there is something newer; it downloads and installs nothing.

This repository is public because the app has to read the file without carrying
a credential. It contains no source code and no installers — only the version
number, a one-line summary, and links to the release notes and the download.

Written automatically by `scripts/distribute.py` when a release is shipped.
