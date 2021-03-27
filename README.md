# blinkist-amazon-scraper
Takes the output from blinkist-scraper, gets the amazon reviews and outputs as html.  
The actual html output can be found here:  
https://github.com/johndoe-dev00/blinkist-books-sorted-by-amazon-reviews

## Requirements
* Linux + Docker  
or  
* Windows + WSL2 + Docker Desktop for Windows

## Instructions
1. Run blinkist-scraper and fetch all books
2. `git clone https://github.com/johndoe-dev00/blinkist-amazon-scraper.git` to your desired location
3. From blinkist-scraper copy `./dump/*.json` to the new blinkist-amazon-scraper `./dump` folder
