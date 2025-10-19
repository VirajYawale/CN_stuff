# CN_stuff

### Accessing the file from the PC wirelessly with the help of ip address and server.
both the server should be connected by the same network

```bash
// for mac
ipconfig getifaddr en0
python3 -m http.server 6789 --bind 0.0.0.0 // for python local server

// for windows
ipconfig
python -m http.server 6789 --bind 0.0.0.0 // for python local server

```

idea for the application which can access the file wireless from the mac to the mobile. (Can also do with the windows)

