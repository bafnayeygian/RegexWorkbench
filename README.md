# RegexWorkbench

Test regular expressions against text corpora, report matches and capture groups, and benchmark repeated execution.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/RegexWorkbench.git
cd RegexWorkbench
python -m pip install .
```


A local CLI for quickly validating regex behavior before shipping it into production code.

```bash
regex-workbench "\bERROR\b" app.log
regex-workbench "(?P<id>\d+)" sample.txt --benchmark 1000
```


## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
