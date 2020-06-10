# SauceFinder Alt
*I didn't realise there actaully was an api *

This is a alternate version of Saucefinder that uses the api instead of scraping. Everything else remains the same


### TODO
- [x] Image preview
- [x] Display tags correctly
- [x] Balance GUI (partially done, more improvements in future)
- [x] data fetch on a seperate thread so the gui doesn't freeze if your internet sucks
- [x] general code improvements
- [x] full image previews maybe
- [x] downloading & saving?
- [x] probably some sort of input validation but anything wrong should just return 404
- [x] some sort of catch for connection timeout so it doesn't hang forever
- [x] add clicking support of the viewer
- [x] image downloading in backgrounds

### Installation
In case you are braindead:
1. `git clone https://github.com/zhang-chenfeng/SauceFinder-alt.git saucefinder`
2. `cd saucefinder_2 (activate your venv)`
3. `python -m pip install -r requirements.txt`
4. `python sauce_new.py`

### Usage

#### UI
UI Elements\
<img src="https://cdn.discordapp.com/attachments/496020212764901387/709842419306463242/main.png" width="600">

#### Viewer
Viewer supports navigation with mouse and/or arrow keys\
<img src="https://cdn.discordapp.com/attachments/496020212764901387/709833761130414171/viewer_2.png" width="400">

#### Settings
Choose between a scaled and fullsize view\
<img src="https://cdn.discordapp.com/attachments/496020212764901387/709528532195213442/setting.png" width="300">

#### Download
Save images to local\
<img src="https://cdn.discordapp.com/attachments/496020212764901387/709843641597821088/down.png" width="600">
