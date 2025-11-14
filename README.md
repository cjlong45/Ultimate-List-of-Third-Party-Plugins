markdown


# 🎯 Ultimate List of Jellyfin Plugin Repositories

A comprehensive, curated list of verified Jellyfin plugin repositories. Add these URLs to your Jellyfin instance to access hundreds of community plugins.

---

## 📖 Table of Contents

- [How to Add Repositories](#how-to-add-repositories)
- [Official Repositories](#official-repositories)
- [Third-Party Plugin Repositories](#third-party-plugin-repositories)
- [Individual Plugin Repositories](#individual-plugin-repositories)
- [Manual Installation Plugins](#manual-installation-plugins)
- [Repository Statistics](#repository-statistics)

---

## 🔧 How to Add Repositories

1. Open Jellyfin and go to **Dashboard**
2. Navigate to **Plugins** → **Repositories**
3. Click the **➕ (Plus)** button
4. Enter:
   - **Repository Name:** Any name you want (e.g., "Intro Skipper")
   - **Repository URL:** Copy URL from list below
5. Click **Save**
6. Go to **Catalog** tab to browse and install plugins
7. **Restart Jellyfin** after installing plugins

---

## 🏛️ Official Repositories

### **Jellyfin Official Repository**
https://repo.jellyfin.org/files/plugin/manifest.json

code


**Pre-configured in Jellyfin by default**

**Includes:**
- TMDb Box Sets - Automatic movie collections
- Fanart - Additional artwork provider
- Open Subtitles - Subtitle downloads
- Playback Reporting - Watch statistics
- Trakt - Scrobbling to Trakt.tv
- LDAP Authentication - LDAP login support
- NextPVR - Live TV integration
- Kodi Sync Queue - Kodi synchronization
- AniDB, AniList, Kitsu - Anime metadata providers
- TheTVDB - TV metadata provider
- Reports - Media library reports
- Bookshelf - Ebook support
- And many more...

---

### **Jellyfin Official Unstable Repository**
https://repo.jellyfin.org/files/plugin-unstable/manifest.json

code


**Beta/unstable versions of official plugins for testing**

⚠️ **Warning:** Unstable builds may have bugs

---

## 🎨 Third-Party Plugin Repositories

### **Intro Skipper** ⭐
https://intro-skipper.org/manifest.json

code


**Most popular intro-skipping plugin**

**Features:**
- Automatically detect and skip TV show intros
- Skip credits/outros
- Uses audio fingerprinting for accurate detection
- Customizable skip buttons
- Chapter-based detection support

---

### **Danieladov's Plugin Collection** ⭐
https://raw.githubusercontent.com/danieladov/JellyfinPluginManifest/master/manifest.json

code



**Includes 3 essential plugins:**
- **Merge Versions** - Automatically group duplicate movies (4K, 1080p, etc)
- **Theme Songs** - Download TV show theme songs from YouTube
- **Skin Manager** - Download and manage Jellyfin themes/skins

---

### **Jellyscrub** ⭐
https://raw.githubusercontent.com/nicknsy/jellyscrub/main/manifest.json

code



**Features:**
- Smooth mouse-over thumbnail previews while scrubbing
- Generates BIF (trickplay) files for your media
- Bufferless preview images
- Configurable thumbnail generation settings

---

### **SSO Authentication (9p4)** ⭐
https://raw.githubusercontent.com/9p4/jellyfin-plugin-sso/manifest-release/manifest.json

code



**Features:**
- Single Sign-On support
- Authenticate via Google, Microsoft, Facebook, GitHub
- Support for custom OIDC providers
- Simplifies user management
- One-click login

---

### **Ani-Sync** ⭐
https://raw.githubusercontent.com/vosmiic/jellyfin-ani-sync/master/manifest.json

code



**Features:**
- Sync anime watch progress to MyAnimeList
- Sync to AniList
- Sync to Kitsu
- Sync to Simkl
- Automatic episode tracking
- Status synchronization (watching, completed, etc)

---

### **Shokofin**
https://raw.githubusercontent.com/ShokoAnime/Shokofin/metadata/stable/manifest.json

code



**Features:**
- Integrate Shoko anime database with Jellyfin
- Advanced anime library management
- Comprehensive metadata from AniDB
- Episode grouping and organization
- Multi-source metadata aggregation

---

### **Shemanaev's Plugin Repository**
https://raw.githubusercontent.com/shemanaev/jellyfin-plugin-repo/master/manifest.json

code



**Includes:**
- **MyShows** - Scrobble TV shows to MyShows.me (Russian service)
- **Enhanced Webhooks** - Advanced webhook notifications with Plex format support
- **Media Cleaner** - Auto-delete watched media after set time period

---

### **LinFor's Kinopoisk Plugin**
https://raw.githubusercontent.com/LinFor/jellyfin-plugin-kinopoisk/master/dist/manifest.json

code



**Features:**
- Metadata from Kinopoisk.ru (Russian movie database)
- Russian language titles and descriptions
- Ratings, cast, crew information
- Trailers and posters
- Popular in Russian-speaking communities

---

### **LizardByte's Themerr**
https://app.lizardbyte.dev/jellyfin-plugin-repo/manifest.json

code


**Alternative URL:**
https://lizardbyte.github.io/jellyfin-plugin-repo/manifest.json

code



**Features:**
- Automatically download theme songs for movies and TV shows
- Uses ThemerrDB database
- Enhances browsing experience with authentic theme music

---

### **Ankenyr's YouTube Metadata**
https://raw.githubusercontent.com/ankenyr/jellyfin-plugin-repo/master/manifest.json

code



**Features:**
- Metadata for YouTube content
- Local provider using yt-dlp info.json files
- Remote provider downloads info via yt-dlp
- Thumbnails, descriptions, upload dates
- Channel information

---

### **K-Matti's Repository**
https://raw.githubusercontent.com/k-matti/jellyfin-plugin-repository/master/manifest.json

code



**Includes:**
- **SMS Notification** - Send SMS alerts for Jellyfin events
- **NapiSub** - Polish subtitle downloads from NapiProjekt

---

### **TubeArchivist Metadata**
https://raw.githubusercontent.com/tubearchivist/tubearchivist-jf-plugin/master/manifest.json

code



**Features:**
- Integration with TubeArchivist
- Organize archived YouTube content
- Metadata and library management for YouTube videos
- Works with TubeArchivist backend

---

### **AudioMuse AI**
https://raw.githubusercontent.com/neptunehub/audiomuse-ai-plugin/master/manifest.json

code



**Features:**
- AI-powered music recommendations
- Sonic analysis of audio files
- Smart song clustering
- Replaces InstantMix with better suggestions
- Audio fingerprinting technology

---

### **MyAnimeList Metadata Provider**
https://raw.githubusercontent.com/ryandash/jellyfin-plugin-myanimelist/main/manifest.json

code



**Features:**
- MyAnimeList as metadata provider
- Uses Jikan API and MAL
- Anime ratings, descriptions, relationships
- Comprehensive anime information

---

### **Jellyfin.Xtream (IPTV)**
https://kevinjil.github.io/Jellyfin.Xtream/repository.json

code



**Features:**
- Integrate Xtream-compatible IPTV APIs
- Live TV streams
- VOD (Video on Demand) content
- TV series from IPTV providers
- EPG (Electronic Program Guide) support

---

### **WizdomSubs Hebrew Subtitles**
https://raw.githubusercontent.com/DeDuplicate/Jellyfin_wizdomsubs_downloader/refs/heads/main/manifest.json

code



**Features:**
- Automatic Hebrew subtitle downloads
- WizdomSubs integration
- High-quality Hebrew subtitles
- Automatic media file matching

---

### **m3u Editor**
https://simoni.dev/jellyfin/repo.json

code



**Features:**
- Edit m3u playlists for Live TV
- Manage IPTV channel lists
- Customize EPG settings

---

### **IAmParadox Plugins**
https://www.iamparadox.dev/jellyfin/plugins/manifest.json

code



**Includes:**
- **Media Bar** - Featured content carousel
- **Home Sections** - Customize home screen sections
- **Collection Sections** - Display collections/playlists
- **File Transformation** - Modify Jellyfin web files

---

### **InfuseSync (Firecore)**
https://files.firecore.com/jellyfin/manifest.json

code



**Features:**
- Sync playback with Infuse app (Apple devices)
- Watched status synchronization
- Resume position syncing
- Seamless cross-platform viewing

---

### **Jellyfin Enhanced**
https://raw.githubusercontent.com/n00bcodr/jellyfin-enhanced/main/manifest.json

code



**Features:**
- Keyboard shortcuts
- Advanced subtitle styling
- TMDB reviews integration
- Jellyseerr search and request
- Multiple UI/UX improvements

---

### **Custom Logo Plugin**
https://raw.githubusercontent.com/bvolvy/CustomLogoPlugin/main/manifest.json

code



**Features:**
- Replace default Jellyfin logo
- Upload custom branding
- Personalize login screen
- Custom header logo

---

### **Auto Collections (KeksBombe)**
https://raw.githubusercontent.com/KeksBombe/jellyfin-plugin-auto-collections/refs/heads/main/manifest.json

code



**Features:**
- Automatically create collections
- Dynamic collection rules
- Based on genres, actors, directors, studios
- Maintain collections automatically
- Flexible criteria system

---

### **Letterboxd Sync**
https://raw.githubusercontent.com/danielveigasilva/jellyfin-plugin-letterboxd-sync/master/manifest.json

code



**Features:**
- Sync watched movies to Letterboxd
- Automatic diary updates
- Track movie viewing history
- Integration with Letterboxd account

---

### **Meilisearch Enhanced Search**
https://raw.githubusercontent.com/arnesacnussem/jellyfin-plugin-meilisearch/refs/heads/master/manifest.json

code



**Features:**
- Lightning-fast search
- Typo tolerance
- Advanced filtering
- Dramatically improved search performance
- Better search accuracy

---

### **ProviderStuff**
https://raw.githubusercontent.com/kamilkosek/jellyfin-plugin-provider-stuff/main/manifest.json

code



**Features:**
- Auto-tag items with streaming provider info
- Create collections per provider (Netflix, Disney+, etc)
- Organize content by source
- Automatic provider detection

---

### **MetaTube** 🔞
https://raw.githubusercontent.com/metatube-community/jellyfin-plugin-metatube/dist/manifest.json

code



**Features:**
- Metadata for adult content
- Multiple provider support
- Face detection
- Auto-translation
- Comprehensive metadata (titles, genres, actors, studios)

⚠️ **Adult content plugin** - Use responsibly

---

### **MyTube (Alternative MetaTube)**
https://raw.githubusercontent.com/Topbcy/jellyfin-plugin-mytube/refs/heads/main/manifest.json

code



**Features:**
- Alternative MetaTube instance
- Different configuration options
- Adult content metadata

⚠️ **Adult content plugin** - Use responsibly

---

## 📦 Individual Plugin Repositories

These plugins have their own standalone repositories:

### **Intro Skipper (Standalone - Already Listed Above)**
Already included in Third-Party section above ⬆️

---

## 🔧 Manual Installation Plugins

These plugins don't have hosted manifest files and require manual installation via GitHub Releases:

### **InPlayerEpisodePreview**
- **GitHub:** https://github.com/giladgd/jellyfin-inplayerepisodepreview-plugin
- **Purpose:** Episode list in video player
- **Install:** Download .zip from Releases, extract to plugins folder

---

### **Jellyfin Icon Metadata**
- **GitHub:** https://github.com/crobibero/jellyfin-icon-metadata
- **Purpose:** Adds metadata provider icons
- **Install:** Manual installation from releases

---

### **Jellyfin Ignore**
- **GitHub:** https://github.com/ConfusedPolarBear/jellyfin-plugin-ignore
- **Purpose:** Ignore filename patterns during library scans
- **Install:** Manual installation from releases

---

### **Jellyfin JavaScript Injector**
- **GitHub:** https://github.com/lukencode/jellyfin-plugin-javascript-injector
- **Purpose:** Inject custom JavaScript into Jellyfin UI
- **Install:** Manual installation from releases

---

### **Jellyfin Local Posters**
- **GitHub:** https://github.com/h1dden-da3m0n/jellyfin-local-posters
- **Purpose:** Auto-match and import local posters (TPDb/MediUX formats)
- **Install:** Manual installation from releases

---

### **Jellyfin Music Tags**
- **GitHub:** https://github.com/lyarenei/jellyfin-plugin-musictags
- **Purpose:** Extract audio metadata to Jellyfin tags
- **Install:** Manual installation from releases

---

### **Jellyfin Newsletter Plugin**
- **GitHub:** https://github.com/Cloud9Developer/jellyfin-plugin-newsletter
- **Purpose:** Send newsletters for recently added media
- **Install:** Manual installation from releases

---

### **Jellyfin Air Times**
- **GitHub:** https://github.com/Kevinjil/jellyfin-plugin-air-times
- **Purpose:** Show localized series air times
- **Install:** Manual installation from releases

---

### **Jellyfin AnimeThemes**
- **GitHub:** https://github.com/Vemoo/jellyfin-plugin-animethemes
- **Purpose:** Fetch anime themes from AnimeThemes.moe
- **Install:** Manual installation from releases

---

### **Jellyfin Collection Import**
- **GitHub:** https://github.com/Kevinjil/jellyfin-plugin-collection-import
- **Purpose:** Import collections from mdblist and other sources
- **Install:** Manual installation from releases

---

### **Jellyfin Cinema Mode**
- **GitHub:** https://github.com/nathanssantos/jellyfin-plugin-cinemamode
- **Purpose:** Cinema mode with local trailers
- **Install:** Manual installation from releases

---

### **Jellyfin Language Tags**
- **GitHub:** https://github.com/Kevinjil/jellyfin-plugin-languageTags
- **Purpose:** Add language tags based on audio tracks
- **Install:** Manual installation from releases

---

### **Jellyfin ListenBrainz**
- **GitHub:** https://github.com/lyarenei/jellyfin-plugin-listenbrainz
- **Purpose:** Scrobble music to ListenBrainz
- **Install:** Manual installation from releases

---

### **Jellyfin One Pace**
- **GitHub:** https://github.com/Chaphasilor/jellyfin-plugin-onepace
- **Purpose:** One Pace project integration (fan-edited One Piece)
- **Install:** Manual installation from releases

---

### **Jellyfin Pages**
- **GitHub:** https://github.com/crobibero/jellyfin-plugin-pages
- **Purpose:** Create custom Jellyfin pages matching native UI
- **Install:** Manual installation from releases

---

### **Jellyfin Streamyfin Companion**
- **GitHub:** https://github.com/streamyfin/streamyfin-jellyfin-plugin
- **Purpose:** Companion plugin for Streamyfin mobile app
- **Install:** Manual installation from releases

---

### **Jellyfin Telegram Notifier**
- **GitHub:** https://github.com/Viperinius/jellyfin-plugin-TelegramNotifier
- **Purpose:** Receive Jellyfin notifications via Telegram
- **Install:** Manual installation from releases

---

### **Jellyfin Roulette**
- **GitHub:** https://github.com/DarHa1531212/Jellyfin-Roulette
- **Purpose:** Play random entry from playlist
- **Install:** Manual installation from releases

---

### **Jellyfin Stream Limit**
- **GitHub:** https://github.com/3dproger/Jellyfin.Plugin.StreamLimit
- **Purpose:** Limit simultaneous streams per user
- **Install:** Manual installation from releases

---

### **Jellyfin Editors Choice**
- **GitHub:** https://github.com/Nalsai/jellyfin-editors-choice-plugin
- **Purpose:** Netflix-style featured content slider
- **Install:** Manual installation from releases

---

### **Jellyfin Media Bar**
- **GitHub:** https://github.com/Nalsai/jellyfin-plugin-media-bar
- **Purpose:** Featured content bar for homepage
- **Install:** Manual installation from releases

---

### **Gelato (Stremio Integration)**
- **GitHub:** https://github.com/n1rvana-labs/gelato
- **Purpose:** Replace search with Stremio-powered results, auto-import catalogs
- **Install:** Manual installation from releases
- ⚠️ **Advanced users only**

---

### **Plexyfin**
- **GitHub:** https://github.com/shadowninja108/Plexyfin
- **Purpose:** Sync artwork and collections from Plex to Jellyfin
- **Install:** Manual installation from releases

---

### **Static Assets Plugin**
- **GitHub:** https://github.com/crobibero/jellyfin-plugin-static-assets
- **Purpose:** Upload and serve static assets (CSS, JS, images)
- **Install:** Manual installation from releases

---

### **TeleJelly**
- **GitHub:** https://github.com/Viperinius/TeleJelly
- **Purpose:** Sign in via Telegram Login Widget
- **Install:** Manual installation from releases

---

## 📊 Repository Statistics

### **Repositories with Hosted Manifests:** 27
### **Manual Installation Plugins:** 24
### **Total Plugins Documented:** 51+

### **Categories:**
- 🎬 **Video Enhancement:** 6 plugins
- 📊 **Analytics & Reporting:** 3 plugins
- 🔐 **Authentication:** 2 plugins
- 🎵 **Music:** 3 plugins
- 📺 **Live TV/IPTV:** 2 plugins
- 🌐 **Metadata Providers:** 8 plugins
- 📝 **Subtitles:** 2 plugins
- 🔔 **Notifications:** 4 plugins
- 🎨 **UI/UX:** 8 plugins
- 📚 **Library Management:** 7 plugins
- 🔄 **Sync/Integration:** 8 plugins
- 🔧 **Utilities:** 6 plugins

---

## 🛠️ Manual Installation Instructions

For plugins requiring manual installation:

1. **Download** the latest .zip from the plugin's GitHub Releases page
2. **Extract** the .zip file
3. **Navigate** to your Jellyfin data directory:
   - **Windows:** `C:\ProgramData\Jellyfin\Server\plugins\`
   - **Linux:** `/var/lib/jellyfin/plugins/`
   - **Docker:** `/config/plugins/`
4. **Create folder** named after the plugin (e.g., `InPlayerEpisodePreview`)
5. **Copy** the extracted files into that folder
6. **Restart** Jellyfin server
7. **Verify** plugin appears in Dashboard → Plugins

---

## ⚠️ Important Notes

### **Compatibility**
- Check each plugin's `targetAbi` version matches your Jellyfin version
- Most plugins target Jellyfin 10.9.x or 10.10.x
- Some older plugins may not work with latest Jellyfin

### **Stability**
- Official plugins are most stable
- Third-party plugins vary in quality and maintenance
- Always backup before installing new plugins
- Test plugins on non-production servers first

### **Security**
- Only install plugins from trusted sources
- Review plugin permissions before installation
- Be cautious with plugins requiring external services

### **Support**
- For official plugins: Jellyfin forums and GitHub
- For third-party plugins: Contact plugin developer on their GitHub
- Check plugin's GitHub Issues page for known problems

---

## 🔄 Keeping This List Updated

This list is maintained at:
**https://github.com/cjlong45/Ultimate-List-of-Jellyfin-Plugins**

### **Contributions Welcome!**
- Found a new plugin repository? Submit a PR!
- Plugin URL changed? Let me know!
- Plugin no longer maintained? Report it!

---

## 📖 Additional Resources

- **Jellyfin Official Plugins:** https://jellyfin.org/docs/general/server/plugins/
- **Awesome Jellyfin:** https://github.com/awesome-jellyfin/awesome-jellyfin
- **Jellyfin Forum:** https://forum.jellyfin.org/
- **Jellyfin Discord:** https://jellyfin.org/contact

---

## 📜 License

This list is provided as-is for informational purposes. Each plugin has its own license - check individual repositories for details.

---

## 🙏 Credits

- **Jellyfin Team** - For the amazing media server
- **All plugin developers** - For extending Jellyfin's functionality
- **Community contributors** - For discovering and sharing plugins

---

**Last Updated:** November 2024  
**Maintained by:** cjlong45  
**Total Repositories:** 27 hosted + 24 manual install

---

## 🚀 Quick Start Recommended Repositories

If you're new to Jellyfin plugins, start with these essential repositories:

1. ✅ **Intro Skipper** - Must-have for TV shows
2. ✅ **Jellyscrub** - Essential for smooth scrubbing
3. ✅ **Danieladov's Collection** - Merge Versions + Theme Songs + Skin Manager
4. ✅ **Official Repository** - Pre-configured, includes Fanart, TMDb, etc.

These four repositories will give you access to the most popular and useful plugins!

---

**Happy Streaming! 🎬🍿**
