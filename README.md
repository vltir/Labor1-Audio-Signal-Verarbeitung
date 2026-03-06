# Python Umgebung

Je nach Präferenz verwende eine der folgenden Python Redistributables:

- https://docs.astral.sh/uv
- https://anaconda.org (entweder umfangreiche "Anaconda" oder minimale "Miniconda")
- https://python.org

# Python Abhängigkeiten

Die benötigten Abhängigkeiten sind in der Datei `requirements.txt` hinterlegt.
Um diese in einem Rutsch zu installieren, öffne die Python Shell und führe `pip install -r requirements.txt` aus.
Im Falle von "Python UV" führe stattdessen `uv pip install -r requirements.txt` aus.

# Jupyter Notebook

Die Übungsblätter sind im "Jupyter Notebook" Format mit Dateiendung `.ipynb` hinterlegt.
Um diese bearbeiten und ausführen zu können, muss die Jupyter Notebook Serverinstanz lokal gestartet werden.
Öffne hierfür die Python Shell und führe `jupyter notebook` aus.
Im Falle von "Python UV" führe stattdessen `uv run jupyter notebook` aus.

# Übungsblätter

Block 1a:

- Basics
- Oscillator

Block 1b:

- Beating
- Karaoke

Block 2:

- Doppler
- Vibrato
- Tremolo

Block 3:

- Aliasing
- Chameleon
- Shepard

Bonus:

- GC69T67
