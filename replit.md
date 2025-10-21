# Toki Pona 비공식 사전

# request 요청사항
리플릿아 사이트 안에서 단어를 추가할수 있게 해줘.

## Overview
This is an unofficial dictionary project for Toki Pona words created by Sonya. The project displays information about Toki Pona, a minimalist constructed language created by Canadian linguist Sonja Lang in 2001.

## Project Structure
- `index.html` - Main web page displaying the Toki Pona dictionary information
- `server.js` - Node.js HTTP server serving the static content
- `README.md` - Original project documentation (in Korean)

## Technical Setup
- **Language**: Node.js 20
- **Server**: Simple HTTP server on port 5000
- **Host**: 0.0.0.0 (to work with Replit's proxy)
- **Deployment**: Configured for autoscale deployment

## Running the Project
The server automatically starts on port 5000 and serves the static HTML page. No additional dependencies are required.

## Features
- Clean, modern web interface
- Responsive design
- Information about Toki Pona language
- Cache-control headers to ensure fresh content delivery

## Deployment
The project is configured for autoscale deployment using Replit's deployment system. The server runs `node server.js` in production.
