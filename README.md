# omegle-geolocation
![CodeQL](https://github.com/daniieljc/omegle-geolocation/workflows/CodeQL/badge.svg)
### REQUIREMENTS

```sh
$ pip3 install maxminddb-geolite2
```

### HOW TO USE

If your network interface is ethernet

```python
cmd = r"C:\Program Files\Wireshark\tshark.exe -i ethernet"
```

You can list all your interfaces by running this in the cmd

```cmd
"C:\Program Files\Wireshark\tshark.exe" --list-interfaces
```

If your interface is in position 6 put

```python
cmd = r"C:\Program Files\Wireshark\tshark.exe -i 6"
```

### START IT

```sh
$ py App.py
```

### DEMONSTRATION

![Imagen de prueba](https://i.postimg.cc/sgWNXwmH/screenshot-75.png)

<font size="1"> based on https://github.com/crclayton/streamer-locator</font>
