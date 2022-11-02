# Create a permanent python shinyapp

## Install

```python
pip install shinylive
```

## Create an app

```python
shiny create myapp
```

## Create distribution of app

```python
shinylive export myapp site
```

## Preview application

```python
python3 -m http.server --directory site 8008
```

## Deploy application to arweave

```python
arweave deploy-dir site --key-file wallet.json --timeout 9999999999
```


