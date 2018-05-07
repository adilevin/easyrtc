
Demonstrates a server broadcasting its screen, enabling clients to connect via a web browser. Clients do not need to install anything.

Based on [EasyRTC](http://easyrtc.com) and [Muaz-Khan's Chrome extensions](https://github.com/muaz-khan/Chrome-Extensions)

# Instructions

### Server side

1. Clone the repo
1. Install the Chrome extension `\chrome-extension\desktopCapture-adi`
    
    - navigate to [chrome://extensions](chrome://extensions/) 
    - use "Load Unpacked"
1. Install and run the server
    - `npm install` in the repo root folder
    - `npm install` in the `\server_example` subfolder
    - `node server.js` in the `\server_example` subfolder
1. Start sharing the screen
    - Navigate to [http://localhost:8080/demos/adi_server.html](http://localhost:8080/demos/adi_server.html)
    - Hit `connect`
    - Select `share desktop`
1. Notice details for connecting clients
    - Connection code that was allocated by the server
    - Server IP address

### Client side

1. Open a modern web browser
1. Navigate to `<server ip address>:8080/demos/adi_client.html`
1. Hit `connect`
1. Select the connection code that was generated on the server

