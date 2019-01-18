H2-example
===

An example of HTTP/2 client and server implemented with hyper-h2. Initially, the client sends a POST request to the server and the server responses with the corresponding content. Meanwhile, the server uses SERVER PUSH to send a new response before receiving the request from the client.


Install
===
The code is tested on Python 3.6.5. Running on other versions may require some changes in the code.

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