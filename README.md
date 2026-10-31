# ITE183_Lab2_Websocket
  
   ## Laboratory Report
[Download the Lab 2 Report (PDF)](Lab2_Report__1_.pdf)

A WebSocket chat server built with the Bonezegei Scripting Language (v1.3.3).

## Features
- Serves static files from `public/`
- Custom 404 page for unknown routes
- WebSocket connection handling (connect, message, disconnect)
- Real-time broadcast of messages to all connected clients

## How to Run
1. Install Bonezegei v1.3.3 and verify with `bonezegei -v`
2. Run `bzg install`
3. Run `bzg run`
4. Open `http://localhost:8000` in multiple browser windows

## Project Structure
- `app.bzg` - HTTP and WebSocket server
- `package.json` - project configuration
- `public/index.html` - chat client
- `public/404.html` - custom 404 page
- `.gitattributes` - GitHub syntax highlighting for `.bzg` files
