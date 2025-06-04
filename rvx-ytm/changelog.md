# YouTube Music RVX LITE Modules

- Patch version: v5.6.2

# Changelogs 

- bumped YouTube Music base version to v8.14.54 ( for android 8+ )
- Added support for v7.16.53 , v6.42.55 (A7+) , v6.20.51 (A5-6+)

- feat(YouTube Music): Remove Spoof client patch inotia00/ReVanced_Extended#2832 (comment)

- feat(YouTube Music - Custom branding icon): Update afn icons inotia00/ReVanced_Extended#2866

- feat(YouTube Music - Hide layout components): Add Hide search button setting inotia00/ReVanced_Extended#2850
- feat(YouTube Music - Spoof app version): Add target version 7.17.52
- fix(YouTube Music - Disable music video in album): The redirect wait time may be too short.
- fix(YouTube Music - Spoof app version): Show warning when spoofing app version with YT Music 5.xx

- feat(YouTube Music): Add Spoof player parameter patch inotia00/ReVanced_Extended#2832

- feat(YouTube Music - Navigation bar components): Add Replace Samples button and Replace Upgrade button settings ReVanced/revanced-patches#870
- feat(YouTube Music - Spoof client): Excluded by default inotia00/ReVanced_Extended#2832

- fix(YouTube Music - Change start page): YouTube Music 6.20.51 does not allow changing the start page to Search (Not implemented)
- fix(YouTube Music - Disable music video in album): Redirects even from playlists other than Album inotia00/ReVanced_Extended#2835

- feat(YouTube Music): Add Disable QUIC protocol patch inotia00/ReVanced_Extended#2763
- fix(YouTube Music - Custom header): Patch error occurs in a specific environment

- fix(YouTube Music - Disable Cairo splash animation): 8.05.51 is not included in the support version inotia00/ReVanced_Extended#2792
- fix(YouTube Music - Disable music video in album): Piped API not available inotia00/ReVanced_Extended#2793

- fix(YouTube Music - Hide ads): Hide premium promotion popups setting hides the playlist dialog inotia00/ReVanced_Extended#2798
- fix(YouTube Music - Hide layout components): Hide sound search button setting is not added to 8.05.51+

- feat(YouTube Music): Add patch Watch history
- feat(YouTube Music - Change start page): Add more start pages **[#135](https://github.com/inotia00/revanced-patches/pull/135)**
- feat(YouTube Music - Flyout menu components): Add setting Hide Not interested menu
- feat(YouTube Music - Hide action bar components): Add setting Change action bar position (YouTube Music 7.25.53+) (Close inotia00/ReVanced_Extended#2770)

- feat(YouTube Music - Hide action bar components): Add setting Hide Song / Video button (YouTube Music 7.33.51+)

- feat(YouTube Music - Hide action bar components): Add support for setting Override Download action button on YouTube Music 7.25.53+ inotia00/ReVanced_Extended#2733

- feat(YouTube Music - Player components): Add settings Change seekbar position and Enable thick seekbar (YouTube Music 7.29.51+, Close inotia00/ReVanced_Extended#2770)

- feat(YouTube Music - Player components): Add settings Player background primary color and Player background secondary color (Close inotia00/ReVanced_Extended#2119)

- feat(YouTube Music - Spoof app version): Remove the version that is no longer valid inotia00/ReVanced_Extended#2743

- feat(YouTube Music - Spoof client): Add support for latest versions, Remove Spoof streaming data patch
- fix(YouTube Music - Dark theme): Gradient is applied to the button of the action bar
- fix(YouTube Music - Dark theme): Gradient layer overlaps
- fix(YouTube Music - Flyout menu components): Flyout menu does not close when Watch on YouTube is clicked
- fix(YouTube Music - Flyout menu components): Setting Hide Download menu does not work inotia00/ReVanced_Extended#2771
- fix(YouTube Music - Hide ads): New type of Premium promotion popups are shown
- fix(YouTube Music - Hide ads): Renewal banner or update banner disappears too late

- fix(YouTube Music - Hide ads): Setting Hide fullscreen ads does not completely hide the fullscreen ads inotia00/ReVanced_Extended#2515

- fix(YouTube Music - Return YouTube Dislike): Length of the separator is different in the new action bar
- fix(YouTube Music - Return YouTube Dislike): Margin does not match on 7.16.53 or earlier
- fix(YouTube Music - Settings): ListPreference dialog always selects default value inotia00/ReVanced_Extended#2731
- fix(YouTube Music - Spoof client): Some users have a playback issue even if Spoof client is turned on (A/B testing)
- fix(YouTube Music - Spoof client): When the default client is Android Music, playback speed menu does not open


# Version Comparison 

- v6.20.51 : For Android 5-6 users
- v6.42.55 : For Android 7 users 
- v7.16.53 : This Last version which supports all the RVX features
- v8.14.54 : Latest version of YouTube Music For Android 8+ users. Everything works fine on this version except these settings : Hook/Override Download Button , Remember Shuffle State , Spoof App version inotia00/ReVanced_Extended#2554 ( check this more details )

**Thanks to @inotia00**

Telegram: https://t.me/rvx_lite
