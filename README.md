#### Установка раста -> https://www.rust-lang.org/learn/get-started
```sh
./alog.sh -h
```
```sh
Usage: alog [OPTIONS]

Options:
  -p, --paths <PATHS>              Путь к файлу или директории с логами
  -l, --pattern <PATTERN>          Регулярное выражение для фильтрации строк логов [default: ]
  -s, --system-info
  -j, --output-json <OUTPUT_JSON>
  -h, --help                       Print help
  -V, --version                    Print version
```
``` sh
./alog.sh -p ./log/daemon.log -l " " -j ./log/daemon.json
```
