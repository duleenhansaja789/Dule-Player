DSHOT PLAYER PRIVACY POLICY

Effective date: 17 July 2026
Last updated: 22 July 2026

DSHOT Player ("DSHOT Player," "the App," "we," "us," or "our") is an Android music and media player developed by D HANSAJA. This Privacy Policy explains what information the App accesses, how that information is used and stored, when information is sent to third-party services, and the choices available to users.

By installing or using DSHOT Player, you acknowledge this Privacy Policy. If you do not agree with this policy, do not use the App's online features.

1. SUMMARY

DSHOT Player is primarily a local music player with optional internet and private-network media features. The App does not require a DSHOT account. Local music, playlists, favorites, playback history, equalizer settings, network-library profiles, video resume positions, preferences, and on-device audio-analysis results are stored locally on the user's device. DSHOT Player does not upload local audio or video files to the developer and does not sell personal information.

When a user chooses an online feature, limited song metadata or search text may be sent to the relevant third-party service to provide search results, artwork, lyrics, online audio, track identification, or a YouTube video. Those third parties receive normal network information, such as the user's IP address, according to their own privacy policies.

2. INFORMATION ACCESSED ON THE DEVICE

With the user's permission, DSHOT Player may access:

- Local audio files and, when a local-video feature is used, local video files and MediaStore records;
- Track title, artist, album, duration, bitrate, folder, date-added information, embedded artwork, and content URI;
- Playback position, queue, play counts, listening history, favorites, playlists, ratings or preferences created in the App;
- Equalizer, compressor, audio-enhancement, theme, animation, download, and other App settings;
- Locally generated audio-analysis classifications and compact signatures;
- Mobile-network country, SIM country, or phone-region information used locally to suggest a radio country;
- Approximate location, only when the user chooses location-based radio-country detection. Coordinates are used temporarily to derive a country code and are not retained;
- Network connection status, including whether Wi-Fi is available, the device's current private IPv4 subnet used for optional SMB discovery, and responses from devices checked for SMB availability; and
- Information required by Android to display media controls, playback notifications, widgets, Trash reminders, and ringtone or alarm-tone actions selected by the user; and
- SMB server profiles supplied or selected by the user, including display name, server address, port, share, folder, username and optional domain. If Remember Password is enabled, the SMB password is encrypted using a key held by Android Keystore. If it is disabled, the password is retained only for the current App process/session. SMB credentials are not included in DSHOT backup exports or Android cloud backup.

DSHOT Player does not use the microphone for track identification. When enabled, audio intelligence analyzes short decoded samples from the music source already being played. This processing runs on the device. The audio sample itself is not sent to an AI server.

3. ANDROID PERMISSIONS

DSHOT Player may request the following permissions or system access:

- Music and audio access: used to scan, display, organize, and play local audio files;
- Notification access: used for playback controls and Trash-retention reminders;
- Internet and network-state access: used for optional online search, streaming, YouTube Video mode, artwork, lyrics, metadata services, SMB discovery, and direct communication with a user-selected computer, NAS, or SMB server on the local network;
- Local-network or Nearby Devices access: Android currently permits the App's target version to make local-network connections through Internet access. A future Android version or target-SDK update may require a separate runtime local-network permission. If required, DSHOT Player will explain and request it before SMB discovery or connection, and denial will disable Network Library without blocking ordinary local playback;
- Approximate location access: optional and requested in context only when needed or when the user chooses Improve in Live Radio. It is used once to identify the country and place local radio stations first. DSHOT Player does not request precise or background location, store coordinates, or prevent worldwide radio browsing when this permission is denied;
- Foreground media-playback access: used to continue playback and show media controls when the App is not in the foreground; and
- Modify system settings access: requested only when the user chooses to set a track or selected track segment as a phone ringtone or alarm tone.

Permissions can be denied or revoked through Android Settings. Some features will not work without their related permission.

4. LOCAL STORAGE AND PERSONALIZATION

The App may store the following information locally:

