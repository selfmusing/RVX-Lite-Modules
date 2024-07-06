# YouTube RVX LITE Modules

Patch version: v4.10.1

# Changelogs 

- bumped YouTube base to 19.25.39

- feat(YouTube): integrate Change Shorts repeat state patch into the Shorts components patch
- feat(YouTube): integrate Hide animated button background, Hide double tap to like animations patch into the Shorts components patch
- feat(YouTube): integrate Hide double tap overlay filter patch into the Player components patch
- feat(YouTube/Alternative thumbnails): add alternative domain
- feat(YouTube/Client spoof): downgrade hardcoded client version
- feat(YouTube/Custom branding icon): add old splash animation for Revancify Red and Revancify Blue
- feat(YouTube/Miniplayer): add Enable double-tap action setting (YouTube 19.25.39+)
- feat(YouTube/Settings): restyle search view
- feat(YouTube/Shorts components): add Double-tap animation settings
- feat(YouTube/Shorts components): add Enable timestamps, Timestamp long press action, Meta panel bottom margin settings (YouTube 19.25.39+)
- feat(YouTube/Toolbar components): add Hide image search button settings
- fix(YouTube/Hide ads): new ads are not blocked inotia00/ReVanced_Extended#2210
- fix(YouTube/Hide ads): patch closes fullscreen ads too quickly, so fullscreen ads are shown repeatedly
- fix(YouTube/Hide feed components): detect if a keyword filter hides all videos ReVanced/revanced-patches#3365
- fix(YouTube/Hide feed components): video filters do not work properly on accounts with A/B testing applied
- fix(YouTube/Settings): toolbar added twice to RVX settings
- fix(YouTube/Shorts components): Hide sound button doesn't work (A/B tests) inotia00/ReVanced_Extended#2193
- fix(YouTube/Theme): reverts background color of More comments icon in live chats inotia00/ReVanced_Extended#2197
- feat(YouTube/Description components): separate the Hide Key concepts section setting from the Hide Chapters section setting
- feat(YouTube/Miniplayer): add Enable drag and drop setting (YouTube 19.23.40+)
- feat(YouTube/Navigation bar components): add Enable translucent navigation bar settings (YouTube 19.23.40+, Android 12+)
- feat(YouTube/Seekbar components): add Enable Cairo seekbar settings (YouTube 19.23.40+) inotia00/ReVanced_Extended#2178
- fix(YouTube): Hide animated button background patch doesnt work inotia00/ReVanced_Extended#2179
- fix(YouTube/Hide action buttons) : empty space is left after hiding all action buttons under videos inotia00/ReVanced_Extended#2180
- fix(YouTube/Hide ads): app crashes in the old client inotia00/ReVanced_Extended#2146
- fix(YouTube/Hide feed components): Hide carousel shelf setting does not work (A/B tests) inotia00/ReVanced_Extended#2172
- fix(YouTube/Hide feed components): Hide comments by keywords setting hides unintended layout
- fix(YouTube/Hide feed components): Hide expandable chip under videos setting does not work (A/B tests) inotia00/ReVanced_Extended#2173
- fix(YouTube/Hide feed components): Keyword filter, Hide low views video, Hide recommended videos by views setting does not work (A/B tests)
- fix(YouTube/Hide feed components): community posts are not hidden inotia00/ReVanced_Extended#2074
- fix(YouTube/Miniplayer): Hide expand and close buttons setting is not disabled in Modern 1 on YouTube 19.20.35+
- fix(YouTube/Overlay buttons): in devices that do not use xxhdpi, some buttons are not replaced correctly
- fix(YouTube/Player components): Hide Open mix playlist button and Hide Open playlist button aren't working inotia00/ReVanced_Extended#2174
- fix(YouTube/Spoof client): change default value to ON
- fix(YouTube/Spoof client): seekbar thumbnail not shown in Android Testsuite client
- fix(YouTube/Spoof client): update side-effects inotia00/ReVanced_Extended#2166
- fix(YouTube/Toolbar components): add support for Cairo icon
- Check this section to read more about the new changes: https://github.com/inotia00/revanced-patches/releases

# Important Announcement 

- The playback issue on YouTube has been fixed with the Spoof client patch.
- If you have playback issues, turn on the settings in the following path:
Settings > ReVanced Extended > Miscellaneous > Spoof client > Spoof client
- Restore old seekbar thumbnails setting has been deprecated in YouTube 19.17.41+.
- If you want to use the Restore old seekbar thumbnails setting, just patch YouTube 18.29.38 ~ 19.16.39.


**Thanks to inotia00**

Telegram: https://t.me/rvx_lite