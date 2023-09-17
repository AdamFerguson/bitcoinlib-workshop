
## Bitcoinlib Workshop

Working with [bitcoinlib](https://github.com/1200wd/bitcoinlib)

[Slides can be found here](https://docs.google.com/presentation/d/e/2PACX-1vTSKfzb92DMjGBiuHqGnfNuA3A8x0kcFiHPBGBW-RELY-Et9bTKEwNAcMwUAtKzsMQR-wpPFNxYK0rG/pub?start=false&loop=false&delayms=3000)

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

6. Copy `bitcoin-sample.conf` to `bitcoin.conf` and tweak the settings to connect to your own bitcoin node

```bash
cp bitcoin-sample.conf bitcoin.conf
```

7. Start up Jupyter

```bash
jupyter notebook
```

8. In the web browser, open bitcoinlib.ipynb and begin working!

