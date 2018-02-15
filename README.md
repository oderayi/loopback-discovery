# loopback-discovery
Simple model discovery for LoopBack.

## Usage: 
 - Clone into the server folder of your LoopBack application:
     > `git clone https://github.com/oderayi/loopback-discovery.git`
 - Set up "exposed_db" in your datasources.jason file.
 - Run discovery:
    > `$ node ./server/loopback-discovery/discovery`
 - Your "models" should contain all your model files and your model-config.json file should also be updated.
