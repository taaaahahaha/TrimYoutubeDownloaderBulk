# Trim Bulk Youtube Videos

## Prerequisites

1. Git (To clone Repository)
2. Python
3. ImageMagik (Refer PS)


## Process

The Web-Application is primarily focused on extracting and making subclips of Youtube Videos.

Excel file provided should contain atleast three columns, providing urls of videos to be downloaded, start and end time stamps of corresponding videos to be clipped.


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

Sample Input :


<img src="https://github.com/taaaahahaha/TrimYoutubeDownloaderBulk/blob/main/static/SampleImage.png"/>

- Input : Excel Sheets
- Output : .mp4 files (Individual) or refer `/static/Output` 
