# MoSCoW

This todo list is a set of MoSCoW targets so I can maintain the scope of the project. I understand it's an ambitious project and sure it's probably going to get stuck at some point, but I think if I maintain persistence and work on it like it's a job, I think I'll be able to get it done.

Each target will probably have sub-targets so I can make each target bite-sizeable. If you see something that you might be able to help with, feel free to open an issue stating what you're doing, fork the project, and commit regularly to your fork, so I can see what you're up to so I don't double up your work!

## The Gist

<small>*The gist helps me keep an idea of what the product is, so I don't accidentally deviate the scope.*</small>

> Spinnr is a music library to download, manage, and sync songs and their metadata, but aimed specifically for DJ super users.

Spinnr stands out from the rest by being able to synchronise with Spotify (and other platforms).

Spinnr's main purpose is to interface with the exportable *Rekordbox XML Database*.

## Must Have

- [ ] Sync with spotify playlists
  - [ ] Local up to Spotify
  - [ ] Spotify down to local
- [x] Read and understand Rekordbox XML file to generate a Spinnr Library
  - [ ] Spinnr must also be able to save back to an XML
- [ ] Gather song metadata from cloud APIs (spotify, Tunebat, SongBPM, etc)
- [ ] Allow user-created playlists
- [ ] The ability to tag songs with elements, vibe, instruments, words, etc
- [ ] The ability to add multiple genres to a song
- [ ] Song suggestions for individual songs and for a playlist
  - [ ] This should use an intuitive graph-like feature where songs can be planned
- [ ] ...

## Should Have

- [ ] Generate a reproducable playlist from, to, and around a soung
- [ ] Allow playlists generated from expressions
  - [ ] Let the expressions be verbose, and text-transformable
  - What this means is that the expressions should be easily toggleable to/from a nice UI and a text field.
  - Does this mean I could be using a GraphQL-flavoured language?
- [ ] Simulate decks and a mixer to allow simple mixing
- [ ] Program state saving to allow for quick-start
- [ ] Auto-updating feature
- [ ] Settings should be saved to a location that is easily accessible
- [ ] ...

## Could Have

- [ ] Generate a reproducable playlist using songs as stop points (like a gradient - called a Gradient Playlist)
- [ ] A centralised database for song metadata.
  - [ ] This could be used as a cache
  - [ ] This database would also hold (hot)-cue points that are used by the Spinnr community
- [ ] A web-based dashboard for users to see the community (hot)-cue points, as well as the cached song metadata
- [ ] Automation on the simulated decks to allow for more complex mixing (ie, deck one will fade out in a certain way, allowing for two handed control of deck two)
- [ ] Midi control to allow for external mixers and decks to be programmed for Spinnr
- [ ] Modifiable, easy and intuitive key bindings
  - [ ] Key Bind profile saving
- [ ] Save to a USB that can be read by commercial decks
- [ ] ...

## Won't Have

- **No mobile application.** This product is designed to manage a library. Perhaps the web-based UI could have an adaptive design and be mobile friendly?