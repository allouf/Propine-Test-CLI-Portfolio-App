Portfolio CLI
Command line interface written in Node.js to get portfolio value

Register an https://min-api.cryptocompare.com/

Usage
npm install

npm link
Commands
# Help & Commands
Portfolio -h

# Version
Portfolio -V

# API Key Commands
Portfolio key set
Portfolio key show
Portfolio key remove

# CSV File Management Commands
Portfolio file set
Portfolio file show

# portfolio get Commands
# portfolio get latest value per token
portfolio get value

# get for specific token (default: BTC)
portfolio get value --token=ETH

# get on specific date (default: "2021-12-01")
portfolio get value --date="2021-11-05"

# get for specific token on specific date
portfolio get value --token=ETH --date="2021-11-05"

# Currency (Default: USD)

Version
1.0.0
