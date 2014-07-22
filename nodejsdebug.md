If you want to use the chrome debugger with you nodejs it is pretty simple

open two command line windows

in one enter ```node-inspector --web-port=8585``` and go to the url it directs you to in chrome.

in the other run ```node yourproject.js -debug-brk``` while in your projects directory.

refresh the the chrome window and the file should be running in the chrome console.
