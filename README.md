> [!IMPORTANT]
> **Blunt AI disclosure:** Most of Novera's code was generated with assistance from GitHub Copilot. I am not hiding or minimizing that fact.
>
> AI was used exclusively for programming. Despite having approximately three years of programming experience, I had never worked with JavaScript before, and Novera was too ambitious for me to build entirely on my own without a budget or outside assistance.
>
> GitHub Copilot was used to generate much of the code, but only for features and functionality that I had already conceived and directed. Every concept, feature, design choice, creative decision, and aspect of the project's direction came from me. AI was not used to create Novera's concept, artwork, branding, or any other creative assets. The current and future final logo have been designed by human, and some code will be reviewed and edited by real programmers to ensure the player is as efficient and lightweight as it can be.
>
> I understand why many people dislike or oppose generative AI, and I do not disagree with those concerns. If you object to my use of AI-assisted programming, I respect your decision not to use or support Novera.
>
<sub> No generative AI was used when writing this note. </sub>

<div align="center">

# Novera

</div>
A lightweight, customizable offline music player for Windows, built with Electron and powered by Chromium’s audio engine. It is designed to provide a modern, flexible alternative to traditional desktop music players while retaining support for advanced customization.

Novera supports a wide range of audio formats, including FLAC, Opus, MP3, OGG, M4A, WAV, AAC, and more. It also supports embedded and LRC-based plain-text, synchronized, and word-level karaoke lyrics.

<img src="Screenshot 2026-09-13 130742.png" alt="Early Development Screenshot">
<img src="Screenshot 2026-09-13 131228.png" alt="Early Development Screenshot">
<img src="Screenshot 2026-09-13 131434.png" alt="Early Development Screenshot">
<img src="Screenshot 2026-09-13 131631.png" alt="Early Development Screenshot">

> Novera is currently in early development and does not yet have a downloadable build ready. Some icons, visuals, and features are still being refined (see below for list).

<div align="center">

## ✅ - Completed    ⌛ - In progress    ❌ - Not started, only planned

</div>

## Functional features

- ✅ Audio file playback with support for importing multiple directories for music library
- ✅ Togglable synced-lyric display in now playing bar for active line
- ✅ Four built-in themes: Light, Dark, Black / AMOLED, and Dynamic (changes colors to match album art)
- ✅ Ability to customize built-in themes with custom RGB colors, and custom fonts
- ✅ Overwrite the default dynamic theme colors per-song or per-album to your own, saved locally to the app in a list in settings
- ✅ Ability to override default artist name text & album/artist artwork with custom images
- ✅ Automatic artist logos & album/artist artwork importing from folders
- ✅ Customizable artist and genre separators
- ✅ Writable artist descriptions
- ✅ Remappable keyboard shortcuts for the large majority of functions
- ✅ Toggle to keep the screen awake while app is in focus
- ✅ Smart search that adds autocomplete to search, and a top-results section showing the most relevant matches
- ✅ Fully functional playlist creation and management with ability to export/import playlists as M3U
- ✅ Setting to restore queue and actively playing song from last close on app open
- ✅ Setting to automatically resume/play restored song on app open if this setting is enabled
- ✅ Metadata editor
- ✅ Last.fm integration for art and descriptions
- ✅ Discord Rich Presence with Last.fm album art
- ✅ Customizable home page and sidebar layouts
- ✅ Optional righthand sidebar with media controls like Spotify, with added miniview function: Switch between viewing the actively playing artists, active song's album view, queue, and lyrics, all in one small tab switcher
- ✅ Gapless playback support
- ✅ Two styles for displaying artists in both the miniview and regular pages
- ✅ MusicBrainz release-type support for albums, EPs, singles, and more
- ✅ Optional “Up Next” toast with customizable time length

## Planned Features (WIP)

