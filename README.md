# QtB3Poker

This is a public implementation of a poker client and server, in pyQt5, playing Bordeaux3 poker variant

## Dependencies

### Client

The only requirements are from pip packages listed under client-requirements.txt and can be installed using `pip install -r client-requirements.txt`

#### Building windows client executable

```
pip install pyinstaller
python -m PyInstaller -F client.py
```

Resulting exe is under `./dest`.

### Server

The server uses the python3 port of the deuces library. https://github.com/arthur-hav/deuces

You will also need a local running instance of MongoDB.

Other requirements are listed in server-requirements.txt and can be installed 
using `pip install -r server-requirements.txt`

Running under supervisor is advised.

