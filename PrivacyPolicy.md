DULE PLAYER PRIVACY POLICY

Effective date: 15 August 2026
Last updated: 16 October 2026
App version covered: 0.3.25 (version code 33), including model-profile, speaker-preset and DJ-mode updates

Sound Lab processes decoded music locally to estimate bass energy and K-weighted loudness,
manage gain and support volume leveling. These rolling estimates
stay in temporary memory and are not microphone recordings or uploaded audio. Optional measured
model profiles can be selected in Sound Lab. Profiles retired before this update are not silently
reactivated. Automatic output-aware tuning uses Android's
reported output type and available name; these do not measure acoustic response or guarantee
an exact model match. True-peak protection uses an oversampled estimate and short local
audio buffer; it does not send music to a server. This update introduces no paid audio service.

Model profiles use the AutoEq catalog (https://github.com/jaakkopasanen/AutoEq).
The searchable index is bundled in the App. Selecting an uncached model, or enabling optional
Auto-match Bluetooth for an uncached supported model, requests its EQ text from GitHub's
raw.githubusercontent.com service. GitHub receives normal connection metadata such as your IP
address and the requested model-file path. Dule does not send song audio, music history, raw
Bluetooth addresses or account credentials in these requests. Selected profiles and downloaded
EQ text are saved locally for offline reuse. Auto-match Bluetooth is off until enabled by you.
Output Memory may use a locally derived hash of an Android-provided output address, when
available, or the reported output type/name. This is not a measurement or guaranteed model ID.
Use general tuning removes the active model selection; cached text may remain until App storage
is cleared or the App is uninstalled. These changes do not update the published policy website.

Optional DJ mode overlaps supported local tracks, normally starting the next song about ten
seconds before the current song ends. Cached on-device audio classifications and rhythm/energy
estimates can adjust the overlap. Short songs and available decoder resources can limit it.
DJ mode and transition-sound preferences, and existing compact audio-analysis results, are
stored locally. Music-reactive visuals read decoded playback levels locally. Temporary audio
buffers, next-song preloading and bass/volume handovers are processed on the device.
Optional original transition sounds are synthesized locally; they are not downloaded samples.
DJ mode introduces no microphone recording, upload of local music, paid AI service or extra
network prefetch. It does not mix YouTube video, remote casting, live radio or network streams.

Speaker model starting presets are bundled and work offline. They are Dule speaker-size
voicings, not measured acoustic corrections or manufacturer-endorsed calibrations. Optional
Bluetooth matching uses specific supported model names, not a guaranteed hardware identity.
Selections and general-tuning choices can be remembered locally per output. Opening a
manufacturer-information link uses your browser and that website's normal connection metadata.

Dule Player ("Dule Player," "Dule," "the App," "we," "us," or "our") is an Android music and media player developed by D HANSAJA. This Privacy Policy explains what information the App accesses, how that information is used and stored, when information is sent to third-party services, and the choices available to users.

Dule Player was previously identified during development as "DSHOT Player" or "D Shot Player." It is the same Android API Client. This branding change does not change the App's package identifier (com.dshot.player), individual developer ownership, Google Cloud project, YouTube API use case, or data practices described in this Policy.

Please read this Policy before using Dule. Android permissions and the App's in-context notices explain choices for features that need additional access or transfer information to other services. Do not use an optional online or sharing feature if you do not accept the data handling described for it.

1. SUMMARY

Dule is primarily a local music player with optional internet and private-network media features. The App does not require a Dule account. Local music, playlists, favorites, playback history, equalizer settings, network-library profiles, video resume positions, preferences, and on-device audio-analysis results are stored locally on the user's device. Dule does not upload local audio or video files to the developer and does not sell personal information.

When a user chooses an online feature, limited song metadata or search text may be sent to the relevant third-party service to provide search results, artwork, lyrics, online audio, track identification, or a YouTube video. Those third parties receive normal network information, such as the user's IP address, according to their own privacy policies.

Dual lyrics normally uses downloaded on-device translation models. Sinhala is not supported by that model. When Dual translates lyrics to or from Sinhala, it sends lyric lines over HTTPS to Dule's Cloudflare Worker, which forwards them to Microsoft's Azure Translator and returns translated lines. This works on Wi-Fi or mobile data. The Worker receives the lyric lines and source/target language codes needed for the request. Its source code does not intentionally persist or log lyric text, but Cloudflare and Microsoft may process operational and security information under their own policies. This is not a promise of zero platform logging. Cloudflare receives connection information, such as IP address, and Cloudflare and Microsoft process data under their own privacy policies. Users can select Original instead of Dual to avoid sending lyric text for translation. This version removes any personal Azure Translator key saved by earlier versions. Translation may be inaccurate or unavailable when a free quota is reached.

Google ML Kit identifies lyric languages and translates supported language pairs on the phone. Input lyrics and on-device translation results are not sent to Google for translation. Language models download from Google when needed. Wi-Fi and mobile-data downloads are allowed by default; the App's main mobile-data setting also controls metered-network downloads for Dual language packs. The separate Wi-Fi-only artwork/lyric-lookup setting does not control these packs. Mobile-data charges may apply. ML Kit may send device and app information, technical performance, usage metrics and model-download information to Google under its privacy terms (https://developers.google.com/ml-kit/terms). Sinhala uses the separate online translation path described above.

Downloaded translation models remain on the phone for reuse without another download while the required models are available. The translation-language selector shows installed packs and offers download or removal controls where supported. Removing a model does not remove music files or independently cached lyric translations; the model can be downloaded again. Sinhala uses the online service and has no offline model pack in this App. Android storage management, clearing App storage or uninstalling can remove downloaded models.

Language-download notifications, when allowed, show the language and current song title with private lock-screen visibility. Android's notification settings control whether these details are visible. They do not contain lyric text. Download indicators do not claim byte percentages; the percentage inside Dual measures translated lyric lines. Download-status notices stop showing progress when the SDK reports completion or failure and expire automatically. Disabling notifications does not disable translation.

For supported non-Sinhala pairs, Dule caches source lyric lines, their translations and the detected source language in private, disposable on-device storage to avoid repeating completed work. The cache is limited to 80 entries and 8 MB; entries expire after 30 days without use and Android may evict them sooner. Filenames use hashes rather than track titles or paths. Clear cache or Clear downloaded lyrics removes these cached results; these controls keep downloaded ML Kit language models. Clearing App storage or uninstalling removes this local data. Sinhala's online translation path is unchanged and is not added to this persistent translation cache.

Dule retains a private local snapshot of device music metadata to keep the library available when Scan on launch is off. A fresh scan replaces this snapshot; filters for excluded folders, minimum track length and Dule Trash still apply. It contains track identifiers, titles, artists, albums, content/artwork URIs and available file metadata, not the audio files. The snapshot and translation cache are not included in Dule's selected Android backup rules. Imported custom fonts are stored as private copies, with the active copy and one previous copy retained; they are removed by clearing App storage or uninstalling.

Listening History off or Private Session stops new listening-history entries and play-count/last-played statistics, including service-owned background playback. Existing records remain until cleared. Clear listening history removes the timeline, recently played entries and play-count/last-played statistics while keeping playlists, favorites and media. Optional Listening Safety uses separate local duration and volume-exposure records, is controlled by Safety monitoring, and may operate while the screen is off. These estimates are not a medical measurement.

The Now Playing lyrics controls are Original, Dual and Coach. Original displays the source lyrics; Dual adds a translation where available; Coach provides on-device pronunciation assistance. The selected mode and translation-language preferences are stored locally. The separate Say control has been removed, and a previously saved Say selection changes to Original locally when the player opens. This migration does not send lyrics or preferences to an online service. Choosing Original or Coach avoids Dual translation requests, but does not disable optional online lyric lookup or other online features the user has enabled.

2. INFORMATION ACCESSED ON THE DEVICE

With the user's permission, Dule may access:

- Local audio files and their MediaStore records;
- Track title, artist, album, duration, bitrate, folder, date-added information, embedded artwork, and content URI;
- Playback position, queue, play counts, listening history, favorites, playlists, ratings or preferences created in the App;
- Timestamped Listening Memory events and locally calculated recommendation reasons and scores used by Transparent Intelligence;
- Equalizer, compressor, immersive-audio, Auto Boost, theme, animation, download, and other App settings;
- App-language and font preferences. Dule supports Unicode media text and may use the selected app locale or the device locale;
- Locally generated audio-analysis classifications and compact signatures;
- Mobile-network country, SIM country, or phone-region information used locally to suggest a radio country;
- Approximate location, only when the user chooses location-based radio-country detection. Coordinates are used temporarily to derive a country code and are not retained by Dule. Android's Geocoder may send the coordinates to the device's geocoding service under that provider's privacy policy;
- Network connection status, including whether Wi-Fi is available, the device's current private IPv4 subnet used for optional SMB discovery, and responses from devices checked for SMB availability;
- Information required by Android to display media controls, playback notifications, widgets, Trash reminders, and ringtone or alarm-tone actions selected by the user;
- Media information and commands exposed through Android's system media framework for Android Auto and paired Wear OS controls, including track title, artist, album, artwork, duration, playback position, queue, browse/search results, and play, pause, seek, previous, and next actions;
- On-device diagnostics shown to the user, such as playback state, queue size, cache size, permission status, the most recent playback error and its time, and current device storage, memory, or processor-use estimates. Dule does not automatically send these diagnostics to the developer;
- Live DSP measurements calculated from the decoded audio being played, including input and processed peak levels, sample rate, active-filter count, preamp/headroom values, limiter reduction, clipping counters, and processing status. These measurements are displayed temporarily in Sound Lab and are not automatically transmitted to the developer. Selected technical measurements can be included in a bug-report email only when the user enables Include app diagnostics and sends the email;
- Per-output sound-profile information used by Output Memory, including the Android-provided output type or device name and the equalizer, normalization, Auto Boost, and spatial-audio preferences associated with that output;
- SMB server profiles supplied or selected by the user, including display name, server address, port, share, folder, username and optional domain. If Remember Password is enabled, the SMB password is encrypted using a key held by Android Keystore. If it is disabled, the password is retained only for the current App process/session. SMB credentials are not included in Dule backup exports or Android cloud backup; and
- When Dule Rooms is explicitly used, the temporary room name and address, current track identifier, title, artist, playback position, duration, participant count, device model/name, protocol version, room chat messages, room queue, guest song requests and approval decisions, and—when LAN audio is needed—the bytes of an approved local audio file exchanged directly between room devices. While connected, each participant's Dule app reports the title and artist currently selected in Dule, whether it is playing or paused, and whether maker controls are allowed so the room maker can show live listening presence and the correct controls. The host can see each connected device's local IP address for identification and moderation. Guest IP addresses and listening presence are not intentionally redistributed to other guests. Personal seek position and equalizer state remain local.

Dule does not use the microphone for track identification. When enabled, audio intelligence analyzes short decoded samples from the music source already being played. This processing runs on the device. The audio sample itself is not sent to an AI server.

3. ANDROID PERMISSIONS

Dule may request the following permissions or system access:

- Music and audio access: used to scan, display, organize, and play local audio files;
- Notifications permission: used for playback controls, Trash-retention reminders and lyric-language download status; it does not grant access to other apps' notifications;
- Internet and network-state access: used for optional online search, streaming, YouTube Video mode, artwork, lyrics, metadata services, SMB discovery, and direct communication with a user-selected computer, NAS, or SMB server on the local network;
- Local-network or Nearby Devices access: Android currently permits the App's target version to make local-network connections through Internet access. A future Android version or target-SDK update may require a separate runtime local-network permission. If required, Dule will explain and request it before SMB discovery or connection, and denial will disable Network Library without blocking ordinary local playback;
- Approximate location access: optional and requested in context only when needed or when the user chooses Improve in Live Radio. It is used once to identify the country and place local radio stations first. Dule does not request precise or background location, store coordinates, or prevent worldwide radio browsing when this permission is denied;
- Foreground media-playback and wake-lock access: used to continue playback and show media controls when the App is not in the foreground;
- Vibration access: used for enabled haptic feedback and music-haptics features;
- Android Auto and paired Wear OS media access: used through Android's system media framework so compatible vehicle displays and paired watches can browse or search the Dule library, show current media information, and control playback. These surfaces do not create a separate Dule account or give the developer the user's vehicle or watch data; and
- Modify system settings access: requested only when the user chooses to set a track or selected track segment as a phone ringtone or alarm tone.

When the user chooses Scan room QR, Dule opens the Google Play services Code Scanner interface. Dule does not request a permanent camera permission for this feature. The scanner returns the QR text to Dule; Dule accepts a valid Dule Room address and uses it to attempt the requested local-network connection. Users can always enter the room address manually instead.

Permissions can be denied or revoked through Android Settings. Some features will not work without their related permission.

4. LOCAL STORAGE AND PERSONALIZATION

The App may store the following information locally:

- App settings and audio-effect preferences;
- Widget identifiers, themes, selected library modes and control-visibility preferences. Widgets display selected artwork, song metadata, recent/favorite tracks and playback or Sound Lab state through Android's home-screen framework. People who can view the home screen may see this information;
- Favorites, playlists, queue information, play counts, listening history, snoozed recommendations, and playback-session information;
- Smart Bookmarks containing a track identifier, track title, saved playback position, optional user label, and creation time;
- Listening Safety estimates derived from local playback duration, system media-volume level, and recent high-volume exposure. These estimates are informational, stay on the device, and are not medical measurements;
- Sound DNA summaries and Dule Fusion data. A Fusion code contains an aggregate preference profile rather than song titles or listening history; it leaves the device only when the user intentionally copies or shares it;
- Output Memory and headphone-profile preferences associated with locally detected wired, Bluetooth, USB, speaker, or external output routes, including the output type/device name, saved manual EQ or preset, Auto Boost, compressor, normalization, balance and immersive settings. Immersive settings include enablement, amount, center focus, ambience, cinema bass, Auto Immersive, crossfeed and stereo width;
- Library Doctor and integrity-monitor results, including locally detected missing files, duplicate candidates, weak or damaged media indicators, incomplete metadata, and broken playlist references;
- User-written natural-language playlist rules and the local playlists generated from those rules; accessibility, font, contrast, and reduced-motion preferences;
- Downloaded or cached lyrics and artwork;
- Track-identification results and on-device audio-analysis results;
- Selected YouTube video matches, including video ID, title, channel name, and thumbnail URL;
- The detected or selected radio country and the general detection source, such as mobile network, SIM, phone region, or approximate location. Geographic coordinates are not stored;
- Metadata for tracks placed in Dule Trash, including the date they entered Trash; and
- Network-video resume positions, playback speed, fit/fill preference, and selected media-track preferences used to restore the video player.

This information is used to operate the App, restore playback, personalize recommendations and Smart Shuffle, reduce repeated network requests, and improve track matching. Listening history can be disabled with Private Session or the Listening History setting. History, recommendations, downloaded artwork, and downloaded lyrics can be cleared using controls in the App.

Settings search matches the user's query against a settings catalog locally on the device. Settings-search text is not sent to the developer or to an online search provider. Selecting a result opens the relevant category or feature panel, scrolls to the matching control and briefly highlights it. This navigation does not itself change a setting, start calibration, clear data or send a support report. These actions require the user to use the corresponding control separately. This local Settings search is distinct from online music, artwork, lyric and video searches described elsewhere in this Policy.

Listening Memory and Transparent Intelligence operate locally. Listening Memory uses timestamped play events to build a private timeline. Transparent Intelligence uses local play counts, favorites, and artist affinity to display why a song was recommended and a visible recommendation score. The developer does not receive these records through a Dule server.

Dule Fusion, Smart Bookmarks, Listening Safety, Output Memory, Library Doctor, natural-language playlist rules, accessibility controls, and Sound Lab diagnostics operate locally. Dule Fusion creates an aggregate Sound DNA code that the user may choose to share with another person; Dule does not automatically upload or distribute that code. A recipient may retain any code the user shares. Live DSP meter values are short-lived interface state and are reset or replaced as playback changes. Collapsing meters or Details changes only their visibility; it does not stop enabled audio processing. Restart audio processing refreshes the playback DSP without sending a diagnostic report or changing saved sound preferences.

Dule Player's graphic equalizer, Auto Boost, compressor, limiter, adaptive bass, vocal protection, listening-comfort filters, and immersive stereo processing run on the device as part of playback. Auto Boost may use locally produced energy, rhythm, bitrate, output type, and classification labels to select a reversible tone curve and safety headroom. These settings and compact analysis results may be stored locally to restore the user's sound profile, but decoded audio samples and processed audio output are not uploaded to the developer. Live DSP values are not automatically uploaded; the optional support-email diagnostics described below may include selected technical measurements. Immersive stereo is two-channel signal processing; it does not create or collect room maps, head-tracking data, or microphone recordings. Dule Immersive Audio has its own control independent of Auto Boost, with both governed by Sound Lab's master switch. When Output Memory is enabled, saved immersive preferences restore for a recognized output. Older saved profiles inherit the existing local values for newly added immersive fields during migration; this migration does not contact an online service. Device names supplied by Android are not a guarantee of exact brand/model recognition or calibrated hardware matching.

When the user hosts or joins a Dule Room, up to fifteen devices communicate directly over the same local network. The joining phone sends its device model/name, a random session identifier and supported room-protocol version; the host also observes the source local IP address supplied by the network connection. These details help identify participants, moderate requests and maintain compatibility. Dule Rooms first uses a matching local track on each device when one is available. If no match exists, Dule can stream an approved supported phone-local track directly from the phone that owns it through a temporary, token-protected LAN connection. A guest may explicitly request one of their local tracks; its title, artist, duration and temporary stream address are sent to the host, and audio becomes available to the room only after host approval. The receiving phone plays this stream without intentionally saving a permanent music-file copy. Online-provider, radio, SMB, and other unsupported sources are not re-streamed through this fallback. After joining, participants may independently select any track available to their own Dule app without changing the shared queue. While connected, the participant's current Dule track title, artist, play/pause state and maker-control permission are sent to and shown only to the room maker as live listening presence. When the participant permits it, the maker may send play, pause, previous, next or return-to-room-track commands to that participant's phone; supported versions return temporary delivery confirmations and safely deduplicate retries. Following a short network interruption, Dule may retry the same private-network room connection up to five times with increasing delays. The participant can disable maker controls or leave at any time. This presence and control channel stop when the participant leaves and are not a wider listening-history upload. Seek position and equalizer state remain on the participant's phone.

Dule Room chat sends the display device name, message text, message identifier and timestamp directly to the host, which relays the message to current room participants. Unicode text and emoji are supported. Chat is temporary in memory, limited to recent messages, not uploaded to a Dule server and cleared when the room process ends; receiving participants may still take screenshots or otherwise retain messages. Do not send sensitive information. Chat is not end-to-end encrypted and should be used only on a trusted private network.

Users may replace their automatically suggested device identity with a custom room display name, which is stored locally and shared with room participants while connected. Queue votes, emoji reactions, DJ/listener roles, room-permission settings, request cooldown state, accepted-request counts and round-trip latency measurements are temporary room data. The host can lock the room, change participant roles or remove a participant. Latency is calculated from local message round trips and is not a precise location measurement. Saving a room session creates a local playlist only from tracks already available in that phone's library.

The room QR contains only a Dule-formatted local IP address and temporary control port. A separate media address and random session token are sent after the guest connects. Room audio, addresses, and session data are not routed through or stored by a Dule-operated server. The current Rooms transport is not end-to-end encrypted and does not authenticate participants with a Dule account or room password. Anyone on the same network who obtains the active room information may attempt to connect, and the network administrator may observe connection volume and timing. Users should use Rooms only on a trusted private network, share the QR or address only with intended participants, and end the room when finished.

Dule Rooms is subject to a separate in-App Privacy Notice and Terms consent screen. The acceptance version and acceptance time, or the most recent decline time, are stored only in the App's local preferences. Declining temporarily blocks Dule Rooms without blocking unrelated playback features. Dule may request acceptance again after a material Rooms change. Clearing App storage or uninstalling removes this local consent record.

When a participant leaves, or the maker confirms End Room, Dule closes the active Room control connection and LAN-sharing session and clears temporary participant, listening-presence, command-confirmation, chat, reaction, vote, request and queue state from memory. The App then returns to the Library. Audio already playing independently on a phone may continue through that phone's normal local playback service until its user pauses or changes it. The locally stored Rooms consent record and custom room identity are not erased merely by leaving a session.

When the Cast interface is opened, Google Play services may discover compatible receivers on the current network and display information such as receiver names and connection state. When the user explicitly selects a Google Cast receiver and starts remote playback, Dule sends the selected online media URL, title, artist, album, optional network artwork URL and playback position through Google Cast. The receiver fetches the media directly from its provider. Google, the receiver, the media host and the network administrator may receive ordinary device-discovery, connection and playback information under their own policies. Dule does not upload or expose phone-only content files for casting. Bluetooth, AirPlay-compatible routes supplied by a device manufacturer, and other system outputs are controlled by Android's output interface.

When the user opens Add Network Server, Dule may scan only the device's current private Wi-Fi or Ethernet /24 subnet by attempting short TCP connections to SMB port 445. No username or password is sent during this discovery. Nearby devices, the router, firewall, or network administrator may observe or log those connection attempts. The scan is initiated in the Network Library setup flow and is not used for background location tracking.

After the user selects or enters an SMB server, Dule connects directly from the phone to that server. It receives share names, directory listings, file information, and server-reported share capacity and available-space values, and reads selected audio, video and subtitle data for streaming and seeking. Capacity values refresh while the connected Network Library screen is open and may represent a disk, volume, quota, or storage pool according to the server. Browsing and playback are read-only by default. If the user explicitly selects Rename, Delete, or Move to phone and confirms the operation, the App sends the corresponding file operation directly to the selected server. Copy to phone does not modify the server source. Rename and Delete require write/delete permission from the server. Folder deletion is limited to empty folders.

Copy to phone and Move to phone create a local file either in Downloads/Dule through Android MediaStore or in a folder the user selects through Android's secure document picker. When a folder is selected, Android grants Dule access to that folder URI; the App uses it only to create the requested copy. Move first completes the local copy and only then attempts to delete the server source. If source deletion fails, the local copy is retained and the App reports that the source remains. Server Delete and the delete stage of Move permanently bypass Dule Trash. The App stores only the local result needed to show the operation outcome; it does not send this information to the developer.

Video decoding, resume-position storage and subtitle rendering occur on the device. The developer does not receive the server address, credentials, directory listing, media, subtitles, file-operation requests, or viewing history. The server or network administrator may keep ordinary authentication, connection, file-access, rename, and deletion logs under their own policies. Removing a saved server deletes its profile and encrypted password from the App but does not undo completed server operations or remove exported device copies.

SMB2/SMB3 authentication protects access to the selected share, but encryption of media while it travels across the local network depends on the SMB dialect and encryption settings supported and required by the server. Users should use a trusted private network, maintain the NAS or server securely, and enable SMB encryption on the server when appropriate.

Android may include selected App settings and personal-library preferences in an encrypted device backup or device-to-device transfer when the user has enabled Android backup. These backups are controlled by Android and the user's platform account, not by the Dule developer.

5. YOUTUBE API SERVICES AND EMBEDDED PLAYER

Dule uses YouTube API Services, including the YouTube Data API, to find relevant embeddable music videos. The App also uses the official YouTube embedded player to display and play the video selected by the user.

When YouTube Video mode or YouTube-assisted artwork matching is used, Dule may send a search query derived from the local track's title, artist, and corrected metadata to the YouTube Data API. The App may receive and display YouTube API Data such as:

- YouTube video ID;
- Video title;
- Channel title;
- Thumbnail URL; and
- Search-result and embeddability information.

Dule may save the selected video ID, title, channel title, and thumbnail URL on the device to reduce repeated searches. This locally stored YouTube API Data is deleted or refreshed within 30 calendar days. Users can remove it sooner with Clear YouTube matches in Settings, by clearing Dule's app storage, or by uninstalling the App.

Dule currently uses an API key and does not require users to sign in to a Google Account. It does not request OAuth authorization and does not access private YouTube account information, subscriptions, playlists, uploads, comments, likes, or Google profile data.

When the embedded YouTube player loads, basic device and request information may be sent to YouTube to render video information, determine availability and restrictions, and prevent fraud or abuse. YouTube or Google may directly store, access, or recognize cookies, device identifiers, local storage, or similar technologies on or from the device through the embedded web player. When video playback begins, YouTube may collect additional playback and interaction information. YouTube and Google process this information under their own policies.

Use of YouTube features is subject to:

- YouTube Terms of Service: https://www.youtube.com/t/terms
- Google Privacy Policy: https://policies.google.com/privacy
- YouTube API Services Terms of Service: https://developers.google.com/youtube/terms/api-services-terms-of-service
- Google Account permissions and connected-app controls: https://security.google.com/settings/security/permissions

By using YouTube features within Dule, users also agree to be bound by the YouTube Terms of Service.

Dule does not download YouTube videos, extract YouTube audio, remove YouTube advertising, cover or crop the YouTube player, hide official player links or controls, or provide hidden playback outside the visible embedded YouTube player.

6. OTHER ONLINE AND PLATFORM SERVICES

Depending on enabled features and service availability, Dule may communicate with:

- MusicBrainz, for music metadata and track matching;
- Cover Art Archive, for album artwork;
- LRCLIB, for synchronized or plain lyrics;
- Audius, for online music search and playback;
- Jamendo, for licensed online music search and playback;
- Audiomack, when configured, for online search, stream resolution, and play accounting; and
- YouTube and Google, for video search, thumbnails, embedded playback, and related services; and
- Radio Browser, for the public country and station directory, station availability information, station artwork, stream URLs, and anonymous station-click accounting.
- Google Play services, for Google Cast receiver discovery and control and the optional Dule Room QR-code scanner.
- Cloudflare Workers and Microsoft Azure Translator, for the Sinhala-related online lyric translations described in Section 1. Provider privacy information: https://www.cloudflare.com/privacypolicy/ and https://www.microsoft.com/en-us/privacy/privacystatement.
- Google MediaPipe Tasks, for on-device audio classification. MediaPipe processes the decoded audio sample on the device and does not send that input audio to Google. The SDK may send technical performance and utilization metrics to Google under Google's privacy terms.

Android Auto and paired Wear OS media controls are provided through Android's Media3 and system media-control framework. A compatible vehicle display, watch, phone, Google component, or device manufacturer may receive the current media metadata, artwork, queue, browse/search responses, and playback state needed to display and control Dule. Playback commands are returned to Dule through that framework. Dule does not operate a server for this integration and the developer does not receive vehicle identity, watch identity, route, driving information, health information, or commands used through these system surfaces. Android, Google, the vehicle system, watch, or device manufacturer may process diagnostic or interaction information under their own policies.

Queries sent to these services may include track title, artist, album, duration, user-entered search text, or the selected radio country and station identifier. Audiomack integration may use a randomly generated App-install session identifier for play accounting. It is not the phone's hardware identifier. Radio favorites and recent stations are stored locally. Local audio files are not uploaded to these services for ordinary metadata, artwork, lyric, radio, or video searches.

Each third-party service operates under its own terms and privacy policy. Dule does not control how those providers process information they receive directly through a user's network connection or platform service. Google describes the Code Scanner as on-device processing and states that it does not store scan results or image data; current details are available at https://developers.google.com/ml-kit/vision/barcode-scanning/code-scanner. Google Cast information is available at https://developers.google.com/cast/.

7. INFORMATION NOT COLLECTED BY THE DEVELOPER

The current version of Dule does not include a developer-operated user account system, developer analytics, cloud listening-history storage or a standalone developer advertising service. The embedded YouTube player may serve YouTube advertisements and other third-party content under Google's policies; this App is not a promise of ad-free YouTube playback. The developer does not receive the user's local audio files, playlists, listening history, on-device model results, or equalizer settings through a Dule server. Third-party SDK technical metrics described above are not received through a Dule server.

Dule does not sell or rent personal information. The Sinhala translation proxy processes the limited request data described in Section 1, and the developer receives support messages only when a user sends them.

8. DATA RETENTION AND DELETION

Most Dule data remains on the device until the user clears it, clears App storage, or uninstalls the App. Available deletion controls include:

- Clear Listening History;
- Reset Recommendations;
- Clear Downloaded Artwork;
- Clear Downloaded Lyrics;
- Clear YouTube Matches;
- Delete or edit playlists; and
- Android's Clear Storage and Uninstall controls.

Clearing App storage or uninstalling Dule removes locally stored settings, history, caches, network-server profiles and credentials, network-video resume positions, selected YouTube video matches, and analysis results. It does not delete original music or video files unless the user explicitly chooses a supported file-deletion action. It also does not undo a completed server Rename, Delete, or Move, and does not remove copies already exported to Downloads/Dule.

Tracks moved to Dule Trash are retained for 20 days. The App is designed to notify the user approximately three days before the retention period ends. Permanent deletion of shared media is completed only after any confirmation required by Android. Restoring a track removes it from Dule Trash.

If a ringtone or alarm-tone copy was created through Set As, that exported copy may remain in the system Ringtones or Alarms folder until the user removes it from device storage.

If you contact support, the developer receives the information in the email you send, such as your name, reply address, issue description and any diagnostics you choose to include. This information is used to answer the request and investigate the issue. Support messages remain in the support mailbox and email-provider systems until removed under the mailbox/provider retention settings. You may request deletion through the support address, subject to applicable legal retention obligations; provider backups and legally required records may have separate retention rules. Avoid including passwords, credentials, private media or unnecessary personal information in a report.

Because Dule does not maintain developer-controlled user accounts or cloud profiles, there is normally no personal Dule account data for the developer to delete. Privacy questions or deletion requests can be sent to the contact address below.

9. DATA SHARING

Dule shares only the limited query or request information needed to provide a user-selected online feature. Information may also be disclosed if required by applicable law, legal process, or a valid governmental request. The developer does not sell personal data or share it with data brokers.

When the user intentionally uses Dule Rooms, Google Cast, an SMB server, a radio station, or another online provider, the limited information described in this Policy is sent directly to the selected peer device, receiver, server, broadcaster, or provider as necessary to perform that action. This is functional data transfer initiated by the user, not a sale of personal information.

10. SECURITY

Dule uses Android application storage, Android Keystore-backed credential encryption, and HTTPS where supported by the relevant internet service. Network Library uses SMB2/SMB3 and does not support SMB1. SMB transport encryption is controlled by the server and network configuration and is not guaranteed for every connection. Dule Rooms currently use a direct, unencrypted local-network connection and should not be used on an untrusted or public network. No system can guarantee absolute security. Users should protect their device and NAS, use a trusted private network, enable appropriate server-side encryption and access controls, avoid sharing active Room addresses publicly, and install Dule only from a trusted source.

11. CHILDREN'S PRIVACY

Dule is a general-audience music application and is not directed to children under 13. The developer does not knowingly collect personal information from children through a Dule-operated server. YouTube content and embedded playback remain subject to YouTube and Google's policies and age-related controls.

12. INTERNATIONAL USE

Online service providers may process network requests in countries other than the user's country. Their handling of information is governed by their respective privacy policies and applicable law.

13. CHANGES TO THIS POLICY

This Privacy Policy may be updated when Dule's features, connected services, data practices, or legal requirements change. The effective date and last-updated date will be revised when changes are published. Material changes should be presented to users through the App, release notes, or the public project page as appropriate.

14. CURRENT PLAYBACK AND SUPPORT FEATURES

- Screen-off playback: Dule may use Android's foreground media-playback service and wake-lock behavior to keep an active track playing when the screen is off. This does not give the developer remote control of the device.
- Sound Lab, equalizer, Dule Immersive Audio, compressor, bass, treble, limiter, Auto Boost, comfort listening and related DSP meters process playback locally. Meter values and effect settings are not automatically uploaded to the developer; selected technical measurements may be included in a support email only as described below.
- Video mode uses a visible embedded YouTube player. Dule stores selected-video metadata and resume information locally to reduce repeated searches. Search requests may be subject to an App or provider quota. Cached metadata or ordinary audio cache must not be interpreted as an offline copy of a YouTube video.
- Bug reports are user-initiated. Selecting Report a bug opens the device's email composer addressed to dule.hqofficial@gmail.com with the name, reply email address, issue type and issue text entered by the user. If Include app diagnostics is enabled, the draft also contains the app/Android version, manufacturer/model, output type, source category, queue size, playback/DSP health, underrun/recovery counts and timing, background/performance-protection state, normalization/headroom/limiter information and redacted error text. The diagnostic builder excludes song names, media, file paths and addresses; users should still review the whole draft, including any text they typed, before sending. No report is sent until the user presses Send in their email app. Email providers process the message under their own policies.
- Offline screens only read the device's network state and show recovery controls. Tapping Network settings opens Android's system settings; Dule does not receive the user's Wi-Fi password.

15. CONTACT

Developer: D HANSAJA
Application: DulePlayer
Contact email: dule.hqofficial@gmail.com
Project page: https://github.com/duleenhansaja789/Dule-Player

For questions, complaints, or requests relating to this Privacy Policy or Dule's privacy practices, contact the developer using the email address above.

END OF PRIVACY POLICY
