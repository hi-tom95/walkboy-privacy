# Walkboy Privacy Policy

*Last updated: 8 November 2026*

Walkboy is a location-based audio guide. When you walk into certain areas (currently Museumsinsel in Berlin), the app plays short audio stories about the places around you. This policy explains what data the app uses and why.

## Who is responsible

Tom Metelka
Schönhauser Allee 71a, 10437 Berlin
Email: tom@walkboy.app

## The short version

- No account, no name, no email, no contacts, no photos, no microphone.
- Your location is used to choose which story to play. It is **not stored**.
- We store anonymous usage events (for example "story finished") linked to a random ID that changes every time you open the app.
- No advertising, no tracking across apps, no selling of data.

## What we process and why

### 1. Location (while you use the app)
Walkboy asks for location access **"While Using the App"** only. While the app is active, including while it plays audio in your pocket with the screen locked, it sends your current position (latitude, longitude, direction of travel and speed) to our server every few seconds. The server uses this to work out which audio zone you are in and replies with the matching audio.

- These location messages are processed in memory and are **not saved** to our database.
- The app never asks for "Always" location access and does not track you when you are not using it.

### 2. Anonymous usage and diagnostic events
To find out which stories work and to fix playback problems, the app sends small events to our server, for example:

- entering or leaving a zone, finishing or skipping a story, and how long you listened;
- technical audio-playback diagnostics (what the audio player was doing, for example "loaded" or "finished"), used during the beta test to find playback bugs.

Each event contains a **random session ID** (generated fresh each time the app starts and not saved on your device), the event type, the zone/story name and a timestamp. It contains **no** location coordinates, name, device identifier or advertising ID. We cannot link sessions to each other or to you.

### 3. Audio downloads
Audio files are downloaded from our storage provider through temporary links and cached on your device so playback works without delay. You can delete the cache by uninstalling the app.

### 4. Technical connection data
Like any internet service, our hosting providers receive your IP address when the app connects. It is used only to deliver the connection and may appear briefly in their technical logs. We do not use it to identify you.

## Legal basis (GDPR)

We process this data to provide the service you request by opening the app (Art. 6(1)(b) GDPR) and, for anonymous usage/diagnostic events, based on our legitimate interest in running a reliable and improving service (Art. 6(1)(f) GDPR).

## Service providers

Data is processed on our behalf by:

- **Fly.io** (application server, Frankfurt region): receives location messages and usage events.
- **Neon** (database, Frankfurt region): stores the anonymous usage events.
- **Cloudflare R2** (audio file storage): delivers audio files.
- **Apple TestFlight** (beta distribution): if you join the beta, Apple shares crash reports and feedback you choose to send, under [Apple's privacy policy](https://www.apple.com/legal/privacy/).

Some of these providers are US companies. Where data may be transferred outside the EU, they rely on the EU Standard Contractual Clauses and/or the EU–US Data Privacy Framework.

## How long we keep data

- Location messages: not stored.
- Anonymous usage and diagnostic events: deleted no later than 12 months after collection, or when the beta test ends, whichever comes first.
- Audio cache: on your device until you uninstall the app.

## Your rights

You have the right to access, correct, delete or restrict processing of your data, to object to processing, and to data portability. Because we do not collect your name or a persistent identifier, we usually cannot link stored events to you. Contact us anyway and we will help where we can. You can also lodge a complaint with a data protection authority, for example the authority in your country of residence.

You can stop all processing at any time by revoking location access in iOS Settings or by uninstalling the app.

## Children

Walkboy is not directed at children under 16 and does not knowingly collect data from them.

## Changes

If this policy changes, we will update it on this page and change the date at the top.

## Contact

Questions? Email support@walkboy.app


