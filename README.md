# Twitching, an HLS Livestreaming App! 🎧 🔌
HLS Livestreaming Application (Twitch.tv Alternative) built using 🍃 Node.js, 🎥 Video.js, 🥾 Bootstrap and 👨‍🔧 Nginx.

## Project Demo

[2022-08-01 08-57-43.webm](https://user-images.githubusercontent.com/53611087/182185239-0969ff33-0c0e-4c3e-be34-2e73c0900697.webm)

## Installation

1. Clone the repository locally.
```
git clone https://github.com/rajatjc/StreamPulse.git
```
2. Importantly, you need to have an active server running (and a corresponding video file) in order to run this application. Alternatively, an existing server on the web can be used as well. A helpful list of free HLS m3u8 URLs can be found at [this link](https://ottverse.com/free-hls-m3u8-test-urls/).

To alter the .m3u8 file, please modify line 38 on `index.html` by changing the value of `src` to your server address.
```
<source src="https://cph-p2p-msl.akamaized.net/hls/live/2000341/test/master.m3u8" type="application/x-mpegURL">
```
3. To install the relevant dependencies:
```
npm install
```
4. To start application (in /client/)
```
npm start
```
5. Open http://localhost:3000 to view the app in your browser.

## Thank you for checking it out! :metal:&#127999;
