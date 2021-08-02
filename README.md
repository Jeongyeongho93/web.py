# web.py

import requests

url = "https://www.instagram.com/"
res = requests.get(url)
res.status_code

res.text

keyword="sllo"
url = f'https://www.instagram.com/explore/tags/sllo={keyword}'
res = requests.get(url)
res.status_code

res.text
