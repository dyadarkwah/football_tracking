# Metrica Sports Sample Data

## About the repo
In this repository you can find sample tracking and event data that exemplify the Elite data package we offer. The idea of this data is twofold: 
1. to allow potential clients to check out this data and get familiar with our formats and data quality. 
2. to provide some sample data to play around with to the broader football analytics community! 

## About the data
- At the moment there are two games in our standard CSV format, in the coming days we will add the same data in the standar FIFA format. 
- The data of these two games is anonymized, meaning there are no references to the names of players, teams or competitions.
- You'll see the data goes from 0 to 1 on each axis. The coordiante (0,0) is the top left, (1,1) is the bottom right, and (0.5,0.5) is the kick off point. 
- The dimensions of the field are the same for both games: 105x68 meters. 
- For the events, in the `documentation` folder you can find a pdf file with the definition and explanation of all our events types and subtypes. 
- Tracking and event data are synchronized.
- [UPDATE 2021-04-15] A new game has been added: Sample Game 3. This game is in the new format (EPTS FIFA format for the tracking and metadata and json for the events). We recommend using [kloppy](https://github.com/PySport/kloppy/) to read this data.

