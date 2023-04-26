# Random Quote Generator Chrome Extension

This repository contains the source code for a Chrome extension that generates a random quote using the quotable API.

## Getting Started

To get started with the extension, simply download or clone the repository to your local machine.

### Prerequisites

To run the extension, you will need to have the Google Chrome browser installed on your machine.

### Installing

1. Open Google Chrome and go to the [chrome://extensions/](chrome://extensions/) page.
2. Enable Developer Mode by clicking the toggle switch in the top right corner.
3. Click the "Load unpacked" button and select the directory where you downloaded or cloned the repository.

## Usage

Once the extension is installed, click on the icon in your Chrome toolbar to generate a random quote. The quote will be displayed in a popup along with a countdown to the next quote.

To customize the behavior of the extension, you can modify the code in the `popup.js` file. The `showNextQuote` function fetches a random quote from the quotable API and displays it in the popup. The `startCountdown` function initiates a countdown to the next quote and calls `showNextQuote` once the countdown is complete.

## Contributing

If you would like to contribute to the extension, feel free to fork the repository and submit a pull request. We welcome any suggestions or improvements!

## Demo

<img src="https://github.com/deepankarvarma/Random-Quotes-Generator-Chrome-Extension/blob/master/demo.png">
