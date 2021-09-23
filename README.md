# Language

Generate text using LSTM.

## About

Generate text using the Neural Network architecture LSTM.

## Built with

- [Python](https://www.python.org/)
- [PyTorch](https://pytorch.org/)

## Installation

Use the package manager APT to install the general dependencies.

```sh
apt install python3 python3-dev python3-pip python3-venv
```

Use the Python 3 CLI to create a virtual environment.

```sh
python3 -m venv venv
```

Activate the virtual estartnvironment.

```sh
source ./venv/bin/activate
```

Use the package manager [Pip](https://pypi.org/project/pip/) to install the dependencies.

```sh
pip3 install -r requirements.txt
```

## Usage

Start a Jupyter Lab server.

```sh
jupyter lab
```

Place your text in _data.raw_ and run the _generator.ipynb_ notebook.

The default text is the Blade Runner and Blade Runner 2049 transcript.

To change the LSTM settings go to the notebook section "training".

## Contributing

Pull requests are welcome. Please, consider the following.

1. Make sure you code have quality, a.k.a standards
2. Make sure your code is secure
3. Make sure your code has no performance issues
4. Make sure your code is documented, if necessary
5. Describe the changes that were done

> No issue or PR template required, but be informative

## License

[MIT](./LICENSE.md)
