# quickbot

This is a chatbot for Pokemon Showdown developed by your mum (bad joke I know.)



## Installation
Quickbot requires [Node.js][2] version 4.0 or later and a command line (e.g. `Command Prompt` on Windows or `Terminal` on Mac OS/Linux) to run. Once you have compatible software, complete installation by following these steps:

1. Cloning/Downloading this repo

  You can do this through the [GitHub client][3] by clicking the "Save" button on the home page of the repository (which is to the left of the "Download ZIP" button), download a .zip file with the aforementioned button, or clone the repository with the following [Git][4] command:
  
  `git clone https://github.com/InactiveUser/quickbot.git`

  [2]: https://nodejs.org/
  [3]: https://desktop.github.com/
  [4]: https://git-scm.com/

2. Navigate to the root directory

  The remaining steps will take place in the root directory of your Quickbot files. Navigate there with the command:

  `cd DIRECTORY`
  
  Replace `DIRECTORY` with the filepath to your directory (e.g. `C:\Users\InactiveUser\Documents\GitHub\quickbot`). 

  On Windows, you can also do `cd %HOMEPATH%/Desktop/quickbot` if the file is on the Desktop.

3. Install dependencies

  Run the following command to install required dependencies:

  `npm install`


4. Set up the config file

  Copy and paste the `config-example.js` file, rename it to `config.js`, and open it in your text editor to enter your desired information. Alternatively, you could just do step 3 before this one.

From this point on, you can start the bot by running the following command:

  `node main.js [your PS! username]`

  Putting in your username will give you full admin privileges on the bot. Make sure not to misspell your name, or else that account will get the permissions, and you WILL have to delete the bot files for that server and start again.

 You can also give other users permissions to use the bot by using the `promote [user], [rank]` command.

 Congratualtions! You have successfully started running Quickbot!

## Development

  Issues and pull requests are welcomed! 

#### Credits

  * ([@InactiveUser][5]) - Lead developer
  * [Pokemon Showdown][1] - In-game data files  

  [5]: https://github.com/InactiveUser
  [1]: https://github.com/Zarel/Pokemon-Showdown
