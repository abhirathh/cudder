# Official Cudder API documentation

Cudder is an easy to use decentralized key-value datastore. By installing our Python SDK, you can store data on a decentralized network from the program itself.

- Author: [Abhirath Dubey](https://www.linkedin.com/in/abhirath-dubey-8756831a5/)
- Contact: [email](mailto:unruly.abhirath@gmail.com)
- Cudder API is free for everyone, as of now.

### Installation
```
pip install pydappdb
```
### Initialization
Create your API key [here](http://192.168.1.6:6969/).

```
from pydappdb import DappDb

cudder_username = 'abc'
cudder_api_key = '123'

dappinit = DappDb(cudder_username, cudder_api_key)
```
### Set Data

```
dappsetdata = dappinit.dappset('foo_key', 'foo_value')
```

### Get Data

```
dappgetdata = dappinit.dappget()
```
