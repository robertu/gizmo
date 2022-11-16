# Environment builder based on invoke
## Requirements

OS: debian 11 bullseye, Python 3.11.1, Oracle 19c, cx-oracle 8.3.0

packages:

* python3-invoke
Install packages:
```
apt install -y python3-rich python3-invoke python3-apt python3-dotenv
```

## Building for the first time

Po uruchomieniu make, powinieneś po paru minutach mieć gotowe środowisko

```
make
```


## Rebuilding


```
make distclean all
```
