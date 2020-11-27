# Raddatenanalyse München

Jupyter Notebook zum Artikel: https://entwicklernotizen.de/blog/machine-learning-mit-radzaehldaten-in-muenchen/

## Entwicklungsumgebung

- `docker run -p 8888:8888 -v "$PWD":/home/jovyan/work --name jupyter-notebook jupyter/minimal-notebook` - Jupyter Notebook Container erstellen und starten
- image hat noch nicht pandas, matplotlib und fastai, pytorch (dauert am längesten) installiert. Muss man dann nochmal per Hand machen im Notebook. -> In Zukunft eigenes Images dass die dependencies schon installiert hat?
- `docker start -a jupyter-notebook` - bestehenden Container neustarten