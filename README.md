# dingtalk-ngrok

## Build info

Build from https://github.com/hauntek/python-ngrok

- python 3.8.10
- pyinstaller
- upx 3.96

## Usage

Site URL will be http://[SUBDOMAIN].vaiwan.com

### Windows

```
ngrok.exe [SUBDOMAIN] [PORT] [HOST]
```

### Linux

```
chmod +x ngrok
./ngrok [SUBDOMAIN] [PORT] [HOST]
```

### Notes

- The `[HOST]` cloud be `127.0.0.1` usually.
- `[SUBDOMAIN]` should set as long as better.
