# eco-kg embeddings

This workspace contains Jupyter notebooks exploring creating node2vec embeddings for the eco-kg graph dataset.

# Quickstart

Create and activate a python virtualenv, then install the required packages into it using this command:

```
pip install -r requirements.txt
```

Once all the dependencies have been installed, you can run a Jupyter Lab server using this command:

```
./run_jupyter.sh
```

A browser should open displaying the Jupyter Lab UI, with the root directory set to `./notebooks`.

# Notebooks

There are currently two notebooks:
- **embiggen_ecokg:** an attempt to run ecokg locally, abandoned in favor of the Colab version
- **embiggen_ecokg_colab:** a successful attempt at creating the embeddings, run via Colab Pro