# free-mp3-download-cli

python script for downloading full albums and tracks as mp3 or flac from http://free-mp3-download.net/

# features
* downloads full albums
* downloads individual tracks
* grabs cover art and metadata
* choose between mp3 or lossless (flac)
* uses selenium for manual captcha grabbing (firefox support soon)
* optional 2captcha for captcha solving

# how to use

1. `pip install -r requirements.txt`
2. Install [chromedriver](https://chromedriver.chromium.org/downloads) and set to PATH
3. `python main.py -a -s <search query> -o <output folder location>`

# options

```
  -h, --help            Show help message and exit
  -s SEARCH, --Search SEARCH
                        Search query
  -o OUTPUT, --Output OUTPUT
                        Download location
  -c CAPTCHA, --Captcha CAPTCHA
                        2Captcha Key
  -a                    Search for album
  -t                    Search for track
  -l                    Download lossless .flac (default is mp3)
```
