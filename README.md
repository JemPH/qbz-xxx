# qbz-xxx
Just Qobuz thing, nothing much.

## Features
* Download FLAC and MP3 files from Qobuz
* Remod Version of qobuz-dl, only for user_id and user_token.

## Installation
#### Termux

`pkg update && pkg upgrade`
`pkg install git python`
`pip install --upgrade pip`
`git clone https://github.com/JemPH/qbz-xxx.git`
`cd qbz-xxx`
`pip install -r requirements.txt`

Add Credentials `python qbzremake.py -r`

Download Track/Album/Playlist Link: `python qbzremake.py dl <URL> -q 27`
Download using Search: `python qbzremake.py lucky` or `python qbzremake.py fun`
#### Windows
1. Install Python.
2. Add Python to System Path
3. Open Terminal then type `pip install --upgrade pip`
4. Download the zipped file then extract
5. goto directory and execute the script. `pip install -r requirements.txt`
6. Then execute the script `python qbzremake.py -r` to add credentials
7. * Download Track/Album/Playlist Link: `python qbzremake.py dl <URL> -q 27`
   * Download using Search: `python qbzremake.py lucky` or `python qbzremake.py fun`
