# SinC Web Radio Player

Demo Link: [https://sincinteria.github.io/SinC-AI-WEB-Radio-Player/](https://sincinteria.github.io/SinC-AI-WEB-Radio-Player/)

A simple and elegant web-based radio player with a retro tuner interface. This application allows users to listen to various Polish radio stations through an intuitive tuning dial interface.

![Radio Player Interface](tuner.png)

## Features

- Retro-style tuner interface with rotating dial
- 20 pre-configured Polish radio stations
- Support for both MP3 and HLS streaming formats
- Real-time station switching with visual feedback
- Full audio controls
- Touch-screen compatible
- Responsive audio player display

## Technical Details

The player is built using pure HTML, CSS, and JavaScript, with the following features:

- Uses `hls.js` for HLS stream playback
- Supports both mouse and touch controls
- Implements smooth dial rotation with snap-to-station functionality
- Handles various audio streaming formats (MP3, AAC, M3U8)
- Error handling for failed streams

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/SinC-AI-WEB-Radio-Player.git
```

2. Ensure you have the required assets in your project directory:
   - `tuner.png` (background image)
   - `pokretlo.png` (dial image)
   - `play.png` (play button)
   - `stop.png` (play button in stop position)

3. Open `index.html` in a web browser

## Usage

1. The radio will automatically start playing the first station (Tok FM) when You press PLAY button
2. Rotate the tuning dial by clicking and dragging:
   - Clockwise to move up the station list
   - Counter-clockwise to move down the station list
3. The current station name will be displayed in the radio display
4. Use the audio controls to adjust volume

## Supported Stations

The player includes 20 Polish radio stations:
- Tok FM
- PR 24
- PR 4
- PR 3
- PR 2
- PR 1
- Rock Radio
- MeloRadio
- AntyRadio
- Eska Rock
- Eska Poznań
- Radio Nowy Świat
- ChilliZet
- VOX FM
- Italo 4 U
- RMF FM
- Radio 357
- Złote Przeboje
- RMF Maxxx
- Radio Zet

## Browser Compatibility

The application is compatible with modern web browsers that support:
- HTML5 Audio
- CSS3 Transforms
- JavaScript ES6
- HLS playback (via hls.js)

## Dependencies

- [hls.js](https://github.com/video-dev/hls.js/) - For HLS stream playback

## Technical Implementation

The radio player implements several key features:

1. **Rotation Handling**:
   - Uses mathematical calculations to determine dial position
   - Implements 18-degree steps for 20 stations
   - Smooth animation transitions between positions

2. **Audio Stream Management**:
   - Automatic stream type detection
   - Seamless switching between stations
   - Error handling for failed connections

3. **User Interface**:
   - Touch and mouse event handling
   - Visual feedback for current station
   - Responsive audio controls

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is distributed under the MIT License. See `LICENSE` file for more information.

## Acknowledgments

- Design inspired by classic radio tuners
- Built for Polish radio station streaming
- Uses modern web technologies for a retro interface

## Contact

SinCinteria - sinc@interia.pl
Project Link: https://github.com/sincinteria/SinC-AI-WEB-Radio-Player
