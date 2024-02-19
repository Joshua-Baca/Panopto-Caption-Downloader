# Panopto Caption Downloader

The Panopto Caption Downloader userscript allows you to easily download captions from Panopto videos in a variety of languages. It provides a simple interface for selecting the caption language and optionally removing timestamps from the downloaded file. This script is compatible with most modern web browsers through the use of userscript manager extensions such as Greasemonkey, Tampermonkey, or Violentmonkey.

## Installation Instructions

To use the Panopto Caption Downloader, you will need to install a userscript manager extension for your browser. Follow the steps below based on the browser and extension you are using.

### 1. Install a Userscript Manager

#### For Firefox:

- **Greasemonkey**: Install from the [Firefox Add-ons page](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/).
- **Tampermonkey**: Install from the [Firefox Add-ons page](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/).
- **Violentmonkey**: Install from the [Firefox Add-ons page](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/).

#### For Chrome:

- **Tampermonkey**: Install from the [Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).
- **Violentmonkey**: Install from the [Chrome Web Store](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag).

#### For Opera:

- **Tampermonkey**: Install from the [Opera add-ons page](https://addons.opera.com/en/extensions/details/tampermonkey-beta/).
- **Violentmonkey**: Install from the [Chrome Web Store](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag). 

#### For Edge:

- **Tampermonkey**: Install from the [Edge add-ons page](https://microsoftedge.microsoft.com/addons/detail/tampermonkey-beta/fcmfnpggmnlmfebfghbfnillijihnkoh).
- **Violentmonkey**: Install from the [Edge add-ons page](https://microsoftedge.microsoft.com/addons/detail/violentmonkey/eeagobfjdenkkddmbclomhiblgggliao). 

### 2. Install the Panopto Caption Downloader Userscript

- Visit the script's page directly at [Greasy Fork - Panopto Caption Downloader](https://greasyfork.org/en/scripts/487743-panopto-caption-downloader)
- Click on the "Install this script" button.
- Your userscript manager will open a new tab or window showing the script. Confirm the installation when prompted.

or

- Search for the script's page on [Greasy Fork](https://greasyfork.org/).
- Search for "Panopto Caption Downloader".
- Click on the "Install this script" button.
- Your userscript manager will open a new tab or window showing the script. Confirm the installation when prompted.


## Usage Instructions

Once installed, navigate to any Panopto video page that matches the URL patterns specified in the script's metadata (e.g., `https://*.panopto.com/Panopto/Pages/Viewer.aspx?id=*`). The script automatically adds a "View Captions" button to the page.

1. **View Captions**: Click the "View Captions" button to open the caption download modal.
2. **Select Language**: Use the dropdown menu in the modal to select the desired caption language.
3. **Remove Timestamps** (optional): Check the box if you wish to download the captions without timestamps.
4. **Download**: Click the "Download Captions" button to download the captions in the selected language and format.

Note: The script currently has known issues with gathering captions from playlist videos, and this functionality is a work in progress.
