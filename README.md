# NLP Course project #22

**NOTE** Running this all at once is likely to get your connection throttled from to and duckduckgo. Run the cells staggered to avoid this.

Requirements:

- Python3
- Venv

```shell
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

All code is available in `project.ipynb`. Datasets are found under _data_, see table below for details

| dataset             | filename                | description                                    |
| ------------------- | ----------------------- | ---------------------------------------------- |
| Synonyms            | synonyms.txt            | synonym pairs and their webjaccard similarity  |
| Antonyms            | antonyms.txt            | antonym pairs and their webjaccard similarity  |
| Hypernyms           | hypernyms.txt           | hypernym pairs and their webjaccard similarity |
| snippets\_[x][0..2] | snippets\_[x][0..2].txt | snippet pairs (a,b) and set from 0-2           |