- App settings and audio-effect preferences;
- Favorites, playlists, queue information, play counts, listening history, snoozed recommendations, and playback-session information;
- Downloaded or cached lyrics and artwork;
- Track-identification results and on-device audio-analysis results;
- Selected YouTube video matches, including video ID, title, channel name, and thumbnail URL; and
- The detected or selected radio country and the general detection source, such as mobile network, SIM, phone region, or approximate location. Geographic coordinates are not stored;
- Metadata for tracks placed in DSHOT Trash, including the date they entered Trash; and
- Network-video resume positions, playback speed, fit/fill preference, and selected media-track preferences used to restore the video player.

This information is used to operate the App, restore playback, personalize recommendations and Smart Shuffle, reduce repeated network requests, and improve track matching. Listening history can be disabled with Private Session or the Listening History setting. History, recommendations, downloaded artwork, and downloaded lyrics can be cleared using controls in the App.

When the user opens Add Network Server, DSHOT Player may scan only the device's current private Wi-Fi or Ethernet /24 subnet by attempting short TCP connections to SMB port 445. No username or password is sent during this discovery. Nearby devices, the router, firewall, or network administrator may observe or log those connection attempts. The scan is initiated in the Network Library setup flow and is not used for background location tracking.

After the user selects or enters an SMB server, DSHOT Player connects directly from the phone to that server. It receives share names, directory listings and file information, and reads selected audio, video and subtitle data for streaming and seeking. Video decoding, resume-position storage and subtitle rendering occur on the device. The developer does not receive the server address, credentials, directory listing, media, subtitles, or viewing history. The server or network administrator may keep ordinary authentication, connection and file-access logs under their own policies. Removing a saved server deletes its profile and encrypted password from the App.

SMB2/SMB3 authentication protects access to the selected share, but encryption of media while it travels across the local network depends on the SMB dialect and encryption settings supported and required by the server. Users should use a trusted private network, maintain the NAS or server securely, and enable SMB encryption on the server when appropriate.

Android may include selected App settings and personal-library preferences in an encrypted device backup or device-to-device transfer when the user has enabled Android backup. These backups are controlled by Android and the user's platform account, not by the DSHOT Player developer.

5. YOUTUBE API SERVICES AND EMBEDDED PLAYER

DSHOT Player uses YouTube API Services, including the YouTube Data API, to find relevant embeddable music videos. The App also uses the official YouTube embedded player to display and play the video selected by the user.

When YouTube Video mode or YouTube-assisted artwork matching is used, DSHOT Player may send a search query derived from the local track's title, artist, and corrected metadata to the YouTube Data API. The App may receive and display YouTube API Data such as:

- YouTube video ID;
- Video title;
- Channel title;
- Thumbnail URL; and
- Search-result and embeddability information.

DSHOT Player may save the selected video match on the device to reduce repeated searches. Users can remove locally stored YouTube matches by clearing DSHOT Player's app storage or uninstalling the App.

DSHOT Player currently uses an API key and does not require users to sign in to a Google Account. It does not request OAuth authorization and does not access private YouTube account information, subscriptions, playlists, uploads, comments, likes, or Google profile data.

When the embedded YouTube player loads, basic device and request information may be sent to YouTube to render video information, determine availability and restrictions, and prevent fraud or abuse. When video playback begins, YouTube may collect additional playback and interaction information. YouTube and Google process this information under their own policies.

Use of YouTube features is subject to:

- YouTube Terms of Service: https://www.youtube.com/t/terms
- Google Privacy Policy: https://policies.google.com/privacy
- YouTube API Services Terms of Service: https://developers.google.com/youtube/terms/api-services-terms-of-service

By using YouTube features within DSHOT Player, users also agree to be bound by the YouTube Terms of Service.

DSHOT Player does not download YouTube videos, extract YouTube audio, remove YouTube advertising, or provide hidden playback outside the visible embedded YouTube player.

6. OTHER ONLINE SERVICES

Depending on enabled features and service availability, DSHOT Player may communicate with:

