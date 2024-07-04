# No place for beginners or sensitive hearts
## When sentiment is left to chance
### No place to be ending but somewhere to start
#### No need to ask, he's a smooth operator
##### Smooth operator
###### Smooth operator


![image](https://github.com/Exp-Communicate-Using-Markdown-Cohort-1/series-communicate-using-markdown-NicoJSuarez2/assets/174117595/03368287-1d0f-4b09-8a4e-d716ae9d10d2)
```
$ pip install youtube-search-python

```

```
from youtubesearchpython import VideosSearch

def buscar_video(titulo):
    videos_search = VideosSearch(titulo, limit=1)
    resultado = videos_search.result()
    if resultado['result']:
        video_url = resultado['result'][0]['link']
        return video_url
    else:
        return "No se encontró el video."

titulo = "Smooth Operator"
link = buscar_video(titulo)
print(f"Link del video: {link}")


```
- [x] Smooothhh 
- [x] Operator
- [ ] 🥁 🎺 🥁
