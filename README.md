# PathSense-Collector-Releases

Public releases for PathSense collector embedded software. This is designed to be installed on PathSense devices only. Other debian-based devices may work but are not officially supported and will require building from source.

## Installation

Run the following command anywhere to download:
```sh
curl https://raw.githubusercontent.com/CBILITY-PathSense/PathSense-Collector-Releases/refs/heads/main/download.sh | sh
```

Then install with the install script:
```sh
cd pathsense-collector-release
./install-legacy.sh # for legacy rc.local installation
```

## Uninstallation

 Run the remove script:
```sh
cd pathsense-collector-release
./remove-legacy.sh # for legacy rc.local installation
```
