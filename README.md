# FXCM notebooks

Jupyter notebooks that trade on FXCM through `fxcmpy` and store prices in PostgreSQL (2021).

Secrets are read from the environment, never stored in the notebooks:

```
set FXCM_TOKEN=<your FXCM API token>
set PGPASSWORD=<your PostgreSQL password>
```

Outputs were cleared. `pip install fxcmpy pandas sqlalchemy psycopg2-binary`.
