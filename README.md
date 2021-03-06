# Chrome Extension
This project is a simple exercise to build a chrome extension to download videos from youtube.
# project-setup:

Run-server-locally:
1. you need to have `node-js` installed locally
2. Run `git clone` to clone the repository
3. `cd` into the repository
4. Run `npm install`, `yarn add`
5. Run the server by running `node index.js` into the terminal

Upload extension to chrome:
1. open `chrome://extensions` in the chrome browser
2. set developer mode on
3. click load unpacked and load the `src` directory of this repository
4. After doing so, pin the extensionn to appear in the bar of extensions
5. Open any youtube video and click on extension icon
6. fill up the required details and click `Download`
7. Video will be downloaded to `YoutubeDownloader` folder in default downloads directory
   
#Notes
* This is the first attempt of doing this, I will surely be updating it and improving
* I used a local server to help run the extension, and I have plans to change this
* If you have any suggestions/feedback feel free to contact me, I am very open to that
* This is just a learning project :) 
