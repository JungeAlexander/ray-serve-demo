# Ray Serve Demo

Follows [this official Ray tutorial](https://docs.ray.io/en/latest/serve/getting_started.html#getting-started)
([GitHub commit](https://github.com/ray-project/ray/blob/e39efeaf59633f92cf9f73d1b27aa9b431bb19e8/doc/source/serve/getting_started.md)).

## Minimal test

```console
poetry install --no-root

serve run serve_deployment:translator_app
python model_client.py  # Returns: Bonjour monde!

serve run graph:app
 python composed_client.py # Returns: c'était le meilleur des temps, c'était le pire des temps .
```

