# Browser Support #
The WebSocket draft is still not finalised, only Chrome offers support out of the box. Luckily fallback solutions have been developped. See **Flash Fallback**.

## Chrome ##
Chrome is fully supported

## Opera and Firefox ##
Opera and Firefox have WebSockets disabled by default. When enabled it is compatible with phpws. Normally you would need a Flash fallback to support these browsers.

## Internet Explorer ##
Flash fallback needed. A native clientside implementation demo can be downloaded from HTML5Labs.

## Flash Fallback ##
Multiple fallback options exist. For example https://github.com/gimite/web-socket-js. Fallback scripts must support the Hixie #76 or the Hybi #12 draft to be compatible.