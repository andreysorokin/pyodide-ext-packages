# pyodide-ext-packages

This is a curated list of pyodide meta.yml files with patches.
The last version of Docker image of pyodide checked with the packages: pyodide/pyodide:0.20.0

Notes and README are generally available for all packages.

Packages that can be easily generated (w/o patches) via:
	
	python -m pyodide_build mkpkg <packagename>
	python -m pyodide_build buildpkg  /src/pyodide/packages/<packagename>/meta.yaml

are not listed in the repository.