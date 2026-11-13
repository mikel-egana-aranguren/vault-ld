# My work notes

Set up python env and install libraries:

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
(.venv) $ pip install rdflib pyyaml
```

Export to RDF:

```bash
(.venv) $ python ../scripts/vault_to_rdf.py . --context ./context.jsonld --out-dir ./build
```


