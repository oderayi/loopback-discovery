# loopback-discovery
Simple model discovery for LoopBack.

## Usage: 
 - Ensure you have the appropriate connector installed.
  > e.g for Sql Server: `npm install loopback-connector-mssql`
 - Clone into the server folder of your LoopBack application:
     > `git clone https://github.com/oderayi/loopback-discovery.git`
 - Set up "exposed_db" in your datasources.jason file.
 - Run discovery:
    > `$ node ./server/loopback-discovery/discovery`
 - Your `models` folder should contain all your model files and your `model-config.json` file should also be updated.
