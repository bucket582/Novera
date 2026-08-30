> [!IMPORTANT]
> **Blunt AI disclosure:** Most of Novera's code was generated with assistance from GitHub Copilot. I am not hiding or minimizing that fact.
>
> AI was used exclusively for programming. Despite having approximately three years of programming experience, I had never worked with JavaScript before, and Novera was too ambitious for me to build entirely on my own without a budget or outside assistance.
>
> GitHub Copilot was used to generate much of the code, but only for features and functionality that I had already conceived and directed. Every concept, feature, design choice, creative decision, and aspect of the project's direction came from me. AI was not used to create Novera's concept, artwork, branding, or any other creative assets.
>
> I understand why many people dislike or oppose generative AI, and I do not disagree with those concerns. If you object to my use of AI-assisted programming, I respect your decision not to use or support Novera.
>
<sub> No generative AI was used when writing this note. </sub>

# Novera
A lightweight, customizable offline music player for Windows, built with Electron and powered by Chromium’s audio engine. It is designed to provide a modern, flexible alternative to traditional desktop music players while retaining support for advanced customization.

Novera supports a wide range of audio formats, including FLAC, Opus, MP3, OGG, M4A, WAV, AAC, and more. It also supports embedded and LRC-based plain-text, synchronized, and word-level karaoke lyrics.

> Novera is currently in early development and does not yet have a downloadable build ready. Some icons, visuals, and features are still being refined (see below for list).

## Functional features

- Audio file playback with support for importing multiple directories for music library
- Togglable synced-lyric display in now playing bar for active line
- Four built-in themes: **Light, Dark, Black / AMOLED, and Dynamic** (changes colors to match album art)
- Ability to customize built-in themes' with custom RGB colors (not available on Dynamic theme), and custom fonts 
- Ability to override default album art and artist artwork with custom images
- Automatic album and artist artwork importing from folders
- Customizable artist and genre separators
- Writable artist descriptions
- Custom-mappable keyboard shortcuts
- Discord Rich Presence
- Toggle to keep the screen awake while app is in focus
- Toggleable "smart search" function that adds autocomplete to search, and a top-results section showing the most relevant matches
- Fully functional playlist creation and management with ability to export/import playlists as M3U
- Setting to restore queue and actively playing song from last close on app open
- Setting to automatically resume/play restored song on app open if this setting is enabled

## Planned Features (WIP)

- A couple colorful custom theme presets
- Custom background images for custom themes
- Ability to import and export custom themes, with shared community themes accessible to import through linked Discord Server
- Further theme customization options
- Ability to use custom icon packs as part of custom themes
- Album-art blur theme
- Further UI polish and visual tweaks
- Fullscreen player view
- YouTube Music-style maximized player view
- Pop-out now-playing window
- Visualizer support with customizable theming
- Optional right-hand sidebar with media controls like Spotify
- Resizable player panels and sidebar
- Ability to minimize left sidebar
- Customizable home page and sidebar layouts
- Minimize-to-system-tray support
- Media controls in the notification area
- Media buttons in the application window preview on hover
- An option to respect the Windows light/dark theme when scheduling automatic theme changes, unless a custom or dynamic theme is activated
- An option to launch the application at system startup
- Ability to export/import app settings
- An option to adjust the fade duration when pausing/resuming playback
- A toggle for gapless playback
- Music video support
- Custom HTML/CSS embeds
- Equalizer button to open Peace Equalizer/Equalizer APO window
- Automixes based on your listening habits and genre tags
- Metadata editor
- Lyric editor with powerful synchronized and karaoke lyric tools
- MusicBrainz release-type support for albums, EPs, singles, and more
- A "Featured on" section on artist pages for songs featuring the artist where the associated album is not tagged with the artist as an album artist
- Setting to hide "- Single" and "- EP" from album names if written into album metadata
- Ability to capture the current queue and save it as a playlist
- Ability to choose custom playlist image from file
- ListenBrainz & Last.fm integration
- Listening stats
- About/credits page

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
