DULE PRIVACY POLICY

Effective date: 17 July 2026
Last updated: 30 July 2026
App version covered: 0.1.1

Dule ("Dule," "the App," "we," "us," or "our") is an Android music and media player developed by D HANSAJA. This Privacy Policy explains what information the App accesses, how that information is used and stored, when information is sent to third-party services, and the choices available to users.

Dule was previously identified during development as "DSHOT Player" or "D Shot Player." Dule is the same Android API Client. This branding change does not change the App's package identifier (com.dshot.player), individual developer ownership, Google Cloud project, YouTube API use case, or data practices described in this Policy. The public project URL may continue to contain the former DSHOT-Player repository name.

By installing or using Dule, you acknowledge this Privacy Policy. If you do not agree with this policy, do not use the App's online features.

1. SUMMARY

Dule is primarily a local music player with optional internet and private-network media features. The App does not require a Dule account. Local music, playlists, favorites, playback history, equalizer settings, network-library profiles, video resume positions, preferences, and on-device audio-analysis results are stored locally on the user's device. Dule does not upload local audio or video files to the developer and does not sell personal information.

When a user chooses an online feature, limited song metadata or search text may be sent to the relevant third-party service to provide search results, artwork, lyrics, online audio, track identification, or a YouTube video. Those third parties receive normal network information, such as the user's IP address, according to their own privacy policies.

2. INFORMATION ACCESSED ON THE DEVICE

With the user's permission, Dule may access:

- Local audio files and, when a local-video feature is used, local video files and MediaStore records;
- Track title, artist, album, duration, bitrate, folder, date-added information, embedded artwork, and content URI;
- Playback position, queue, play counts, listening history, favorites, playlists, ratings or preferences created in the App;
- Timestamped Listening Memory events and locally calculated recommendation reasons and scores used by Transparent Intelligence;
- Equalizer, compressor, audio-enhancement, theme, animation, download, and other App settings;
- App-language and font preferences. Dule supports Unicode media text and may use the selected app locale or the device locale;
- Locally generated audio-analysis classifications and compact signatures;
- Mobile-network country, SIM country, or phone-region information used locally to suggest a radio country;
- Approximate location, only when the user chooses location-based radio-country detection. Coordinates are used temporarily to derive a country code and are not retained;
- Network connection status, including whether Wi-Fi is available, the device's current private IPv4 subnet used for optional SMB discovery, and responses from devices checked for SMB availability;
- Information required by Android to display media controls, playback notifications, widgets, Trash reminders, and ringtone or alarm-tone actions selected by the user;
- Media information and commands exposed through Android's system media framework for Android Auto and paired Wear OS controls, including track title, artist, album, artwork, duration, playback position, queue, browse/search results, and play, pause, seek, previous, and next actions;
- On-device diagnostics shown to the user, such as playback state, queue size, cache size, permission status, the most recent playback error and its time, and current device storage, memory, or processor-use estimates. Dule does not automatically send these diagnostics to the developer;
- SMB server profiles supplied or selected by the user, including display name, server address, port, share, folder, username and optional domain. If Remember Password is enabled, the SMB password is encrypted using a key held by Android Keystore. If it is disabled, the password is retained only for the current App process/session. SMB credentials are not included in Dule backup exports or Android cloud backup; and
- When Dule Rooms is explicitly used, the temporary room name and address, current track identifier, title, artist, playback position, duration, participant count, device model/name, protocol version, room chat messages, room queue, guest song requests and approval decisions, and—when LAN audio is needed—the bytes of an approved local audio file exchanged directly between room devices. While connected, each participant's Dule app reports the title and artist currently selected in Dule, whether it is playing or paused, and whether maker controls are allowed so the room maker can show live listening presence and the correct controls. The host can see each connected device's local IP address for identification and moderation. Guest IP addresses and listening presence are not intentionally redistributed to other guests. Personal seek position and equalizer state remain local.

Dule does not use the microphone for track identification. When enabled, audio intelligence analyzes short decoded samples from the music source already being played. This processing runs on the device. The audio sample itself is not sent to an AI server.

3. ANDROID PERMISSIONS

Dule may request the following permissions or system access:

- Music and audio access: used to scan, display, organize, and play local audio files;
- Notification access: used for playback controls and Trash-retention reminders;
- Internet and network-state access: used for optional online search, streaming, YouTube Video mode, artwork, lyrics, metadata services, SMB discovery, and direct communication with a user-selected computer, NAS, or SMB server on the local network;
- Local-network or Nearby Devices access: Android currently permits the App's target version to make local-network connections through Internet access. A future Android version or target-SDK update may require a separate runtime local-network permission. If required, Dule will explain and request it before SMB discovery or connection, and denial will disable Network Library without blocking ordinary local playback;
- Approximate location access: optional and requested in context only when needed or when the user chooses Improve in Live Radio. It is used once to identify the country and place local radio stations first. Dule does not request precise or background location, store coordinates, or prevent worldwide radio browsing when this permission is denied;
- Foreground media-playback access: used to continue playback and show media controls when the App is not in the foreground; and
- Android Auto and paired Wear OS media access: used through Android's system media framework so compatible vehicle displays and paired watches can browse or search the Dule library, show current media information, and control playback. These surfaces do not create a separate Dule account or give the developer the user's vehicle or watch data; and
- Modify system settings access: requested only when the user chooses to set a track or selected track segment as a phone ringtone or alarm tone.

When the user chooses Scan room QR, Dule opens the Google Play services Code Scanner interface. Dule does not request a permanent camera permission for this feature. The scanner returns the QR text to Dule; Dule accepts a valid Dule Room address and uses it to attempt the requested local-network connection. Users can always enter the room address manually instead.

