
# Awesome mpv [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of [awesome](https://github.com/topics/awesome) mpv resources.

# Table of contents

- [Media Player](#media-player)
  - [Cross-platform](#cross-platform)
  - [Windows](#windows)
  - [MacOS](#macos)
  - [Linux](#linux)
- [Build/Installation](#buildinstallation)
- [Support](#support)
- [User Script](#user-script)
  - [GUI](#gui)
  - [Playback](#playback)
  - [File Managment](#file-managment)
  - [On Screen Controller (OSC)](#on-screen-controller-osc)
  - [Input](#input)
  - [Subtitle](#subtitle)
  - [Learning](#learning)
  - [Streaming](#streaming)
  - [Image](#image)
  - [Video Editing](#video-editing)
  - [Social](#social)
  - [Configuration](#configuration)
  - [Script collections](#script-collections)
  - [Other](#other)
- [Music Player](#music-player)
- [Mobile Player](#mobile-player)
- [Media Center](#media-center)
- [Streaming](#streaming)
- [Configuration](#configuration)
- [Social](#social)
- [Video Conversion](#video-conversion)
- [Video Processing](#video-processing)
- [Video Editing](#video-editing)
- [Image Viewer](#image-viewer)
- [External Tools](#external-tools)
- [Remote Control](#remote-control)
- [Tutorial](#tutorial)
- [Building](#building)
- [Library](#library)
- [Other](#other)

# Media Player

## Cross-platform

- [mpv](https://mpv.io) - Based on C/Lua.
- [MoonPlayer](https://github.com/coslyk/moonplayer) - Based on C++/QT/QML.
- [SMPlayer](https://github.com/smplayer-dev/smplayer) - Based on C++/QT.
- [mpc-qt](https://github.com/mpc-qt/mpc-qt) - Based on C++/QT.
- [ImPlay](https://github.com/tsl0922/ImPlay) - Based on C++/imgui.
- [MPV-EASY Player](https://github.com/422658476/MPV-EASY-Player)
- [Baka-MPlayer](https://github.com/u8sand/Baka-MPlayer) - Unmaintained, based on C++/QT.
- [movie-monad](https://github.com/lettier/movie-monad) - Unmaintained, based on Haskell/GTK.
- [OvoPlayer](https://github.com/varianus/ovoplayer) - Unmaintained, based on Pascal.

## Windows

- [mpv.net](https://github.com/mpvnet-player/mpv.net) - Based on C#/WinForms/WPF.

## MacOS

- [IINA](https://iina.io) - Based on Swift/Cocoa.

## Linux

- [Celluloid](https://celluloid-player.github.io) - Based on C/GTK.
- [Kawaii Player](https://github.com/kanishka-linux/kawaii-player) - Player/Library/Server, based on Python/QT.
- [xt7-player-mpv](https://github.com/kokoko3k/xt7-player-mpv) - Based on Gambas/QT.
- [mpvz](https://github.com/Zren/mpvz) - Based on C++/QT/QML.
- [Haruna](https://invent.kde.org/multimedia/haruna) - Based on C++/QT/QML.
- [Deepin Movie](https://github.com/linuxdeepin/deepin-movie-reborn) - Unmaintained, based on C++/QT.

# Build/Installation

- [Official installation instruction](https://mpv.io/installation)
- [mpv-winbuild-cmake by shinchiro](https://github.com/shinchiro/mpv-winbuild-cmake) - Daily Windows builds of mpv and libmpv, based on CMake/C/Shell.
- [mpv-winbuild by zhongfly](https://github.com/zhongfly/mpv-winbuild) - Daily Windows builds of mpv and libmpv, based on Shell.

# Support

- https://www.reddit.com/r/mpv
- https://github.com/mpv-player/mpv/issues

# User Script

## GUI

### Searchable Menu

Searchable menus (also known as command palette) are used to find key bindings and many other things like searching the playlist.

- [mpv-search-page](https://github.com/CogentRedTester/mpv-search-page) - On screen menu.
- [search_menu](https://github.com/stax76/mpv-scripts) - Menu based on Rofi or terminal based on fzf.
- [M-x](https://github.com/Seme4eg/mpv-scripts) - On screen menu.
- [mdmenu](https://codeberg.org/NRK/mpv-toolbox/src/branch/master/mdmenu) - Menu based on dmenu.

### Custom on screen menu

- [menu](https://github.com/jonniek/mpv-menu) - On screen menu to launch custom commands.
- [osm](https://github.com/stax76/mpv-scripts/blob/main/osm.lua) - On screen menu to launch custom commands.

## Playback

- [playlist-manager](https://github.com/jonniek/mpv-playlistmanager) - Create and manage playlists.
- [recent](https://github.com/hacel/recent) - Recently played menu.
- [trackselect](https://github.com/po5/trackselect) - Select tracks based on their title.
- [chapterskip](https://github.com/po5/chapterskip) - Skip chapters based on their title.
- [sort_script](https://github.com/TheAMM/mpv_sort_script) - Sort directories and files.
- [fastforward](https://github.com/zsugabubus/mpv-fastforward) - Fast-forward instead of skipping.
- [history](https://github.com/stax76/mpv-scripts/blob/main/history.lua) - Writes filename and time to a log file.
- [smart-volume](https://github.com/stax76/mpv-scripts/blob/main/smart-volume.lua) - Records the relative volume per song in order to restore it in future sessions.
- [libunity](https://github.com/mrlotfi/mpv-libunity) - Show a nice progress bar on your Linux panel/dock.

## File Managment

- [file-browser](https://github.com/CogentRedTester/mpv-file-browser) - On screen file browser. 
- [filenavigator](https://github.com/jonniek/mpv-filenavigator) - Navigate and open local files.
- [delete-current-file](https://github.com/stax76/mpv-scripts/blob/main/delete-current-file.lua) - Instantly delete the file that is currently playing via keyboard shortcut, the file is moved to the recycle bin and removed from the playlist.
- [file-rating](https://github.com/stax76/mpv-scripts/blob/main/file-rating.lua) - Writes a star rating to the filename of rated files.
- [open-file-dialog](https://github.com/rossy/mpv-open-file-dialog) - Launch a regular Windows open file dialog from a key binding.

## On Screen Controller (OSC)

- [thumbnail_script](https://github.com/TheAMM/mpv_thumbnail_script) - Shows preview thumbnails in the seekbar.
- [uosc](https://github.com/tomasklaen/uosc) - Minimalist proximity-based UI.
- [ModernX](https://github.com/cyl0/ModernX) - Modern OSC replacement.
- [tethys](https://github.com/Zren/mpv-osc-tethys) - OSC replacement with seekbar thumbnail preview.
- [dark-box](https://github.com/maoiscat/mpv-dark-box) - OSC replacement.
- [modern-x-compact](https://github.com/1-minute-to-midnight/mpv-modern-x-compact) - Compact version of modern-x.
- [oscc](https://github.com/longtermfree/oscc) - Dark-themed OSC.

## Input

- [gestures](https://github.com/omeryagmurlu/mpv-gestures) - Touchscreen and mouse gestures.

## Subtitle

- [autosub](https://github.com/davidde/mpv-autosub) - Automatic subtitle downloading.
- [sub-select](https://github.com/CogentRedTester/mpv-sub-select) - Advanced conditional subtitle track selector.
- [autosubsync](https://github.com/Ajatt-Tools/autosubsync-mpv) - Automatic subtitle synchronization script.

## Learning

- [mpvacious](https://github.com/Ajatt-Tools/mpvacious) - Add keybindings to create Anki flashcards for (language) learning.
- [interSubs](https://github.com/oltodosel/interSubs) - Interactive subtitles, instantly translate selected word/sentence.
- [immersive](https://github.com/Ben-Kerman/immersive) - Language learning script for looking up words generating Anki flashcards.
- [sub-scripts](https://github.com/Ben-Kerman/mpv-sub-scripts) - Automatically pause after each subtitle line and skipping intervals between subtitles.

## Streaming

- [sponsorblock](https://github.com/po5/mpv_sponsorblock) - Script to skip sponsored segments of YouTube videos.
- [quality-menu](https://github.com/christoph-heinrich/mpv-quality-menu) - Change the streamed video and audio quality (ytdl-format) on the fly.
- [youtube-download](https://github.com/cvzi/mpv-youtube-download) - Download youtube audio and video with one key press.
- [youtube-upnext](https://github.com/cvzi/mpv-youtube-upnext) - Play "up next"/recommended YouTube videos.
- [ytdlautoformat](https://github.com/Samillion/mpv-ytdlautoformat) - Auto change ytdl-format for Youtube and Twitch.
- [streamsave](https://github.com/Sagnac/streamsave) - Save live streams without encoding.

## Image

- [thumbfast](https://github.com/po5/thumbfast) - High-performance on-the-fly thumbnailer for mpv.
- [crop_script](https://github.com/TheAMM/mpv_crop_script) - Take cropped screenshots.
- [gif-generator](https://github.com/the-honey/mpv-gif-generator) - Creates animated gifs using hotkeys.
- [auto-mode](https://github.com/stax76/mpv-scripts/blob/main/auto-mode.lua) - Use mpv as music player and image viewer.
- [waifu2x](https://github.com/jonniek/mpv-waifu2x) - Take screenshot and convert images with waifu2x.

## Video Editing

- [trim](https://github.com/aerobounce/trim.lua) - Trim clips without transcoding.
- [easycrop](https://github.com/aidanholm/mpv-easycrop) - Cropping videos with ease.
- [videoclip](https://github.com/Ajatt-Tools/videoclip) - Easily create video and audio clips in a few keypresses.
- [video-splice](https://github.com/pvpscript/mpv-video-splice) - Video cutting.

## Social

- [Discord RPC](https://github.com/cniw/mpv-discordRPC) - Discord Rich Presence integration.

## Configuration

- [persist-properties](https://github.com/d87/mpv-persist-properties) - Keep selected property values (like volume) between player sessions.

## Script collections

- [mpv wiki](https://github.com/mpv-player/mpv/wiki/User-Scripts)
- [GitHub tag/topic 'mpv-script'](https://github.com/topics/mpv-script)
- [script-directory (Script/Package manager)](https://nudin.github.io/mpv-script-directory)
- [occivink](https://github.com/occivink/mpv-scripts)
- [Eisa01](https://github.com/Eisa01/mpv-scripts)
- [jonniek](https://github.com/jonniek/mpv-scripts)
- [CogentRedTester](https://github.com/CogentRedTester/mpv-scripts)
- [detuur](https://github.com/detuur/mpv-scripts)
- [stax76](https://github.com/stax76/mpv-scripts)
- [blue-sky-r](https://github.com/blue-sky-r/mpv)
- [yuukidach](https://github.com/yuukidach/mpv-scripts)
- [Seme4eg](https://github.com/Seme4eg/mpv-scripts)
- [dyphire](https://github.com/dyphire/mpv-scripts)
- [misc.lua](https://github.com/stax76/mpv-scripts/blob/main/misc.lua)

## Other

- [webm](https://github.com/ekisu/mpv-webm) - WebM converter based on MoonScript.
- [manager](https://github.com/po5/mpv_manager) - Script and shader manager.
- [changerefresh](https://github.com/CogentRedTester/mpv-changerefresh) - Automatically change the refresh rate of the current display to match the playing video.

# Music Player

- [Harmonoid](https://harmonoid.com) - Cross-platform, based on Dart/Flutter.
- [Olivia](https://github.com/keshavbhatt/olivia) - Linux cloud music player, based on C++/QT/Web.
- [vmn](https://github.com/Dudemanguy/vmn) - Cross-platform CLI music player, based on C/TUI.

# Mobile Player

- [mpv-android](https://github.com/mpv-android/mpv-android) - For Android, based on Kotlin.

# Media Center

- [Stremio](https://github.com/Stremio) - Cross-platform, based on C++/QT.

# Streaming

- [Macast](https://xfangfang.github.io/Macast) - DLNA Media Renderer. You can push videos, pictures or musics from your mobile phone to your computer, based on Python/Web.
- [jellyfin mpv shim](https://github.com/jellyfin/jellyfin-mpv-shim) - Jellyfin (Emby/Plex alternative) Client, based on Python.
- [Botflix/stream-cli](https://github.com/kaboussi/Botflix) - Command-line tool that combines scrapy and webtorrent for streaming movies, based on Python/TUI.
- [ff2mpv](https://github.com/woodruffw/ff2mpv) - A Firefox/Chrome extension for playing URLs in mpv, based on PowerShel/Shell/Python/JavaScript.
- [plex-mpv-shim](https://github.com/iwalton3/plex-mpv-shim) - Cast media from Plex Mobile and Web apps to MPV, based on Python.
- [play-with-mpv](https://github.com/Thann/play-with-mpv) - Chrome extension for playing URLs in mpv, based on JavaScript/Python/Web.
- [qtube](https://github.com/hdb/qtube) - Linux YouTube frontend, based on Python/QT.
- [TubiTui](https://codeberg.org/777/TubiTui) - Cross-platform YouTube client based on Rust/TUI.
- [DLNAmpvRenderer](https://github.com/PCigales/DLNAmpvRenderer) - Windows DLNA/UPnP renderer based on Python.
- [Plaincast](https://github.com/aykevl/plaincast) - Unmaintained Linux server that acts like a lightweight/headless Chromecast that only includes YouTube, based on Golang.
- [orion](https://github.com/alamminsalo/orion) - Unmaintained cross platform Twitch.tv client, based on C++/QT/QML.

# Configuration

- [lazy](https://github.com/hooke007/MPV_lazy)
- [Glow](https://glowmpv.github.io)
- [dyphire](https://github.com/dyphire/mpv-config)
- [noelsimbolon](https://github.com/noelsimbolon/mpv-config)
- [Awan](https://github.com/Awan/cfg/tree/master/mpv/.config/mpv)
- [Natural-Harmonia-Gropius](https://github.com/Natural-Harmonia-Gropius/mpv_config)

# Social

- [Syncplay](https://syncplay.pl) - Synchronize playback on mpv/VLC/MPC on many computers and chat with friends. Cross-platform, based on Python.
- [KikoPlay](https://github.com/KikoPlayProject/KikoPlay) - Cross-platform [Danmu](https://en.wikipedia.org/wiki/Danmu) player, based on C++/QT.

# Video Conversion

- [boram](https://github.com/Kagami/boram) - Unmaintained cross-platform WebM converter, based on JavaScript/Web/Electron.
- [webm.py](https://github.com/Kagami/webm.py) - Cross-platform command-line WebM converter, based on Python.
- [mpv-webm](https://github.com/ekisu/mpv-webm) - WebM converter based on MoonScript.

# Video Processing

- [mpv-prescalers](https://github.com/bjin/mpv-prescalers) - Prescalers for mpv, as user shaders.

# Video Editing

- [vidcutter](https://github.com/ozmartian/vidcutter) - Cross-platform video cutter/joiner, based on Python/QT.
- [tsv_edl.vim](https://github.com/scateu/tsv_edl.vim) - Linux video editing with vim/spreadsheet/sed/python.

# Image Viewer

- [qimgv](https://github.com/easymodo/qimgv) - Cross-platform, based on C++/QT.
- [mpv-image-viewer](https://github.com/occivink/mpv-image-viewer) - Configuration, scripts and tips for using mpv as an image viewer.
- [auto-mode](https://github.com/stax76/mpv-scripts/blob/main/auto-mode.lua)

# External Tools

- https://add0n.com/external-application-button.html
- https://github.com/Flow-Launcher/Flow.Launcher
- https://github.com/stax76/Flow.Launcher.Plugin.Favorites
- https://github.com/stax76/OpenWithPlusPlus
- https://github.com/ikas-mc/ContextMenuForWindows11

# Remote Control

- [mpv-mpris](https://github.com/hoyon/mpv-mpris) - On Linux allows controlling mpv using standard media keys.
- [simple-mpv-webui](https://github.com/open-dynaMIX/simple-mpv-webui) Based on Python/Lua/JavaScript/Web.
- [mpv-remote-app](https://github.com/mcastorina/mpv-remote-app) - For Android, based on Java/Python.
- [mpv-remote-app](https://github.com/husudosu/mpv-remote-app) - For Android, based on Web/VUI/Ionic/Node.js.
- [MPVMediaControl](https://github.com/datasone/MPVMediaControl) - Windows 10 System Media Transport Controls (SMTC).
- Classic remote control: 'One For All Contour URC1210' using Philips code 0556 together with 'FLIRC USB (gen2)'.

# Tutorial

- [How to Use MPV on Windows](https://www.makeuseof.com/how-to-use-mpv-on-windows)
- [mpv: The Best Video Player for Language Learning](https://www.youtube.com/watch?v=bbg6ztWecbU)

# Building

- [Helper scripts to compile mpv on Linux](https://github.com/mpv-player/mpv-build)
- [Compiling for Windows](https://github.com/mpv-player/mpv/blob/master/DOCS/compile-windows.md)
- [Building mpv and libmpv using wsl2 and Ubuntu](https://github.com/mpvnet-player/mpv.net/wiki/Building-mpv-and-libmpv-using-wsl2-and-Ubuntu)
- [Media Auto Build Suite (MABS)](https://github.com/m-ab-s/media-autobuild_suite)
- [crosscompile-mingw-tedious](https://github.com/qyot27/mpv/blob/extra-new/DOCS/crosscompile-mingw-tedious.txt)

# Library

- [python-mpv](https://github.com/jaseg/python-mpv) - Python interface.
- [mpv.js](https://github.com/Kagami/mpv.js) - Embeddable player for Electron/NW.js applications.
- [mpv-user-input](https://github.com/CogentRedTester/mpv-user-input) - API to allow mpv scripts to request user text input.
- [extended-menu](https://github.com/Seme4eg/mpv-scripts/tree/master/script-modules) - Searchable menu (Command Palette).

# Other

- [install](https://github.com/rossy/mpv-install) - Sets up file associations for mpv on Windows.
- [Memento](https://github.com/ripose-jp/Memento) - Cross-platform video player for studying Japanese, based on C++/QT.
- [blitzloop](https://github.com/marcan/blitzloop) - Linux karaoke software, based on Python/OpenGL.
- [mpvQC](https://github.com/mpvqc/mpvQC) - Cross-platform application for quality control of videos, based on Python/QT.
- [vidify](https://vidify.org) - Cross-platform app that detects playing songs on your device and plays their music videos anywhere, based on Python.
- [Karaoke Mugen](https://karaokes.moe/de/) - Cross-platform karaoke management app, based on JavaScript/node.js/Web.
