# ventilator-pressure-prediction

Projektarbeit an der Hochschule Karlsruhe zum Thema Maschinelles Lernen. Baut auf einer Kaggle-Challenge von Google Brain namens [Ventilator Pressure Prediction](https://www.kaggle.com/c/ventilator-pressure-prediction/) auf. Sie beschäftigt sich mit der Frage, wie Methoden des Machine Learnings Ärzt*innen bei der künstlichen Beatmung von Patient*innen in Zukunft unterstützen können. Hierzu wurden Zeitreihen von einer künstlichen Lunge an einem Open-Source-Beatmungsgerät aufgenommen.

In dieser Projektarbeit wird anhand von einer Reihe von Atemzügen der Druck, welcher beim Einatmen an der Lunge anliegt, mit verschiedenen Methoden (lineare Regression mit sklearn, lineares Modell mit PyTorch, LSTM-Netzwerk mit PyTorch) vorhergesagt und diese miteinander verglichen. 

## Inhalt und Ausführung

Ein Überblick über die Daten der Challenge sowie die Umsetzung der linearen Regression bzw. des linearen Modells befindet sich in der Datei [Ventilator Pressure Prediction.ipynb](./Ventilator%20Pressure%20Prediction.ipynb). 

Die Umsetzung des LSTM-Modells befindet sich in der Datei [LSTM-trained.ipynb](./LSTM-trained.ipynb).

Beide Notebooks können mit [Jupyter](https://jupyter.org) ausgeführt werden. Die [Daten der Kaggle-Challenge](https://www.kaggle.com/c/ventilator-pressure-prediction/data) müssen sich hierfür in einem Ordner namens `ventilator-pressure-prediction-data` auf der gleichen Ebene wie der Wurzelordner dieses Repositorys befinden.