# kilonova-cli

CLI tool for [kilonova](https://kilonova.ro). Uses the public API, auto-detects language from file extension.

## Install

```
git clone https://github.com/dragosgatan/kilonova-cli.git
cd kilonova-cli
./install.sh
```

## Usage

```
kn login
kn submit <problem_id> <file>        # language detected from extension
kn submit <problem_id> <file> --lang cpp20
kn langs                             # list supported language IDs
kn stats                             # submission summary
kn history                           # per-problem breakdown
kn trends                            # bar chart of last 30 days
kn logout
```

## Example

```
$ kn submit 1 solve.go
```

```
submitted #1119030
score: 100
5 correct, 0 wrong  avg time: 0.003s  avg memory: 972 KB
```
