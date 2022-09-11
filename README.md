# INCLUSION NUMERIQUE - SCHEMA (tests)

## Mini server for local development

A mini server is writen in the `server.py` to serve this folder's files, so we could test and develop locally while running [multi-site-app]()

To install the mini-server :

```sh
pip install --upgrade pip
python3 -m pip install --user virtualenv
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

or

```sh
sh setup.sh
source venv/bin/activate
```

To run the server on `http://localhost:8900`:

```sh
python server.py
```

or

```sh
sh run_server.sh
```

Files will be locally served on :

- `http://localhost:8900/content/<path:folder_path>/<string:filename>`
- `http://localhost:8900/statics/<path:folder_path>/<string:filename>`

---

## Crédits

| | logo | url |
| :-: | :-: | :-: |
| **coopérative numérique multi** | ![multi](./images/multi-logo.png) | https://multi.coop |
