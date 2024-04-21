

This is just a Monero (XMR) miner


## Getting Started


 clone repo

 `cd go-nym`
 
 
 To build the miner, run:

> go build -o nym 

This will create an executable file named monero-miner. To start mining, simply run:

> ./nym --address --pool 

Replace YOUR_MONERO_ADDRESS with your actual Monero address, and MINING_POOL_URL with the URL of the mining pool you wish to join. For example:

> ./nym --address 4AkjdfLKsjdflksdjf3290u4wEHUWnfdslknASDFLKJ --pool strat

## Configuration

You can also specify the following options when starting the miner:

    --address: Your Monero wallet address. Required.
    --pool: The URL of the mining pool. Required.
    --threads: Number of CPU threads to use for mining. Default is all available cores.
    --difficulty: Difficulty level for mining. Default is 500 KH/s.
    --logfile: Path to log file. Default is no logging.
