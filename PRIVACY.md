# Training Room — privacy for invited testers

Updated 20 November 2026

Training Room is an experimental project from **JinJanMcFlan**. For app help, privacy questions, or access, correction and deletion requests, contact **jinjanmcflan@gmail.com**. Please do not send passwords, Discord tokens, identity documents or unrelated personal information.

## The short version

Discord sign-in connects your Training Room activity to your account. Some information stays on your device, and signed-in training history and library information are stored on the Training Room server. This is **not a local-only app**. Microphone logging and experimental game capture are optional. Sharing information with a party, coach or community makes it available beyond your own account.

This notice describes the invited-test features. Some planned features are unfinished; a Coming soon label does not mean a feature is already collecting information.

## Discord sign-in and optional permissions

Basic sign-in requests Discord's **identify** permission. The service receives your Discord profile and stores your user ID, username and display name to identify your Training Room account. Basic sign-in does not request your Discord password, email permission or access to your messages. Sign-in takes place through Discord's authorization page.

A browser session cookie keeps you signed in. The server stores a hashed session identifier and account identity. Sessions normally expire after approximately 30 days, and you can sign out sooner. Session expiry does not delete your training history.

Optional linked-profile lookup separately requests **connections** permission to suggest gaming profiles. An optional Discord Activity teammate picker, if enabled and used, separately requests **relationships.read** permission. These extra permissions are not required by basic sign-in. Review the permission screen before authorizing an optional feature.

## Training information

Saved information can include mechanics, attempts, hits and misses, left/right or unspecified side, session dates, notes, goals, routines, training-pack plans, clip links and display preferences. It is used to provide history, progress, practice and sharing features. Some goals and preferences are stored in your browser or desktop app; signed-in history and libraries also use server storage.

Deleting browser data or uninstalling the app does not erase server records. Revoking access in Discord prevents future authorized access but does not itself remove information already saved in Training Room.

## Microphone and experimental tracking

When you enable voice logging, the app requests on-device speech recognition. The current implementation does not switch to online recognition if local recognition is unavailable. Recognized words are interpreted as logging actions. Saved attempts can include their voice source, mechanic and timing; uncertain possible attempts can be retained for review. Training Room's saved history format does not store raw microphone recordings or full speech transcripts.

Experimental game capture starts when you choose **Start capture** in the Windows app and can be stopped there. It receives available events from a local game feed. The tracking page keeps its latest 60 sanitized status samples in memory, including event counts, clock/context and raw speed information. **Export diagnostics** saves a file you choose to share; the page's export omits player names and player IDs. Review any diagnostic file before sharing it. Capture does not automatically award mechanic successes. Setup can change a game configuration file you select after confirmation, saving a backup beside it first.

## Sharing and other people

Published clip-gallery entries include a display name, title, mechanic and Medal link. The gallery stores the link, not an uploaded video. Shared routines and combinations can contain your creator name and instructions. People with a shared link may be able to open or pass it on.

Party activity includes participant identity and game information. When you choose to contribute a party report, its summary is shared with the saved audience of party participants. Reports you export or send to a coach can be copied by their recipients. Do not include private information about someone else without permission. Removing information from Training Room cannot retrieve independent copies already held by other people.

## Service operation and third parties

The Training Room server processes signed-in activity and requests. Network connections expose technical information such as an IP address to the server and the infrastructure carrying the connection. The app uses connection information for access checks and rate limiting; its host monitor records aggregate service-health information, such as online counts and performance.

Discord handles authorization under its own policies. Download/update hosts process download requests. Opening linked services such as Medal or Rocket League Tracker sends you to those services, whose policies apply. If you email support, the information you send is handled through Gmail as well as by JinJanMcFlan. Send only what is needed for your request, and avoid posting private diagnostics in public channels.

## Retention and your choices

The invited-test service does not yet have a fixed automatic expiry for all account and training records. Some records remain until removed through available controls or handled through a support request. History removal, clip withdrawal and sign-out are different actions; none should be understood as a complete account-erasure button. Expired party rooms are cleaned up, but shared report or account records may exist separately.

Use **jinjanmcflan@gmail.com** to ask what information is held, correct it, or request deletion. Include your Training Room/Discord username and the request; do not send your Discord password or authorization token. Account ownership may need to be verified. Requests are reviewed through support; the complete manual account-deletion procedure is still under development and has not yet been verified end to end. There is no automatic account-erasure control. Any limits involving backups, legal retention or copies shared with others need to be explained when the request is reviewed; immediate erasure from every copy is not promised. This development status does not remove any rights you have under applicable law.

You can stop microphone use and capture, sign out, revoke Discord authorization, and choose whether to share content. Keep your own export of important training information. This is an early test service; neither uninterrupted availability nor absolute security is guaranteed. Material changes to these practices should be reflected in this notice before affected new features are enabled.
