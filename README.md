# feast-custom-stores-demo

This is an example repo which implements a custom online store for Feast, and then uses it in a feature repo.

## Installation

This installation guide assumes you have mysql.server running locally already. 
If not, please follow [this guide](https://flaviocopes.com/mysql-how-to-install/).

This guide assumes running all the commands from the root of this repo, once it's cloned locally.

- Create a virtualenv: 
```
virutalenv -p python3.7 env
. env/bin/activate
```
- Install the `feast-custom-stores-demo` package
```bash
pip install -u pip
pip install -e .
```
- Apply the feature repo:
```bash
cd feature_repo && feast apply
```

This should 