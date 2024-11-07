Video Speed Controller Chrome Extension
This Chrome extension allows you to set custom playback speeds for videos on any website. With a simple and user-friendly interface, you can easily adjust video playback speed on platforms like YouTube or any other site with HTML5 video players.


Features
Custom Playback Speed: Set video playback speed from 0.1x to 5x.
Easy to Use: Simple input and apply button to quickly change the speed.
Supports All Sites: Works on any website with HTML5 videos, including YouTube, Vimeo, and more.
Installation
Clone this repository:
bash
Copy code
git clone https://github.com/your-username/video-speed-controller.git
Navigate to the project directory:
bash
Copy code
cd video-speed-controller
Install dependencies and build the project:
bash
Copy code
npm install
npm run build
Open Chrome and go to chrome://extensions/.
Enable Developer mode in the top right corner.
Click Load unpacked and select the build folder from this project.
The extension will now be added to your Chrome browser.

Usage
Open a website with a video (e.g., YouTube).
Click on the extension icon to open the Video Speed Controller.
Enter your desired playback speed (e.g., 1.5 for 1.5x speed).
Click Apply to set the speed for the video.
Files and Folders
public/manifest.json: The extension manifest file that provides metadata and configuration for Chrome.
public/background.js: Background script for handling installation and extension setup.
src/App.js: Main React component containing the UI for setting playback speed.
src/App.css: CSS file to style the React component.
Technologies Used
React: For the frontend UI.
JavaScript: To handle Chrome extension interactions.
HTML5: Works with HTML5 video elements on any website.
Customization
You can change the styling, default speed, or any other feature by editing the App.js and App.css files in the src folder. Build and reload the extension in Chrome after making any changes.
