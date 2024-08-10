# YouTube RVX LITE Modules

Patch version: v4.12.1

# Changelogs 

- bumped YouTube base to 19.16.39
 inotia00/ReVanced_Extended#2241
 
- feat(YouTube): add Hook download actions patch #70
- feat(YouTube/Client spoof): update hardcoded client version
- feat(YouTube/Shorts components): move Change Shorts repeat state setting to Experimental Flags (close inotia00/ReVanced_Extended#2231, inotia00/ReVanced_Extended#2295)
- fix(YouTube/Hide comments components): Hide Comments section in home feed setting not working in new component name
- fix(YouTube/Hide feed components): sometimes Hide carousel shelf setting doesn't work
- fix(YouTube/Hide layout components): no longer hiding Settings inotia00/ReVanced_Extended#1424
- fix(YouTube/Hook download actions): Override playlist download button setting does not work in Download playlist menu of flyout panel
- fix(YouTube/Overlay buttons): Always repeat button doesn't work when the video is minimized inotia00/ReVanced_Extended#2293
- fix(YouTube/Return YouTube Dislike): dislikes not appearing due to new component name
- fix(YouTube/SponsorBlock): improve create segment manual seek accuracy ReVanced/revanced-patches#3491
- fix(YouTube/Spoof client): change default value
- fix(YouTube/Spoof client): fix background playback issue with livestream on iOS clients inotia00/ReVanced_Extended#2290
- fix(YouTube/Spoof client): partial fix for watch history issue of brand accounts on iOS clients inotia00/ReVanced_Extended#2297 
- feat(YouTube): add Watch history patch inotia00/ReVanced_Extended#2275
- feat(YouTube/Client spoof): update hardcoded client version
- feat(YouTube/Description components): add Hide Contents section setting inotia00/ReVanced_Extended#2262
- feat(YouTube/Overlay buttons): add patch option Change top buttons #66
- feat(YouTube/Player components): add Hide zoom overlay setting #67
- feat(YouTube/Video playback): show AlertDialog when changing Skip preloaded buffer setting
- fix(YouTube/Client spoof): some side effects of iOS client (No HDR video → HDR video is supported only on AV1 codec, Higher video qualities may not be available / Live streams not available on Android 8.0 → fixed) inotia00/ReVanced_Extended#2261
- fix(YouTube/Disable auto captions): turning on Disable forced auto captions will disable subtitles inotia00/ReVanced_Extended#2267
- fix(YouTube/Feed components): Hide recommended videos setting does not working in home feed inotia00/ReVanced_Extended#2220
- fix(YouTube/Hide feed components): Hide carousel shelf setting sometimes hides the Watch history in the You tab
- fix(YouTube/SponsorBlock): the new SponsorBlock segment popup doesn't show minutes in the timestamp inotia00/ReVanced_Extended#2263
- fix(YouTube/Toolbar components): turning on the Hide voice search button setting makes the margin of the searchbar 0 inotia00/ReVanced_Extended#2270
 
- feat(YouTube): separate the Bypass image region restrictions patch from the Alternative thumbnails patch (Reflecting changes in ReVanced)
- feat(YouTube/Alternative thumbnails): add support for more domains (Alternative domain) inotia00/revanced-integrations#49
- feat(YouTube/Overlay buttons): add Mute Video button #63
- feat(YouTube/Player components): Hide player popup panels setting now hides the products panel (Contributed by @OxrxL) inotia00/ReVanced_Extended#2236
- feat(YouTube/Shorts components): add Hide paused header setting inotia00/ReVanced_Extended#2213
- feat(YouTube/Swipe controls): add Enable save and restore brightness setting (Reflecting changes in ReVanced) inotia00/ReVanced_Extended#2232
- fix(YouTube): restart dialog that appears when the user first installs the app restarts the app too quickly, so the new layout is not fetched (add a restart delay to resolve issues)
- fix(YouTube/Alternative thumbnails): handle more thumbnails inotia00/revanced-integrations#52
- fix(YouTube/Disable forced auto captions): subtitles don't work after playing Shorts inotia00/ReVanced_Extended#2202
- fix(YouTube/Hide feed components): Hide carousel shelf setting sometimes hides the Watch history in the You tab
- fix(YouTube/Hide feed components): do not hide flyout menu ReVanced/revanced-integrations#664
- fix(YouTube/Miniplayer): change invalid string
- fix(YouTube/Overlay buttons): add missing resources
- fix(YouTube/Overlay buttons): change default value
- fix(YouTube/Overlay buttons): remove used resources
- fix(YouTube/SponsorBlock): skip segments when casting ReVanced/revanced-patches#3331
- fix(YouTube/Spoof client): delay when the video starts
- fix(YouTube/Video playback): default video quality does not apply inotia00/ReVanced_Extended#2157
- refactor(YouTube/Overlay buttons): rename class, method, and resource files to be more appropriate
- revert(YouTube/Hide feed components): Hide expandable chip under videos setting does not work (as support version has been rolled back to YouTube 19.16.39) inotia00/revanced-integrations@2555ab3

- Check this section to read more about the new changes: https://github.com/inotia00/revanced-patches/releases

# Important Announcement 

- The playback issue on YouTube has been fixed with the Spoof client patch.
- If you have playback issues, turn on the settings in the following path:
Settings > ReVanced Extended > Miscellaneous > Spoof client > Spoof client


**Thanks to inotia00**

Telegram: https://t.me/rvx_lite