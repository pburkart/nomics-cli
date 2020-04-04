# nomics-cli
A CLI to the nomics.com API

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
