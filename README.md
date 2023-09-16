
## Bitcoinlib Workshop

[bitcoinlib](https://github.com/1200wd/bitcoinlib)

### Getting Started

1. [Install Python 3 on your system](https://docs.python-guide.org/starting/installation/)

2. [Install virtualenv](https://virtualenv.pypa.io/en/latest/) to keep the workshop dependencies isolated from the rest of your system.

```bash
pip install virtualenv
```

3. Create a virtualenv

```bash
virtualenv .venv
```

4. Activate the virtualenv (Note: this will need to be done anytime you come back to this repo)

```bash
source .venv/bin/activate
```

5. Install dependencies

```bash
pip install -r requirements.txt
```

6. Start up Jupyter

```bash
jupyter notebook
```