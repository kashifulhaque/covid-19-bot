# A COVID-19 India Discord bot
> An unofficial Discord bot which uses the [COVID-19 India](https://www.covid19india.org/) API to fetch current Coronavirus stats in India!

### Want to add the bot to your server?
> Link will be updated here

• Use **!covid-19** to get Nation-wide COVID-19 stats or **!covid-19 states** to get7a list of states with their statecodes.
• You can also type **!covid-19 <statecode>** to get stats about that particular state. Example: **`!covid-19 DL`** will show current stats of New Delhi.
• You can also type **!covid-19 <statecode> district** to get district-wise stats of that particular state. Example: **`!covid-19 WB district`** will show current district-wise stats of West Bengal.

### How to get the source code

1. Make sure you have Node.js installed (version 12 or above). If you don't have Node.js installed, you can download it [here](https://nodejs.org/en/)
2. Run `git clone https://github.com/kashifulhaque/covid-19-bot.git` in a directory
3. `cd covid-19-bot`
4. Rename `dummy_config.json` to `config.json` and open it. Add the necessary keys. Save & close the file.
5. Run `npm install` in the directory.
6. To run the app, type `node index.js` in the console or you may use `nodemon`/`pm2`. Check their respective documentation on how to use 'em.

*If you're facing error, make sure you're Node.js v12 or higher.*