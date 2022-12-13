
# Awesome mpv [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of projects related to the mpv media player.

# Media Player

## Cross-platform

- [mpv](https://mpv.io) - 20.9k stars, based on C/Lua.
- [MoonPlayer](https://github.com/coslyk/moonplayer) - 525 stars, based on C++/QT/QML.
- [SMPlayer](https://github.com/smplayer-dev/smplayer) - 319 stars, based on C++/QT.
- [mpc-qt](https://github.com/mpc-qt/mpc-qt) - 144 stars, based on C++/QT.
- [ImPlay](https://github.com/tsl0922/ImPlay) - 22 stars, based on C++/imgui.
- [MPV-EASY Player](https://github.com/422658476/MPV-EASY-Player) - 617 stars.
- [Baka-MPlayer](https://github.com/u8sand/Baka-MPlayer) - Unmaintained, 375 stars, based on C++/QT.
- [movie-monad](https://github.com/lettier/movie-monad) - Unmaintained, 397 stars, based on Haskell/GTK.
- [OvoPlayer](https://github.com/varianus/ovoplayer) - Unmaintained, 41 stars, based on Pascal.

## Windows

- [mpv.net](https://github.com/mpvnet-player/mpv.net) - 1.7k stars, based on C#/WinForms/WPF.

## MacOS

- [IINA](https://iina.io) - 31.9k stars, based on Swift/Cocoa.

## Linux

- [Celluloid](https://celluloid-player.github.io) - 840 stars, based on C/GTK.
- [Kawaii Player](https://github.com/kanishka-linux/kawaii-player) - Player/Library/Server, 523 stars, based on Python/QT.
- [xt7-player-mpv](https://github.com/kokoko3k/xt7-player-mpv) 84 stars, based on Gambas/QT.
- [mpvz](https://github.com/Zren/mpvz) - 38 stars, based on C++/QT/QML.
- [Haruna](https://invent.kde.org/multimedia/haruna) - 17 stars, based on C++/QT/QML.
- [Deepin Movie](https://github.com/linuxdeepin/deepin-movie-reborn) - Unmaintained, 60 stars, based on C++/QT.

# Build/Installation

- [Official installation instruction](https://mpv.io/installation)
- [mpv-winbuild-cmake by shinchiro](https://github.com/shinchiro/mpv-winbuild-cmake) - Daily Windows builds of mpv and libmpv, 219 stars, based on CMake/C/Shell.
- [mpv-winbuild by zhongfly](https://github.com/zhongfly/mpv-winbuild) - Daily Windows builds of mpv and libmpv, 81 stars, based on Shell.

# Support

- https://www.reddit.com/r/mpv
- https://github.com/mpv-player/mpv/issues

# User Script

- [User scripts listed in the mpv wiki](https://github.com/mpv-player/mpv/wiki/User-Scripts) - This is the most important and most complete list of available mpv scripts.
- [Users scripts on GitHub tagged with 'mpv-script'](https://github.com/topics/mpv-script)
- [mpv-script-directory](https://nudin.github.io/mpv-script-directory)

## GUI

### Searchable Menu

Searchable menus (also known as command palette) are used to find key bindings and many other things like searching the playlist.

- [mpv-search-page](https://github.com/CogentRedTester/mpv-search-page) - On screen menu.
- [search_menu](https://github.com/stax76/mpv-scripts) - Menu based on Rofi or terminal based on fzf.
- [M-x](https://github.com/Seme4eg/mpv-scripts) - On screen menu.
- [mdmenu](https://codeberg.org/NRK/mpv-toolbox/src/branch/master/mdmenu) - Menu based on dmenu.

### Custom on screen menu

- [menu](https://github.com/jonniek/mpv-menu) - On screen menu to launch custom commands, 33 stars.
- [osm](https://github.com/stax76/mpv-scripts/blob/main/osm.lua) - On screen menu to launch custom commands.

## Playback

- [playlist-manager](https://github.com/jonniek/mpv-playlistmanager) - Create and manage playlists, 348 stars.
- [recent](https://github.com/hacel/recent) - Recently played menu,  35 stars.
- [history](https://github.com/stax76/mpv-scripts/blob/main/history.lua) - Writes filename and time to a log file.
- [smart-volume](https://github.com/stax76/mpv-scripts/blob/main/smart-volume.lua) - Records the relative volume per song in order to restore it in future sessions.

## File Managment

- [file-browser](https://github.com/CogentRedTester/mpv-file-browser) - On screen file browser. 
- [filenavigator](https://github.com/jonniek/mpv-filenavigator) - Navigate and open local files, 55 stars.
- [delete-current-file](https://github.com/stax76/mpv-scripts/blob/main/delete-current-file.lua) - Instantly delete the file that is currently playing via keyboard shortcut, the file is moved to the recycle bin and removed from the playlist.
- [file-rating](https://github.com/stax76/mpv-scripts/blob/main/file-rating.lua) - Writes a star rating to the filename of rated files.

## On Screen Controller (OSC)

- [mpv_thumbnail_script](https://github.com/TheAMM/mpv_thumbnail_script) - Shows preview thumbnails in the seekbar, 575 stars.
- [uosc](https://github.com/tomasklaen/uosc) - Minimalist proximity-based UI, 412 stars.
- [ModernX](https://github.com/cyl0/ModernX) - Modern OSC replacement, 188 stars.
- [mpv-osc-tethys](https://github.com/Zren/mpv-osc-tethys) - OSC replacement with seekbar thumbnail preview, 94 stars.

## Subtitle

- [autosub](https://github.com/davidde/mpv-autosub) - Automatic subtitle downloading, 200 stars.
- [sub-select](https://github.com/CogentRedTester/mpv-sub-select) - Advanced conditional subtitle track selector, 40 stars.

## Learning

- [mpvacious](https://github.com/Ajatt-Tools/mpvacious) - Add keybindings to create Anki flashcards for (language) learning, 286 stars.
- [interSubs](https://github.com/oltodosel/interSubs) - Interactive subtitles, instantly translate selected word/sentence, 159 stars.
- [immersive](https://github.com/Ben-Kerman/immersive) - Language learning script for looking up words generating Anki flashcards, 55 stars.
- [sub-scripts](https://github.com/Ben-Kerman/mpv-sub-scripts) - Automatically pause after each subtitle line and skipping intervals between subtitles, 44 stars.

## Streaming

- [sponsorblock](https://github.com/po5/mpv_sponsorblock) - Script to skip sponsored segments of YouTube videos, 379 stars.
- [quality-menu](https://github.com/christoph-heinrich/mpv-quality-menu) - Change the streamed video and audio quality (ytdl-format) on the fly, 39 stars.
- [youtube-download](https://github.com/cvzi/mpv-youtube-download) - Download youtube audio and video with one key press, 37 stars.
- [youtube-upnext](https://github.com/cvzi/mpv-youtube-upnext) - Play "up next"/recommended YouTube videos, 36 stars.
- [streamsave](https://github.com/Sagnac/streamsave) - Save live streams without encoding, 30 stars.
- [ytdlautoformat](https://github.com/Samillion/mpv-ytdlautoformat) - Auto change ytdl-format for Youtube and Twitch, 29 stars.

## Image

- [thumbfast](https://github.com/po5/thumbfast) - High-performance on-the-fly thumbnailer for mpv, 141 stars.
- [crop_script](https://github.com/TheAMM/mpv_crop_script) - Take cropped screenshots, 81 stars.
- [gif-generator](https://github.com/the-honey/mpv-gif-generator) - Creates animated gifs using hotkeys, 33 stars.
- [auto-mode](https://github.com/stax76/mpv-scripts/blob/main/auto-mode.lua) - Use mpv as music player and image viewer.

## Video Editing

- [trim](https://github.com/aerobounce/trim.lua) - Trim clips without transcoding, 65 stars.
- [easycrop](https://github.com/aidanholm/mpv-easycrop) - Cropping videos with ease, 64 stars.
- [videoclip](https://github.com/Ajatt-Tools/videoclip) - Easily create video and audio clips in a few keypresses, 49 stars.
- [video-splice](https://github.com/pvpscript/mpv-video-splice) - Video cutting, 35 stars.

## Social

- [Discord RPC](https://github.com/cniw/mpv-discordRPC) - Discord Rich Presence integration, 112 stars.

## Configuration

- [persist-properties](https://github.com/d87/mpv-persist-properties) - Keep selected property values (like volume) between player sessions, 55 stars.

## Script collection miscellaneous

- [occivink](https://github.com/occivink/mpv-scripts) - 298 stars.
- [Eisa01](https://github.com/Eisa01/mpv-scripts) - 211 stars.
- [jonniek](https://github.com/jonniek/mpv-scripts) - 140 stars.
- [CogentRedTester](https://github.com/CogentRedTester/mpv-scripts) - 118 stars.
- [detuur](https://github.com/detuur/mpv-scripts) - 38 stars.
- [stax76](https://github.com/stax76/mpv-scripts) - 26 stars.
- [Seme4eg](https://github.com/Seme4eg/mpv-scripts) - 11 stars.
- [dyphire](https://github.com/dyphire/mpv-scripts) - 7 stars.
- [misc.lua](https://github.com/stax76/mpv-scripts/blob/main/misc.lua)

## Other

- [mpv-webm](https://github.com/ekisu/mpv-webm) - WebM converter based on MoonScript.

# Music Player

- [Harmonoid](https://harmonoid.com) - Cross-platform, 2.3k stars, based on Dart/Flutter.
- [Olivia](https://github.com/keshavbhatt/olivia) - Linux cloud music player, 317 stars, based on C++/QT/Web.
- [vmn](https://github.com/Dudemanguy/vmn) - Cross-platform CLI music player, 31 stars, based on C/TUI.

# Mobile Player

- [mpv-android](https://github.com/mpv-android/mpv-android) - For Android, 1.1k stars, based on Kotlin.

# Media Center

- [Stremio](https://github.com/Stremio) - Cross-platform, 334 stars, based on C++/QT.

# Streaming

- [Macast](https://xfangfang.github.io/Macast) - DLNA Media Renderer. You can push videos, pictures or musics from your mobile phone to your computer, 4.3k stars, based on Python/Web.
- [jellyfin mpv shim](https://github.com/jellyfin/jellyfin-mpv-shim) - Jellyfin (Emby/Plex alternative) Client, 1k stars based on Python.
- [Botflix/stream-cli](https://github.com/kaboussi/Botflix) - Command-line tool that combines scrapy and webtorrent for streaming movies, 376 stars, based on Python/TUI.
- [ff2mpv](https://github.com/woodruffw/ff2mpv) - A Firefox/Chrome extension for playing URLs in mpv, 334 stars, based on PowerShel/Shell/Python/JavaScript.
- [plex-mpv-shim](https://github.com/iwalton3/plex-mpv-shim) - Cast media from Plex Mobile and Web apps to MPV, 279 stars, based on Python.
- [play-with-mpv](https://github.com/Thann/play-with-mpv) - Chrome extension for playing URLs in mpv, 278 stars, based on JavaScript/Python/Web.
- [qtube](https://github.com/hdb/qtube) - Linux YouTube frontend, 19 stars, based on Python/QT.
- [TubiTui](https://codeberg.org/777/TubiTui) - Cross-platform YouTube client based on Rust/TUI.
- [DLNAmpvRenderer](https://github.com/PCigales/DLNAmpvRenderer) - Windows DLNA/UPnP renderer based on Python.
- [Plaincast](https://github.com/aykevl/plaincast) - Unmaintained Linux server that acts like a lightweight/headless Chromecast that only includes YouTube, 116 stars, based on Golang.
- [orion](https://github.com/alamminsalo/orion) - Unmaintained cross platform Twitch.tv client, 309 stars, based on C++/QT/QML.

# Configuration

- [MPV_lazy](https://github.com/hooke007/MPV_lazy) - Full Windows configuration including scripts for Chinese users, 1k stars.
- [Glow](https://glowmpv.github.io) - Config File Generator for Windows, 237 stars.
- [dyphire/mpv-config](https://github.com/dyphire/mpv-config) - Full Windows configuration including scripts for Chinese users, 67 stars.

# Social

- [Syncplay](https://syncplay.pl) - Synchronize playback on mpv/VLC/MPC on many computers and chat with friends. Cross-platform, 1.6k stars, based on Python.
- [KikoPlay](https://github.com/KikoPlayProject/KikoPlay) - Cross-platform [Danmu](https://en.wikipedia.org/wiki/Danmu) player,
828 stars, based on C++/QT.

# Video Conversion

- [boram](https://github.com/Kagami/boram) - Unmaintained cross-platform WebM converter, 393 stars, based on JavaScript/Web/Electron.
- [webm.py](https://github.com/Kagami/webm.py) - Cross-platform command-line WebM converter, 128 stars, based on Python.
- [mpv-webm](https://github.com/ekisu/mpv-webm) - WebM converter based on MoonScript.

# Video Processing

- [mpv-prescalers](https://github.com/bjin/mpv-prescalers) - Prescalers for mpv, as user shaders, 258 stars.

# Video Editing

- [vidcutter](https://github.com/ozmartian/vidcutter) - Cross-platform video cutter/joiner, 1.2k stars, based on Python/QT.
- [tsv_edl.vim](https://github.com/scateu/tsv_edl.vim) - Linux video editing with vim/spreadsheet/sed/python.

# Image Viewer

- [qimgv](https://github.com/easymodo/qimgv) - Cross-platform, 1.5k stars, based on C++/QT.
- [mpv-image-viewer](https://github.com/occivink/mpv-image-viewer) - Configuration, scripts and tips for using mpv as an image viewer.
- [auto-mode](https://github.com/stax76/mpv-scripts/blob/main/auto-mode.lua)

# External Tools

- https://add0n.com/external-application-button.html
- https://github.com/Flow-Launcher/Flow.Launcher
- https://github.com/stax76/Flow.Launcher.Plugin.Favorites
- https://github.com/stax76/OpenWithPlusPlus
- https://github.com/ikas-mc/ContextMenuForWindows11

# Remote Control

- [mpv-mpris](https://github.com/hoyon/mpv-mpris) - On Linux allows controlling mpv using standard media keys, 450 stars.
- [simple-mpv-webui](https://github.com/open-dynaMIX/simple-mpv-webui) - 115 stars, based on Python/Lua/JavaScript/Web.
- [mpv-remote-app](https://github.com/mcastorina/mpv-remote-app) - For Android, 68 stars, based on Java/Python.
- [mpv-remote-app](https://github.com/husudosu/mpv-remote-app) - For Android, 31 stars, based on Web/VUI/Ionic/Node.js.
- [MPVMediaControl](https://github.com/datasone/MPVMediaControl) - Windows 10 System Media Transport Controls (SMTC), 26 stars.
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

- [python-mpv](https://github.com/jaseg/python-mpv) - Python interface, 401 stars.
- [mpv.js](https://github.com/Kagami/mpv.js) - Embeddable player for Electron/NW.js applications, 377 stars.

# Other

- [mpv-install](https://github.com/rossy/mpv-install) - Sets up file associations for mpv on Windows, 379 stars.
- [Memento](https://github.com/ripose-jp/Memento) - Cross-platform video player for studying Japanese, 240 stars, based on C++/QT.
- [blitzloop](https://github.com/marcan/blitzloop) - Linux karaoke software, 174 stars, based on Python/OpenGL.
- [mpvQC](https://github.com/mpvqc/mpvQC) - Cross-platform application for quality control of videos, 34 stars, based on Python/QT.
- [vidify](https://vidify.org) - Cross-platform app that detects playing songs on your device and plays their music videos anywhere. 114 stars, based on Python.
- [Karaoke Mugen](https://karaokes.moe/de/) - Cross-platform karaoke management app, based on JavaScript/node.js/Web.