- MusicBrainz, for music metadata and track matching;
- Cover Art Archive, for album artwork;
- LRCLIB, for synchronized or plain lyrics;
- Audius, for online music search and playback;
- Jamendo, for licensed online music search and playback;
- Audiomack, when configured, for online search, stream resolution, and play accounting; and
- YouTube and Google, for video search, thumbnails, embedded playback, and related services; and
- Radio Browser, for the public country and station directory, station availability information, station artwork, stream URLs, and anonymous station-click accounting.

Queries sent to these services may include track title, artist, album, duration, user-entered search text, or the selected radio country and station identifier. Audiomack integration may use a randomly generated App-install session identifier for play accounting. It is not the phone's hardware identifier. Radio favorites and recent stations are stored locally. Local audio files are not uploaded to these services for ordinary metadata, artwork, lyric, radio, or video searches.

Each third-party service operates under its own terms and privacy policy. DSHOT Player does not control how those providers process information they receive directly through a user's network connection.

7. INFORMATION NOT COLLECTED BY THE DEVELOPER

The current version of DSHOT Player does not include a developer-operated user account system, developer analytics, cloud listening-history storage, or active advertising. The developer does not receive the user's local audio files, playlists, listening history, on-device model results, or equalizer settings through a DSHOT Player server.

DSHOT Player does not sell or rent personal information.

8. DATA RETENTION AND DELETION

Most DSHOT Player data remains on the device until the user clears it, clears App storage, or uninstalls the App. Available deletion controls include:

- Clear Listening History;
- Reset Recommendations;
- Clear Downloaded Artwork;
- Clear Downloaded Lyrics;
- Delete or edit playlists; and
- Android's Clear Storage and Uninstall controls.

Clearing App storage or uninstalling DSHOT Player removes locally stored settings, history, caches, network-server profiles and credentials, network-video resume positions, selected YouTube video matches, and analysis results. It does not delete original music or video files unless the user explicitly chooses a supported file-deletion action.

Tracks moved to DSHOT Trash are retained for 20 days. The App is designed to notify the user approximately three days before the retention period ends. Permanent deletion of shared media is completed only after any confirmation required by Android. Restoring a track removes it from DSHOT Trash.

If a ringtone or alarm-tone copy was created through Set As, that exported copy may remain in the system Ringtones or Alarms folder until the user removes it from device storage.

Because DSHOT Player does not maintain developer-controlled user accounts or cloud profiles, there is normally no personal DSHOT account data for the developer to delete. Privacy questions or deletion requests can be sent to the contact address below.

9. DATA SHARING

DSHOT Player shares only the limited query or request information needed to provide a user-selected online feature. Information may also be disclosed if required by applicable law, legal process, or a valid governmental request. The developer does not sell personal data or share it with data brokers.

10. SECURITY

DSHOT Player uses Android application storage, Android Keystore-backed credential encryption, and HTTPS where supported by the relevant internet service. Network Library uses SMB2/SMB3 and does not support SMB1. SMB transport encryption is controlled by the server and network configuration and is not guaranteed for every connection. No system can guarantee absolute security. Users should protect their device and NAS, use a trusted private network, enable appropriate server-side encryption and access controls, and install DSHOT Player only from a trusted source.

11. CHILDREN'S PRIVACY

DSHOT Player is a general-audience music application and is not directed to children under 13. The developer does not knowingly collect personal information from children through a DSHOT Player-operated server. YouTube content and embedded playback remain subject to YouTube and Google's policies and age-related controls.

12. INTERNATIONAL USE

Online service providers may process network requests in countries other than the user's country. Their handling of information is governed by their respective privacy policies and applicable law.

13. CHANGES TO THIS POLICY

This Privacy Policy may be updated when DSHOT Player's features, connected services, data practices, or legal requirements change. The effective date and last-updated date will be revised when changes are published. Material changes should be presented to users through the App, release notes, or the public project page as appropriate.

14. CONTACT

Developer: D HANSAJA
Application: DSHOT Player
Contact email: dulhaara25@gmail.com

For questions, complaints, or requests relating to this Privacy Policy or DSHOT Player's privacy practices, contact the developer using the email address above.

END OF PRIVACY POLICY
