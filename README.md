# monero-powpy

Monero POW mining in Python.

Utterly pointless for profit, but useful for testing / learning purposes.

## Why?

Good question! Simply there are so many people asking on
[monero.stackexchange.com](https://monero.stackexchange.com/search?q=python+miner).

## Usage

First clone or download the repository, then install the dependencies:

```
pip install --user -r requirements.txt
```

To run the pool miner, execute:

```
python stratum-miner.py
```

To solo mine a single block, execute:

```
python solo-block.py
```

To exit, just hit `ctrl-c`.

Both miners have some simple, self-explanatory, configuration variables at the
top of each file. I have chosen sane defaults so the scripts can run as-is,
without the *requirement* to change them, but you may want to change things like
the wallet address (for checking payouts), or the pool / daemon RPC being used.

## License

Please see the [LICENSE](./LICENSE) file.

[//]: # ( vim: set tw=80: )
