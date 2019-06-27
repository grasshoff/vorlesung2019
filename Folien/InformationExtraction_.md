  
  
# Text Corpus {#text-corpus }
  
Text Sammlungen sind in Dataframes abgelegt, die als JSON gespeichert sind und direkt in einen Pandas Dataframe eingelesen werden.
  
~~~~{.python startFrom="100"}
dfExoplanetsAbs=pd.read_json("./data/dfExoplanetsNASAabsClear_v1.json",orient="table")
dfExoplanetsSent=pd.read_json("./data/dfE.json",orient="table")
~~~~
  
## Exoplanets {#exoplanets }
  
## Kepler's *Astronomia Nova* {#keplers-astronomia-nova }
  