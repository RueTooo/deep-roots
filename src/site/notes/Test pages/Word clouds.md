---
{"dg-publish":true,"permalink":"/test-pages/word-clouds/"}
---


Chartsview

```chartsview
type: WordCloud

data: "wordcount:Character Logs/"

options:
  wordField: "word"
  weightField: "count"
  colorField: "count"
  wordStyle:
    rotation: 30
```

```chartsview
type: WordCloud 
data: "wordcount:Entities/"

options:
  wordField: "word"
  weightField: "count"
  colorField: "count"
  wordStyle:
    rotation: 30
```


Tag, Word, 