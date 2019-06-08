# ethereum-polling-app

> Polling app with ethereum.


## Step to install

Clone this repository, then run `npm install`.

```
 https://github.com/AjithAnil/ethereum-polling-app.git
```

## Starting The App

Steps to start app;

1) Start a local Ethereum network: `npm run network`
2) In a new terminal tab, migrate your contract to the local network: `npm run migrate`
3) Start the app: `npm start`

## Configuration
To configure the poll options, edit `./candidates.json`. To edit the poll question, just edit the paragraph in the render method of `./src/App.js`.

## Usage
Once the app is running, you can just vote. You can open multiple windows and vote, and use the "Refresh" link at the bottom of the results list to refresh the results that are coming in from other windows. To vote again, reload the page to reset the poll UI. To clear the poll results, stop and restart the local Ethereum network.

## Notes

* By default, votes are stored on an in-memory blockchain. This means if you stop and restart the `npm run network` command you will lose any stored votes.
