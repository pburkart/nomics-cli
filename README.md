# nomics-cli
A simple CLI application for retrieving the price, volume, and % change of different cryptocurrencies. This project was done following [Brad Traversy](https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA)'s "[Node.js CLI for Cryptocurrency Prices](https://www.youtube.com/watch?v=-6OAHsde15E)" tutorial on YouTube. 
```Usage: nomics-cli [options] [command]

Options:
  -V, --version                     ouput the version number
  -h, --version                     display help for a command
  
Commands:
  key                               Manage API Key -- https://nomics.com
  check                             Check coin info
  help [command]                    display help for a command
  
Examples:
  nomics-cli check price            Returns the price of the top 3 cryptos
  nomics-cli check price --coin=XRP Returns the price of Ripple (XRP)
  nomics-cli key set                Prompts for the user's API key```
