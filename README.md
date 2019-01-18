H2-example
===

An example of HTTP/2 client and server with hyper-h2.


Install
===
The code is tested on Python 3.6.5. Running on over versions may require some changes in the code.

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

Start Server
===
```bash
python -m basic.server
```

Start Client
===
```bash
python -m basic.client
```