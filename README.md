# ![privacy-redirect](assets/images/logo-small.png)

[![Donate](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/SimonBrazell/donate) [![Buy me a coffee](assets/images/buy-me-a-coffee.png)](https://www.buymeacoffee.com/SimonBrazell)

[![Firefox Add-on](assets/images/amo-badge.png)](https://addons.mozilla.org/en-US/firefox/addon/privacy-redirect/) [![Chrome Extension](assets/images/chrome-badge.png)](https://chrome.google.com/webstore/detail/privacy-redirect/pmcmeagblkinmogikoikkdjiligflglb)

A web extension that redirects Twitter, YouTube, Instagram & Google Maps requests to privacy friendly alternatives - [Nitter](https://github.com/zedeus/nitter), [Invidious](https://github.com/omarroth/invidious), [Bibliogram](https://github.com/cloudrac3r/bibliogram) & [OpenStreetMap](https://www.openstreetmap.org/).

Allows for setting custom [Nitter](https://github.com/zedeus/nitter/wiki/Instances), [Invidious](https://github.com/omarroth/invidious/wiki/Invidious-Instances), [Bibliogram](https://github.com/cloudrac3r/bibliogram/wiki/Instances) & [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Tile_servers) instances and toggling all redirects on & off.

## Build

1.  `npm install --global web-ext`
2.  `web-ext build --overwrite-dest`
3.  See `web-ext-artifacts/` for outputs.

## License

Code released under [the MIT license](LICENSE.txt).
