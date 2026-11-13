# My local Vault-LD example

Set up python env and install libraries:

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
(.venv) $ pip install rdflib pyyaml
```

Copy default example to test RDF export:

```bash
(.venv) $ cp -r ../Vault-LD\ Example/* .
```

Export to RDF:

```bash
(.venv) $ python ../scripts/vault_to_rdf.py . --context ./context.jsonld --out-dir ./build
```


