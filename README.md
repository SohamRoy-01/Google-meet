# Next.js Google Meet Integration with WebRTC

This project demonstrates how to integrate Google Meet-like video conferencing functionality into a Next.js application using WebRTC.

## Features

- **Video Conferencing**: Allow users to join video conferences with multiple participants.
- **Audio Conferencing**: Support audio-only mode for participants.
- **Real-time Communication**: Utilize WebRTC for real-time audio/video streaming between participants.
- **Dynamic Room Creation**: Dynamically create meeting rooms for participants to join.
- **Responsive UI**: Provide a responsive user interface suitable for different screen sizes.

## Technologies Used

- **Next.js**: A React framework for building server-side rendered applications.
- **WebRTC**: A real-time communication protocol for audio, video, and data streaming.
- **Simple Peer**: A WebRTC library for handling peer-to-peer connections.
- **PeerJS**: A peer-to-peer communication library built on top of WebRTC.
- **Socket.io**: A WebSocket library for real-time bidirectional event-based communication.
- **Lodash**: A utility library for JavaScript.
- **Tailwind CSS**: A utility-first CSS framework for building custom designs.

## Installation

1. Clone the repository:

```bash
   git clone https://github.com/SohamRoy-01/Google-meet.git
```
2. Install dependencies:

```bash
npm install
or
yarn
```
## Usage

1. Start the development server:

```bash
npm run dev
# or
yarn dev
```
2. Open your browser and navigate to http://localhost:3000.

3. Create a room or join any room by roomID".

## Configuration

Signaling Server: Configure the signaling server URL in socket.js to match your signaling server implementation.

## Acknowledgements

- [Simple Peer](https://github.com/feross/simple-peer)
- [PeerJS](https://peerjs.com/)
- [Socket.io](https://socket.io/)
- [Lodash](https://lodash.com/)
- [Tailwind CSS](https://tailwindcss.com/)


## Author

[Your Name](https://portfolio-self-sigma-93.vercel.app/)
