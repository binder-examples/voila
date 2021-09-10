# Interactive dashboard from notebook with Voilà

| Voilà | JupyterLab |
| :-----------------------: | :---------------------: |
| [![voila-binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/binder-examples/voila/HEAD?urlpath=voila%2Frender%2Findex.ipynb)| [![jupyterlab-binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/binder-examples/voila/HEAD?urlpath=lab%2Ftree%2Findex.ipynb) |

This example demonstrates how to use [Voilà](https://github.com/voila-dashboards/voila) on Binder.

![screenshot](https://user-images.githubusercontent.com/591645/132238479-9af8dff6-ea12-465f-bb7c-2570defcdd26.png)

## Configuration

If you would like to use the same configuration as this repository but for another project, check out the following steps:

1. Make sure the repository is publicly available (on GitHub, Gitlab or as a [GitHub Gist](https://gist.github.com)
2. Define the dependencies in [`environment.yml`](./environment.yml). `requirements.txt` is also supported. In the dependency file, add `voila`.
3. Go to [mybinder.org](https://mybinder.org) and enter the URL of the repository.
4. In `Path to a notebook file`, select `URL` and use the Voilà endpoint: `voila/render/path/to/notebook.ipynb`
5. Click `Launch`.
6. Binder will trigger a new build if this is the first launch (or if there have been new changes since
   the last build). This might take a few minutes to complete. If an image is already available,
   the server will be able to start within a few seconds.

Here is an overview of the Binder configuration on [mybinder.org](https://mybinder.org):

![image](https://user-images.githubusercontent.com/591645/132292481-01f877c3-77f8-46ba-b265-23bd3e25f513.png)

For more details, check out the Voilà documentation on https://voila.readthedocs.io/en/latest/deploy.html#deployment-on-binder

## JupyterLab Preview Extension for Voilà

The JupyterLab Preview Extension for Voilà should normally be automatically available, since Binder now defaults to JupyterLab 3.0.

For consistency, you can add `jupyterlab=3` as a dependency in `environment.yml`.

![lab-preview](https://user-images.githubusercontent.com/591645/132293167-88c22f5a-e9a7-4e26-badb-09e094d2191e.png)
