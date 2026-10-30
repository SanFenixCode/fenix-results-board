# Fenix Results Board

Election-night results graphics for Fenix News Network's "Midterms Madness" stream.

Open the site, click **Open output tab**, and share that tab into Riverside. Type a winner's name and press Enter to call a race; Esc shows the standby slate, R replays the reveal. Calls are remembered in the browser that made them.

Photo credits are in CREDITS.md in the production files.

## Race Watcher

`watcher.html` watches the board's races on [civicAPI](https://civicapi.org) and posts each race call to Slack (plus a chime on screen). Open it in its own Chrome window, paste the Slack incoming-webhook link once, and click **Start watching**. Practice mode uses civicAPI's made-up test numbers so you can rehearse. Races civicAPI doesn't cover are marked "Ciara only".
