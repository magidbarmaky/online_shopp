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
  * link: Returns a **list** of css links (default)
  * code : It returns a **dictionary** of css codes whose key is the css link and its value is the css code.


 ### Get information :

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.information())

```
Returns a list of whois information as str


### social networks:

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.social())

```
It returns a dictionary whose key is the name of the social network and its value is the address of the social network

### get Textual content :

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.text())

```
Returns the text content as str


###  Technologies used  :

```python
import pars_web as pw

url = pw.set_url("https://python.org")


print(url.technology())

```
It returns the used technologies in the form of a dictionary.

### Find a word in url:

```python
import pars_web as pw

url = pw.set_url("https://python.org")

print(url.isit('python'))

```

**parameters :**
1. `word`:It is equal to the desired word, if the desired word exists in the url, it returns true and if it does not exist, it returns false.

