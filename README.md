# Mazen-Track

A lightweight Python OSINT and information-gathering CLI tool for IP lookups, phone number analysis, and username checks across social platforms.

```text
       __  ___                           ______                __
      /  |/  /___ _____  ___  ____      /_  __/________ ______/ /__
     / /|_/ / __ `/_  / / _ \/ __ \______/ / / ___/ __ `/ ___/ //_/
    / /  / / /_/ / / /_/  __/ / / /_____/ / / /  / /_/ / /__/ ,<
    /_/  /_/\__,_/ /___/\___/_/ /_/    /_/ /_/   \__,_/\___/_/|_|

                 [ + ]  C O D E   B Y  M A Z E N  [ + ]
```

## Features

- **`[ 1 ] IP Tracker`** — Retrieves geolocation, country/region info, coordinates with a Google Maps link, ISP/ASN/ORG details, and timezone data for a target IP address (powered by `ipwho.is`).
- **`[ 2 ] Show Your IP`** — Displays your current public IP address (via `api.ipify.org`).
- **`[ 3 ] Phone Number Tracker`** — Parses and validates a target phone number using `phonenumbers`, showing location, region code, timezone, carrier, number type, and formatted outputs (International, Mobile, E.164).
- **`[ 4 ] Username Tracker`** — Checks username availability across major platforms including Facebook, Twitter, Instagram, LinkedIn, GitHub, YouTube, TikTok, Twitch, Telegram, and more.

## Requirements

- Python 3
- Dependencies listed in [`requirements.txt`](requirements.txt):
  - `requests`
  - `phonenumbers`

## Installation

### Linux (Debian / Ubuntu)
```bash
sudo apt-get update
sudo apt-get install -y git python3 python3-pip
```

### Termux
```bash
pkg install -y git python
```

### Windows
Install [Python 3](https://www.python.org/downloads/) and [Git](https://git-scm.com/downloads), then run the usage commands below in PowerShell or Command Prompt.

## Usage

```bash
git clone https://github.com/<your-username>/Mazen-Track.git
cd Mazen-Track
pip install -r requirements.txt
python3 MA-TR.py
```

> On Windows, run `python MA-TR.py` instead of `python3 MA-TR.py`.

## Menu Preview

```text
[ 1 ] IP Tracker
[ 2 ] Show Your IP
[ 3 ] Phone Number Tracker
[ 4 ] Username Tracker
[ 0 ] Exit
```

## Author

- **mazen**

> **Disclaimer:** This tool is intended for educational purposes and authorized OSINT lookups only.
