# BPF
Scripts for BPF-based troubleshooting

## Requirements
* python-bcc

## How to install requirements

* Ubuntu:

```
echo "deb [trusted=yes] https://repo.iovisor.org/apt/xenial xenial-nightly main" | sudo tee /etc/apt/sources.list.d/iovisor.list
sudo apt-get update
sudo apt-get install bcc-tools
```

## Usefull links

* https://github.com/iovisor/bcc/

## Scripts
* scripts/[ipt_do_table](scripts/ipt_do_table) - trace `ipt_do_table()` kernel function, prints some function args and result.
