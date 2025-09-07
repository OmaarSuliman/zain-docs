---
{"publish":true,"title":"Load","description":"Command-line YouTube video & audio downloader","created":"2025-09-04T19:24:14.030+03:00","modified":"2025-09-07T23:04:37.674+03:00","tags":["python","cli","youtube","downloader","zainos"],"cssclasses":""}
---


# Load - YouTube Downloader

**License:** GPL-3.0 | **Author:** khomod | **Project:** ZainOS  
**GitHub:** [omar-Suleiman14/load](https://github.com/omar-Suleiman14/load)

![CLI Preview](https://i.postimg.cc/gcCT2qS2/Screenshot-2025-09-04-184544.png)

## Features
- Download YouTube videos (MP4: 1080p–360p)  
- Extract audio (MP3, WAV, FLAC)  
- Rich CLI with progress bars  
- Pre-built executables (Win/Mac/Linux)  
- No Python/FFmpeg needed  

## Installation

### Pre-built Binaries
[Download Latest Release](https://github.com/omar-Suleiman14/load/releases/latest)

**Windows**

```bash
.\load-windows.exe
````

**macOS**

```bash
chmod +x ./load-macos
./load-macos
```

**Linux**

```bash
chmod +x ./load-linux
./load-linux
```

### From Source

```bash
git clone https://github.com/omar-Suleiman14/load.git
cd load
python -m venv venv
source venv/bin/activate   # or .\venv\Scripts\activate on Win
pip install -r requirements.txt
python main_cli.py
```

## Usage

```bash
./load-linux         # executable
python main_cli.py   # from source
```

Steps:

1. Run program
    
2. Enter YouTube URL
    
3. Pick video/audio format
    
4. Track progress
    

## Development

```bash
git clone https://github.com/omar-Suleiman14/load.git
cd load
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Build executable:

```bash
pip install pyinstaller
pyinstaller --onefile --name load main_cli.py
```

## License

GPL-3.0 – free to use, modify, and distribute.

---

_Last updated: September 2025_

```

Would you like me to **keep a short API reference** (Downloader methods, formats, etc.) in this concise version, or remove all dev-level details entirely?
```