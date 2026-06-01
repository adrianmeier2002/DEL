# DEL
Ziel dieses Repositories ist es, die Minichallenge im Modul Deep Learning zu lösen. Es soll ein Modell trainiert werden, das die Bilder des SVHN-Datensatzes klassifiziert. Es werden verschiedene Modelle und Hyperparameter ausprobiert, um die Performance zu verbessern. Alle Experimente und Ergebnisse werden in diesem Repository dokumentiert.

## Installation
Das Notebook wurde mit Python 3.12.6 erstellt. Um die benötigten Pakete zu installieren, kann man folgenden Befehl ausführen:
```bash
pip install -r requirements.txt
```

## Experimente
Die Experimente werden im Notebook `MC.ipynb` dokumentiert. Dort werden die verschiedenen Modelle und Hyperparameter beschrieben, sowie die Ergebnisse visualisiert.


## TensorBoard Logs
Alle Logs alle Experimente sind unter './runs/' gespeichert. In der TensorBoard-UI links kann man die Runs per Regex filtern. Bsp. 'experiment_1' um alle Runs von Experiment 1 zu sehen.