Permissions can be denied or revoked through Android Settings. Some features will not work without their related permission.

4. LOCAL STORAGE AND PERSONALIZATION

The App may store the following information locally:

- App settings and audio-effect preferences;
- Favorites, playlists, queue information, play counts, listening history, snoozed recommendations, and playback-session information;
- Downloaded or cached lyrics and artwork;
- Track-identification results and on-device audio-analysis results;
- Selected YouTube video matches, including video ID, title, channel name, and thumbnail URL;
- The detected or selected radio country and the general detection source, such as mobile network, SIM, phone region, or approximate location. Geographic coordinates are not stored;
- Metadata for tracks placed in Dule Trash, including the date they entered Trash; and
- Network-video resume positions, playback speed, fit/fill preference, and selected media-track preferences used to restore the video player.

This information is used to operate the App, restore playback, personalize recommendations and Smart Shuffle, reduce repeated network requests, and improve track matching. Listening history can be disabled with Private Session or the Listening History setting. History, recommendations, downloaded artwork, and downloaded lyrics can be cleared using controls in the App.

Listening Memory and Transparent Intelligence operate locally. Listening Memory uses timestamped play events to build a private timeline. Transparent Intelligence uses local play counts, favorites, and artist affinity to display why a song was recommended and a visible recommendation score. The developer does not receive these records through a Dule server.

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

Dule may save the selected video match on the device to reduce repeated searches. Users can remove locally stored YouTube matches by clearing Dule's app storage or uninstalling the App.

Dule currently uses an API key and does not require users to sign in to a Google Account. It does not request OAuth authorization and does not access private YouTube account information, subscriptions, playlists, uploads, comments, likes, or Google profile data.

When the embedded YouTube player loads, basic device and request information may be sent to YouTube to render video information, determine availability and restrictions, and prevent fraud or abuse. When video playback begins, YouTube may collect additional playback and interaction information. YouTube and Google process this information under their own policies.

Use of YouTube features is subject to:

- YouTube Terms of Service: https://www.youtube.com/t/terms
- Google Privacy Policy: https://policies.google.com/privacy
- YouTube API Services Terms of Service: https://developers.google.com/youtube/terms/api-services-terms-of-service
- Google Account permissions and connected-app controls: https://security.google.com/settings/security/permissions

By using YouTube features within Dule, users also agree to be bound by the YouTube Terms of Service.

Dule does not download YouTube videos, extract YouTube audio, remove YouTube advertising, or provide hidden playback outside the visible embedded YouTube player.

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

Android Auto and paired Wear OS media controls are provided through Android's Media3 and system media-control framework. A compatible vehicle display, watch, phone, Google component, or device manufacturer may receive the current media metadata, artwork, queue, browse/search responses, and playback state needed to display and control Dule. Playback commands are returned to Dule through that framework. Dule does not operate a server for this integration and the developer does not receive vehicle identity, watch identity, route, driving information, health information, or commands used through these system surfaces. Android, Google, the vehicle system, watch, or device manufacturer may process diagnostic or interaction information under their own policies.

Queries sent to these services may include track title, artist, album, duration, user-entered search text, or the selected radio country and station identifier. Audiomack integration may use a randomly generated App-install session identifier for play accounting. It is not the phone's hardware identifier. Radio favorites and recent stations are stored locally. Local audio files are not uploaded to these services for ordinary metadata, artwork, lyric, radio, or video searches.

Each third-party service operates under its own terms and privacy policy. Dule does not control how those providers process information they receive directly through a user's network connection or platform service. Google describes the Code Scanner as on-device processing and states that it does not store scan results or image data; current details are available at https://developers.google.com/ml-kit/vision/barcode-scanning/code-scanner. Google Cast information is available at https://developers.google.com/cast/.

7. INFORMATION NOT COLLECTED BY THE DEVELOPER

The current version of Dule does not include a developer-operated user account system, developer analytics, cloud listening-history storage, or active advertising. The developer does not receive the user's local audio files, playlists, listening history, on-device model results, or equalizer settings through a Dule server.

Dule does not sell or rent personal information.

8. DATA RETENTION AND DELETION

Most Dule data remains on the device until the user clears it, clears App storage, or uninstalls the App. Available deletion controls include:

- Clear Listening History;
- Reset Recommendations;
- Clear Downloaded Artwork;
- Clear Downloaded Lyrics;
- Delete or edit playlists; and
- Android's Clear Storage and Uninstall controls.

Clearing App storage or uninstalling Dule removes locally stored settings, history, caches, network-server profiles and credentials, network-video resume positions, selected YouTube video matches, and analysis results. It does not delete original music or video files unless the user explicitly chooses a supported file-deletion action. It also does not undo a completed server Rename, Delete, or Move, and does not remove copies already exported to Downloads/Dule.

Tracks moved to Dule Trash are retained for 20 days. The App is designed to notify the user approximately three days before the retention period ends. Permanent deletion of shared media is completed only after any confirmation required by Android. Restoring a track removes it from Dule Trash.

If a ringtone or alarm-tone copy was created through Set As, that exported copy may remain in the system Ringtones or Alarms folder until the user removes it from device storage.

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

14. CONTACT

Developer: D HANSAJA
Application: Dule
Contact email: dulhaara25@gmail.com
Project page: https://github.com/duleenhansaja789/DSHOT-Player

For questions, complaints, or requests relating to this Privacy Policy or Dule's privacy practices, contact the developer using the email address above.

END OF PRIVACY POLICY
