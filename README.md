# Working with parse_web

### Get IP address:

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.get_ip())

```


### Get ping :

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.ping())

```

**parameters :**
1. `mode`: The mod parameter can be equal to:
  min: Returns the lowest ping
  mid : Returns the average ping
  max: Returns the maximum ping.
2. `number` : 
is an integer, the higher this numerical parameter is, the more accurate the obtained ping is. But it takes a lot of time to get ping.

### Get links :

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.get_links())
```

### Get link of images :

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.get_images())
```

### Get link of videos :

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.get_videos())
```

### Get CSS code :

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.css_code())

```

**parameters :**
1. `link_or_code`: The mod parameter can be equal to:
  link: Returns a **list** of css links (default)
  code : It returns a **dictionary** of css codes whose key is the css link and its value is the css code.
 
