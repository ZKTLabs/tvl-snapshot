# ZKUSD - TVL by User

In this repo you will find the code responsible to get data from the on chain data and calculate the TVL by users.
The main scripts is generating a output as CSV and there is another one that can be used to generate the JSON file.

## How to execute this project?

Edit `src/index.ts` and change the `snapshotBlocks` to what you want to calculate the TVL.

```
npm install // install all packages
npm run watch //other terminal tab
npm run start // other terminal tab
```

Now you can see the outputData.csv file. That's it.