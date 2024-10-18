# YouTube RVX LITE Modules

Patch version: v4.15.1-dev.3

# Changelogs 

- bumped YouTube base to 19.16.39
 inotia00/ReVanced_Extended#2241
- Also posted BETA builds ( v19.30.39 )
- chore(YouTube/PlayerType): supplement PlayerType limits under certain conditions
- feat(YouTube/Hide comments components): add Hide highlighted search links setting inotia00/ReVanced_Extended#2435
- feat(YouTube/Hide feed components): remove Hide UPCOMING video setting inotia00/ReVanced_Extended#2427 (comment)
- feat(YouTube/Shorts components): add Hide in channel setting (Hide the Shorts shelf on the channel home tab)
- feat(YouTube/Spoof app version): enabled by default in YouTube 19.16.39+ inotia00/ReVanced_Extended#2419 (comment)
- feat(YouTube/Swipe controls): add Swipe sensitivity settings ReVanced/revanced-patches#1646
- fix(YouTube/Hide ads): Hide view products banner not working (untested) inotia00/ReVanced_Extended#2437
- fix(YouTube/Hide ads): new type of ads are not hidden
- fix(YouTube/Hide feed components): Hide carousel shelf setting hides the library shelf
- fix(YouTube/Hook YouTube Music actions): app crashes when first installed
- fix(YouTube/LithoFilter): remove unused keywords
- fix(YouTube/Spoof streaming data): wrong register used
- feat(YouTube/YT Music - Return YouTube Username): add Display format setting
- feat(YouTube/YT Music): add Return YouTube Username patch
- feat(YouTube/YT Music - Return YouTube Dislike): add Show estimated likes setting ReVanced/revanced-patches#3667
- fix(YouTube/YT Music - GmsCore support): unimplemented service in GmsCore causes memory leak ReVanced/revanced-patches#3768
- chore(YouTube): replace with a fingerprint that supports a wider range of versions
- feat(YouTube/Hide player flyout menu): add Hide 1080p Premium menu setting ReVanced/revanced-patches#3760
- feat(YouTube/Seekbar components): add Disable seekbar chapters setting #90
- feat(YouTube/Spoof app version): add target version 19.13.37 - Restores old style Rolling number animations inotia00/ReVanced_Extended#2419
- feat(YouTube/Toolbar components): add Hide YouTube Doodles setting ReVanced/revanced-patches#3743
- fix(YouTube/Custom Shorts action buttons): low image quality for Cairo option on YouTube 18.29.38
- fix(YouTube/Hide feed components): change default offset for Hide related videos setting
- fix(YouTube/Settings): EditTextDialog's background color does not match when Theme patch is excluded inotia00/ReVanced_Extended#2422
- fix(YouTube/Settings): If the title of the setting is too long, it will be displayed as ...
- fix(YouTube/Shorts components): Shorts are hidden in Watch history shelf in Library tab
- fix(YouTube/Shorts components): Hide paused header setting does not work
- fix(YouTube/Shorts components): Replace channel handle setting no longer uses RSS feeds to retrieve usernames
- fix(YouTube/Spoof streaming data): Authorization key is always included when fetching an API, even if there is no Authorization in the header (e.g. the user is not logged in or using the Incognito Mode)
- fix(YouTube/Spoof streaming data): playback issues occur when data connection changes or RVX has been open for a long time inotia00/ReVanced_Extended#2416
- fix(YouTube/Spoof streaming data): revert reduce response timeout and cache size

- Check this section to read more about the new changes: https://github.com/inotia00/revanced-patches/releases

# Important Announcement 

- The playback issue on YouTube has been fixed with the Spoof streaming data.
- If you have playback issues, turn on the settings in the following path:
Settings > ReVanced Extended > Miscellaneous > Spoof streaming data > Enable Spoof streaming Data toggle

**Thanks to inotia00**

Telegram: https://t.me/rvx_lite ( JOIN FOR SUPPORT )