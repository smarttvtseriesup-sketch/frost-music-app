# FROST

A privacy-first, ad-free React Native music experience.

> This repository currently uses openly hosted demo MP3 previews from the SoundHelix catalog. It is not a licensed commercial streaming service. Connect only legally authorized providers in production.

## Run

```bash
npm install
npx expo start
```

Press `a` for Android. A real Android build:

```bash
npx expo prebuild
npx expo run:android
```

## Environment

No API keys are required for the demo. Provider secrets belong on a backend and must never be shipped in this app.

## Features

- Five-tab navigation
- Demo music playback and background audio setup
- Search and library UI
- AI Mix controls
- Local listening preference storage
- Privacy and licensing information
- Frosted glass Android-first interface
