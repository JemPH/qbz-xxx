# qbz-xxx
Just Qobuz thing, nothing much.

## Features
* Download FLAC and MP3 files from Qobuz
* Remod Version of qobuz-dl, only for user_id and user_token.

## Installation
#### Termux

`pkg update && pkg upgrade`<br>
`pkg install git python`<br>
`pip install --upgrade pip`<br>
`git clone https://github.com/JemPH/qbz-xxx.git`<br>
`cd qbz-xxx`<br>
`pip install -r requirements.txt`<br>


<u>For UserID and Token Option</u><br>
Add Credentials `python qbzremake.py -r`<br>

Download Track/Album/Playlist Link: `python qbzremake.py dl <URL> -q 27`<br>
Download using Search: `python qbzremake.py lucky` or `python qbzremake.py fun`<br>

<u>For Hashed Password Option</u><br>
Add Credentials `python qbzhash.py -r`<br>

Download Track/Album/Playlist Link: `python qbzhash.py dl <URL> -q 27`<br>
Download using Search: `python qbzhash.py lucky` or `python qbzhash.py fun`<br>

#### Windows
1. Install Python.
2. Add Python to System Path
3. Open Terminal then type `pip install --upgrade pip`
4. Download the zipped file then extract
5. goto directory and execute the script. `pip install -r requirements.txt`
6. Then execute the script `python qbzremake.py -r` to add credentials
7. * Download Track/Album/Playlist Link: `python qbzremake.py dl <URL> -q 27`
   * Download using Search: `python qbzremake.py lucky` or `python qbzremake.py fun`
