# Weather Display
Simple live weather display for a dedicated monitor. Intended to be run 24/7 on a low-spec computer, like a Raspberry Pi.

## Setup
1. Setup your computer. Ensure it has a desktop environment.
2. Install a web browser. This will render the weather display.
3. Setup a local web server and have it run on startup.
4. Clone this repository into the web server's public directory.
5. Go to [weatherwidget.io](https://weatherwidget.io/), set your location, set your labels, customize the widget however you'd like, select *GET CODE*, then *COPY TO CLIPBOARD*.
6. In `weatherdisplay.html`, replace whatever is in the `<body>...</body>` tags with the code you copied in (5).
7. Make sure everything displays properly on `localhost` in your browser of choice. Adjust the browser zoom for the weather display to fit your monitor. Take note of the URL.
8. Have the URL from (7) load in the browser of choice on startup, in fullscreen.
9. Reboot your computer and check that the weather display loads as expected.

## Credit
This display uses the weather widget from [weatherwidget.io](https://weatherwidget.io/).
