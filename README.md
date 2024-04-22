# Working with parse_web
## 1.The first step is to set the url

```python
import pars as pw

url = pw.set_url("https://python.org")

```
## 2.The second step is to use methods

### Get IP address:

```python
print(url.get_ip())

```


### Get ping site :

```python
print(url.ping()) # 109.55 

```
parameters :
1- mode: The mod parameter can be equal to:
min: Returns the lowest ping
mid : Returns the average ping
max: Returns the maximum ping.
2- number : 
