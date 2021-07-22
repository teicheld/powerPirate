# The PowerPirate

let you download all torrents from thePirateBay.party linked with the searchterms of the list you provide as argument.

## process in detail

- it collectes magnetlinks.
- it generates a script called "start_downloading.sh".
- the script starts a predefined amount of torrents simultaneously, keeps track of the state but does not start new torrents if others are done. So if you have for example 1000 torrents to load and you set the option "--max-concurrent-downloads" to 100, then you have to start the script 10 times. Adjust the value corresponding to your Hardware.
