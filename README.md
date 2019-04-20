# Simple Cloudflare Nodejs Dynamic Domain Name System

This is a nodejs script that consume the [http API](https://api.cloudflare.com/) from [cloudflare](https://www.cloudflare.com/) to update the value of  an  "_Existing Resource Record_ " of a cloudflare managed domain (aka zone) with your public ip address, polling it from [ipyfy](https://www.ipify.org) public service. 

## Requires

This script was developed and tested using:


## Install


Clone the repository .
```
git clone https://github.com/lemyskaman/namesilo_ddns_record_updater.git

cd namesilo_ddns_record_updater
```

Install all node modules.
```
npm install 
```


## Usage

If everything above is ok then just run the script.
```
npm start 
```
