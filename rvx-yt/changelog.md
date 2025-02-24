# YouTube RVX LITE Modules

Patch version: v5.4.1

# Changelogs 

- bumped YouTube base to 19.44.39 (STABLE)
- Also providing Alternative updates for 19.16.39 (STABLE) & 20.06.42 (BETA)
- Make sure to read this before using 20.06.42 : https://github.com/inotia00/ReVanced_Extended/issues/2717

- chore(YouTube - Hide ads): Remove duplicated ads filter
- chore(YouTube - Inclusive span): Update SpanType
- chore(YouTube - Miniplayer): Move Miniplayer from PreferenceScreen General to PreferenceScreen Player inotia00/ReVanced_Extended#2725

- chore(YouTube - Settings): Change default value
- chore(YouTube - Spoof streaming data): Change the **[document link](https://github.com/inotia00/scrape-youtube-termux)** for issuing PoToken
- feat(YouTube): Add patch Hide accessibility controls dialog inotia00/ReVanced_Extended#2756

- feat(YouTube): Add patch Disable resuming Miniplayer on startup inotia00/ReVanced_Extended#469

- feat(YouTube - Change start page): Add more start pages **[#136](https://github.com/inotia00/revanced-patches/pull/136)**
- feat(YouTube - Description components): Remove setting Title in video description panel (No more necessary)
- feat(YouTube - Hide action buttons): Add setting Hide action button by index, Remove patch option Hide action buttons by index
- feat(YouTube - Hide ads): Add setting Hide end screen store banner **[#131](https://github.com/inotia00/revanced-patches/pull/131)**
- feat(YouTube - Hide feed flyout menu): Add setting Feed flyout menu filter type
- feat(YouTube - Hide layout components): Add setting Account menu filter type (Close inotia00/ReVanced_Extended#2574)
- feat(YouTube - Navigation bar components): Add user dialog message
- feat(YouTube - Seekbar components): Add option to use custom seekbar accent color (For YouTube 19.25.39+, Close inotia00/ReVanced_Extended#2738)

- feat(YouTube - Spoof streaming data): Change Default client to iOS TV inotia00/ReVanced_Extended#2777

- fix(YouTube): Playback speed sometimes changes to 1.0x in PiP mode (Unpatched YouTube bug)
- fix(YouTube - Change live ring click action): Cannot play the playlist
- fix(YouTube - Change live ring click action): Channel does not open when the live ring of Shorts live stream is clicked
- fix(YouTube - Change live ring click action): Check more information for the guarantee of the more accurate operation of the patch
- fix(YouTube - Change live ring click action): Sometimes channel opens even if the live ring is not clicked
- fix(YouTube - Change live ring click action): Update patch limitation
- fix(YouTube - Custom Shorts action buttons): Exception is thrown when patching with Revancify inotia00/ReVanced_Extended#2773
- fix(YouTube - Hide ads): New types of ads are shown ReVanced/revanced-patches#4352
- fix(YouTube - Hide feed components): Podcasts subpage is empty when Hide carousel shelves is on

- fix(YouTube - Hide feed components): Hide Playables not working inotia00/ReVanced_Extended#2485

- fix(YouTube - Hide feed components): Hide category bar in feed does not work on the Subscriptions tab inotia00/ReVanced_Extended#2751

- fix(YouTube - Hide feed components): Hide community posts in subscriptions not working inotia00/ReVanced_Extended#2729

- fix(YouTube - Hide feed components): Hide community posts not working
- fix(YouTube - Player components): Show anyway button on the search results is hidden when Hide info panels is turned on ReVanced/revanced-patches#3245
- fix(YouTube - Remove background playback restriction): Play/Pause button not working in PiP mode (Unpatched YouTube bug) inotia00/ReVanced_Extended#2764
- fix(YouTube - Shorts components): When Shorts repeat state is AutoPlay, HUD is hidden (YouTube 19.34+) ReVanced/revanced-patches#4426

- fix(YouTube - Translations): Patch exception thrown when the patch option String resources to keep is empty inotia00/ReVanced_Extended#2778
- feat(Universal): Add patch Spoof Wi-Fi connection inotia00/ReVanced_Extended#2757
- fix(GmsCore support): Add missing permissions and intents
- fix(GmsCore support): Remove unnecessary provider hooking

- Checkout this site to read more about previously added changes: https://github.com/inotia00/revanced-patches/releases

# Important Announcement 

- The playback issue on YouTube has been fixed with the Spoof streaming data.
- If you have playback issues, turn on the settings in the following path:
Settings > ReVanced Extended > Miscellaneous > Spoof streaming data > Enable Spoof streaming Data toggle > Set it to IOS TV or IOS (potoken) to prevent any side-effects

**Thanks to inotia00**

Telegram: https://t.me/rvx_lite ( JOIN FOR SUPPORT )