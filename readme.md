# WebRTC Video Call Demo

This repository contains a simple implementation of a cross-browser WebRTC video call.

## Features

- Allows users to make video calls in real-time.
- Cross-browser compatibility.
- Basic user interface with start and end call buttons.

## Getting Started

To run the demo, simply open the `index.html` file in a web browser that supports WebRTC.

## Code Explanation

### HTML

The HTML file (`index.html`) defines the basic structure of the page, including video elements and buttons.

### CSS

The CSS file (`styles.css`) sets the styling for the video elements.

### JavaScript

The JavaScript file (`script.js`) implements the WebRTC functionality.

#### Variables

- Declares variables for video elements, buttons, local stream, and remote stream.

#### Functions

- `startCall()`: Initiates a video call by getting the user's media stream and setting up a peer connection.
- `endCall()`: Terminates the video call by stopping streams and resetting video elements.

#### Event Listeners

- Attaches event listeners to buttons for starting and ending calls.

## How to Use

1. Open `index.html` in a supported web browser.
2. Click the "Start Call" button to initiate a video call.
3. Click the "End Call" button to terminate the call.

## Support

For any issues or questions, please [open an issue](link-to-issues) in this repository.

## License

This project is licensed under the [MIT License](link-to-license).
