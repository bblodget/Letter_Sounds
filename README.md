# Letter Sounds

A simple, interactive web application for learning letter sounds. Press any letter key (A-Z) to hear its phonetic sound.

## Features

- Interactive letter display
- High-quality sound playback
- Text-to-speech fallback when sound files are unavailable
- Responsive design that works on all devices
- No external dependencies
- Works fully client-side (static hosting)

## Live Demo

Visit the [Letter Sounds site](https://bblodget.github.io/Letter_Sounds/) to try it out.

## Usage

1. Open the application in a web browser
2. Press any letter key (A-Z) to:
   - Display the letter
   - Play its phonetic sound
3. Press `Esc` to clear the display

## Sound Files

The application uses `.ogg` format sound files for each letter. See the [sounds/README.md](sounds/README.md) for details on adding or updating sound files.

## Technical Details

- Built with vanilla JavaScript (no frameworks)
- Uses the Web Audio API for sound playback
- Falls back to Speech Synthesis API when sound files are unavailable
- Responsive design using CSS Grid and modern viewport units
- Multiple font options for letter display:
  - Andika: A free and open font family designed for literacy and language learning, supporting Latin, Cyrillic, and Greek scripts. [Source](https://software.sil.org/andika/)
  - Lexend: A variable font designed to improve reading performance and reduce visual stress. [Source](https://www.lexend.com/)
  - Teachers: A variable font designed specifically for educational materials and literacy learning. [Source](https://fonts.google.com/specimen/Teachers)

All fonts are open source and licensed under the Open Font License (OFL).

## Browser Support

Works in all modern browsers that support:
- Web Audio API
- Speech Synthesis API (for TTS fallback)
- CSS Grid

## Development

1. Clone the repository
2. Add sound files to the `sounds/` directory (optional)
3. Open `index.html` in a browser to test locally

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. 