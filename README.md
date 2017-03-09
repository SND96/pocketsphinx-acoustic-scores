First step is to download the repository. Open a terminal and run the following commands

`$ git clone https://github.com/SND96/pocketsphinx-acoustic-scores`
`$ cd pocketsphinx-acoustic-scores`

# Dependencies
These dependencies are required for the application to run.
*Elixir.js
*Formidable.js

To install them run the following commands
Express
`$ npm init`
Hit Enter
`$ npm install express --save
$ npm install express`

Formidable
`$ npm i -S formidable`

# Running the application

First open a browser with web security disable
For Chrome run
`$ open -a Google\ Chrome --args --disable-web-security --user-data-dir`

Then use cd to navigate to the webapp folder of the repository and enter the following command
`$ node index.js`

Then in the opened browser window go to address localhost:8080

Select the "What's your name?" option in the drop down menu and press start to record your voide. Pressing stop ends the recording and outputs the acoustic scores.
NOTE: The acoustic scores for now are output in the terminal window itself.