- ⌛ A couple colorful custom theme presets
- ⌛ Ability to import and export custom themes, with shared community themes accessible to import through a linked Discord server
- ⌛ Further theme customization options
- ⌛ Further UI polish and visual tweaks
- ⌛ Media buttons in the application window preview on hover
- ❌ Setting to allow multiple columns of songs in a list to be more compact when possible
- ❌ Move play button on song list to album art and make track number visibility persistent
- ❌ Allow horizontal scrolling on release lists to see more without hitting “see all”
- ❌ Synced lyrics display options: remove glow, remove slide highlight animation, and remove highlight color
- ❌ Prettier synced lyrics
- ❌ TTML synced lyrics support
- ❌ Upload artist logo to replace default text on artist view, Apple Music-style
- ❌ AMLL-dialect background-vocal lines
- ❌ Enhanced control over the parameters of what/where shuffle being on shuffles and what it does not
- ❌ Support for multiple lyric files, embedded vs. LRC, and lyric translations/languages
- ❌ Setting to mark music symbols in synced lyrics as blank spaces to convert into an in-app three-dots animation when an instrumental is playing
- ❌ “Select all” button for selecting multiple songs so you can select from one section immediately
- ❌ More tidy settings page, with items grouped into submenus
- ❌ Custom background images for custom themes
- ❌ Ability to use custom icon packs as part of custom themes
- ❌ Fullscreen player view
- ❌ YouTube Music-style maximized player view
- ❌ Pop-out now-playing window
- ❌ Visualizer support with customizable theming
- ❌ Resizable player panels and sidebar
- ❌ Ability to collapse/minimize the left sidebar
- ❌ Minimize-to-system-tray support
- ❌ An option to respect the Windows light/dark theme when scheduling automatic theme changes, unless a custom or dynamic theme is activated
- ❌ Replace all default Windows hover-text popups with in-app-styled ones
- ❌ An option to launch the application at system startup
- ❌ Ability to export/import app settings
- ❌ Music video support
- ❌ Swap sides of the sidebar and right-side now-playing bar
- ❌ Musixmatch synced lyrics
- ❌ Muspy RSS integration for artist notifications - Hit the bell icon on an artist page, and become notified whenever that artist releases new music!
- ❌ History function
- ❌ Custom HTML/CSS embeds
- ❌ Equalizer button to open the Peace Equalizer/Equalizer APO window
- ❌ Automixes based on your listening habits and genre tags
- ❌ Lyric editor with powerful synchronized and karaoke lyric tools
- ❌ Setting to hide “- Single” and “- EP” from album names if written into album metadata
- ❌ Ability to capture the current queue and save it as a playlist
- ❌ Ability to choose a custom playlist image from a file
- ❌ ListenBrainz support
- ❌ Track 0 support, throwing a song at the end of the list with last numbering
- ❌ Optional ability to hide track 0 so you have to go back through track 1, like on CD players
- ❌ “[silence]” track support
- ❌ Sorting besides alphabetically by artist when “respect album artist” is checked
- ❌ Support for multiple album images for different sides, such as front, back, and disc
- ❌ Zoom settings and zoom lyrics settings
- ❌ Option to ignore “A” and/or “The” from artist, song, and album titles when sorting
- ❌ Listening stats
- ❌ Updated final logo, code fixes, and UI styling improvements by people
## Development Status

Novera is still in early production and is not yet ready for general release. The interface and feature set are actively being developed, and placeholder icons or artwork are present.

The project will be published as free and open-source (FOSS) software at this repository once it is ready.

## License

Novera is free and open-source software licensed under the
[GNU General Public License v3.0 or later](https://www.gnu.org/licenses/gpl-3.0.html).

You may use, study, modify, and redistribute Novera under the terms of that
license. Any distributed modified version must also provide the corresponding
source code under the GNU GPL v3.0 or later.

See the [LICENSE](LICENSE) file for the complete license text.

Novera uses third-party software distributed under their own licenses.
Third-party copyright notices and license information will be listed in
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) as the project develops.
