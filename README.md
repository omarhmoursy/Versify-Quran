# Quran Align

A modern Quran application that helps users read, listen to, and memorize the Quran with synchronized verse highlighting and audio playback.

## Features

- Clean and responsive UI similar to Tarteel AI
- Verse-by-verse audio playback with highlighting
- Memorization mode with progressive verse revelation
- Support for custom recitations
- Audio processing and verse alignment
- Background audio playback
- Cross-platform support (iOS and Android)

## Technical Stack

- React Native with Expo
- TypeScript
- React Navigation
- React Native Track Player
- React Native Vector Icons
- React Native Slider

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- Expo CLI
- iOS Simulator (for iOS development)
- Android Studio (for Android development)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/quran-align.git
cd quran-align
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Run on iOS:
```bash
npm run ios
```

5. Run on Android:
```bash
npm run android
```

## Project Structure

```
src/
  ├── components/       # Reusable UI components
  ├── screens/         # Screen components
  ├── navigation/      # Navigation configuration
  ├── services/        # Business logic and API services
  ├── hooks/           # Custom React hooks
  ├── types/           # TypeScript type definitions
  └── assets/          # Static assets
```

## Audio Processing

The app uses the following process for audio alignment:

1. Upload a Quran recitation audio file
2. Process the audio using faster-whisper for transcription
3. Generate SRT file with timestamps
4. Align verses with the SRT timestamps
5. Split audio into individual verse files
6. Generate JSON file with verse alignments

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Tarteel AI for UI inspiration
- OpenAI's Whisper model for audio transcription
- The React Native community for their excellent tools and libraries # Versify-Quran
