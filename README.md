# TapeCue
A simple application to help arrange audio for cassette dubbing

## Tutorial
Open the folder and run TapeCue.exe.
The application is split into two lists, one for side A and the other for side B. Drag audio files into either of these areas to begin. Tracks can be arranged by dragging them around. The total duration of that side is displayed above each list. Tracks can be deleted.

Hit "Start A" or "Start B" to start each side respectively. If you click a track before hitting either button, playback will start from that track. Basic playback controls for previous / next track and a scrubbing bar are included.

The options tab contains some useful items. A gap between tracks can be set here. Also included is a tone generator which will add a new track containing that audio. The "Merge all tracks" button will combine tracks for each side for smooth, gapless playback of premixed tracks.

Track lists can be saved and loaded under the "file" menu at the top of the program. These are saved as CSV.

## Limitations
Gapless playback is currently a WIP feature. There will be a slight delay between tracks even if the delay is disabled. To get around this, a "merge all tracks" button was added. This will merge all tracks from the A and B lists into a single WAV file in your temp directory.
