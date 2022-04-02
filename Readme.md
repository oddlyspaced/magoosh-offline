# magoosh-offline

### What is this?
A python notebook which helps in facilitating the downloads of magoosh lessons so they can be kept for offline viewing.

### Why does this exist?
Internet in my college is trash, and buffering videos is more or less not an option for me. The best way to view content (atleast for me) is to download it first. However magoosh.com does not provide any proper way to download anything. This python notebook / program solves this problem (atleast for me) by programmatically finding lesson links and downloading them to your local storage.

### How does this work?
The notebook makes use of Selenium which is a browser automation framework. With Selenium and some simple loop logic it extracts video links from all lessons and then downloads them to your storage.

### What this script is not!
Do note that using this would still require you to have a magoosh subscription, or else you won't be able to access the lessons on their website!

## Requirements
- Python3
- Selenium
- Chromium

## Credits
[@oddlyspaced](https://github.com/oddlyspaced)