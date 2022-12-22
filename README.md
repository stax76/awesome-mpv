
# Awesome mpv [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of [awesome](https://github.com/topics/awesome) mpv resources.

# Table of contents

- [Media Player](#media-player)
  - [Cross-platform](#cross-platform)
  - [Windows](#windows)
  - [MacOS](#macos)
  - [Linux](#linux)
- [Installation/Download](#installationdownload)
- [Documentation](#documentation)
- [Support](#support)
- [User Script](#user-script)
  - [Menu](#menu)
  - [Playback](#playback)
  - [Files](#files)
  - [On Screen Controller](#on-screen-controller)
  - [Input](#input)
  - [Subtitle](#subtitle)
  - [Learning](#learning)
  - [Music](#music)
  - [Audio](#audio)
  - [Streaming](#streaming)
  - [Video](#video)
  - [Image](#image)
  - [Video Editing](#video-editing)
  - [Social](#social)
  - [Configuration](#configuration)
  - [Library](#library)
  - [Other](#other)
- [Music Player](#music-player)
- [Mobile Player](#mobile-player)
- [Media Center](#media-center)
- [Streaming Tools](#streaming-tools)
- [User Configuration](#user-configuration)
- [Social Tools](#social-tools)
- [Video Conversion](#video-conversion)
- [Shaders](#shaders)
- [VapourSynth Scripts](#vapoursynth-scripts)
- [Video Editing Tools](#video-editing-tools)
- [Image Viewer](#image-viewer)
- [Launcher](#launcher)
- [Remote Control](#remote-control)
- [Building](#building)
- [Library](#library)
- [Other Tools](#other-tools)

# Media Player

## Cross-platform

- [mpv](https://mpv.io) - Based on C/Lua.
- [MoonPlayer](https://github.com/coslyk/moonplayer) - Based on C++/QT/QML.
- [SMPlayer](https://github.com/smplayer-dev/smplayer) - Based on C++/QT.
- [ImPlay](https://github.com/tsl0922/ImPlay) - Based on C++/imgui.
- [Baka-MPlayer](https://github.com/u8sand/Baka-MPlayer) - Unmaintained, based on C++/QT.
- [movie-monad](https://github.com/lettier/movie-monad) - Unmaintained, based on Haskell/GTK.
- [OvoPlayer](https://github.com/varianus/ovoplayer) - Unmaintained, based on Pascal.

## Windows

- [mpv.net](https://github.com/mpvnet-player/mpv.net) - Based on C#/WinForms/WPF.
- [mpc-qt](https://github.com/mpc-qt/mpc-qt) - Based on C++/QT.
- [MPV-EASY Player](https://github.com/422658476/MPV-EASY-Player)

## MacOS

- [IINA](https://iina.io) - Based on Swift/Cocoa.

## Linux

- [Celluloid](https://celluloid-player.github.io) - Based on C/GTK.
- [Kawaii Player](https://github.com/kanishka-linux/kawaii-player) - Player/Library/Server, based on Python/QT.
- [xt7-player-mpv](https://github.com/kokoko3k/xt7-player-mpv) - Based on Gambas/QT.
- [mpvz](https://github.com/Zren/mpvz) - Based on C++/QT/QML.
- [Haruna](https://invent.kde.org/multimedia/haruna) - Based on C++/QT/QML.
- [Deepin Movie](https://github.com/linuxdeepin/deepin-movie-reborn) - Unmaintained, based on C++/QT.
- [bomi player](https://bomi-player.github.io) - Unmaintained, based on C++/QT.

# Installation/Download

- [Official mpv installation instruction](https://mpv.io/installation)
- [mpv-winbuild-cmake by shinchiro](https://github.com/shinchiro/mpv-winbuild-cmake) - Daily Windows builds of mpv and libmpv.
- [mpv-winbuild by zhongfly](https://github.com/zhongfly/mpv-winbuild) - Daily Windows builds of mpv and libmpv.

# Documentation

- [Manual](https://mpv.io/manual/stable/)
- [Wiki](https://github.com/mpv-player/mpv/wiki)
- [Guides](https://github.com/mpv-player/mpv.io/tree/master/source/guides)
- [How to Use MPV on Windows](https://www.makeuseof.com/how-to-use-mpv-on-windows)
- [mpv: The Best Video Player for Language Learning](https://www.youtube.com/watch?v=bbg6ztWecbU)
- https://wiki.archlinux.org/title/mpv
- https://manpages.ubuntu.com/manpages/bionic/en/man1/mpv.1.html

# Support

- https://mpv.io/community/
- https://www.reddit.com/r/mpv
- https://github.com/mpv-player/mpv/issues

# User Script

The most complete/up-to-date list of user scrips can be found
in the [wiki](https://github.com/mpv-player/mpv/wiki/User-Scripts),
the advantage of the following list is that everything is categorized
into popular sections, like Subtitles etc.

## Menu

- [M-x](https://github.com/Seme4eg/mpv-scripts/tree/master#m-x) - Searchable and configurable menu to quickly find key bindings and commands.
- [mpv-search-page](https://github.com/CogentRedTester/mpv-search-page) - Searchable and configurable menu to quickly find key bindings, commands, options and properties.
- [search-menu](https://github.com/stax76/mpv-scripts) - Searchable and configurable menu to quickly find key bindings, commands, properties, audio/subtitle tracks and playlist entries.
- [mdmenu](https://codeberg.org/NRK/mpv-toolbox/src/branch/master/mdmenu) - Use dmenu (Linux launcher) for selecting audio/subtitle/chapters etc.
- [Tcl/Tk context-menu](https://gist.github.com/avih/bee746200b5712220b8bd2f230e535de) - Configurable context-menu based on Tcl/Tk (cross-platform).
- [menu](https://github.com/jonniek/mpv-menu) - Configurable on screen menu to launch custom commands.
- [osm](https://github.com/stax76/mpv-scripts/blob/main/osm.lua) - Configurable on screen menu to launch custom commands.
- [mpvc-tui](https://github.com/gmt4/mpvc) - Command-line and TUI for mpv.
- [contextmenu](https://gitlab.com/carmanaught/mpvcontextmenu) - Configurable context-menu based on Tcl/Tk (cross-platform).
- [menu](https://github.com/nezumisama/mpvmenu) - Configurable on screen context-menu.

## Playback

- [playlist-manager](https://github.com/jonniek/mpv-playlistmanager) - Create and manage playlists.
- [recent](https://github.com/hacel/recent) - Recently played menu.
- [trackselect](https://github.com/po5/trackselect) - Select tracks based on their title.
- [chapterskip](https://github.com/po5/chapterskip) - Skip chapters based on their title.
- [createchapter](https://github.com/shinchiro/mpv-createchapter) - Temporarily mark the current playback position as a chapter so you can seek to it later. Also allows writing current chapters as XML.
- [chapters](https://github.com/zxhzxhz/mpv-chapters) - Display chapters and switch between chapters.
- [chapter-list](https://github.com/CogentRedTester/mpv-scroll-list/blob/master/examples/chapter-list.lua) - Interractive chapter-list menu.
- [chapter-make-read](https://github.com/dyphire/mpv-scripts/blob/main/chapter-make-read.lua) - Automatically read an load the namesake external chapter file with extension of CHP. Temporarily mark the current playback position as a chapter so you can seek to it later. Also allows writing current chapters as CHP or XML. Based on `createchapter`.
- [chapters-menu](https://github.com/Seme4eg/mpv-scripts/tree/master#chapters-menu) - List all chapters of current video, search and choose any.
- [betterchapters](https://gist.github.com/Hakkin/4f978a5c87c31f7fe3ae) ([update](https://github.com/mpv-player/mpv/issues/4738#issuecomment-321298846)) - Loads the next or previous playlist entry if there are no more chapters in the seek direction.
- [sort_script](https://github.com/TheAMM/mpv_sort_script) - Sort directories and files.
- [fastforward](https://github.com/zsugabubus/mpv-fastforward) - Fast-forward instead of skipping.
- [libunity](https://github.com/mrlotfi/mpv-libunity) - Show a nice progress bar on your Linux panel/dock.
- [segment-linking](https://github.com/CogentRedTester/mpv-segment-linking) - Supports Matroska hard segment linking.
- [quack](https://github.com/CounterPillow/mpv-quack) - Reduces audio volume temporarily after seeking.
- [control](https://github.com/oe-d/control) - Various features mainly for controlling playback.
- [groupwatch_sync](https://github.com/po5/groupwatch_sync) - Automatically start and get back in sync with a group watch.
- [unseen-playlistmaker](https://github.com/jonniek/unseen-playlistmaker) - Keeps track of your watched files from a directory, and on keypress enters playlist-mode to watch unseen files from that specified directory.
- [multiloop](https://github.com/unusualpepe/mpv-multiloop) - Loop over multiple A-B points.
- [bluetooth-av-delay](https://github.com/fatihkaan22/mpv-bluetooth-av-delay) - Adds desired A-V delay automatically, if default audio sink is a bluetooth device.
- [skip-silence](https://github.com/idMysteries/mpv-skip-silence) - Playback mode that automatically skips/speed up silent parts.
- [dvd-browser](https://github.com/CogentRedTester/mpv-dvd-browser) - Browse and load DVD titles.
- [plugin-myshows](https://github.com/gim-/mpv-plugin-myshows) - Automatically marks a currently watched episode in MyShows.
- [writename](https://github.com/paradox460/mpv-scripts/tree/master/writename) - Write the currently playing filename/path to a file, optionally skipping/removing from current playlist and muting.
- [when-to-loop](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/when-to-loop.lua) - Intelligently decide when mpv should loop, i.e. while shuffling or while playing a short file.
- [UndoRedo](https://github.com/Eisa01/mpv-scripts#undoredo) - If you seek to a different time in the video, press undo [ctrl]+[z] to linearly undo the seeks in the video, and press redo [ctrl]+[y] to linearly return to previous undo positions. More details in the link above.
- [history](https://github.com/stax76/mpv-scripts) - Writes date, time, playtime and filename to a log file: `10.09.2022 19:50  3 D:\Samples\Big Buck Bunny.mkv`
- [history](https://gist.github.com/garoto/e0eb539b210ee077c980e01fb2daef4a) - Simple played media logger. Will generate a `mpvhistory.log` in the default mpv config folder (%APPDATA%/mpv/ or $HOME/.config/mpv/) in the format `[$DATE $TIME] $PATH ($?MEDIA-TITLE)`. Only tested on Windows.
- [excessive-history](https://gist.github.com/Abject-Web/3f4f0e85dad73303b9dd1ef1f55c3147) - Excessive played media logger. Logs file name, time, and which parts were played. Will generate a `history.txt` in the mpv config folder. Only tested on Windows.
- [history-bookmark](https://github.com/yuukidach/mpv-scripts) - Create a history file to store the episode we watched last time. And let us easily jump to the video we watched last time.
- [plugin-bookmark](https://github.com/yozorayuki/mpv-plugin-bookmark) - Record your playing history for each folder.
- [bookmark](https://github.com/sorayuki-winter/mpv-plugin-bookmark) - Record and resume last play in current playing folder
- [bookmarker-menu](https://github.com/NurioHin/mpv-bookmarker) - Menu to manage all your bookmarks.
- [misc](https://github.com/stax76/mpv-scripts) - When seeking display position and duration like so: 70:00 / 80:00
- [misc](https://github.com/stax76/mpv-scripts) - Navigate in playlist to next/previous/first/last file.
- [misc](https://github.com/stax76/mpv-scripts) - Jump to a random position in the playlist.
- [misc](https://github.com/stax76/mpv-scripts) - Load or append files/URLs from clipboard.
- [misc](https://github.com/stax76/mpv-scripts) - Cycle audio and subtitle tracks, include only languages you know.
- [misc](https://github.com/stax76/mpv-scripts) - Show detailed media info on screen.
- [censor](https://github.com/zenyd/mpv-scripts) - Skip over parts of videos you don't want (others) to view
- [autoload](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua) - Automatically load playlist entries before and after the currently playing file, by scanning the directory.
- [total_playtime](https://github.com/oltodosel/mpv-scripts/blob/master/total_playtime.lua) - Shows total playtime of current playlist.
- [track-list](https://github.com/dyphire/mpv-scripts/blob/main/track-list.lua) - Interractive track-list menu.
- [trakt](https://github.com/LiTO773/trakt-mpv) - Connects trakt.tv with mpv and automatically scrobbles movies/shows.
- [tree-profiles](https://github.com/fbriere/mpv-scripts/blob/master/scripts/tree-profiles.lua) - Automatically apply profiles to certain directories or files.
- [timer](https://github.com/AdamD2/mpv-timer) - Allows the user to set a starting time and an ending time and see the time elapsed between those points with millisecond precision.
- [time](https://github.com/mustaqimM/mpv-scripts/blob/master/time.lua) - Shows the current time or the time at which playback will end.
- [stats](https://github.com/Argon-/mpv-stats/) - Display some statistics about the currently played file on-screen.
- [speed - adjusted timings](https://github.com/oltodosel/mpv-scripts#speed_osd3lua) - Recalculates osd-msg3 timecodes with speed != 1
- [speed-transition-Audio](https://gist.github.com/bitingsock/e8a56446ad9c1ed92d872aeb38edf124) - Changes playback speed based on volume thresholds.
- [speed-transition](https://github.com/zenyd/mpv-scripts) - Increases playback speed if a subtitle will not be displayed soon. Resumes normal speed just before the subtitle shows up.
- [speed](https://github.com/oltodosel/mpv-scripts#speedlua) - Changing speed based on regex of filename/path.
- [speed](https://github.com/vflorelle/mpv-scripts#speed) - Always show current playback speed on the OSD.
- [SimpleBookmark-1.0](https://github.com/Eisa01/mpv-scripts#simplebookmark) - Bookmark with a [ctrl]+[b], then list and access your bookmarks with [b]. Assign your favorites to a keybind then access your favorites with that same keybind. Much more explained in the link above.
- [SimpleHistory-1.0](https://github.com/Eisa01/mpv-scripts#simplehistory) - Powerful history features that logs videos that you opened into a log file along with the time you have reached on each video. Select, filter, and search from your history list, Optional resume by [ctrl]+[r] for all videos you have played. Much more explained in the link above.
- [SimpleUndo-3.2](https://github.com/Eisa01/mpv-scripts#simpleundo) - Simple undo feature. If you accidentally seek/jump to a different time in the video, press undo [ctrl]+[z] to return to your previous time and vice-versa. More details in the link above.
- [skipchapters](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/scripts/avail/skipchapters.lua) - Automatically skip chapters matching a given list of regular expressions (eg. "OP" or "Opening").
- [skiptofade](https://gist.github.com/bossen/3cfe86a6cdd61452dbb96865128fb327) - Seeks forward until a black screen appears. Built to skip openings. Uses the lavfi blackdetect filter. 
- [skiptosilence](https://github.com/detuur/mpv-scripts) - This script skips to the next silence in the file. The intended use for this is to skip until the end of an opening or ending sequence, at which point there's often a short period of silence.
- [save-playlist](https://github.com/NaiveInvestigator/save-playlist) - This script saves your playlist to the working directory of the mpv process.
- [rewindPlaylist](https://gist.github.com/bitingsock/0f22c631295273d5a53e4337c25fe161) - keybind to rewind to the end of the previous playlist entry
- [seek-to](https://github.com/occivink/mpv-scripts#seek-tolua) - Seek to an absolute timestamp specified via keyboard input.
- [review](https://gitlab.com/lvml/mpv-plugin-review) - Allows to remove files viewed quickly from within mpv
- [reload](https://github.com/dya-tel/mpv-scripts) - Sometimes you have unstable internet connection, or YouTube server dies, or your computer was sleeping for too long, or whatever. The thing is: you were watching something, you lost the connection, MPV doesn't want to play it further, you don't want to find the video again and then seek it to the moment you were watching.
- [reload](https://github.com/4e6/mpv-reload) - When an online video is stuck during buffering or got slow CDN source, restarting often helps. This script provides automatic reloading of videos that didn't have buffering progress for some time, keeping the current time position. It also adds `Ctrl+r` keybinding to reload video manually.
- [radio-title](https://github.com/olivierlemoal/mpv-radio-title-script/) - Automatically fetch current playing title from webradio website when not provided by stream.
- [playlistnoplayback](https://github.com/422658476/MPV-EASY-Player/blob/master/portable-data/scripts/playlistnoplayback.lua) - If you enable the save play history and progress function, this lua script can solve the problem of automatically jumping to the previous playback progress when playing the next file when playing the playlist, that is, let the playlist always play the next file from the beginning every time. the limitations of this script, please see the comments section in the content.
- [playlist-view](https://github.com/occivink/mpv-gallery-view) - Display and navigate the playlist in a grid view of thumbnails.
- [playlist-navigator](https://github.com/drogers141/mpv-playlist-navigator) - OSD display features easy navigation with scrolling and search to select files to play or remove from playlist.
- [permanent-pause-indicator](https://github.com/oltodosel/mpv-scripts#pause-indicatorlua) - Displays a permanent indicator in the middle of the screen while mpv is paused. [Preview](https://github.com/oltodosel/mpv-scripts/raw/master/pause-indicator.jpg)
- [pause-indicator](https://gist.github.com/torque/9dbc69543118347d2e5f43239a7e609a) - Displays a momentary icon that flashes in the middle of the screen, similar to YouTube.
- [nextfile](https://github.com/jonniek/mpv-nextfile) - Force opens next or previous file in the currently playing files directory.
- [Change-OSD-Media-Title](https://github.com/nmoorthy1/mpv-Change-OSD-Media-Title) - Displays filename, percentage watched, current chapter, and number of frames dropped in the OSD media title and updates it whenever one of the values has changed.
- [bookmarker](https://github.com/nimatrueway/mpv-bookmark-lua-script) - Bookmark your favorite time on media files
- [List chapters](https://github.com/oltodosel/mpv-scripts#show_chapterslua) - Shows chapters and their time at the bottom left corner. [example](https://github.com/oltodosel/mpv-scripts/raw/master/show_chapters.jpeg)
- [lats](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/lats.lua) - The Low ATtention Span mpv script. Plays brief segments from random positions of one or more files, kinda like flipping through TV channels.
- [interactive-video](https://github.com/mosquito-byte/mpv-interactive-video) - Script for watching interactive videos (such as Netflix's *Black Mirror: Bandersnatch*).
- [guess-media-title](https://github.com/zenwarr/mpv-config/blob/master/scripts/guess-media-title.lua) - Uses [guessit](https://github.com/guessit-io/guessit) to detect a media title by filename and set `force-media-title` variable. Useful for getting cleaner screenshot file names.
- [fastforward](https://github.com/jgreco/mpv-scripts/blob/master/fastforward.lua) - Instead of skipping forward in media files, speed up the playback for a few seconds.  Playback speed decays back to 1x after a few seconds.  Tap rapidly or hold down to go faster.
- [evafast](https://github.com/po5/evafast) - Fast-forwarding and seeking on a single key, with quality of life features like slowing down a bit when subtitles are shown.
- [autoloop](https://github.com/zc62/mpv-scripts/blob/master/autoloop.lua) - Automatically loops files that are under a given duration (default 5 seconds).
- [autosave](https://gist.github.com/Hakkin/5489e511bd6c8068a0fc09304c9c5a82) - Periodically saves "watch later" data during playback, rather than only saving on quit. Newer [fork](https://gist.github.com/CyberShadow/2f71a97fb85ed42146f6d9f522bc34ef).
- [auto-save-state](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/auto-save-state.lua) - Periodically saves progress with write-watch-later-config, and also cleans up the watch later data after the file is finished playing (so playlists may continue at the correct file).
- [always-play-on-startup](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/always-play-on-startup.lua) - Always play on startup, never start playback in a paused state.

## Files

- [file-browser](https://github.com/CogentRedTester/mpv-file-browser) - On screen file browser. 
- [filenavigator](https://github.com/jonniek/mpv-filenavigator) - Navigate and open local files.
- [delete-current-file](https://github.com/stax76/mpv-scripts) - Moves the current file instantly to the recycle bin.
- [delete-file](https://github.com/zenyd/mpv-scripts) - Delete files being played.
- [file-rating](https://github.com/stax76/mpv-scripts) - Writes a star rating to the filename of the current file.
- [open-file-dialog](https://github.com/rossy/mpv-open-file-dialog) - Launch a Windows open file dialog.
- [zenity-open-files](https://github.com/alifarazz/mpv-zenity-open-files) - Use GTK's zenity to add files to playlist, subtitles to playing video or open URLs.
- [KDialog-open-files](https://gist.github.com/ntasos/d1d846abd7d25e4e83a78d22ee067a22) - Use KDE's KDialog to add files to playlist, subtitles to playing video or open URLs.
- [simple-loader](https://github.com/fhlfibh/simple-loader) - (Linux) Browse dirs and files on OSD, and launch them with mpv.
- [Serkio Tagger](https://github.com/SerkioTeam/Tagger) - Annotate videos with tags while you watch.
- [show-filename](https://github.com/yuukidach/mpv-scripts) - Show the name of the current playing file.
- [rename](https://github.com/Kayizoku/mpv-rename) - Rename files on the go directly from within MPV player window without leaving it.
- [limited-autoload](https://github.com/glubsy/mpv-limited-autoload) - Auto-load files in a lazy way by limiting how many are loaded into playlist at once
- [locate-file](https://github.com/nimatrueway/mpv-locatefile-lua-script) - Locate current media file on your OS file browser 
- [fuzzydir](https://github.com/dya-tel/mpv-scripts) - This script will read your paths from `mpv.conf`, find those which end with `**` and explode them for good! For example, imagine we have a directory named `subs`, which contains `a` and `b` subdirectories.
- [fuzzydir](https://github.com/sibwaf/mpv-scripts) - Allows using wildcards for `sub-file-paths` and `audio-file-paths`.

## On Screen Controller

- [uosc](https://github.com/tomasklaen/uosc) - Minimalist proximity-based UI.
- [osc-modern](https://github.com/maoiscat/mpv-osc-modern) - Modern OSC replacement.
- [ModernX](https://github.com/cyl0/ModernX) - Modern OSC replacement.
- [modern-x-compact](https://github.com/1-minute-to-midnight/mpv-modern-x-compact) - Compact version of modern-x.
- [tethys](https://github.com/Zren/mpv-osc-tethys) - OSC replacement with seekbar thumbnail preview.
- [dark-box](https://github.com/maoiscat/mpv-dark-box) - OSC replacement.
- [oscc](https://github.com/longtermfree/oscc) - Dark-themed OSC.
- [thumbnail_script](https://github.com/felipefacundes/mpv_thumbnail_script) - Shows preview thumbnails in the seekbar.
- [thumbnail_script](https://github.com/TheAMM/mpv_thumbnail_script) - Shows preview thumbnails in the seekbar.
- [thumbnail_script](https://github.com/marzzzello/mpv_thumbnail_script) - Shows preview thumbnails in the seekbar.
- [sosc](https://github.com/christoph-heinrich/sosc) - An OSC supplement for OSC replacements. Provides the idle message and script messages from the original OSC.
- [progressbar](https://github.com/torque/mpv-progressbar) - A minimalistic OSC replacement. It provides a small, unintrusive progress bar that persists at the bottom of the video window.
- [osd-bar](https://github.com/422658476/MPV-EASY-Player/blob/master/portable-data/scripts/osd-bar.lua) - Always show osd progress bar, with the more beautiful color matching in the [configuration file](https://github.com/422658476/MPV-EASY-Player/blob/master/mpv-easy-data/rjno1.conf), you can make the osd progress bar display the current progress at the bottom of the window beautifully,this is a [preview](https://raw.githubusercontent.com/422658476/MPV-EASY-Player/master/img/mpv-easy-player-osd-bar-lua.jpg).
- [osc-style](https://github.com/422658476/MPV-EASY-Player/tree/master/mpv-easy-data/osc-style) - Change the mpv osc to a more beautiful and practical look, which is the osc theme feature, a variety of styles to choose from,this is a [tutorial and a preview](https://github.com/422658476/MPV-EASY-Player#%E7%9C%8B%E5%88%B0%E4%B8%8A%E9%9D%A2%E5%9B%BE%E4%B8%8A%E8%BF%99%E4%BA%9Bosc%E6%A0%B7%E5%BC%8F%E4%BA%86%E5%90%97%E5%AE%83%E4%BB%AC%E4%B8%8D%E4%BB%85%E5%8F%AF%E4%BB%A5%E5%AD%98%E5%9C%A8%E4%BA%8Empv-easy-player%E4%B8%AD%E4%BD%A0%E4%BD%BF%E7%94%A8%E7%9A%84mpv%E7%9A%84osc%E4%B9%9F%E5%8F%AF%E4%BB%A5%E5%8F%98%E6%88%90%E8%BF%99%E6%A0%B7).
- [osc-show-hide-hotkey](https://github.com/linguisticmind/mpv-scripts/tree/master/osc-show-hide-hotkey) - Toggles the on-screen controller with a hotkey. [Video demonstration](https://www.youtube.com/watch?v=b-5XOZpXZMg&t=1h7m17s)
- [osc-orange](https://github.com/maoiscat/mpv-osc-orange) - An osc/ui replacement in dark theme.
- [mfpbar](https://codeberg.org/NRK/mpv-toolbox/src/branch/master/mfpbar) - A minimalistic progressbar and osc replacement.

## Input

- [gestures](https://github.com/omeryagmurlu/mpv-gestures) - Touchscreen and mouse gestures.
- [cheatsheet](https://github.com/ento/mpv-cheatsheet) - Looking up keyboard shortcuts (bindings).
- [InputEvent](https://github.com/Natural-Harmonia-Gropius/InputEvent) - Enhanced input.conf with better, conflict-free, low-latency event mechanism.
- [zones](https://github.com/wiiaboo/mpv-scripts/blob/master/zones.lua) - Handles commands depending on where the mouse pointer is at, mostly for mouse wheel handling.
- [russian-layout-bindings](https://github.com/zenwarr/mpv-config/blob/master/scripts/russian-layout-bindings.lua) - As mpv does not support shortcuts independent of the keyboard layout (https://github.com/mpv-player/mpv/issues/351), this script tries to workaround this issue for some limited cases with russian (йцукен) keyboard layout. Upon startup, it takes currently active bindings from `input-bindings` property and duplicates them for russian layout. You can adapt the script for your preferred layout, but it won't (of course) work for layouts sharing unicode characters with english.
- [repl](https://github.com/rossy/mpv-repl) - A REPL for input commands that is displayed on the video window.
- [pointer-event](https://github.com/christoph-heinrich/mpv-pointer-event) - Low latency mouse/touch input event detection. Executes configurable commands on single-click, double-click, long-click and dragging. Events are mutually exclusive. See [example](https://github.com/christoph-heinrich/mpv-pointer-event#example) for simple gesture detection.
- [multisocket](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/multisocket.lua) - Creates a numbered socket for each instance of mpv.
- [Sockets](https://github.com/wis/mpvSockets) - creates one IPC sockets per mpv instance, instead of one socket for the last started instance.   _Supports_: Linux, MacOS and Windows.
- [multi-command-if](https://github.com/VideoPlayerCode/mpv-tools/) - Very powerful conditional logic and multiple action engine for your keybindings, without having to write a single line of code!
- [leader key](https://github.com/Seme4eg/mpv-scripts/tree/master#leader) - Adds _leader_ key to your mpv. With prefixes and [which-key](https://github.com/justbur/emacs-which-key) functionality. [demo](https://i.imgur.com/dUWFu3u.gif)
- [cycle-commands](https://github.com/CogentRedTester/mpv-scripts/blob/master/cycle-commands.lua) - Allows input.conf commands to be cycled through with keybinds.
- [cycle_messages](https://gist.github.com/rrooij/59f57ff5f5a952e56bbb) - Cycle between custom OSD messages.
- [boss-key](https://github.com/detuur/mpv-scripts) - Minimise and pause video at the same time. Windows/Linux. Eliminated the time lag in previous versions.
- [blackout](https://github.com/dya-tel/mpv-scripts) - Couldn't find the "Boss key", but you don't want someone (or simply anyone) to see what you are watching?
- [blackout](https://github.com/sibwaf/mpv-scripts) - A fast crossplatform boss-key, but without window minimization (and possible problems with some VO drivers).
- [audio-file-keys](https://github.com/fbriere/mpv-scripts/blob/master/scripts/audio-file-keys.lua) - Automatically apply key bindings when playing audio files.
- [auto-mode](https://github.com/stax76/mpv-scripts/blob/main/auto-mode.lua) - Use mpv as video player, music player and image viewer, switch automatically between, video, audio and image mode.

## Subtitle

- [assrt](https://github.com/AssrtOSS/mpv-assrt) - Automatically download subtitles from assrt.net.
- [autosub](https://github.com/davidde/mpv-autosub) - Automatic subtitle downloading.
- [sub-select](https://github.com/CogentRedTester/mpv-sub-select) - Advanced conditional subtitle track selector.
- [autosubsync](https://github.com/Ajatt-Tools/autosubsync-mpv) - Automatic subtitle synchronization script.
- [intersubs](https://github.com/abdnh/intersubs) - Interactive subtitles.
- [sub-transition](https://github.com/Ajatt-Tools/sub-transition) - Speed up the video if no subtitles are visible.
- [sub](https://github.com/yassin-l/submpv) - Automatic downloading/adding of subtitles from subscence.
- [tts-subs](https://github.com/jgreco/mpv-scripts/blob/master/tts-subs.lua) - Use voice synthesis to read subtitles out-loud.
- [trueautosub](https://github.com/fullmetalsheep/mpv-iina-scripts) - Fork of autosub, automatically downloads subtitles if not present using **subliminal**. (osx/linux only)
- [subtitle-search](https://github.com/zenwarr/mpv-config/blob/master/scripts/subtitle-search.lua) - Script to search for a phrase inside an active `.srt` subtitle. Displays matched lines in OSD list, takes `sub-delay` into account and allows searching for Unicode text in utf8 subtitle files.
- [subselect Tk](https://github.com/zenyd/mpv-scripts) - Download subtitles with a GUI - select the one you want and automatically load them up in mpv. Supports searching for arbitrary names and different subtitle languages. Works on Windows and Linux, possibly macOS.
- [subit](https://github.com/wiiaboo/mpv-scripts/blob/master/subit.lua) - Yet another script for downloading subtitles using subliminal. Supports better customization of options, such as easy language selection, authentication for providers that need it, and support for URLs.
- [sub_export](https://github.com/dyphire/mpv-scripts/blob/main/sub_export.lua) - fork, updated. Extract selected subtitles from .mkv file.
- [sub-bilingual](https://github.com/kelciour/mpv-scripts/blob/master/sub-bilingual.lua) - Generate bilingual subtitles.
- [sub-bookmarks](https://github.com/kelciour/mpv-scripts/blob/master/sub-bookmarks.lua) - Save current position and subtitles in .txt file.
- [sub-export](https://github.com/kelciour/mpv-scripts/blob/master/sub-export.lua) - original, outdated
- [sub-pause](https://github.com/Ben-Kerman/mpv-sub-scripts) - Automatically pause just before the end of each subtitle line. Also allows replaying the currently active line.
- [sub-playback](https://github.com/kelciour/mpv-scripts/blob/master/sub-playback.lua) - Add interactive move, i.e. automatically pause at the end of the fragment with option to continue playback or replay it again with or without subtitles.
- [sub-replay](https://github.com/kelciour/mpv-scripts/blob/master/sub-replay.lua) - Replay previous sentence.
- [sub-search](https://github.com/kelciour/mpv-scripts/blob/master/sub-search.lua) - Search for phrase in subtitles and skip to it.
- [sub-sentences](https://github.com/kelciour/mpv-scripts/blob/master/sub-sentences.lua) - Generate subtitles with sentences.
- [sub-skip](https://github.com/Ben-Kerman/mpv-sub-scripts) - Automatically skip parts of a video that don't contain any subtitles. Does so by either fast-forwarding or seeking.
- [sub-transition](https://github.com/Ajatt-Tools/sub_transition) - Speed up playback when no subtitles are visible. 
- [sub](https://github.com/vflorelle/mpv-scripts#sub) - Select subtitle by id via input box (Windows)
- [save-sub-delay](https://github.com/zc62/mpv-scripts/blob/master/save-sub-delay.lua) - This script saves the sub-delay quantity for each file. When next time the file is opened, sub-delay is automatically restored.
- [restore-subtitles](https://github.com/zenwarr/mpv-config/blob/master/scripts/restore-subtitles.lua) - Saves selected subtitle tracks and visibility state to `saved-subs.json` file in config directory and restores them whenever file is loaded. Differs from `watch-later`-saved data in that it saves secondary subtitles too (and uses subtitle file paths instead of ids).
- [playphrase](https://github.com/kelciour/playphrase) - Search and play phrases from movies and audiobooks.
- [copy-subtitle](https://github.com/linguisticmind/mpv-scripts/tree/master/copy-subtitle) - Copies currently displayed subtitle line to clipboard.
- [libass_sub_selector](https://github.com/po5/libass_sub_selector) - Visually select individual subtitles a la PotPlayer.
- [fix_sub_timing](https://github.com/wiiaboo/mpv-scripts/blob/master/fix-sub-timing.lua) - Compute the correct speed/delay of subtitles by manually synching two points in time.
- [find_subtitles](https://github.com/directorscut82/find_subtitles) - (Down)load subtitles with subliminal.
- [dessubdb](https://github.com/demanuel/dessubdb/blob/master/mpv.lua) - Download automatically subtitles from the thesubdb.com using [DESSubdb](https://github.com/demanuel/dessubdb).
- [autosubsync](https://github.com/joaquintorres/autosubsync-mpv) - Automatically sync subtitles using **ffsubsync**.
- [autosub](https://github.com/vayan/autosub-mpv/blob/master/autosub.lua) - Automatically download subtitles using **subliminal**.
- [Audio WebDAV & Sub WebDAV](https://github.com/Kibakus/mpv-scripts) - Auto connection of external subtitles and sound, using the "WEBDAV" protocol. The connection is explicit due to explicitly specifying folders on the WebDAV server.

## Learning

- [mpvacious](https://github.com/Ajatt-Tools/mpvacious) - Add keybindings to create Anki flashcards for (language) learning.
- [interSubs](https://github.com/oltodosel/interSubs) - Interactive subtitles, instantly translate selected word/sentence.
- [immersive](https://github.com/Ben-Kerman/immersive) - Looking up words generating Anki flashcards.
- [migaku](https://github.com/migaku-official/migaku-mpv) - Learn languages together with the Migaku browser extension.
- [Yomichampv](https://github.com/laelnasan/yomichampv) - A simple solution for integration with Yomichan - a browser-based japanese dictionay.
- [subs2srs](https://github.com/kelciour/mpv-scripts/blob/master/subs2srs.lua) - Automatically add new card in Anki with audio, picture and text.
- [sub-voracious](https://github.com/kelciour/mpv-scripts/blob/master/sub-voracious.lua) - Reading and listening practice.
- [rikai](https://github.com/fxmarty/rikai-mpv) - Integrated Japanese dictionary and parser to translate by hovering over words. Works on Linux.
- [mpv2anki](https://github.com/SenneH/mpv2anki) - A simple way to add notes to Anki with Audio, screenshots and/or subtitles, with few dependencies.
- [lang-learner](https://github.com/liberlanco/mpv-lang-learner) - Turn MPV into language learner tool. Includes:  AB-loop current subtitle or auto loop each one, quick switch between lang you know and lang you are learning, forward to browser (dictionaries, translators), record for future extra learning, export to external script for integrations, and a bit more.

## Music

- [coverart](https://github.com/CogentRedTester/mpv-coverart) - Automatically loads external cover art for music files.
- [metadata-osd](https://github.com/vc-01/metadata-osd) - Adds OSD showing song name, album name and other metadata.
- [lrc](https://sr.ht/~guidocella/mpv-lrc) - Download synchronized lyrics of the currently playing song.

## Audio

- [Open Sound Control](https://github.com/lvm/mpv-osc) - Open Sound Control listener.
- [visualizer](https://github.com/mfcc64/mpv-scripts/blob/master/visualizer.lua) - Various audio visualizations.
- [smart-volume](https://github.com/stax76/mpv-scripts) - Replay gain alternative.
- [pitchcontrol](https://github.com/FichteFoll/mpv-scripts/blob/master/pitchcontrol.lua) - Adjusts audio pitch in half-tone steps.
- [volnorm](https://gitlab.com/derobert/mpv-volnorm) - Client-server setup to provide EBU R.128 volume leveling to MPV, even if files stored on a server and played on multiple machines. (Works on Linux, probably all Unix-like; server in Perl).
- [firequalizer15](https://github.com/mfcc64/mpv-scripts/blob/master/firequalizer15.lua) - Linear phase 15-bands equalizer.
- [equalizer](https://gist.github.com/avih/41acff712abd32e1f436235388c8b523) - 5-bands equalizer with colorful display.
- [drcbox](https://gist.github.com/richardpl/0c8011dc23d7ac7b7831b2e6d680114f) - Dynamic Audio Normalizer filter with visual feedback.
- [dbvol](https://gist.github.com/Artefact2/0a9c87d6d0f0ef6a565e44d830943fff) - Replaces the default volume controls with a decibel (dB) scale instead of arbitrary percentages.
- [cycle-audio-device](https://gist.github.com/bitingsock/ad58ee5da560ecb922fa4a867ac0ecfd) - Cycle through available audio devices with key binds.
- [channel mixer](https://gist.github.com/bitingsock/1e7ef04a151963b38e347a723d7e3201) - A set of keybindings using a modifier (Shift or Ctrl) and the function keys (F8-F12) to can adjust the mixing level of surround channels on the fly.
- [audio-dupe](https://gist.github.com/bitingsock/5e9714efff963c9689b0671d68f195ad) - Runs a child process to play a second audio stream. Synced through named pipe.
- [audio-balance](https://github.com/wiiaboo/mpv-scripts/blob/master/audio-balance.lua) - Port of mpv's balance property to FFmpeg lavfi pan filter.
- [Audio WebDAV & Sub WebDAV](https://github.com/Kibakus/mpv-scripts) - Auto connection of external subtitles and sound, using the "WEBDAV" protocol. The connection is explicit due to explicitly specifying folders on the WebDAV server.
- [adevice-list](https://github.com/dyphire/mpv-scripts/blob/main/adevice-list.lua) - Interractive audio-device list menu.
- [acompressor](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/acompressor.lua) - Dynamic range compressor using acompressor ffmpeg filter with controls to dynamically adjust parameters.

## Streaming

- [jellyfin](https://github.com/EmperorPenguin18/mpv-jellyfin) - Turns mpv into a Jellyfin client.
- [mpvDLNA](https://github.com/chachmu/mpvDLNA) - Browse and watch content hosted on DLNA servers.
- [selectformat](https://github.com/ghesy/mpv-selectformat) - Select the format (quality) of internet videos.
- [sponsorblock_minimal](https://codeberg.org/jouni/mpv_sponsorblock_minimal) - More simple version of the sponsorblock script.
- [sponsorblock](https://github.com/po5/mpv_sponsorblock) - Script to skip sponsored segments of YouTube videos.
- [streamsave](https://github.com/Sagnac/streamsave) - Save live streams without encoding.
- [mpvf](https://github.com/seanbreckenridge/mpvf) - Select youtube-dl format for streaming.
- [quality-menu](https://github.com/christoph-heinrich/mpv-quality-menu) - Change the streamed video and audio quality (ytdl-format) on the fly.
- [youtube-download](https://github.com/cvzi/mpv-youtube-download) - Download YouTube audio and video with one key press.
- [youtube-search](https://github.com/CogentRedTester/mpv-scripts/blob/master/youtube-search.lua) - A script that allows users to search youtube and open results from within mpv. Requires a couple of extra API scripts, along with curl and a personal youtube API key.
- [youtube-search](https://github.com/rozari0/mpv-youtube-search) - Use zenity and youtube-dl to search YouTube.
- [youtube-upnext](https://github.com/cvzi/mpv-youtube-upnext) - A menu for (auto) playing YouTube's "up next"/recommended videos, that show up on the right side on the website.
- [ytdlautoformat](https://github.com/Samillion/mpv-ytdlautoformat) - Auto change ytdl-format for Youtube and Twitch.
- [ytdl-preload](https://gist.github.com/bitingsock/17d90e3deeb35b5f75e55adb19098f58) - Precache the next entry in your playlist if it is a network source by downloading it to a temp file ahead of time. Updated to download all streams in parallel so you can watch it while it downloads.
- [webtorrent-hook](https://github.com/noctuid/mpv-webtorrent-hook) - Allows streaming torrents using webtorrent (same as mpv-peerflix-hook but using webtorrent instead). Webtorrent-cli can play in mpv with `webtorrent --mpv`, but this script allows using torrent identifiers as the file argument to mpv or pasting them into the current playlist using one of the pasting scripts listed here. It also supports additional functionality like automatic file cleanup and the ability to remember the last file played in the torrent. See the readme for more information. See [here](https://github.com/noctuid/mpv-webtorrent-hook#comparison-with-webtorrent-mpv-hook) for a comparison with the other javascript webtorrent plugin. I recommend this plugin over my others (mpv-peerflix-hook and btfs-stream).
- [play-with](https://github.com/grmat/play-with) - A web browser extension that can open a video stream on a web page with an external player.
- [confluence](https://github.com/ftk/mpv-confluence) - Open magnet links using [confluence](https://github.com/anacrolix/confluence) HTTP service.
- [btfs-hook](https://github.com/aitet/mpv-btfs-hook) - Allows streaming torrents using FUSE via btfs. 
- [btfs-stream](https://github.com/noctuid/mpv-btfs-stream) - Allows streaming torrents using btfs. As far as I can tell, it is much simpler than the above scripts (no long shell script execution) and much more configurable (the other scripts have no settings). This is much slower than using webtorrent though, so I recommend using webtorrent-hook instead.
- [streamcache](https://gitlab.com/lvml/mpv-plugin-streamcache) - Provides for more network-glitch-robust caching of live streams by adjusting replay speed.
- [stopCache](https://gist.github.com/bitingsock/19c3094cc8680bb7b97b09aaf7d11176) - stops the demuxer from downloading more if it is already past --end 
- [spotify](https://github.com/olivierlemoal/mpv-spotify-script) - Add current playing title to an user defined Spotify playlist.
- [sopcast](https://github.com/Akemi/mpv-sopcast-hook) - Adds support for sop:// urls.
- [show-stream-title](https://github.com/blue-sky-r/mpv/blob/master/scripts/show-stream-title.lua) - Show OSD stream/channel title when switching the IPTV channels from m3u playlist.
- [peerflix-hook](https://gist.github.com/ekisu/bba287693830055a6bad90081c1ad4e2) - Allows streaming of magnet links using peerflix, similar to youtube-dl.
- [yledl](https://github.com/pekkarr/mpv-yledl) - Watch videos from YLE Areena in mpv using yle-dl
- [peerflix-hook](https://github.com/noctuid/mpv-peerflix-hook) - Stream magnet links in mpv with peerflix.
- [acestream](https://github.com/Digitalone1/mpv-acestream) - Add AceStream protocol handler to mpv. Let the user open streams by dropping Acestream links into mpv GUI or by passing them as command line argument.
- [reduce_stream_cache](https://github.com/divout/mpv_reduce_stream_cache) - Reduces MPV cache for streams by increasing playback speed. Works with Twitch through Streamlink.
- [last.fm scrobbler](https://github.com/l29ah/w3crapcli/blob/master/last.fm/mpv-lastfm.lua) - Sends the information about playing tracks to [last.fm](http://last.fm/), see http://www.last.fm/help/faq?category=99 for more info.

## Video

- [changerefresh](https://github.com/CogentRedTester/mpv-changerefresh) - Automatically change the refresh rate of the current display to match the playing video.
- [autospeed](https://github.com/kevinlekiller/mpv_scripts/blob/master/autospeed/) - To adjust monitor refresh rate and video speed for almost 1:1 playback. (*nix)
- [autospeedwin](https://github.com/kevinlekiller/mpv_scripts/tree/master/autospeedwin) - To adjust monitor refresh rate and video speed for almost 1:1 playback. (Windows)
- [gpufreq](https://github.com/CounterPillow/mpv-gpufreq) - Displays the current and maximum GPU frequency as an osd message.
- [mvtools-script](https://github.com/maoiscat/mpv-mvtools-script) - vapoursynth-mvtools script.
- [store-shaders](https://github.com/butterw/bShaders/blob/master/mpv/settings/scripts/store-shaders.js) - Store current glsl-shaders config on first run, this config will then be restored by subsequent calls.
- [switch-shader](https://github.com/butterw/bShaders/blob/master/mpv/settings/scripts/switch-shader.js) - Provides a switch to disable/restore shaders and vf filters.
- [xrandr](https://gitlab.com/lvml/mpv-plugin-xrandr) - Automatically sets the display refresh rate to the one best suitable for the video played
- [vlcaspectratio](https://github.com/kism/mpvscripts/blob/main/scripts/vlcaspectratio.lua) - Implements a VLC style aspect ratio hotkey 'a' that stretches the video to different aspect ratios.
- [cycle-video-rotate](https://github.com/VideoPlayerCode/mpv-tools/) - Allows you to perform video rotation which perfectly cycles through all 360 degrees without any glitches.
- [autocrop](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autocrop.lua) - Automatically crop the video by using lavfi's cropdetect filter to detect black bars.
- [vlccrop](https://github.com/kism/mpvscripts/blob/main/scripts/vlccrop.lua) - Implements a VLC style crop hotkey 'c' that cycles through crop settings, useful for cropping letter-boxed or pillar-boxed content.
- [matroska-crop](https://github.com/sbruder/mpv-matroska-crop) - Automatically crop video using the Matroska PixelCrop properties. Includes optional workaround for hardware decoding.
- [dynamic-crop](https://github.com/Ashyni/mpv-scripts#dynamic-croplua) - Dynamically crop the video by using lavfi's cropdetect filter to detect hard-coded black bars for Ultra Wide Screen (21:9) or any screen different from 16:9 (phone/old TV).
- [crop](https://github.com/occivink/mpv-scripts#croplua) - Crop the video by defining the target rectangle with the cursor
- [cropmode](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/cropmode.lua) - Adds a keyboard-oriented mode for cropping, outputting the result in a format suitable for ffmpeg.
- [use-cpu](https://github.com/422658476/MPV-EASY-Player/blob/master/portable-data/scripts/use-cpu.lua) - If the width of the video is greater than 3000 or the height of the video is greater than 2000, it will automatically switch back to using cpu decoding.
- [waveform](https://github.com/MikelSotomonte/mpv-waveform/tree/main) - Displays a waveform of the video in real-time.
- [BoxToWide](https://github.com/Samillion/mpv-boxtowide) - A simple mpv script to change 4:3 aspect-ratio of video files/streams to 16:9 automatically.
- [frame_info](https://github.com/Kagami/mpv_frame_info) - Show frame info, similar to ffdshow's OSD.
- [live-filters](https://github.com/hdb/mpv-live-filters) - Add, remove or toggle ffmpeg video filters during mpv playback.
- [histogram](https://github.com/detuur/mpv-scripts) - Exposes a configurable way to overlay ffmpeg histograms in mpv. There is a substantial amount of config available.
- [filter-test](https://gitlab.com/mozbugbox/mpv-script-mozbugbox) - Test mpv/FFmpeg video filter(vf) strings with editable popup dialog. 
- [cycle-denoise](https://gist.github.com/myfreeer/d744c445aa71c0eeb165ca39cf6c0511) - Cycle between lavfi's denoise filters (press n)
- [autodeint](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autodeint.lua) - Automatically deinterlace the video by using lavfi's idet filter to detect interlaced content.
- [cycle-deinterlace-pullup](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/cycle-deinterlace-pullup.lua) - Cycle between deinterlacing, pullup (IVTC), and both filters off.
- [curvesman](https://gitlab.com/mozbugbox/mpv-script-mozbugbox) - Manipulate color curves filter of FFmpeg with hotkeys. Brighten up color, change color temperature/tone, hopefully more. Adjust yellow light tone to white light tone.
- [blur-edges](https://github.com/occivink/mpv-scripts#blur-edgeslua) - Replace black bars with a blurry copy of the video

## Image

- [thumbfast](https://github.com/po5/thumbfast) - High-performance on-the-fly thumbnailer for mpv.
- [screenshot-to-clipboard](https://github.com/zc62/mpv-scripts/blob/master/screenshot-to-clipboard.js) - Takes a screenshot and saves it to the clipboard.
- [takeSsSequence](https://github.com/Arieleg/mpv-takeSsSequence) - Take a sequence of equispaced screenshots.
- [clipshot](https://github.com/ObserverOfTime/mpv-scripts/blob/master/clipshot.lua) - Screenshot the video (with subs, without subs or the whole window) and copy it to the clipboard. For Windows, Linux/BSD and MacOs
- [crop_script](https://github.com/TheAMM/mpv_crop_script) - Take cropped screenshots.
- [gif-generator](https://github.com/the-honey/mpv-gif-generator) - Creates animated gifs using hotkeys.
- [auto-mode](https://github.com/stax76/mpv-scripts/blob/main/auto-mode.lua) - Use mpv as video player, music player and image viewer, switch automatically between, video, audio and image mode.
- [waifu2x](https://github.com/jonniek/mpv-waifu2x) - Take screenshot and convert images with waifu2x.
- [webp-generator](https://github.com/DonCanjas/mpv-webp-generator) - Creates animated webp using mpv hotkeys. (Windows only)
- [image-config](https://sr.ht/~guidocella/mpv-image-config) - A configuration to use mpv as an image viewer.
- [gallery-dl_hook](https://github.com/jgreco/mpv-scripts/blob/master/gallery-dl_hook.lua) - Load online image galleries (imgur, etc) as playlists using [gallery-dl](https://github.com/mikf/gallery-dl/).
- [contact-sheet](https://github.com/occivink/mpv-gallery-view) - Display thumbnails of the current file in the style of a contact sheet
- [abs-screenshot](https://github.com/Thann/mpv-abs-screenshot/blob/master/abs-screenshot.lua) - Uses Exiftool to get the "Date/Time Original" and saves a screenshot with the name being the actual time the video was taken.
- [mpv-image-viewer](https://github.com/occivink/mpv-image-viewer) - Configuration, scripts and tips for using mpv as an image viewer.

## Video Editing

- [trim](https://github.com/aerobounce/trim.lua) - Trim clips without transcoding.
- [easycrop](https://github.com/aidanholm/mpv-easycrop) - Cropping videos with ease.
- [videoclip](https://github.com/Ajatt-Tools/videoclip) - Create video and audio clips.
- [video-splice](https://github.com/pvpscript/mpv-video-splice) - Create a video out of cuts.
- [Pure](https://github.com/4ndrs/PureMPV) - Get the file path, timestamps, and cropping coordinates for ffmpeg.
- [cut](https://github.com/b1scoito/mpv-cut) - Video cutting/clipping/slicing script.
- [sub-cut](https://github.com/kelciour/mpv-scripts/blob/master/sub-cut.lua) - Extract a part of the video as audio or video with subtitles.
- [slicing](https://github.com/Kagami/mpv_slicing) - Cut uncompressed fragments of the video.
- [slicing_copying](https://github.com/snylonue/mpv_slicing_copy) - Cut fragments of video in original format.
- [excerpt](https://gitlab.com/lvml/mpv-plugin-excerpt) - Allows you to quickly create excerpts from media files, you just have to set begin and end markers.

## Social

- [cord](https://github.com/yutotakano/mpvcord) - Discord integration for mpv, using the Game SDK instead of Discord RPC. Supports: MacOS and Windows. (Linux is not supported by Game SDK)
- [discordRPC](https://github.com/cniw/mpv-discordRPC) - Discord Rich Presence integration.
- [discordRPC](https://github.com/noaione/mpv-discordRPC) - Discord RPC integration for mpv using lua-discordRPC as base.
- [discord](https://github.com/tnychn/mpv-discord) - A cross-platform Discord Rich Presence integration for mpv with no external dependencies. Consists of a Go binary for updating the presence and a Lua script for launching it.
- [irc](https://github.com/po5/mpv_irc) - Displays lines from an irc channel.
- [LoadDanmaku](https://github.com/huisedenanhai/LoadDanmaku) - Load local damaku files.
- [youtube-chat](https://github.com/BanchouBoo/mpv-youtube-chat) - Overlays YouTube chat on top of a video using yt-dlp.
- [twitch-chat-irc](https://github.com/morrah/mpv-twitch-chat-irc) - Show Twitch chat messages as subtitles when watching Twitch LIVE.
- [twitch-chat](https://github.com/CrendKing/mpv-twitch-chat/) - Show Twitch chat messages as subtitles when watching Twitch VOD with mpv.

## Configuration

- [persist-properties](https://github.com/d87/mpv-persist-properties) - Keep selected property values (like volume) between player sessions.
- [remember-props](https://github.com/zenwarr/mpv-config/blob/master/scripts/remember-props.lua) - When a property changes, it saves it to restore on next start. Saved values are not file-specific. List of properties to save is configured in `script-opts/remember-props.conf` file.
- [config-saver](https://github.com/Static39/mpv-scripts/tree/main/config-saver) - Saves current audio track, subtitle track, subtitle position, etc. for all videos in the folder.
- [cycle-through-existing](https://github.com/viniciusbm/mpv-cycle-through-existing) - Cycle through existing video/audio/subtitle tracks, skipping the "none" option.
- [auto-keep-gui-open](https://github.com/VideoPlayerCode/mpv-tools/) - Intelligently switches mpv's "keep-open" behavior based on whether you are running in video-mode or audio-only mode.

## Library

- [user-input](https://github.com/CogentRedTester/mpv-user-input) - API to request text user input.
- [scroll-list](https://github.com/CogentRedTester/mpv-scroll-list) - API to create interactive scrollable lists
- [extended-menu](https://github.com/Seme4eg/mpv-scripts/tree/master/script-modules) - API to create a searchable menu (command palette).
- [osc-framework](https://github.com/maoiscat/mpv-osc-framework) - OSC framework to help build your custom OSC.

## Other

- [webm](https://github.com/ekisu/mpv-webm) - WebM converter based on MoonScript.
- [manager](https://github.com/po5/mpv_manager) - Script and shader manager.
- [copyStuff](https://github.com/0xR3V/mpv-copyStuff) - Copy to clipboard the filename, full filename path, relative filename path, current video time, current displayed subtitle text, video duration/metadata.
- [copyTime](https://github.com/Arieleg/mpv-copyTime) - Copies the current time to the clipboard.
- [copy to music](https://github.com/yazeed44/mpv-scripts) - Copies the current media file you're playing to a predefined directory, and plays the next entry in the playlist (Unix-like)
- [copy-paste-URL](https://github.com/zenyd/mpv-scripts) - Paste URLs directly from clipboard into mpv
- [copy-permalink](https://gist.github.com/olejorgenb/a5194d9bc183dbe0bfb02aac18fe37f9) - Copy `mpv --time=<current-position> <path-playing>` to clipboard. Useful for sharing when playing URLs.
- [copy-time-in-seconds](https://github.com/linguisticmind/mpv-scripts/tree/master/copy-time-in-seconds) - Copies current playback position in seconds with milliseconds to clipboard.
- [copy-time](https://github.com/linguisticmind/mpv-scripts/tree/master/copy-time) - Copies current timecode in HH:MM:SS.MS format to clipboard.
- [cp-paste-URL](https://github.com/yassin-l/cp-paste-url.git) - Fork of copy-paste-URL with support for Linux.
- [SmartCopyPaste-3.0](https://github.com/Eisa01/mpv-scripts#smartcopypaste) - Powerful copy paste features. Paste URL or local videos directly to mpv. Copy URL or currently playing video in mpv player then paste to access at a later time. Add videos to playlist simply by pasting. Much more explained in the link above.
- [SmartCopyPaste-II-3.0](https://github.com/Eisa01/mpv-scripts#smartcopypaste_ii) - Powerful copy paste and clipboard list features using a log file. Select, filter, and search from your clipboard list. Paste URL or local videos directly to mpv. Copy URL or currently playing video in mpv player then paste to access at a later time. Paste to access previously copied times of same video. Much more explained in the link above.
- [vr-reversal](https://github.com/dfaker/VR-reversal) - View 3D side-by-side video as a 2D video, allows you to look around and zoom within the video, logs the head motions to a file for later rendering out to a 2D video with ffmpeg.
- [vo_battery](https://gist.github.com/ekisu/04924e899648e84f2e18) - Choose the VO based on if the laptop is on battery or not.
- [tv-output](https://github.com/blue-sky-r/mpv/blob/master/scripts/tv.lua) - TV output handling - activate on mpv playback and deactivate on mpv shutdown.
- [misc](https://github.com/stax76/mpv-scripts) - Execute Lua code from input.conf.
- [misc](https://github.com/stax76/mpv-scripts) - Restart mpv restoring the properties path, time-pos, pause and volume.
- [i3-floating-centered](https://github.com/mdnghtman/mpv-i3-floating-centered) - Show mpv window in the center of the display when it is in floating mode (i3wm)
- [ontop-window](https://github.com/wishyu/mpv-ontop-window/blob/main/ontop-window.lua) - Disables the ontop property when in fullscreen, and enables it again when in window mode, if it was disabled.
- [ontop-only-while-playing](https://github.com/kungfubeaner/mpv-ontop-only-while-playing-lua/blob/master/on_top_only_while_playing.lua) - Ontop is only active during video playback. Ontop is automatically disabled during idle, pause and is able to be dynamically disabled without having to restart unlike the previous script.
- [ontop-playback](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/ontop-playback.lua) - Disables the ontop property when pausing, and enables it again when unpausing the video, if it was disabled. Change it only when the player is not in fullscreen to prevent screen flickering.
- [pause-when-minimize](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/pause-when-minimize.lua) - Pauses the player video when minimizing, and unpauses it when brought up again.
- [deframe](https://github.com/b4zz4/mpv-deframe) - (Unmaintained) It removes the frame of youtube videos (press g).
- [scale-win](https://gist.github.com/garoto/920b7456d2bdd8f48aa8e7094a12ce47) - Restore old "window-scale" behavior, so to make "add window-scale +/-<value>" keybinds work again when any of the autofit-* options are defined.
- [quick-scale](https://github.com/VideoPlayerCode/mpv-tools/) - Quickly scale the video player to a target size, with full control over target scale and max scale. Helps you effortlessly resize a video to fit on your desktop, or any other video dimensions you need!
- [profile-cycle](https://github.com/Funami580/dotfiles/blob/master/.config/mpv/scripts/profile-cycle.lua) - Cycle between your custom defined profiles while watching the video.
- [open-kinopoisk-page](https://github.com/WANDEX/mpv-open-kinopoisk-page) - Opens the kinopoisk page that corresponds to the currently playing media file.
- [open-imdb-page](https://github.com/ctlaltdefeat/mpv-open-imdb-page) - Opens the IMDb page that corresponds to the currently playing media file.
- [open-anilist-page](https://github.com/ehoneyse/mpv-open-anilist-page) - Opens the Anilist page that corresponds to the currently playing (anime) file.
- [oled-screensaver](https://github.com/Akemi/mpv-oled-screensaver) - To prevent burn-ins on OLED TVs, this script fades-in a black screen after 15 seconds when paused in fullscreen.
- [notify-send](https://github.com/emilazy/mpv-notify-send) - A simpler and more recent notifications script for libnotify-compatible (i.e. Unix-like) notifications daemons only. Supports cover art.
- [notify](https://github.com/rohieb/mpv-notify) - Adds desktop notifications to the mpv media player, which show metadata like artist, album name and track name when the track changes.
- [osd-clock](https://github.com/blue-sky-r/mpv/blob/master/scripts/osd-clock.lua) - Periodically shows OSD clock (many configurable options).
- [clock](https://gitlab.com/mozbugbox/mpv-script-mozbugbox) - Constantly show current time on the lower left corner of the video screen.
- [txt](https://github.com/jgreco/mpv-txt) - Play text files using text-to-speech (TTS). (Works on Linux, MacOS).
- [pdf](https://github.com/jgreco/mpv-pdf) - View PDFs in mpv using ImageMagick. (for Linux, MacOS)
- [manga-reader](https://github.com/Dudemanguy/mpv-manga-reader) - Script for using mpv as a manga reader.
- [redshift_toggle](https://git.sr.ht/~q3cpma/dotfiles/tree/master/.config/mpv/scripts/redshift_toggle.lua) - Toggle redshift when loading a video file and when reaching the end of said file. Now also handles pause.
- [toggle-redshift-on-play](https://gist.github.com/CreamyCookie/d036b66af4e17ea527d08e303eb96145) - Toggle redshift when viewing videos with mpv.
- [toggle-redshift-on-play kill-restart-version](https://gist.github.com/CreamyCookie/079570ad0dd27d322421f6637c828ab8) - Toggle redshift when viewing videos with mpv.
- [inhibit_gnome](https://github.com/Guldoman/mpv_inhibit_gnome) - Prevent screen blanking on GNOME while content is playing
- [mpegts-truncate](https://github.com/hoehermann/mpv-mpegts-truncate) - Removes beginning of MPEG TS file up to current position without re-writing the whole file.
- [minesweeper](https://github.com/wiiaboo/mpv-scripts/blob/master/mines.lua) - Minesweeper game.
- [local-language](https://github.com/422658476/MPV-EASY-Player/blob/master/portable-data/scripts/local-language.lua) - Let the text displayed by osd become the language you are most familiar with, that is, language localization, such as 【volume: 100%】 becomes 【音量:100%】.
- [kde-do-not-disturb](https://gitlab.com/smaniottonicola/kde-do-not-disturb) - Disable the notifications while mpv is running
- [kde-night-color](https://gitlab.com/smaniottonicola/kde-night-color) - Disable Night Color while mpv is running.
- [gnome-inhibit](https://gist.github.com/crazygolem/a7d3a2d3c0cee5d072c0cbbbdee69286) - Prevent the screen from blanking under GNOME+Wayland while a video is playing.
- [notify](https://github.com/kauron/mpv-notify) - Now-playing-desktop notifications.
- [taskbar-buttons](https://github.com/qwerty12/mpv-taskbar-buttons) - (Windows) Adds thumbbar buttons.
- [xscreensaver](https://gist.github.com/elenril/f8ff9475a7882b7a16cdd723c7dce150) - (Linux) Disables XScreensaver while video playback is active, a replacement for heartbeat-cmd.
- [xfce-genmonify](https://github.com/budRich/mpv-xfce-genmonify) - Update a [xfce4-panel](https://docs.xfce.org/xfce/xfce4-panel/start) [genmon](https://docs.xfce.org/panel-plugins/xfce4-genmon-plugin/start) plugin that is set up with [genmonify](https://github.com/budlabs/genmonify) to display the currently playing media file and elpapsed or remaining time in xfce4-panel.
- [force-window-profile](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/force-window-profile.lua) - Applies the force-window profile when force-window is set (i.e. when starting mpv from the .desktop file)
- [exit-fullscreen](https://github.com/zc62/mpv-scripts/blob/master/exit-fullscreen.lua) - If you use `--keep-open=yes`, this script exits fullscreen mode when the playback reaches the end of file/playlist.
- [encode](https://github.com/occivink/mpv-scripts#encodelua) - Re-encode or remux part of the current video. Can also preserve some filters, such as "crop".
- [convert_script](https://gist.github.com/Zehkul/25ea7ae77b30af959be0) - Script to quickly convert and crop videos from within mpv, with a GUI.
- [composition guides](https://github.com/Ares-0/mpv-composition-guides) - Overlay basic composition guides onto your video.
- [clipboard](https://github.com/CogentRedTester/mpv-clipboard) - Provides a set of generic commands to interact with the clipboard. Specifically it allows user to copy arbitrary text to the clipboard and provides the ability to paste the contents of the clipboard into other commands.

# Music Player

- [Harmonoid](https://harmonoid.com) - Cross-platform, based on Dart/Flutter.
- [Olivia](https://github.com/keshavbhatt/olivia) - Linux cloud music player, based on C++/QT/Web.
- [vmn](https://github.com/Dudemanguy/vmn) - Cross-platform CLI music player, based on C/TUI.

# Mobile Player

- [mpv-android](https://github.com/mpv-android/mpv-android) - For Android, based on Kotlin.

# Media Center

- [Stremio](https://github.com/Stremio) - Cross-platform, based on C++/QT.

# Streaming Tools

- [Macast](https://xfangfang.github.io/Macast) - DLNA Media Renderer. You can push videos, pictures or musics from your mobile phone to your computer, based on Python/Web.
- [jellyfin mpv shim](https://github.com/jellyfin/jellyfin-mpv-shim) - Jellyfin (Emby/Plex alternative) Client, based on Python.
- [Botflix/stream-cli](https://github.com/kaboussi/Botflix) - Command-line tool that combines scrapy and webtorrent for streaming movies, based on Python/TUI.
- [webtorrent-mpv-hook](https://github.com/mrxdst/webtorrent-mpv-hook) - Adds a hook that allows mpv to stream torrents using webtorrent.
- [ff2mpv](https://github.com/woodruffw/ff2mpv) - A Firefox/Chrome extension for playing URLs in mpv, based on PowerShel/Shell/Python/JavaScript.
- [plex-mpv-shim](https://github.com/iwalton3/plex-mpv-shim) - Cast media from Plex Mobile and Web apps to MPV, based on Python.
- [play-with-mpv](https://github.com/Thann/play-with-mpv) - Chrome extension for playing URLs in mpv, based on JavaScript/Python/Web.
- [qtube](https://github.com/hdb/qtube) - Linux YouTube frontend, based on Python/QT.
- [TubiTui](https://codeberg.org/777/TubiTui) - Cross-platform YouTube client based on Rust/TUI.
- [DLNAmpvRenderer](https://github.com/PCigales/DLNAmpvRenderer) - Windows DLNA/UPnP renderer based on Python.
- [Plaincast](https://github.com/aykevl/plaincast) - Unmaintained Linux server that acts like a lightweight/headless Chromecast that only includes YouTube, based on Golang.
- [orion](https://github.com/alamminsalo/orion) - Unmaintained cross platform Twitch.tv client, based on C++/QT/QML.

# User Configuration

- [lazy](https://github.com/hooke007/MPV_lazy)
- [Glow](https://glowmpv.github.io)
- [dyphire](https://github.com/dyphire/mpv-config)
- [noelsimbolon](https://github.com/noelsimbolon/mpv-config)
- [Awan](https://github.com/Awan/cfg/tree/master/mpv/.config/mpv)
- [Natural-Harmonia-Gropius](https://github.com/Natural-Harmonia-Gropius/mpv_config)
- [qwerty12](https://github.com/qwerty12/mpv-config)
- [DonCanjas](https://github.com/DonCanjas/mpv-dotfiles)
- [zenwarr](https://github.com/zenwarr/mpv-config)
- [mustaqimM](https://github.com/mustaqimM/mpv-scripts)

# Social Tools

- [Syncplay](https://syncplay.pl) - Synchronize playback on mpv/VLC/MPC on many computers and chat with friends. Cross-platform, based on Python.
- [KikoPlay](https://github.com/KikoPlayProject/KikoPlay) - Cross-platform [Danmu](https://en.wikipedia.org/wiki/Danmu) player, based on C++/QT.

# Video Conversion

- [boram](https://github.com/Kagami/boram) - Unmaintained cross-platform WebM converter, based on JavaScript/Web/Electron.
- [webm.py](https://github.com/Kagami/webm.py) - Cross-platform command-line WebM converter, based on Python.

# Shaders

- [Anime4K](https://github.com/bloc97/Anime4K) - A series of shaders designed to scale and enhance anime. Includes shaders for line sharpening, artefact removal, denoising, upscaling, and more.
- [LumaSharpenHook](https://gist.github.com/voltmtr/8b4404b4e23129b226b9e64863d3e28b) - A sharpen filter similar to using Unsharp Mask in Photoshop ported from SweetFX shader pack.
- [SSimDownscaler, SSimSuperRes, Krig, Adaptive Sharpen, etc.](https://gist.github.com/igv) - * SSimDownscaler: Perceptually based downscaler. More information is [here](https://graphics.ethz.ch/~cengizo/imageDownscaling.htm). SSimSuperRes: The aim of this shader is to make corrections to the image upscaled by mpv built-in scaler (removes ringing artifacts, restores original sharpness, etc). Krig: Chroma scaler that uses luma information for high quality upscaling.
- [Noise](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/shaders/noise.glsl) - Simplistic filter that adds a tunable amount of uniform white noise to the output.
- [Film Grain v1](https://raw.githubusercontent.com/haasn/gentoo-conf/xor/home/nand/.mpv/shaders/filmgrain.glsl)** and **[Film Grain v2](https://raw.githubusercontent.com/haasn/gentoo-conf/xor/home/nand/.mpv/shaders/filmgrain-smooth.glsl) - Two configurable shaders for applying gaussian-weighted white noise to the image. v2 is a smoothed version of v1, which uses an extra gaussian blur pass to shift the grain frequency spectrum. Both versions can trivially be adapted to add film grain to other channels besides `LUMA` by just adding it to the list of hooks.
- [Antiringing](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/shaders/antiring.hook) - This is an antiringing filter that works by clamping to the local neighbourhood. Sort of inspired by the mpv built-in antiringing algorithm, but it's extended in such a way that it also works well for polar (EWA) filters, which the mpv built-in algorithm does not support at all.
- [nnedi3 and ravu](https://github.com/bjin/mpv-prescalers/tree/master) - User shaders for prescaling.
- [FSRCNN](https://github.com/igv/FSRCNN-TensorFlow/releases) - Prescaler based on layered convolutional networks.
- [un360](https://gist.github.com/tesu/196db5421559de3e9555d4f9da9d847d) - Converts equirectangular 360 degree video to be watchable, at a fixed perspective.
- [acme-0.5x](https://gist.github.com/bjin/15f307e7a1bdb55842bbb663ee1950ed) - Fastest 0.5x downscaler for mpv, useful for 4K video playback on FHD screen (bypass chroma upscaling and color conversion in 4K resolution).
- [Nonlinear stretch](https://gist.github.com/sarahzrf/c9909aee70e3656895820f20ac395956) - Non-linear stretch scaling. use with `--no-keepaspect`.
- [lensfix](https://gist.github.com/bjin/33ffbc0fbdbc00aefa21b2e44bbd27cd#file-lensfix-hook) - Fix radial distortion commonly found in wide angle action cameras.
- [hyperview](https://gist.github.com/bjin/399cb23818ad210941725ef768893499) - Dynamic stretching filter aiming to bring effects similar to GoPro SuperView.
- [FidelityFX CAS](https://gist.github.com/agyild/bbb4e58298b2f86aa24da3032a0d2ee6) - AMD FidelityFX Contrast Adaptive Sharpening (CAS) provides a mixed ability to sharpen and optionally scale an image. The algorithm adjusts the amount of sharpening per pixel to target an even level of sharpness across the image. Areas of the input image that are already sharp are sharpened less, while areas that lack detail are sharpened more. This allows for higher overall natural visual sharpness with fewer artifacts.
- [FidelityFX FSR](https://gist.github.com/agyild/82219c545228d70c5604f865ce0b0ce5) - AMD FidelityFX Super Resolution is a spatial upscaler: it works by taking the current anti-aliased frame and upscaling it to display resolution without relying on other data such as frame history or motion vectors. At the heart of FSR is a cutting-edge algorithm that detects and recreates high-resolution edges from the source image. Those high-resolution edges are a critical element required for turning the current frame into a “super resolution” image. FSR provides consistent upscaling quality regardless of whether the frame is in movement, which can provide quality advantages compared to other types of upscalers.
- [NVIDIA Image Scaling](https://gist.github.com/agyild/7e8951915b2bf24526a9343d951db214) - NVIDIA Image Scaling is a spatial scaling and sharpening algorithm. The scaling algorithm uses a 6-tap scaling filter combined with 4 directional scaling and adaptive sharpening filters, which creates nice smooth images and sharp edges. In addition, an adaptive-directional sharpening-only algorithm is available. The directional scaling and sharpening algorithm is named NVScaler while the adaptive-directional-sharpening-only algorithm is named NVSharpen.
- [Post upscale unsharp masking](https://github.com/garamond13/unsharp_masking.glsl) - This is mpvs original image sharpening algorithm ported into the shader, in order to work only after upscaling is done.
- [Non-local means](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/shaders/nlmeans.glsl) - Highly configurable and featureful denoiser and adaptive sharpener.
- [Alt Scale](https://github.com/garamond13/alt-scale) - An alternative to mpv's built in scaling. It can be slightly faster than built in scaling with equivalent quality.
- [Unsharp mask and Gaussian blur](https://github.com/garamond13/Unsharp-mask-and-Gaussian-blur) - A 2 pass unsharp mask and a 2 pass gaussian blur. Similar to those in Photoshop, Image Magick, Gimp, etc.
- [2D Image Resampling](https://github.com/garamond13/2D-Image-Resampling) - 2D Image Resampling is a general resampling algorithm made for experimental / testing use.
- [mpv-prescalers](https://github.com/bjin/mpv-prescalers) - Prescalers for mpv, as user shaders.

# VapourSynth Scripts

- [mvtools](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/filters/mvtools.vpy) - Use [MVTools](https://github.com/dubhater/vapoursynth-mvtools)'s BlockFPS function to perform motion interpolation on the video in realtime.
- [nnedi3](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/filters/nnedi3.vpy) - Use [NNEDI3](https://github.com/dubhater/vapoursynth-nnedi3) to double the resolution of the video. This always performs a single doubling. Note that the vapoursynth-nnedi3 filter is so slow that this practically can't be used in realtime, so it's not much use in practice. 
- [neo_f3kdb_dither](https://github.com/DonCanjas/mpv-dotfiles/blob/main/vs/neo_f3kdb_dither.py) - Use [neo_f3kdb](https://github.com/HomeOfAviSynthPlusEvolution/neo_f3kdb) to dither the video, with dynamic grain as the default. 
- [CCD](https://github.com/DonCanjas/mpv-dotfiles/blob/main/vs/camcorder_color_denoise.py) - Use [CCD](https://github.com/End-of-Eternity/vs-ccd) (Camcorder Color Denoise) to apply chroma denoise/derainbow to video. 

# Video Editing Tools

- [vidcutter](https://github.com/ozmartian/vidcutter) - Cross-platform video cutter/joiner, based on Python/QT.
- [tsv_edl.vim](https://github.com/scateu/tsv_edl.vim) - Linux video editing with vim/spreadsheet/sed/python.

# Image Viewer

- [qimgv](https://github.com/easymodo/qimgv) - Cross-platform, based on C++/QT.

# Launcher

- https://add0n.com/external-application-button.html
- https://github.com/Flow-Launcher/Flow.Launcher
- https://github.com/stax76/Flow.Launcher.Plugin.Favorites
- https://albertlauncher.github.io
- https://github.com/davatorium/rofi
- https://github.com/stax76/OpenWithPlusPlus
- https://github.com/ikas-mc/ContextMenuForWindows11

# Remote Control

- [mpv-mpris](https://github.com/hoyon/mpv-mpris) - On Linux allows controlling mpv using standard media keys.
- [lua-mpris](https://github.com/dodo/lua-mpris) - Adds mpris support to mpv.
- [simple-mpv-webui](https://github.com/open-dynaMIX/simple-mpv-webui) Based on Python/Lua/JavaScript/Web.
- [mpv-remote-app](https://github.com/mcastorina/mpv-remote-app) - For Android, based on Java/Python.
- [mpv-remote-app](https://github.com/husudosu/mpv-remote-app) - For Android, based on Web/VUI/Ionic/Node.js.
- [MPVMediaControl](https://github.com/datasone/MPVMediaControl) - Windows 10 System Media Transport Controls (SMTC).
- Classic remote control used by stax76: 'One For All Contour URC1210' using Philips code 0556 together with 'FLIRC USB (gen2)'.

# Building

- [Helper scripts to compile mpv on Linux](https://github.com/mpv-player/mpv-build)
- [Compiling for Windows](https://github.com/mpv-player/mpv/blob/master/DOCS/compile-windows.md)
- [Building mpv and libmpv using wsl2 and Ubuntu](https://github.com/mpvnet-player/mpv.net/wiki/Building-mpv-and-libmpv-using-wsl2-and-Ubuntu)
- [Media Auto Build Suite (MABS)](https://github.com/m-ab-s/media-autobuild_suite)
- [crosscompile-mingw-tedious](https://github.com/qyot27/mpv/blob/extra-new/DOCS/crosscompile-mingw-tedious.txt)

# Library

- [python](https://github.com/jaseg/python-mpv) - Python interface.
- [py](https://github.com/marcan/pympv) - Another Python interface.
- [ruby](https://github.com/woodruffw/ruby-mpv) - Ruby interface.
- [mpv.d.ts](https://github.com/Cerlancism/mpv.d.ts) - TypeScript definition file (JavaScript).
- [script](https://www.npmjs.com/package/@types/mpv-script) - npm TypeScript definitions (JavaScript).
- [node](https://github.com/rcombs/node-mpv) - Node.js interface (JavaScript).
- [js](https://github.com/Kagami/mpv.js) - Embeddable player for Electron/NW.js (JavaScript).

# Other Tools

- [install](https://github.com/rossy/mpv-install) - Sets up file associations for mpv on Windows.
- [Memento](https://github.com/ripose-jp/Memento) - Cross-platform video player for studying Japanese, based on C++/QT.
- [blitzloop](https://github.com/marcan/blitzloop) - Linux karaoke software, based on Python/OpenGL.
- [mpvQC](https://github.com/mpvqc/mpvQC) - Cross-platform application for quality control of videos, based on Python/QT.
- [vidify](https://vidify.org) - Cross-platform app that detects playing songs on your device and plays their music videos anywhere, based on Python.
- [Karaoke Mugen](https://karaokes.moe/de/) - Cross-platform karaoke management app, based on JavaScript/node.js/Web.
