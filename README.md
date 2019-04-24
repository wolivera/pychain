# Simple Blockchain implementation in Python

This simple blockchain written in Python implements a simple version of the PoW algorithm and supports multi-node consensus conflicts using a largest-chain algorithm. Methods are accesible through the API. The following endpoints are available on each node that you decide to run.

  * `POST /nodes/register` to add a new node to the blockchain
  * `POST /transactions` to create a new transaction
  * `POST /mine` to mine a new block into the blockchain
  * `POST /consensus` to reach consensus on a node blockchain
  * `GET /chain` to get the full chain

## Installation

1. Python 3.6+
2. pipenv

```
$ pip install pipenv
```
3. Install requirements
```
$ pipenv install
```

4. Run the server:
  * `$ pipenv run python api.py`
  * `$ pipenv run python api.py -p 5001`
