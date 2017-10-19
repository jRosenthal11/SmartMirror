**Version 1.0.0**

# SmartMirror
Raspberrry Pi powered smart mirror inspired by HackerHouseYT Smart Mirror project

Displays News, Google Calendar Feed, Current Weather, 5 Day Weather Forecast, Time, Location, and Date.

**TO-DO:** Format time for calendar widget and create fullscreen


# Installation and Updating

Download by pressing green button in repo or

If you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed you can clone the repo:
```
git clone git@github.com:PWRxPSYCHO/SmartMirror.git
```

# Install Your Dependencies
Install pip prior to this step

```
sudo pip install -r requiremtnts.txt
```

# Important: Add your API Token

Use your favorite text editor to add your API token

`sudo apt-get install vim` or `sudo apt-get install nano`. You can use `nano` or `vim` to edit the file

```
sudo nano Mirror.py
```
```
vim Mirror.py
```
Replace `weather_api_key` with your API Token from **[DarkSky](https://darksky.net/)**

# Running the Software

To run the application navigate to the project folder and run the following command

```
python Mirror.py
```
