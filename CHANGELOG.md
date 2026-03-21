# Changelog

## v2.4.0
- **Level names & difficulty** — queue entries now show the actual level name and difficulty rating instead of just the raw ID
- **Difficulty colors** — level names are color-coded by difficulty (green for easy, red for demon, etc.)
- **Requester + difficulty on second line** — each row shows who submitted it and the difficulty tag underneath the level name
- **Channel points support** — works with the new Twitch channel points feature on gdrequests.org

## v2.3.0
- **F2 hotkey** — press F2 (customizable in settings) on any screen to open your queue
- **Back button fix** — back no longer cycles through old levels after viewing requests
- **macOS & Linux** — full support for Mac and Linux players
- **Android & iOS** — mobile players can use the mod too

## v1.2.0
- Request queue is now **scrollable** — all pending requests are visible, not just the first five
- **YT** button is now a plain red text label to match the Remove / Ban Level style

## v1.1.2
- Fixed misleading "check your internet connection" error when the creator token is wrong or not recognised — now shows a clear message directing you to re-copy the token from gdrequests.org

## v1.1.1
- **Remove** and **Ban Level** buttons in the request queue popup are now styled to match the in-game pause menu — plain orange/red text labels, stacked vertically (Remove above Ban Level) instead of small colored boxes
- Reduced main menu icon size so it no longer overlaps the Geometry Dash title text
- Removed non-functional online/offline dot from the request queue popup

## v1.1.0
- Added **Remove from Queue** and **Ban Level** buttons on each request row
- Added **Ban / Remove** buttons in the pause menu while playing a requested level
- Added **YouTube showcase** button — opens showcase video in browser (can be disabled in settings)
- Added **online/offline dot** on each row — green if the requester is currently in your Twitch chat
- Auto-marks a request as **Done** when you enter the level in GD
- Improved text readability in the request popup
- Fixed token input (GD blocks dashes — token is now dash-free)

## v1.0.0
- Initial release
- View pending request queue from the GD main menu
- Tap a request to jump directly to that level
- Syncs with gdrequests.org dashboard
