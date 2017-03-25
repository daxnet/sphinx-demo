# sphinx-demo
A demonstration project of sphinx and readthedocs.org.

This repo demonstrates the usage of the Sphinx with reStructuredText support, as well as the documentation building and integration with [readthedocs.org](https://readthedocs.org).

## Get Started
- Install Python
- Install Sphinx
	- `$ pip install sphinx sphinx-autobuild`
- Create a directory under project repo, e.g. `docs`
	- `$ cd /path/to/project/repo`
	- `$ mkdir docs`
- Run `sphinx-quickstart` to create the documentation project:
	- `$ cd docs`
	- `$ sphinx-quickstart`
	- Then answer the questions
	- To build the documentation assets, under the `docs` folder:
		- `$ make html`
		- Documentation will be placed under `docs/build/html` folder

## References
- [Get started with Read The Docs](https://docs.readthedocs.io/en/latest/getting_started.html)
- [Why you shouldn't use "Markdown" for documentation](http://ericholscher.com/blog/2016/mar/15/dont-use-markdown-for-technical-docs)
- [Sphinx - Python Documentation Generator](http://www.sphinx-doc.org/en/stable)

