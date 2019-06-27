---
title: "Information Extraction BZML"

date: Juni 2019

author: "Gerd Graßhoff"

lang: de

output:
  pdf_document:
    toc: true
    highlight: tango
    fontsize: 11pt
    template: eisvogel.tex
    geometry: margin=1in

titlepage: true

markdown_extensions:
    - codehilite

---

# Text Corpus

Text Sammlungen sind in Dataframes abgelegt, die als JSON gespeichert sind und direkt in einen Pandas Dataframe eingelesen werden.

~~~~{.python startFrom="100"}
dfExoplanetsAbs=pd.read_json("./data/dfExoplanetsNASAabsClear_v1.json",orient="table")
dfExoplanetsSent=pd.read_json("./data/dfE.json",orient="table")
~~~~
In dem Dataframe *dfExoplanetsSent*  sind die einzelnen Sätze mit einer ID Nummer und auch der zugeordneten ID des Abstracts aufgenommen. In der Spalte *features*  werden die Merkmale aufgenommen, die für die weitergehende Klassifikation erforderlich sind.



## Information Extraction


## Exoplanets

## Kepler's *Astronomia Nova*
