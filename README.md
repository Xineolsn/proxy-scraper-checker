# proxy-scraper-checker

![Screenshot](https://i.imgur.com/XgiUPPa.png)

HTTP, SOCKS4, SOCKS5 proxies scraper and checker.

- Asynchronous.
- Uses regex to search for proxies (ip:port format) on a web page, which allows you to pull out proxies even from json without making any changes to the code.
- Supports determining the geolocation of the proxy exit node.
- Can determine if a proxy is anonymous.

## Usage

- Install [Python](https://python.org/downloads) (Windows 7 requires Python 3.8.X). During installation, be sure to check the box `Add Python to PATH`.
- Download and unpack [the archive with the program](https://github.com/monosans/proxy-scraper-checker/archive/refs/heads/main.zip).
- Install dependencies from `requirements.txt` (`cd` into the unpacked folder and run `python -m pip install -U -r requirements.txt` on the command line).
- Edit `config.ini` according to your preference.
- Run `main.py` (`python main.py` on the command line).
