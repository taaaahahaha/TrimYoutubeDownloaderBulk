# Trim Bulk Youtube Videos

## Prerequisites

1. Git (To clone Repository)
2. Python
3. ImageMagik (Refer PS)

## Usage

- `git clone https://github.com/taaaahahaha/TrimYoutubeDownloaderBulk.git`

- `cd /TrimYoutubeDownloaderBulk/`



 ### To set-up and activate virtualenv
 

`pip install virtualenv`

`virtualenv env`

`env/Scripts/activate`


**** The Application will work even without virtualenv

- `pip install -r requirements.txt`
- `python app.py`
- Visit `'http://127.0.0.1:5000/'` or `'http://localhost:5000/'`


## PS

- PS : To run moviepy from scratch, after `pip install moviepy` / `pip install -r requirements.txt`, download ImageMagic externally and enable 'with utilities' option, else wont be able to perform Video Editing Options.


## Input/Output format.

- Input : Excel Sheets
- Output : .mp4 files (Individual) or refer `/static/Output` 
