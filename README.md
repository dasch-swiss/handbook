# DaSCH Organizational Handbook

This is the DaSCH organizational handbook describing how we work.

You'll find this handbook on [handbook.dasch.swiss](https://handbook.dasch.swiss).

## Contribute

If you would like to contribute, please read the following information about file structure.

### File structure

1. **General**
1. **Client Services**
1. **Engineering** 

Images like screenshots and so on has to be stored in `assets/images`.

## Technicalities

The documentation is based on [MkDocs](https://www.mkdocs.org).

To run the documentation locally you'll need [Python](https://www.python.org/) installed, as well as the Python package manager, [pip](http://pip.readthedocs.io/en/stable/installing/). You can check if you have these already installed from the command line:

```shell
$ python --version
Python 2.7.2
$ pip --version
pip 1.5.2
```

MkDocs supports Python versions 2.7, 3.4, 3.5, 3.6, 3.7 and [pypy](https://pypy.org).

### Installing dependencies

Install the required packages by running

```shell
make install-requirements
```

### Getting started

MkDocs comes with a built-in dev-server that lets you preview your documentation as you work on it. Make sure you're in the same directory as the mkdocs.yml configuration file, and then start the server by running the following command:

```shell
$ make serve-docs
INFO    -  Building documentation...
INFO    -  Cleaning site directory
[I 160402 15:50:43 server:271] Serving on http://127.0.0.1:8000
[I 160402 15:50:43 handlers:58] Start watching changes
[I 160402 15:50:43 handlers:60] Start detecting changes
```

Open up http://127.0.0.1:8000/ in your browser, and you'll see the documentation start page being.

In case you need to clean the project directory, run:

```shell
make clean
```

To get some help about the `make` commands, run:

```shell
make help
```

### Building the documentation

To build the documentation just run

```shell
make build-docs
```

### Deploying github page

On each push into `main` branch, a Github action script will build and deploy the documentation on [docs.dasch.swiss](https://docs.dasch.swiss). Behind the scenes, MkDocs builds the documentation and use the [ghp-import](https://github.com/davisp/ghp-import) tool to commit them to the gh-pages branch and then push the gh-pages branch to GitHub. That's it!

Be aware that you have to review the built site before pushing it to `main` branch! Please create an own branch for any changes and review it before merging!