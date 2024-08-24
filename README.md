# Minigrep

## Install / Download
To use this you can either build it yourself using the command below. Or you can download the latest built package
```bash
cargo build --release
```

## Usage
To use the program run the command on the file generated/downloaded. This will do a search that is case sensitive on the file
```bash
./minigrep.exe SEARCH_TERM FILE_PATH
```

To run the program without case sensitivity you must set the environment variable `IGNORE_CASE` which can be done on windows like so
```bash
$Env:IGNORE_CASE=1; ./minigrep.exe SEARCH_TERM FILE_PATH
```

To run the program without case sensitivity on linux you can run the following:
```bash
IGNORE_CASE=1 ./minigrep.exe SEARCH_TERM FILE_PATH
```