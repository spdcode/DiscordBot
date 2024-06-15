<h1 align="center">
Discord Bot
<img src="https://img.shields.io/badge/Made_by-spd-green" />
<img src="https://shields.io/badge/Language-Javascript-yellow" />
<img src="https://img.shields.io/badge/platform-Windows-blue" />
</h1>

## What's this?
This project is the result of a high-school self-learning program where I dedicated two months to mastering JavaScript, HTML, and CSS. Originally it used to be a web project, my focus shifted to a pure JavaScript application due to challenges in front-end design `(I'm really bad at it)`. I've created several Discord bots before, but this is the first one where I've meticulously implemented all the functions, client-side interfaces, and optimizations. I hope you find it useful and well-crafted!

## TODO
1. Add more functions for future enhancements (**especially for my next business**).
2. Potentially use this as a base for WS Reborn's Discord bot (known as WS 2.0).
3. Better optimization.

## How does the COVID Searcher work and what's special about it?
The COVID Searcher was inspired by the way the Taiwan Government and news outlets display daily COVID-19 case numbers, often at the bottom of news broadcasts or on Instagram and Facebook posts. I wanted to replicate this functionality by creating a command that can fetch and display COVID-19 case data for any country, or globally.

So basically when you type the command, the Discord bot fetches the latest data from an API, formats the information into an embed message, and sends it to the Discord channel. This allows users to quickly and easily get up-to-date COVID-19 case information for any country with a single command.

**The command**
![image](https://i.imgur.com/GWRvCYh.png)

**Result**
![image](https://i.imgur.com/bw6QkUV.png)


## Dependencies
- [npm](https://docs.npmjs.com/cli/v10/commands/npm-install) - base
- [mongodb](https://www.mongodb.com/) - databases related
- [mongoose](https://mongoosejs.com/) - database connecting
