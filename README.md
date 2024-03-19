### icesat-parquet

## Overview
A quick and dirty demonstration of generating geoparquet files for Icesat2 Atl08 data.

## Usage
The alt08_earthaccess notebook was created on the [VEDA Jupyterhub environment](https://nasa-impact.github.io/veda-docs/services/jupyterhub.html).  This environment uses a role which has direct access to the `nsidc-cumulus-prod-protected` bucket.

Using this notebook in another environment might require some changes to how files are opened via fsspec.
