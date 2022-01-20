# Monero Python Miner

Monero POW mining in Python.

Utterly pointless for profit, but useful for testing / learning purposes.

## Why?

Good question! Simply there are so many people asking on
[monero.stackexchange.com](https://monero.stackexchange.com/search?q=python+miner).

## Usage

First clone or download the repository, then install the dependencies:

```
pip install py-cryptonight requests git+https://github.com/jtgrassie/pyrx
```

To run the pool miner, execute:

```
python3 stratum-miner.py
```
To exit, just hit `ctrl-c`.
  
# For Windows You Need CMake And C++ Tools  
CMake (30 - 50 MB) = https://cmake.org/download/  
C++ Tools (4 - 5 GB) = https://visualstudio.microsoft.com/visual-cpp-build-tools/  
